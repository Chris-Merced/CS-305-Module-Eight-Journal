# CS-305-Module-Eight-Journal

### Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
Artemis Financial is a consulting firm focused on developing personalized financial plans for clients. The company approached Global Rain
to modernize its operations, specifically seeking expertise in implementing effective software security measures to protect client data and financial information. A key requirement was the addition
of a file verification step to ensure secure communications through checksums during data transfer.

### What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
I effectively identified the software security vulnerabilities by conducting a thorough vulnerability assessment, which included integrating SHA-256 for data integrity verification. It is vital to
code securely to protect sensitive information, prevent data breaches, and maintain user trust. Software security enhances a company’s reputation and ensures compliance with regulations, ultimately
contributing to its overall well-being.

### Which part of the vulnerability assessment was challenging or helpful to you?
One of the challenging aspects of the vulnerability assessment was identifying all potential forms of attack that could occur in the existing application. However, this process was beneficial as it provided a clear
roadmap for implementing necessary security enhancements and understanding the importance of proactive security measures.

### How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
I increased layers of security by implementing HTTPS for secure communications and integrating SHA-256 hashing for file verification. In the future, I would use automated security scanning tools
and regular code reviews to assess vulnerabilities and determine the most effective mitigation techniques.

### How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
After refactoring the code, I ensured the application was functional and secure by running the program and verifying that the output in the browser met the expected results. To confirm that no new vulnerabilities were
introduced, I utilized a dependency-check tool to scan for any potential security issues in the updated code.

### What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
Useful resources included OWASP guidelines for secure coding practices and tools like dependency-check for static code analysis. These practices and tools will be beneficial for future assignments,
helping to ensure that applications are developed with security in mind from the outset.

### Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
To demonstrate my skills and experience to future employers, I would showcase the refactored application, emphasizing the implementation of secure coding protocols, the addition of SHA-256 for data verification,
and the overall enhancement of the software's security posture. This project illustrates my ability to integrate security measures into software development effectively.

