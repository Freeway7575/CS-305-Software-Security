# CS-305 Software Security
## SNHU CS-305 Module Eight Journal

### Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
Artemis Financial is upgrading their customer experience by providing a web interface for them to access their bank information. In order to provide that service to the customer, it is imperative that the system be secure and robust against attacks. The client wanted me to address security vulnerabilities in the third-party libraries being used, as well as review the code that has already been written to ensure it was written with security in mind, updating it as needed, and also to implement encryption for data (in a limited sense) using an appropriate encryption algorithm.

### What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
This project was all about tightening up security and eliminating vulnerabilities. The highest impact tasks were updating the Spring Frameworkvto the latest version, updating other dependencies to eliminate vulnerabilities and selection / creation of the cipher.  These actions along with a maintenance program will ensure Artemis Financial's document archive is secure and accessed by only the intended audience.

### What about the process of working through the vulnerability assessment did you find challenging or helpful?
Correcting the vulnerabilities and refactoring the code was quite challenging.  This may be becaue I had never done it before and the course did not provide a great deal of guidance which made a lot of the work trial and error.  I had a lot of anxiety and uncertainty but eventually everything worked so I ultimately learned enough to complete the assignment.

### How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?
My approach was really dictated by the assignment.  I selected a cipher based on the assigned resources and common practices.  I refactored the sample code to make it work and generate a certificate.  I implemented the certificate for use with the ssl server.  I believe role based authorization would've been a nice add but it was outside of the scope of the assignment.

### How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?
I primarily used code review and the dependency check tool to verify functionality and accuracy.  I did introduce new vulnerabilities after updating the Spring Framework in regards to SnakeYAML.  The upgrade was supposed to fix it but version 1.33 had a new vulnerability which required an upgrade to version 2 which is not yet included in the Spring Framework.  I had to learn how to override which was not a concept taught in the course but I was able to accomplish it.

### What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?
I learned a lot about Eclipse and Spring throughout this assignment.  I also learned a bit about implementing certificates and the code to generate hashes.  I believe all of this will be helpful for future assignments.

### Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?
I'm not sure how worthy this is to demonstrate skill but I could definitely speak to it and show the project as an example should the employer be interested.
