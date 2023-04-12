# Zero Trust Network Access (ZTNA)


### How is Remote Access Secured ?
It involves :
- Data Privacy: A state in which information is concealed from the public and privy only to select people.
- Data Integrity: The accuracy and consistency of data over its lifecycle.
- Authentication: The process of verifying the identity of a person or thing.
- Authorization: The function of specifying access rights to resources.
- Accounting: The record-keeping and tracking of agent activities on a computer network.

### Most Common Secure Access Methods:
- IPsec VPN: IPsec VPN
- SSL VPN : Secure Socket Layer Virtual Private Network.
- ZTNA: Zero Trust Network Access (which incorporates the principle of zero trust.). 
  * It defines the fact that no device inside or outside are trusted in the remote network process securing.

### Types of VPN use cases:
- Secure remote Access: User uses a secure tunnel encrypted VPN travelling a VPN server before reach or surfing on the Internet.
- Site-to-Site: This refers to the connecion between two or more networks. ex A secure connection between an Organization network and a local Branch office.

### Question:
Which feature or principle differentiates ZTNA from VPN ?
- Reliable COnnection
- Zero Trust
- Accounting, Authorization, Authentication
- End-to-end Privacy
- ANs: ``**Zero Trust**``

### Definition ZTNA
- ZTNA establishes a secure session between an end entity and a network, while ensuring granular control over access to resources and exercising zero trust, regardless of the location of either the end entity or the network.

![image](https://user-images.githubusercontent.com/71230412/231349995-7443b53d-f52e-4c08-ba99-ee93024b0b81.png)
![image](https://user-images.githubusercontent.com/71230412/231350085-a0a3f262-6de1-4ef3-90db-4648d8bd8a3b.png)

### Q-2) which two traits are unique to ZTNA ?
- 1- Requires identity validation of both device and user
- 2- Secures site-site communcation, 
- 3- Tunnel type is session-based only, 
- 4- Provides privacy through encryption 
Answer: 1 & 3

- **Explication**: ZTNA is the only remote access solution of the three that is session-based only, and validates both the device and the user. All three solutions ensure the privacy of communication through encryption. ZTNA does not secure site-site communication, but does secure client to network communication.

- - -
## Exam : 
### Q-1 Which feature or principle differentiates ZTNA from VPN?
Select one:
- Authentication
- End-to-end privacy
- Reliable connection
- Zero trust
Answer:
```diff
+ Zero Trust
```

### Q-2) Which three methods are common implementations of secure remote access? (Choose three.)
Select one or more:
- SAML
- PKI
- ZTNA
- SSL VPN
- IPsec VPN
Answer:
```diff
+ ZTNA, SSL VPN, IPsec VPN
```

### Q-3) Which two traits are unique to ZTNA? (Choose two.)
Select one or more:
- Provides privacy through encryption
- Tunnel type is session-based only
- Requires identity validation of device and user
- Secures site-to-site communication
Answer:
```diff
+ Tunnel type is session-based only.
+ Requires identity validation of device and user.
```

### Q-4) Which three examples qualify as working remotely? (Choose three.)
Select one or more:
- A CEO using VPN to securely connect to the network from home.
- A guest auditor working from the data center.
- An HR specialist working from a branch office.
- A partner who is given temporary access to the network while visiting the main office.
- An IT director getting caught up on email using while waiting for a flight.
ANswer:
```diff
+ A  CEO using VPN to securely connect to the network from home.
+ An HR specialist working from a branch office.
+ An IT director getting caught up on email using while waiting for a flight.
```

### Q-5) Which feature is a characteristic of secure access?
Select one:
- Environment simulation
- Deception
- Compliance
- Accounting
Answer:
```diff
+ Accounting 
```

### Q-6) Which statement best describes the zero-trust approach that is the basis for ZTNA design?
Select one:
- After devices are authenticated, they are always trusted.
- No device or user can be trusted inside or outside the network.
- IoT and BYOD devices must be authenticated before they are trusted.
- Remote devices and users cannot be trusted.
Answer:
```diff
- No device or user can be trusted inside or outside the network.
```
