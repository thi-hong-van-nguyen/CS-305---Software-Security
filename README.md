# CS-305-Software-Security

### Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
Artemis Financial is a consulting company specializing in personalized financial plans for clients. Their financial plans encompass areas such as savings, retirement, investments, and insurance. In collaboration with Global Rain, they are aiming to modernize their operations, including the use of a RESTful web application programming interface (API). The primary concern for Artemis Financial is to enhance the security of their operations. They seek Global Rain's expertise to identify potential security vulnerabilities within their web-based software application. The objective is to comprehensively assess the application for potential threats and vulnerabilities and subsequently create a vulnerability assessment report. This report will serve as a roadmap for implementing security measures that effectively mitigate any identified vulnerabilities and safeguard Artemis Financial's software and sensitive financial data from external threats.

### What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
During the process of identifying security vulnerabilities in the client's software, I effectively employed Maven to scan for potential vulnerabilities. This allowed me to leverage automated tools to conduct a comprehensive analysis of the software's dependencies and identify any known security issues.

In addition to utilizing Maven, I conducted meticulous manual code reviews, which encompassed a thorough examination of the software's codebase, including the API built into the program. This hands-on approach enabled me to identify potential entry points for vulnerabilities, analyze coding patterns, and pinpoint any non-trivial security weaknesses that might not be detected by automated tools.

Combining the power of Maven's automated vulnerability scanning with manual code reviews ensured a comprehensive assessment. While automated tools can efficiently identify known vulnerabilities, manual reviews provide the context to uncover more nuanced security issues that might arise from custom code or unique usage scenarios.

By integrating both approaches, I maximized the likelihood of identifying a wide range of security vulnerabilities, from common exploits to more intricate and application-specific weaknesses. This hybrid approach allowed me to provide the client with a detailed vulnerability assessment report that offers a holistic view of potential threats, thereby guiding effective mitigation strategies.

### What part of the vulnerability assessment was challenging or helpful to you?
The vulnerability assessment process presented both challenges and valuable learning opportunities. One particular aspect that proved challenging was devising effective solutions to address the vulnerabilities that were identified. While the assessment highlighted potential security weaknesses, determining the most suitable and efficient ways to mitigate these vulnerabilities required careful consideration and expertise. Some vulnerabilities might not have straightforward fixes, necessitating creative problem-solving and a deep understanding of the software's architecture.

Furthermore, dealing with instances where the automated assessment tools returned false results posed a unique challenge. False positives can lead to unnecessary resource allocation and hinder the overall vulnerability mitigation process. Distinguishing genuine vulnerabilities from false alarms required a discerning eye and the ability to critically evaluate the context and details of each flagged issue.

### How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
To bolster security measures, I adopted a comprehensive strategy that incorporated the implementation of SHA256 (Secure Hash Algorithm 256). SHA256 involves the utilization of both hardware and software components to enhance the safeguarding of sensitive data and deter unauthorized access. By integrating the SHA256 encryption technique, I introduced an extra layer of protection against potential threats. This added complexity makes it notably more arduous for malicious actors to breach the security of the software and gain access to sensitive information.

In the future, to assess vulnerabilities and determine suitable mitigation techniques, I would continue to utilize a combination of automated tools and manual reviews, as well as incorporate best practices from the industry. Automated vulnerability scanning tools, like Maven or specialized security scanners, are invaluable for identifying common vulnerabilities quickly and efficiently. However, I would also emphasize the importance of manual code reviews to catch nuanced vulnerabilities and address custom application-specific issues.

Furthermore, I would prioritize the use of threat modeling, which involves identifying potential threats and vulnerabilities early in the development process. By envisioning potential attack scenarios and systematically analyzing the software's architecture, data flow, and potential weak points, I could proactively identify security risks and design mitigation strategies.

### How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
Ensuring both functionality and security in the code and software application was a meticulous process. To achieve this, I employed a multifaceted approach that involved rigorous testing and validation.

To ensure functionality, I initially executed the software to identify any runtime errors or anomalies that might affect its performance. By running the program and simulating real-world scenarios, I could confirm that the software met its intended requirements and operated as expected.

For security, after implementing SHA256 encryption, I incorporated a checksum generation process. This involved creating a checksum after the encryption process. By checking the checksum, I could ascertain whether the encryption function functioned as intended and whether the data remained unchanged throughout the encryption and decryption processes. This step provided a way to verify that the encryption did not introduce data corruption or inconsistencies.

After refactoring the code, I conducted thorough regression testing. This involved rerunning the full suite of functional and security tests on the refactored codebase to detect any new vulnerabilities that might have emerged during the code changes. By comparing the results of these tests with the pre-refactoring results, I could identify any discrepancies or potential vulnerabilities introduced by the code changes.

### What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
The resources, tools, and coding practices I utilized during this project hold valuable lessons and insights that can greatly aid future assignments and tasks:

Maven for Vulnerability Detection: The use of Maven to identify vulnerabilities within the codebase is a valuable skill that can be applied in future projects. This tool streamlines the process of scanning for known vulnerabilities in dependencies, enhancing security assessment efficiency. Leveraging similar vulnerability scanning tools can be immensely beneficial in identifying potential weaknesses and ensuring software robustness.

Security Best Practices: Incorporating secure coding practices, such as input validation, proper authentication, and authorization mechanisms, and thorough error handling, can significantly enhance the security of any software application. Applying these practices in future assignments will help build secure and resilient software from the ground up.

HSA Encryption Technique: The utilization of the HSA encryption technique showcases the importance of multifaceted security measures. Learning about encryption methodologies and how to implement them effectively can be an invaluable skill in safeguarding sensitive data across various projects.

Checksum Verification: The practice of generating checksums to verify data integrity post-encryption serves as a valuable technique. Applying checksum verification can help validate data transformations and ensure that the encryption process does not introduce any corruption or errors. This practice can be extended to validate data integrity in various scenarios.

### Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
From this assignment, I would have several valuable examples to showcase my skills, knowledge, and experience to future employers:

1. **Vulnerability Assessment Report**: I can present the vulnerability assessment report that I created for Artemis Financial's software application. This report would demonstrate my ability to identify and analyze security vulnerabilities, propose mitigation strategies, and communicate findings effectively. It showcases my proficiency in understanding security risks and formulating actionable solutions.

2. **Code Refactoring and Security Enhancements**: I can showcase the original codebase and the refactored version that includes security enhancements. By comparing the two versions, I can highlight my coding skills in implementing secure practices, such as encryption and checksum verification, to protect sensitive data and fortify the software against potential threats.

3. **Maven Integration**: I can discuss my utilization of Maven for vulnerability detection. Explaining how I leveraged this tool to scan for known vulnerabilities in the software's dependencies showcases my ability to employ modern development tools to enhance security practices and reduce potential risks.

5. **Testing and Validation Artifacts**: I can provide examples of test plans, test cases, and testing results used to validate the functionality and security of the software application. These artifacts showcase my systematic approach to testing and my dedication to ensuring the software's reliability and security.

6. **Documentation and Communication**: I can present any documentation, such as design documents, diagrams, and technical explanations, that I created to effectively communicate security measures and enhancements to stakeholders. This highlights my ability to articulate complex technical concepts and solutions in a clear and understandable manner.
