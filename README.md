# CS-305-Portfolio

**Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?**

Artemis Financial is a consulting firm focused on creating tailored financial plans for clients. They required a review and improvement of their software's security measures to ensure data protection and compliance, specifically for sensitive data handled through their RESTful API.

**What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?**

I identified key vulnerabilities and implemented industry-standard best practices, enhancing the application's resilience to threats. Secure coding is essential to protect sensitive data and maintain the client's trust.

**Which part of the vulnerability assessment was challenging or helpful to you?**

The hardest part of the vulnerability assessment for me was looking for the false positives in the dependency check report. It was difficult to go through the long list of vulnerabilities and determine whether or not it had an impact on my code.

**How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?**

I layered security by implementing HTTPS, validating input, and encrypting data with an algorithm cipher. In future projects, I would use automated static analysis tools combined with manual reviews to asses vulnerabilities.

**How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?**

I encorporated functional testing to ensure that the code was functional and secure. After refactoring the code, I ran a dependency check on the libraries to ensure that the code was secure and made sure there were no errors getting reported in the console.

**What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?**

The Maven dependency check plugin, input validation practices, and SSL/TLS configuration were all useful tools and practices that I plan on implementing in future projects.

**Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?**

I would present this project as a comprehensive example of identifying nad addressing software vulnerabilities through secure coding practices, dependency management, and layered security implementations.
