
## Security Operations Solution

![image](https://user-images.githubusercontent.com/71230412/233114781-16c32907-52bd-4eb2-a209-6654a3768041.png)


### Use Case - Single Pane Management, Visibility,, and Analytics - Solution

![image](https://user-images.githubusercontent.com/71230412/233115540-1c47934e-c79f-4156-8e13-21cfdc8768a4.png)

![image](https://user-images.githubusercontent.com/71230412/233116555-2939de0e-cbac-415e-9fd3-fc5a765f5df1.png)


### Use Case - Advanced Compliance Reporting - Challenges

![image](https://user-images.githubusercontent.com/71230412/233116960-e7d24bf0-9030-4266-a625-b454a0c8ba6f.png)

### Knowledge Check
**FortiSIEM vs FortiAnalyzer**

You should consider deploying FortiSIEM for a mature SOC with multi-vendor environment.
- FortiAnalyzer is the entry level log collection for FOrtinet devices, and is deal for beginner level SOC.
- As more devices are onboarded FortiSIEM can collect thousands of logs per second, analyze them and generates incidents. FortiSIEM can also mitigate incidents but FOrtiAnalyzer cannot.

- - -
## Exam

### 1) What are two ways that FortiSandbox bolsters Security Operations processes? (Choose two.)
Select one or more:
- Provides endpoint visibility through telemetry and ensures that all Security Fabric components have a unified view of endpoints
- Automates the detection and response process across both IT and OT environments
- Creates playbooks for orchestrated response
- Powered by two machine learning models to deal with rapid evolving threats
Answer:
```diff
+ Automates the detection and response process across both IT and OT environments
+ Powered by two machine learning models to deal with rapid evolving threats
```

### 2) What are three capabilities of FortiXDR? (Choose three.)
Select one or more:
- Extends detection and response across digital attack surface edges including endpoints and IoT devices
- Confines the actions of an application to an isolated safe environment, and analyzes behavior to uncover malicious intent
- Enables pre-defined automatic response actions based on user, group, threat type, severity, and scope
- Adds analytics and converts security alerts to a manageable number of high fidelity incidents for investigation
- Optimizes application performance and availability, and provides security through integration with the Security Fabric
Answer:
```diff
+ Extends detection and response across digital attack surface edges including endpoints and IoT devices
+ Enables pre-defined automatic response actions based on user, group, threat type, severity, and scope
+ Adds analytics and converts security alerts to a manageable number of high fidelity incidents for investigation
```

### 3) In FortiDeceptor, which three detection engines comprise the Anti-Reconnaissance and Anti-Exploit Service? (Choose three.)
Select one or more:
- Anti-malware service
- IPS detection
- Security Rating Service
- Web filtering service
- Indicators of Compromise
Answer:
```diff
+ IPS detection
+ Anti-malware service
+ Web filtering service
```

### 4) From which two sources does FortiAnalyzer correlate logs? (Choose two.)
Select one or more:
- FortiGate
- FortiSandbox
- FortiToken
- FortiSwitch
Answer:
```diff
+ FortiGate
+ FortiSandbox
```

### 5) What are three tasks that the FortiNDR Virtual Security Analyst performs? (Choose three.)
Select one or more:
- Classifies threats
- Analyzes and reports on network security gaps
- Applies virtual patches to vulnerable devices
- Investigates threats
- Detects threats
Answer:
```diff
+ Classifies threats
+ Detects threats
+ Investigates threats

```

### 6) What are three capabilities of FortiSOAR? (Choose three.)
Select one or more:
- Visual playbook builder
- HTTP/HTTPS traffic monitoring
- Zero trust network access
- Automate responses to alerts, incidents, and vulnerabilities
Answer:
```diff
+ Visual playbook builder
+ Automate responses to alerts, incidents, and vulnerabilities
+ Customizable dashboards and reports
```

### 7) What EDR feature addresses automated incident response?
Select one:
- Playbooks
- Anomaly detection
- Security risk scoring
- Threat intelligence updates
Answer:
```diff
+ Playbooks
```
### 8) What are three categories of capabilities delivered by the Fortinet Security Operations solution? (Choose three.)
Select one or more:

- Security automation and orchestration
- Centralized management
- Network segmentation
- Application performance optimization
Answer:
```diff
+ Security automation and orchestration
+ Centralized management
+ Security Fabric analytics
```

### 9) What is the FortiDeceptor lifecycle?
Select one:
- Deceive > Contain > Protect
- Detect > Expose > Protect
- Detect > Contain > Eliminate
- Deceive > Expose > Eliminate
Answer:
```diff
+ Deceive > Expose > Eliminate
```
### 10) How does FortiSIEM support multi-tenancy?
Select one:

- It allows multiple customers to share the same network infrastructure.
- It provides support for FortiSIEM to analyse cloud-based resources.
- It allows enterprises and managed service providers to create partitioned reporting domains.
- It allows multiple instances of FortiSIEM to be used on the same network simultaneously.
Answer:
```diff
+ It allows enterprises and managed service providers to create partitioned reporting domains.
```

### 11) The roll back malicious changes feature in FortiEDR is at which stage of the overall attack phase?
Select one:
- Pre-infection
- Scoping
- Enhancement
- Post-infection
Answer:
```diff
+ Post-infection
```

### 12) FortiAnalyzer is primarily used for which purpose?
Select one:
- Central management of any number of Fortinet devices
- Monitor incoming and outgoing network traffic and determines whether to allow or block specific traffic
- Isolate untested code and unknown URLs from the production environment
- Centralized security logging and reporting
Answer:
```diff
+ Centralized security logging and reporting
```

### 13) The FortiNDR Virtual Security Analyst is built on which machine learning model?
Select one:
- Bayesian Probability
- Deep Neural Networks
- Random Forest Tree
- Naive Bayes
Answer:
```diff
+ Deep Neural Networks
```
### 14) What are three key benefits of FortiAnalyzer? (Choose three.)
Select one or more:
- Increases security
- Allows or blocks specific network traffic
- Isolates untested code and unknown URLs
- Reduces complexity of management
- Automates compliance
Answer:
```diff
+ Increases security
+ Reduces complexity of management
+ Automates compliance
```

### 15)  Which statement correctly identifies how FortiDeceptor defends the network?
Select one:
- Builds decoys to lure attackers and inspects their behaviour.
- Blocks IP addresses and URLs that are identified on deny lists.
- Reports and enforces compliance of regulations, such as HIPAA and GDPR.
- Defends against bulk volumetric attacks at layer 3 and layer 4 of the OSI model.
Answer:
```diff
+ Builds decoys to lure attackers and inspects their behaviour.
```
### 16) What database is used by FortiSIEM to perform real-time asset discovery and classification?
Select one:
- Lightweight Directory Access Protocol (LDAP)
- Extract, Transfer, and Load (ETL)
- Relational Database Management System (RDBMS)
- Configuration Management Database (CMDB)
Answer:
```diff
+ Configuration Management Database (CMDB)
```

### 17) What are two FortiGuard services implemented in FortiSandbox? (Choose two.)
Select one or more:
- Cleanup service
- Quarantine service
- Content Patented Recognition Language (CPRL)
- File Query service
Answer:
```diff
+ Content Patented Recognition Language (CPRL)
+ File Query service.
```


### 18) Which Security Operations use case solves the challenges of misconfigurations during deployment and obtaining detailed logs and telemetry?
Select one:
- Advanced compliance reporting
- Network segmentation
- Single pane management, visibility, and analytics
- Cloud container security 
Answer:
```diff
+ Single pane management, visibility, and analytics.
```
