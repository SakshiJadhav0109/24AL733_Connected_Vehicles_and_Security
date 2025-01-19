# 24AL733 - Connected Vehicles and Security 
![](https://img.shields.io/badge/PG-blue) ![](https://img.shields.io/badge/Subject-CVS-blue) <br/>

## Examples 

### RSA Key Exchange Example

#### Given:
- **Public Key (n, e):** (119, 7)  
- **Private Key (n, d):** (119, 103)  
- **Symmetric Key:** 45  

---

#### (a) Encrypt the symmetric key using the public key:
The encryption formula is:  
\[
C = (M^e) mod n
\]
Where:  
\[
M = 45,  e = 7, n = 119
\]

**Step-by-step modular exponentiation:**  
1. \( 45^2 mod 119 = 2025 mod 119 = 6 \)  
2. \( 45^4 mod 119 = (6^2) mod 119 = 36 \)  
3. \( 45^7 mod 119 = (36 o 6 o 45) mod 119 = 9720 mod 119 = 57 \)  

**Encrypted Symmetric Key:**  
\[
C = 57
\]

---

#### (b) Decrypt the encrypted symmetric key using the private key:
The decryption formula is:  
\[
M = (C^d) mod n
\]
Where:  
\[
C = 57, d = 103, n = 119
\]

**Step-by-step modular exponentiation:**  
1. \( 57^2 mod 119 = 3249 mod 119 = 108 \)  
2. \( 57^4 mod 119 = (108^2) mod 119 = 64 \)  
3. \( 57^{103} mod 119 = (64 o 57) mod 119 = 3648 mod 119 = 45 \)  

**Decrypted Symmetric Key:**  
\[
M = 45
\]

---

#### (c) Significance of RSA for Key Exchange:
- RSA ensures the **secure exchange** of symmetric keys.  
- Only the **intended recipient** with the private key can decrypt the symmetric key.  
- This mechanism prevents unauthorized access, even if the communication is intercepted.  
- In connected vehicle networks, this provides a reliable way to exchange keys for secure communication.
