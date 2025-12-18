
# CS305
Repository for CS305

## CS 305 Project Two – Secure Software Refactoring (Artemis Financial)

### Client Summary  
Artemis Financial is a consulting firm that develops personalized financial plans and maintains a public-facing web application. The client required improvements to software security, specifically secure communications and data integrity verification, to protect sensitive financial information during transmission.

### Security Vulnerability Assessment  
I effectively identified and addressed security gaps related to insecure data transmission and integrity verification. Coding securely is critical because financial applications are high-value targets, and vulnerabilities can lead to data breaches, legal exposure, and loss of client trust. Strong software security improves reliability, compliance readiness, and overall organizational stability.

### Assessment Challenges and Insights  
The most helpful part of the vulnerability assessment was reviewing third-party dependencies, as many risks originate outside the application’s core logic. Understanding how outdated libraries introduce vulnerabilities was both challenging and valuable. It is particularly important to analyze transient dependencies, how they play a role in the software code, and if its safe to suppress vulnerability warnings for them. 

### Layers of Security  
I increased security by enabling HTTPS with a self-signed certificate, implementing SHA-256 hashing for checksum-based data integrity, and upgrading dependencies. In future projects, I would continue using static analysis tools, dependency scanning, and secure design reviews to guide mitigation decisions.

### Validation and Testing  
To ensure functionality and security, I ran and tested the refactored application, verified HTTPS communication with self generated certificates, and confirmed consistent checksum generation. I used the OWASP Dependency-Check tool after refactoring to confirm that no new vulnerabilities were introduced.

### Tools and Practices Used  
Key tools and practices included Java Keytool, SHA-256 hashing, HTTPS configuration, Spring Boot dependency upgrades, OWASP Dependency-Check, secure exception handling, and manual code review. These tools and techniques will be useful in future coursework and professional development.

### Portfolio and Career Value  
For future employers, I would showcase this project as an example of secure software refactoring, secure communication implementation, vulnerability assessment, and adherence to industry-standard security practices in a real-world financial application scenario.
