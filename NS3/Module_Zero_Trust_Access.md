
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
- **FortiAuthenticator**: is the gatekeeper of authorization into the FOrtinet secured enterprise network, identifying users, querying access permissions from third-party systems, and communicating the information to FOrtiGate devices for use in identity-based policies.
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

- The Fabric Agent shares telemetry information with FOrtiGate and FortiAnalyzer. This provides security analysts with a holistic visual context of endpoint vulnerabilities from a single-pane-of-glass.

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


 
