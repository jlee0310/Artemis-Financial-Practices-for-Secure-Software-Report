# the-completed-Artemis-Financial-Practices-for-Secure-Software-Report
The client is Artemis Financial, a consulting firm that develops individual financial plans with a public web interface. 
Artemis Financial offers savings, retirement, investment, and insurance, and they want to modernize the platform that provides it. 
With the modernization of their platforms, they need the most up-to-date and effective software security to protect their client data and financial information.  
As part of protecting customer data and financial information, Artemis Financial wants to add file verification step to their web application to ensure secure communications. 

I was able to compensate for the vulnerabilities of the software by strengthening the following six factors, and details are described in the report. 

1.	Algorithm Cipher: 
adopting AES by analyzing which algorithm is most suitable for our needs through research

2.	Certificate Generation: 
creating a self-signed certificate to establish a secure network between the client and the server.

3.	Deploy Cipher: 
securely encrypt client data through checksum verification. 

4.	Secure communications: 
refactoring the code to convert HTTP to the HTTPS

5.	Secondary Testing: 
running a secondary static testing of the refactored code using the OWASP Dependency-check Maven.

6.	Functional Testing: 
identifying the software application’s syntactical, logical, and security vulnerabilities by manually reviewing code. 

Vulnerability testing through Maven dependency check was the most challenging. 
This is because it was difficult to understand the concept of dependency when performing this task in the beginning. 
The test results were huge, and the concept of picking out false positives was also new to me.  
All dependency tests can be supplemented with version upgrades, and I was able to perform the task by opting out all false positives. 

Software vulnerabilities are an important factor that can seriously harm the well-being of the company and 
can be prevented by strengthening security before losing customer assets or compensating for the damage.  
Secure coding has significant role in that this risk can be prevented in advance. 

Through this task, I was able to show that I have an accurate understanding of the importance of software security and the dangers of insecure coding 
by reinforcing the security layer through the three elements of data security: confidentiality, integrity, and authentication.  
Combining these three elements with dependency test and manual code test can promise a firm and strong software security to the company I will work for in the future.


