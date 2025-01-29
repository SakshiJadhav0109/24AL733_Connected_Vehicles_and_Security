# 24AL733 - Connected Vehicles and Security 
![](https://img.shields.io/badge/PG-blue) ![](https://img.shields.io/badge/Subject-CVS-blue) <br/>
![](https://img.shields.io/badge/Lecture-3-orange) ![](https://img.shields.io/badge/Credits-3-orange) 

## CVS#02 - CAN and CAN-FD Vulnerability Analysis
![](https://img.shields.io/badge/Member-Boomika_K_T-gold) <br/> 
![](https://img.shields.io/badge/SDG-TBD-darkgreen) <br/> 
![](https://img.shields.io/badge/Reviewed-TBD-brown) 

### Problem Statement
Modern connected vehicles rely heavily on communication protocols like the Controller Area Network (CAN) and CAN-FD (Flexible Data-rate) to share critical information between Electronic Control Units (ECUs) and sensors. These protocols are vital for vehicle operations, from managing engine performance to ensuring safety systems function properly. However, since CAN and CAN-FD lack built-in security features, they are vulnerable to threats like data tampering, unauthorized access, message injection, and replay attacks.
As connected vehicle technologies, especially Vehicle-to-Everything (V2X) systems, become more widespread, securing communication between ECUs and external sensors (such as radar, LiDAR, cameras, and environmental sensors) is increasingly important. 
Without effective security measures, these vehicles face significant risks, such as:
1.Unauthorized access to sensitive vehicle data.
2.Manipulation or falsification of sensor data, leading to poor decisions.
3.Replay attacks, where attackers reuse valid messages to manipulate the system.
4.Eavesdropping on communication, which raises serious privacy concerns.



---

### Literature Survey
From the literature survey here are some methods used or can be addressed to over come the CAN and CAN-FD vulnerabilities
1.Device Authentication: Ensures only authorized devices can access the network, preventing unauthorized access and safeguarding the system against unverified data exchanges.
2.Message Authentication (HMAC): Hash-based Message Authentication Code (HMAC) is used to verify the integrity and authenticity of messages, protecting against tampering during transmission.
3.Encryption (AES): Encrypting messages with Advanced Encryption Standard (AES) ensures data confidentiality, preventing unauthorized access and eavesdropping.
4.Enhanced Error Detection (CRC & Extended CRC): CRC (Cyclic Redundancy Check) and its extended version in CAN-FD improve error detection by identifying and discarding corrupted or tampered messages, maintaining data integrity.
5.Replay Attack Prevention (Timestamps & Sequence Numbers): Adding timestamps and sequence numbers to messages ensures only current and valid data is processed, blocking attacks that retransmit previously captured messages.
6.Bit Rate Monitoring (for CAN-FD): Monitors and controls the bit-rate switching process in CAN-FD to detect and prevent exploits like timing mismatches that can disrupt communication.
7.Network Isolation and Gateway Security: Implements internal network isolation along with firewalls and gateway security to block unauthorized external access and protect against external threats.
8.Packet Filtering and Intrusion Detection (for CAN-FD): Uses packet filtering and intrusion detection systems to identify and block suspicious messages or abnormal traffic, protecting the network from malicious activities.


---

### Proposed Work


---

### Implementation Details



---


### Mapping to Sustainable Development Goals (SDG)


---

### References
