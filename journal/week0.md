# Week 0 — Billing and Architecture

## Conceptual diagram

A conceptual model is a representation of a system. It consists of concepts used to help people know, understand, or simulate a subject the model represents. In contrast, physical models are physical object such as a toy model that may be assembled and made to work like the object it represents.

## My Archiectural Diagram:

![Diagram-Lucid-Charts](https://user-images.githubusercontent.com/65615660/219713098-a5ba72fb-52bf-4c66-8f4c-0f15dcc45022.png)

https://lucid.app/lucidchart/989b4121-e5cf-4225-ae19-a1c0414be990/edit?viewport_loc=-1086%2C-340%2C3328%2C1668%2C0_0&invitationId=inv_6f425134-1d10-4e1f-8741-0e946d04be24

## AWS Identity and Access Management (IAM)

- **Users**: An IAM user is a resource in IAM that has associated credentials and permissions. An IAM user can represent a person or an application that uses its credentials to make AWS requests.
- **Groups**: An IAM user group is a collection of IAM users. User groups let you specify permissions for multiple users, which can make it easier to manage the permissions for those users. 
- **Permissions**: IAM policies define permissions for an action regardless of the method that you use to perform the operation.
- **Roles**: An IAM role is an IAM identity that you can create in your account that has specific permissions. An IAM role is similar to an IAM user, in that it is an AWS identity with permission policies that determine what the identity can and cannot do in AWS. However, instead of being uniquely associated with one person, a role is intended to be assumable by anyone who needs it. Also, a role does not have standard long-term credentials such as a password or access keys associated with it. Instead, when you assume a role, it provides you with temporary security credentials for your role session.

### IAM Summary
![IAM-summary](https://user-images.githubusercontent.com/65615660/219838181-fb4fa9c9-179e-44f5-a4e4-a3ab3a1384b9.png)

## AWS Organization
AWS Organizations is an account management service that enables you to consolidate multiple AWS accounts into an organization that you create and centrally manage. AWS Organizations includes account management and consolidated billing capabilities that enable you to better meet the budgetary, security, and compliance needs of your business.

## Service Control Policies
Service control policies (SCPs) are a type of organization policy that you can use to manage permissions in your organization. 

## AWS Billing
The AWS Billing console allows you to easily understand your AWS spending, view and pay invoices, manage billing preferences and tax settings, and access additional Cloud Financial Management services.

## AWS Budgets
AWS Budgets is the simplest way to monitor your AWS spend and be alerted when you exceed or are forecasted to exceed your desired spending limit.

![Budgets](https://user-images.githubusercontent.com/65615660/219839595-2f17d11c-15f2-44bf-93c3-5046a17923ef.png)

## AWS Cloudshell
Using AWS CloudShell, a browser-based shell, you can quickly run scripts with the AWS Command Line Interface (CLI), experiment with service APIs using the AWS CLI, and use other tools to increase your productivity. The CloudShell icon appears in AWS Regions where CloudShell is available.

![Cloudshell](https://user-images.githubusercontent.com/65615660/219840319-cd67afcc-e0b1-4363-abc8-b172dec72c63.png)











