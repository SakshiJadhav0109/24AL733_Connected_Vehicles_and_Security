# 24AL733 - Connected Vehicles and Security 
![](https://img.shields.io/badge/PG-blue) ![](https://img.shields.io/badge/Subject-CVS-blue) <br/>
![](https://img.shields.io/badge/Lecture-3-orange) ![](https://img.shields.io/badge/Credits-3-orange) 

## CVS#10 - Firmware Update OTA
![](https://img.shields.io/badge/Member-Mani_Shankar_Molleti-gold) <br/> 
![](https://img.shields.io/badge/SDG-TBD-darkgreen) <br/> 
![](https://img.shields.io/badge/Reviewed-TBD-brown) 

### Problem Statement
The automotive industry's shift toward intelligent vehicles has increased dependence on electronic control units (ECUs) for safety, performance, and operational enhancements. Regular firmware updates are essential to maintain functionality, fix bugs, and improve system performance. Traditional physical update methods are costly, inefficient, and inconvenient for manufacturers and consumers.
Firmware-Over-The-Air (FOTA) technology addresses these limitations by enabling remote updates, streamlining processes, and enhancing user experience. However, transitioning to FOTA introduces significant cybersecurity risks, including data tampering, unauthorized firmware access, replay attacks, and malware injection, which can jeopardize vehicle safety and functionality.
The central challenge is developing a lightweight, secure FOTA protocol that ensures data integrity, authentication, confidentiality, and freshness while addressing the limited computational resources of ECUs and the vulnerabilities of wireless communication. A robust solution is critical to delivering safe, efficient, and reliable updates in the evolving landscape of intelligent vehicles.
---

### Literature Survey
1.	FOTAMOTIVE: Highlights the inefficiencies of traditional update methods and proposes a FOTA solution to address OEM, dealer, and consumer challenges.
2.	Self-Verification Framework: Discusses virtualization techniques and hash-based verification protocols to ensure the integrity of firmware installations.
3.	Secure FOTA Protocols: Focuses on security challenges in intelligent vehicles, emphasizing the need for data integrity, authentication, and resilience to packet loss in wireless communications.
These studies underline the need for robust and secure frameworks to ensure reliable and efficient FOTA implementation in intelligent vehicles.
---

### Proposed Work
The proposed solution focuses on designing a secure and efficient FOTA protocol tailored for intelligent vehicles. Key features include:
•	Integrity Assurance: Ensures firmware remains unaltered during transmission and installation.
•	Authentication Mechanisms: Verifies the authenticity of firmware sources.
•	Confidentiality Protocols: Protects proprietary firmware from unauthorized access.
•	Freshness Verification: Prevents outdated firmware from being reused.
The framework will leverage lightweight cryptographic methods to address the resource constraints of ECUs, ensuring seamless and secure updates.

---

### Implementation Details
The implementation involves the following steps:
1.	Protocol Design: Develop a secure communication protocol with features like encryption, digital signatures, and secure hash algorithms.
2.	Virtualization for Verification: Implement virtualization within the ECU for trusted execution and validation of firmware.
3.	Testing and Validation: Simulate update processes under various scenarios to evaluate security, efficiency, and reliability.
4.	Deployment: Pilot the solution in a controlled environment, iteratively improving based on performance metrics and feedback.

---


### Mapping to Sustainable Development Goals (SDG)
The proposed work aligns with several UN Sustainable Development Goals:
•	SDG 9 (Industry, Innovation, and Infrastructure): Promotes innovation in the automotive industry, enhancing infrastructure through intelligent vehicles.
•	SDG 11 (Sustainable Cities and Communities): Improves vehicle safety and functionality, contributing to sustainable urban mobility.
•	SDG 13 (Climate Action): Reduces physical interventions and operational inefficiencies, lowering the carbon footprint associated with traditional update methods.

---

### References
1.	Nilsson, D. K., Larson, U. E., "Secure Firmware Updates over the Air in Intelligent Vehicles", Communications Workshops, 2008. ICC Workshops 08. IEEE International Conference on.
2.	Shavit, M., Gryc, A., and Miucic, R., "Firmware Update Over The Air (FOTA) for Automotive Industry", SAE Technical Paper, 2007.
3.	Miucic, R., and Mahmud, S. M., "Wireless Multicasting for Remote Software Upload in Vehicles with Realistic Vehicle Movement," Wayne State University, Tech. Rep., 2005.
