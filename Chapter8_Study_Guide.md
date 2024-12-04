### Study Guide: Identity and Access Management

#### Questions and Answers

1. **What are the fundamental concepts of Authentication, Authorization, and Accounting (AAA)?**
   - **Answer:** AAA involves authenticating users and systems, authorizing access to resources, and accounting for actions taken by users or systems. It ensures that the right individuals have the appropriate access levels to perform their tasks [[1]].

2. **What is the purpose of mitigation techniques in securing an enterprise?**
   - **Answer:** Mitigation techniques are used to reduce vulnerabilities and threats to an organization's systems and data, often through access control measures such as Access Control Lists (ACLs) and permissions [[1]].

3. **What is the significance of identity proofing in account provisioning?**
   - **Answer:** Identity proofing is the process of verifying that an individual is who they claim to be, often involving government-issued identification or personal information. It is crucial to ensure the correct individual is granted access during account provisioning [[2]].

4. **What is Multifactor Authentication (MFA), and what types of factors are included?**
   - **Answer:** MFA is a security mechanism that requires users to provide two or more verification factors to gain access to a resource. The factors can include:
     - Something you know (e.g., passwords)
     - Something you have (e.g., security tokens)
     - Something you are (e.g., biometrics)
     - Somewhere you are (e.g., location data) [[2]].

5. **How does Single Sign-On (SSO) work, and what are its benefits?**
   - **Answer:** SSO allows users to log in once and access multiple systems without needing to reauthenticate. Benefits include simplified user experience and improved productivity, although it may reduce the number of security boundaries [[3]].

6. **What are the common types of accounts in an organization?**
   - **Answer:** Common account types include:
     - User accounts (standard access)
     - Privileged accounts (administrative access)
     - Shared accounts (typically discouraged)
     - Guest accounts (temporary, limited access)
     - Service accounts (for applications and services) [[4]].

7. **What is the concept of least privilege, and why is it important?**
   - **Answer:** The principle of least privilege states that users should only have the minimum permissions necessary to perform their job functions. This helps reduce the risk of accidental or malicious misuse of access rights [[5]].

8. **What are the differences between Mandatory Access Control (MAC) and Discretionary Access Control (DAC)?**
   - **Answer:** MAC enforces access controls based on a set policy established by a security administrator and does not allow users to alter permissions. In contrast, DAC allows users to control access to their own resources, enabling them to delegate permissions to others [[6]].

9. **What technologies are commonly used for authentication and authorization?**
   - **Answer:** Common technologies include:
     - RADIUS
     - LDAP (Lightweight Directory Access Protocol)
     - OAuth
     - OpenID
     - SAML (Security Assertion Markup Language) [[2]].

10. **What are password best practices according to NIST?**
    - **Answer:** NIST recommends:
      - Focusing on password length rather than complexity
      - Not requiring special characters
      - Allowing the use of password managers
      - Monitoring passwords to prevent the use of easily compromised passwords [[5]].

11. **What are the risks associated with password managers?**
    - **Answer:** Risks include potential breaches of the password manager itself, leading to exposure of stored passwords. Users should take measures like using strong master passwords and enabling MFA [[6]].

12. **What is the difference between Time-based One-Time Passwords (TOTP) and HMAC-based One-Time Passwords (HOTP)?**
    - **Answer:** TOTP generates a one-time password based on the current time and is valid for a short period. HOTP generates a password based on a counter that increments each time a password is requested [[7]].

#### Summary
This study guide covers key concepts of identity and access management, focusing on authentication, authorization, account types, security principles, and associated technologies. Understanding these topics is crucial for success in managing organizational security effectively.
