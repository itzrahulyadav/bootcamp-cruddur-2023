# Week 0 — Billing and Architecture

My Lucid diagram - [link](https://lucid.app/lucidchart/invitations/accept/inv_6b74d27a-d674-43f2-8a55-eedfdcae0c0d)

![1676534768244_architectural diagram](https://user-images.githubusercontent.com/65400893/220087110-5979c102-d976-4819-b041-64b25786fbae.jpeg)

## Create an AWS Acccount

- I Created my aws account from [here](https://aws.amazon.com/)
- Enabled MFA on the root account
- Created a group and name the group as admin , provide permssion as AdministratorAccess
- Created a user and add user to the admin group
- Enable MFA on the IAM user
- Disable the root user access key and access key ID

## Create a Budget
- Created a budget of 5$ as I have already exceeded my Free tier budget.
- Turned on the notifications to recieve the billing alerts in email.

## Install AWS CLI

To install AWS CLI i refered the AWS documentation. I have a windows computer so I installed using powershell.If you are using windows then use the command below.

```
msiexec.exe /i https://awscli.amazonaws.com/AWSCLIV2.msi
```

## Summary

| Homework      | Completed     | Not Completed  |
| ------------- |:-------------:| -----:|
| Watched Week 0 - Live Streamed Video   | ✔ |  |
|Watched Chirag's Week 0 - Spend Considerations   | ✔     |    |
| Watched Ashish's Week 0 - Security Considerations | ✔      |   |
|Recreate Logical Architectual Diagram in Lucid Charts|✔      |   |
|Recreate Conceptual Diagram in Lucid Charts|✔      |   |
| Create an Admin User| ✔      |   |
| Use CloudShell | ✔   |   |
| Generate AWS Credentials |✔      |   |
| Installed AWS CLI | ✔   |   |
| Create a Billing Alarm | ✔      |   |
| Create a Budget | ✔  |   |
