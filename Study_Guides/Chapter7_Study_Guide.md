# Study Guide: Cryptography and Public Key Infrastructure (PKI)

## Chapter 7: Questions and Answers

### General Concepts

1. **What are the four main goals of cryptography?**
   - **Answer:** The four main goals of cryptography are:
     1. Confidentiality - protecting sensitive information from unauthorized access.
     2. Integrity - ensuring that data is not altered maliciously or unintentionally.
     3. Authentication - validating the identity of individuals or systems.
     4. Non-repudiation - providing proof that a message came from its purported sender [[2]].

2. **What is the difference between symmetric and asymmetric encryption?**
   - **Answer:** 
     - Symmetric encryption uses a shared secret key for both encryption and decryption, requiring a secure method to exchange this key. 
     - Asymmetric encryption uses a pair of keys: a public key (freely shared) and a private key (kept secret). Data encrypted with one key can only be decrypted with the other key from the pair [[60]].

3. **What is the purpose of digital signatures?**
   - **Answer:** Digital signatures provide non-repudiation by allowing a third party to verify the authenticity of a message. They are created by generating a message digest using a hash function and then encrypting that digest with the sender's private key [[60]].

### Cryptographic Techniques

4. **What is the Caesar cipher?**
   - **Answer:** The Caesar cipher is a substitution cipher that shifts letters in the alphabet by a fixed number of places. For example, a shift of three turns 'A' into 'D' [[4]].

5. **What is steganography?**
   - **Answer:** Steganography is the practice of hiding a secret message within another file, such as an image or audio file, in a way that is not noticeable to the observer [[9]].

### Cryptographic Algorithms

6. **What is the Advanced Encryption Standard (AES)?**
   - **Answer:** AES is a symmetric encryption algorithm that supports key lengths of 128, 192, and 256 bits, and is widely used for encrypting sensitive data [[28]].

7. **What are hashing functions and their main requirements?**
   - **Answer:** Hashing functions take an input of any length and produce a fixed-length output. The main requirements are:
     1. They should accept any length of input.
     2. Produce a fixed-length output.
     3. Be easy to compute.
     4. Be one-way (difficult to reverse).
     5. Be collision-free (hard to find two inputs that produce the same output) [[36]].

### Security Practices

8. **What is key management, and why is it important?**
   - **Answer:** Key management refers to the processes surrounding the creation, distribution, storage, destruction, recovery, and escrow of cryptographic keys. It is crucial for maintaining the security of cryptographic systems [[29]].

9. **What is a Certificate Authority (CA)?**
   - **Answer:** A Certificate Authority is an organization that issues digital certificates, verifying the identities of the entities that hold the certificates [[43]].

10. **What are Certificate Revocation Lists (CRLs) and OCSP?**
    - **Answer:**
      - CRLs are lists maintained by CAs that contain serial numbers of revoked certificates.
      - OCSP (Online Certificate Status Protocol) provides real-time verification of certificate validity, allowing clients to check if a certificate has been revoked [[48]].

### Emerging Issues

11. **What is blockchain technology?**
    - **Answer:** Blockchain is a distributed and immutable open public ledger that allows for secure and transparent record-keeping, initially developed for cryptocurrencies like Bitcoin [[57]].

12. **What challenges does quantum computing pose for cryptography?**
    - **Answer:** Quantum computing has the potential to break cryptographic algorithms that rely on factoring large prime numbers, necessitating the development of new cryptographic methods that can withstand quantum attacks [[58]].

---

This study guide encapsulates key concepts from Chapter 7 on cryptography and PKI, providing a solid foundation for understanding essential security principles.
