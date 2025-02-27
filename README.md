# Artemis-Project
                                                      College project to create secure code and fix vulnerabilities

                                                                Artemis Financial Project Reflection

1. Briefly summarize your client, Artemis Financial, and its software requirements.
   
Artemis Financial is a consulting company that provides financial planning services, including savings, investments, and insurance. They needed a secure way to verify files transferred through their web application. The company wanted to add a checksum verification process to ensure data integrity and improve overall security.

3. What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely?
   
I did well in identifying outdated dependencies and configuring HTTPS to secure communication. I also implemented SHA-256 hashing to verify data integrity. Coding securely is important because it prevents cyber threats like data breaches and unauthorized access. Secure software helps companies protect sensitive customer information, maintain trust, and meet compliance standards.

5. Which part of the vulnerability assessment was challenging or helpful to you?
   
The most challenging part was updating dependencies without breaking the project, as some versions had compatibility issues. The OWASP Dependency-Check tool was very helpful in identifying vulnerabilities in third-party libraries. It showed me how important it is to regularly update and scan dependencies to avoid security risks.

7. How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
   
I increased security by encrypting communication with SSL/TLS, implementing data integrity checks with SHA-256, and patching security vulnerabilities in dependencies. In the future, I would use tools like OWASP Dependency-Check, NIST security guidelines, and threat modeling techniques to assess vulnerabilities and choose appropriate mitigation strategies.

9. How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
    
I tested the software by running the application and verifying HTTPS functionality. I also used OWASP Dependency-Check to scan for vulnerabilities after updates. Running security tests after refactoring ensured that no new vulnerabilities were introduced.

11. What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
    
Some useful resources and tools I used were:

 - OWASP Secure Coding Practices for writing secure code.
 - OWASP Dependency-Check for scanning third-party libraries.
 - Java Keytool for generating SSL certificates.
 - Spring Boot Security Best Practices for configuring HTTPS and authentication.
   
These tools will be valuable in future cybersecurity and software development projects.

7. Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
   
I could show future employers how I:

 - Implemented encryption and secure communication (SSL/TLS).
 - Identified and mitigated security vulnerabilities using OWASP tools.
 - Improved data integrity with SHA-256 hashing.
 - Followed secure coding best practices to protect financial data.
