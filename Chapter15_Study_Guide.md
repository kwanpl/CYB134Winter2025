### Study Guide: Digital Forensics

#### Chapter 15: Digital Forensics

---

**1. What is digital forensics?**  
*Answer:* Digital forensics is the investigation and analysis of digital data to determine what happened on a system or device. It supports legal holds, electronic discovery, internal investigations, and incident response processes [[1]].

---

**2. What are legal holds?**  
*Answer:* Legal holds are notifications sent by legal counsel to preserve and retain data that may be relevant to a current or pending case. This includes electronic files, paper documents, and backups [[3]].

---

**3. What is the significance of chain of custody in digital forensics?**  
*Answer:* Chain of custody refers to the documentation that tracks the handling of evidence. It ensures that data has been collected and preserved properly, maintaining its integrity for admissibility in court [[9]].

---

**4. What are the nine stages of the Electronic Discovery Reference Model (EDRM)?**  
*Answer:* The nine stages of EDRM are:
   1. Information governance
   2. Identification of electronically stored information
   3. Preservation of information
   4. Collection of information
   5. Processing of data
   6. Review of data
   7. Analysis of information
   8. Production of data
   9. Presentation of data [[4]].

---

**5. What is the order of volatility?**  
*Answer:* The order of volatility is a guideline that prioritizes data in terms of how quickly it can be lost. It shows that CPU cache and registers are most volatile, followed by ephemeral data, and finally, files and data on a disk are the least volatile [[6]].

---

**6. What tools are commonly used for forensic data acquisition?**  
*Answer:* Common tools for forensic data acquisition include:
   - **dd**: A command-line utility for creating disk images.
   - **FTK Imager**: A tool for creating forensic images in various formats.
   - **WinHex**: A disk editing tool that can acquire disk images [[12]].

---

**7. Why is validating forensic data integrity important?**  
*Answer:* Validating forensic data integrity ensures that the copied data matches the original. This often involves hashing both the original and copied data and comparing the hashes to confirm that no alterations occurred [[17]].

---

**8. What challenges do cloud services introduce to digital forensics?**  
*Answer:* Cloud services complicate forensic efforts due to shared environments where direct access to forensic data may not be possible. Organizations must consider contractual terms, jurisdictional concerns, and right-to-audit clauses [[11]].

---

**9. What are some common forensic locations from which data can be acquired?**  
*Answer:* Common forensic locations include:
   - CPU cache and registers
   - Ephemeral data (e.g., process table)
   - RAM
   - Swap and pagefiles
   - Files and data on disks [[7]].

---

**10. What is the difference between forensic copies and logical copies?**  
*Answer:* Forensic copies are bit-for-bit copies of a drive that preserve the exact structure and deleted file remnants, while logical copies do not capture all the underlying data and may be inadmissible in legal contexts [[18]].

---

This study guide highlights key concepts from Chapter 15 on Digital Forensics, providing a structured approach for review and comprehension. Use this guide to test your understanding and prepare for examinations or practical applications in digital forensics.
