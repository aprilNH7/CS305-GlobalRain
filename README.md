# CS305-GlobalRain

# Briefly summarize your client, Artemis Financial, and their software requirements:
A: Artemis Financial is a consulting company specializing in developing individualized financial plans for their clients, covering areas like savings, retirement, investments, and insurance. They approached Global Rain seeking to modernize their operations, with a specific focus on enhancing the security of their web application. They needed to add a file verification step, such as a checksum, to ensure secure data transfer.

# What did you do very well when you found your client's software security vulnerabilities? Why is it important to code securely? What value does software security add to a company's overall wellbeing?
A: I recommended a strong security approach, using asymmetric encryption with the SHA-256 cipher algorithm and 256-bit keys. This approach is highly secure and, in combination with self-signed certificates, enhances the software's security significantly. It's crucial to code securely because it safeguards sensitive data, protects against potential attackers, and maintains the trust of clients. Software security adds value to a company's overall wellbeing by mitigating risks, preserving its reputation, and ensuring compliance with industry standards and regulations.

# What part of the vulnerability assessment was challenging or helpful to you?
A: The part of the vulnerability assessment that was challenging was increasing layers of security while maintaining usability. Striking the right balance between robust security and user-friendliness is often a complex task. The helpful aspect of the assessment was the dependency check tool, which highlighted potential vulnerabilities in the code and ensured that the code complied with security enhancements.

# How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
A: I increased layers of security by implementing asymmetric encryption, using the SHA-256 cipher, and generating self-signed certificates. To assess vulnerabilities and decide on mitigation techniques in the future, I would continue to use tools like the OWASP Dependency-Check Maven for static code analysis. In conjunction, I would conduct regular code reviews and penetration testing to identify and address security issues.

# How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
A: I made sure the code and software application were functional and secure through a combination of measures. I performed functional testing, both manual and with tools like the OWASP Dependency-Check Maven, to identify and address vulnerabilities. After refactoring the code, I conducted thorough testing to ensure that no new vulnerabilities were introduced. This involved running secondary static testing and manual code reviews to validate the security enhancements.

# What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
A: In this assignment, I used the SHA-256 cipher algorithm, self-signed certificates, and the OWASP Dependency-Check Maven tool. These resources and practices can be extremely valuable in future assignments or tasks where security enhancements are required. , I learned the importance of keeping plugins and libraries up-to-date for ongoing security.

# Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
For future employers, I could showcase the complete secure software report, including the recommendations for encryption, certificate generation, code refactoring, and the results of security testing. This report demonstrates my ability to identify and address security vulnerabilities, apply industry-standard best practices, and ensure the security of software applications, which is a valuable skill in today's technology landscape.
