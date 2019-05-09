These are frequently asked question in regard to security issues.

### Is the Company affiliated with security specialist?

- The Company's security is managed by kt telecop Co., Ltd.

### Is there written policy and administrative instruction for the security of confidential data and information? If so, is that document available to read?

- This repository is the document for the security policy of the Company.
- With this document(repository), the Company instructs security awareness training for employee and partner.
- Customers can get information about the security policy of the Company from this document.

### Are all the employees fully trained for information security? Please explain how education is going.

- Information security education is progressed with this document(repository).
- If an employee violates the security policy, the employee shall follow [Discipline and Sanction Policy](security_disciplinary_action.md).

### Is there a code of conduct in the information security policy of the Company? And does it cover workstation, server, network equipment, and other technical equipment?

- Internet network and inner intranet network for the task is physically separated.
- Workstation for artist uses Linux and is not allowed using USB. Also, Workstation for the artist cannot be physically connected to the internet.
- Only administrator can access to the server room through three times of biometrics(fingerprint). The server room is recorded around the clock through CCTV.

### How much access authority doses the worker have in regard to the project?

- Employees only can access to an ongoing project.

### Does the Company get NDA from employees, contractor and other third parties?

- *Company* conducts a security education and also gets NDA in advance from employees, contractor and other third parties.

### Is there written policy for visitors?

- For visitors, Company proceeds security procedure in accordance with [Visitor Security Policy](guest.md).

### Is there a disaster alert system? If so, is it checked regularly?

- The office monitoring system is managed with Olleh CCTV telecop.
- A fire alarm system is set up.

### Are data storages in a secure place with strict access and monitoring system?

- Server room can be accessed through three times of biometrics(fingerprint).
- The server room is recorded around the clock through CCTV.
- Client data and backup data are being backed up on AWS Cloud for the business continuity.

### Are Anti-virus and Anti-spyware software installed on workstation and server?

- Linux : Vaccine software is not required due to separated network.
- Windows : For the print uses, Only one PC is settled with installed vaccine software.

### What measures does Company take to prevent workers from deletion of confidential information and data without authority? (Measures are including setting the limit on the email attachment, the constraint of USB, network segment and internet/proxy firewall and so on.)

- The company uses a mail forwarding service from Mailgun service. The maximum size of Email attachment is limited to 25MB.
- All the computers using Linux are forced to attach a security seal on a USB port. USB storage type cannot be connected by software.
- Internet network and the inner working network are physically separated.

### Are laptops and mobile devices used for production work? In the case of loss of these devices, what measures does the Company take?

- Every laptop used in the office is forced to attach a security seal on every port.
- Security seals are attached to cameras of a mobile device.

### Does the Company allow the employee to store client data online and offline via personal electronics?

- IN/OUT data of client is uploaded on AWS Cloud.
- Only authorized person can approach to the cloud server through personal account and MFA(Multi-Factored Authentication)

### Is there minimal password policy forcing on every worker and system?

- Password for cloud requires:
  - Eight(8) or more characters
  - Combination of English upper case letters, English lower case letters, numbers, and a special symbol.
  - MFA(Multi-Factor Authentication)
- Password for inner network requires:
  - Eight(8) or more characters
  - Combination of english upper case letters, english lower case letters, numbers and special symbol.
  
### Is the Company using wireless network technology? If so, please explain the Company's security system for the protection of confidential data from the wireless network.

- WIFI is managed with guest WIFI and WIFI for employees. The working network is separated safely.

### Are production data transmitted through security solution such as FTP, Aspera or private network? What kind of data transmission method does company use?

- Every data is only transmitted through AWS IAM(authentication system) and S3(storage)(AWS security policies are following MPAA. : https://aws.amazon.com/ko/compliance/mpaa/)

### If the Production data is physically moved to the driver, do you encrypt this driver? Can you explain how to give the security key to the worker who is in remote? Please explicate about the regulations of physically moving.

- We avoid a physical moving of data. We suggest the client to upload the data on the AWS S3. 


### Please describe how Company back up the data and the method to restore the data in the case of data loss by an unexpected accident. And how long does it take to restore?

- The data is backed up to the Cloud, AWS S3 Glacier for the business continuity.
- After the request, data restoration is completed within 24-48 hours.

### How does the Company notify clients of critical security issues or business issues? How does the Company notify clients of the accident that could affect the delivery of data? Please explain it in detail.

- IN/OUT data of client is uploaded on Cloud. The company uses cloud service to keep business continuity even in the case of an unexpected accident.
- If it fails to keep the deadline, the Company and the client need to discuss how to handle the issue.