## Authentication vs. Authorization
**Key distinctions in security access:**
Authentication: Verifies if the user is really who they claim to be and if they have access (Login).
Authorization: Determines the specific permissions the user has (what they can do).

## IAM Terminology
Core concepts of Identity and Access Management (IAM):

* **IAM Resource:** The objects within AWS that you can work with
* **IAM Entity:** The users and roles that can be authenticated
* **IAM Identity:** Representation of the person or service seeking access
* **Principal:** A person or application that can make a request for an action or operation on an AWS resource

## IAM for AWS Access Control
Components used to manage access:

* **IAM Role:** An identity with specific permissions that is assumable by anyone who needs it
* **IAM Group:** A collection of IAM users. You can use groups to specify permissions for multiple users at a time
* **IAM Policy:** A document that defines one or more permissions