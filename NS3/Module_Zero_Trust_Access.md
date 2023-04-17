
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

- **FortiClient**: connects endpoints with the FOrtinet Security Fabric. It delivers endpoint visibility and enforces endpoint security hygiene by way of **FortiClient Endpoint Management Server (EMS)**. It shares telemetry to the fabric, which includes endpoint security posture and vulnerability status. And it contributes to dynamic virtual groups.
- **FOrtiNAC** : is a security product that implements policy on devices that access networks to increase network visibility and control, and to facilitate automated responses to incidences. An example of the control aspect of FOrtiNAC is when a device connects to a computer network, it is not permitted to access anything unless it complies with network policy, including anti-virus protection level, system update level and configuration.
 
