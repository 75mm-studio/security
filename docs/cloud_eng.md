# Cloud Service Policy
75mm Studio Co., Ltd. shall use AWS cloud computing services.

MPAA-related Rule : MS-4.0(Business Continuity Plan), MS-6.0(Business Continuity Plan, Disaster Recovery), DS-10.9(Backup, Implemantation of Restoration System)

## Employee
- *Company* shall apply individual security policy for each user.
- Passwords for all individual account shall require eight or more characters including:
    - english upper case letters
    - english lower case letters
    - numbers
    - special symbol.
    - MFA(Multi-Factor Authentication)
- In the case of the client, the account is available only for a maximum of 90 days from the day of issuance.
- At the end of the project, accounts of external parties are removed upon the mutual consultation between the parties.
- In the case of loss of On-set device which has access right to the cloud, promptly report to the administrator and remove User Cloud key.

## Retiree
- After notice of dismissal, the retiree prepares a security pledge.
- Immediately after drawing up, *Company* shall remove AWS IAM access key.

## Data of Client
- Work data that the client has requested shall be stored on cloud service.
- *Company* shall store data on cloud service:
    - To prepare for the danger of building collapse and fire.
    - For BCP(Business Continuity Plan).
    
## Project Backup
- Every completed data will be backed up on the cloud(AWS Glacier) at the end of the project.
- *Company* shall store data on cloud service:
    - To prepare for the danger of building collapse and fire.
    - For BCP(Business Continuity Plan).
    
## Cloud service logs policy
- The log will be stored for 12 months on the basis of MPAA. (MPAA-related Rule : PS-16.2)
- Every data stored on storage generates logs according to [access log policy](https://docs.aws.amazon.com/ko_kr/AmazonS3/latest/dev/ServerLogs.html#BucketLoggingStatusChanges).
