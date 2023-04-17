
## What problems Does ZTA Solve ?
- Inconsistent user experience to better user experience:
  * Access from in or out of office identical
  * Automatic secure tunnels to applications
  * Single Sign-On supported 
- Applications exposed to the bad actor to an environement that hides applications, providing better security:
  * No need to know where the applications is located  

## Principles of the Fortinet ZTA:
- Verify : Authenticate and verify on an on-going basis.
- Give minimal access:
  * Segement the network to create zones of control
  * COntrol access to applications, data , resources
  * Grant the least privilege access based on read or role
- Assume that the network is perpetually compromised:
  * Plan as if attackers are inside and outisde the network.
  * Forget the concept of `trusted zone` 
 
## Reducing the Attack Surface
- By granular control to applications
  * Authenticate user identity per connection
  * Supporting strong authentication -- MFA and SSO
  * Verifying device identity per session
  * Verifying device posture per session
  * Restricting user access to resources based on need-to-know
  * Hiding network applications from the internet.
  
## Products of the Zero Trust Access Solution
ZTA enables organizations to see and control everyone and everything on the network, whether on or off premise.

- **FortiAuthenticator**: is the gatekeeper of authorization into the Fortinet secured enterprise network, identifying users, querying access permissions from third-party systems, and communicating the information to FOrtiGate devices for use in identity-based policies.
- FortiAuthenticator leverages information, such as user credentials, groups, and roles, from existing third-party databses or directories to support SSO and access control.

- **FortiClient**: connects endpoints with the Fortinet Security Fabric. It delivers endpoint visibility and enforces endpoint security hygiene by way of **FortiClient Endpoint Management Server (EMS)**. It shares telemetry to the fabric, which includes endpoint security posture and vulnerability status. And it contributes to dynamic virtual groups.
- **FOrtiNAC** : is a security product that implements policy on devices that access networks to increase network visibility and control, and to facilitate automated responses to incidences. An example of the control aspect of FOrtiNAC is when a device connects to a computer network, it is not permitted to access anything unless it complies with network policy, including anti-virus protection level, system update level and configuration.
 
 - - - 
 ## Lesson FortiAuthenticator
 - is an identity ,management product for the enterprise ; providing strong authentication and authorisation to the connected network.

## Lesson FortiClient
It solves Problems like :
- Lack of Visibility
- Vulnerable endpoints
- Unsuspecting users

- The Fabric Agent shares telemetry information with FortiGate and FortiAnalyzer. This provides security analysts with a holistic visual context of endpoint vulnerabilities from a single-pane-of-glass.

- To establish remote secure access and multi-factor authentication, FortiClient must integrate with FortiGuard. **False**.

## Lesson - FortiNAC
- It is the Fortinet network access control product. Network access control (NAC) is a security solution that identifies and enforces policy on devices that access networks to increase visibility and reduce risk.
- Problems solving:
  * Zero Trust for Devices
  * Improve Network Visibility
  * Regulatory compliance

- It applies Zero trust for every node on the network.
  * **Visibility**: Device identification, profiling, and vulnerability scanning
  * **Control**: Supports intent-based segmentation
  * **Automated Response**: means COntinuous Response --> Automated response and network orchestration, Extends Security Fabric.
 
 - **FortiGuard** provides a security rating service not FortiNAC. The scores can be viewed from the root FortiGate. FortiNAC identifies and classifies devices.
 
 ### Continuous Device Profiling
 - 1. Printer connects to the network
 - 2. MAC notification trap triggers FortiNAC
 - 3. FortiNAC profiles device as printer
 - 4. FortiNAC informs Security Fabric to allow printer-type access to the network. 

### Containment of Lateral Threats at Edge 
- 1. User brings infected lapto to work
- 2. FortiGate sends event FortiNAC
- 3. FortiNAC quarantines the laptop at access layer
- 4. Virus contained at switch node.  ****

- FortiNAC integrates with :
* FortiGate
* FortiAnalyzer
* FortiSIEM
* FortiSwitch
* FortiAP
* FortiClient
* FortiEDR

-  **FortiGate** notifies FortiNAC of an affected device on the network.

- **FortiNAC** uses rules, which can consist of up to 20 profiling methods, to identify and categorize an unknown device. Once the device is assigned a device type, it can be added to a role and group that can restrict what the device can do.

-  - -
## EXAM
### 1) Which module of FortiClient supports the secure remote access use case?
Select one:
- Advanced Threat Protection
- Fabric Agent
- Endpoint Protection Platform
- Single Sign On
Answer:
```diff
+ Single Sign On

```

### 2) Which description best identifies a function of FortiAuthenticator as a certificate authority?
Select one:
- Provide digital identities
- Block unauthorized access to network resources
- Track access to network resources
- Verify data integrity of VPN connections
Answer:
```diff
+ Fabric Agent

```

### 3) Which description best identifies a function of FortiAuthenticator as a certificate authority?
Select one:
- Provide digital identities
- Block unauthorized access to network resources
- Track access to network resources
- Verify data integrity of VPN connections
Answer:
```diff
+ Provide digital identities.
```

### 4) Which product helps protect end users who are prone to clicking on phishing scams?
Select one:
- FortiClient
- FortiNAC
- FortiAuthenticator
- FortiAnalyzer
Answer:
```diff
+ FortiClient.
```

### 5) Which product category best describes FortiAuthenticator?
Select one:
- Identity Management
- Analytics
- Certificate Directory
- Monitoring and Reporting
Answer:
```diff
+ Identity Management.
```

### 6) FortiAuthenticator supports self-service registration, social authentication, and pre-defined access codes for which purpose?
Select one:
- Two-factor sign-on
- Malware detection
- FortiGate administrative access
- Guest user access
Answer:
```diff
+ Guest user access.
```

### 7) Which type of network user accounts for the majority of breaches?
Select one:
- External users
- Partners
- Internal users
- IT administrators
Answer:
```diff
+ Internal users
```

### 8) Which product can manage and automatically provision FortiClient to endpoints?
Select one:
- FortiClient Fabric Agent
- Endpoint Management Server
- FortiGate
- FortiManager
Answer:
```diff
+ FortiGate
```

### 9) Which is a principle of zero trust access?
Select one:
- Protection from spoofing and routing attacks
- Multi-factor authentication
- Continuous authentication of users and devices
- Restoration of a device to a previous state after ransomware has been detected
Answer:
```diff
+ Continuous authentication of users and devices.
```

### 10) What is a key capability of FortiNAC?
Select one:
- Segments the network according to device IP address
- Profiles and monitors devices on the network
- Authorizes access to resources based on device profiles
- Blocks traffic when the source of the traffic exceeds a prescribed threshold
Answer:
```diff
+ Profiles and monitors devices on the network.
```

### 11) How does FortiNAC dynamically control access to the network?
Select one:
- Authenticates devices using MFA before allowing access to the network
- Authorizes access to network resources based on user or device roles
- Detects a change in the device profile and automatically quarantines the device
- Connects devices securely using ZTNA technology or VPN SSL
Answer:
```diff
+ 
```

### 12) Which two methods are common examples of second factor authentication that are supported by FortiAuthenticator? (Choose two.)
Select one or more:
- Retina scan
- Digital certificates
- Tokens
- Voice biometrics
Answer:
```diff
+ Digital certificates
+ Tokens.
```

### 13) Complete the sentence to identify which method determines Fortinet ZTA micro-segmentation.
FortiNAC micro-segments the network according to …
Select one:
- subnet mask and IP address.
- trusted and untrusted entities.
- user role and device function.
- internal and guest users.
Answer:
```diff
+ user role and device function.
```

### 14) Which module of FortiClient supports the secure remote access use case?
Select one:
- Endpoint Protection Platform
- Single Sign On
- Advanced Threat Protection
- Fabric Agent
Answer:
```diff
+ Single Sign On
```

### 15) Which three major functions does FortiAuthenticator provide? (Choose three.)
Select one or more:
- Secure access with two-factor authentication
- Scalable VPN through custom FortiASIC hardware acceleration
- Identity management
- Wired and wireless authentication
- Malware detection and remediation
Answer:
```diff
+ Secure access with two-factor authentication
+ Identity management
+ Wired and wireless authentication
```

### 16) Which three key capabilities does FortiNAC offer customers? (Choose three.)
Select one or more:
- Filtration—filters web traffic and stops any known malware
- Control—segments the network by device so that the device can only access those assets it requires
- Malware containment and analysis—isolates a suspicious application in a virtual environment for further testing
- Visibility—provides identification, profiling, and vulnerability scanning of devices
- Automated response—takes automatic action should a device become compromised or be suspected of compromise
Answer:
```diff
+ Control—segments the network by device so that the device can only access those assets it requires.
+ Visibility—provides identification, profiling, and vulnerability scanning of devices
+ Automated response—takes automatic action should a device become compromised or be suspected of compromise
```

### 17) Which Fortinet product is used to profile devices in order to detect changes to device characteristics?
Select one:
- FortiClient
- FortiSandbox
- FortiNAC
- FortiAuthenticator
Answer:
```diff
+ FortiNAC.
```

### 18) Which two Fortinet products integrate with FortiNAC? (Choose two.)
Select one or more:
- FortiClient EMS
- FortiGate
- FortiToken
- FortiPhone
Answer:
```diff
+ FortiClient EMS
+ FortiGate
```

### 19) Which security platform does FortiClient EMS integrate with to increase visibility and compliance control?
Select one:
- Certificate Authority
- Firestorm Security Platform for FortiClient
- SD-WAN
- Fortinet Security Fabric
Answer:
```diff
+ Fortinet Security Fabric.
```

### 20) Which best describes the Zero Trust Access solution pillar?
Select one:
- Applies artificial intelligence as well as integration and automation to reduce risk and improve efficiency
- Secures edges at any scale with full visibility and threat protection
- Enables organizations to see and control everyone and everything on the network
- Orchestrates and automates all of an organization’s security tools to unify operations
Answer:
```diff
+ Enables organizations to see and control everyone and everything on the network.
```
