# Guided Lab: Securing Applications by Using Amazon Cognito

## Overview:
This lab demonstrates how to secure a Node.js web application using Amazon Cognito for authentication and authorization. The Birds App allows students to report and view bird sightings, with certain pages accessible only to authenticated users or administrators.

## 🧭 Objectives

- Configure an Amazon Cognito User Pool for authentication.

- Add users and groups (regular & admin).

- Configure an Amazon Cognito Identity Pool for authorization.

- Integrate Cognito with the Birds web app and DynamoDB.


# 🏗️ Architecture Overview

Initial Setup:

- Node.js app hosted on AWS Cloud9

- Static assets hosted on S3 + CloudFront

Final Setup:

- Cognito User Pool → User authentication

- Cognito Identity Pool → Role-based authorization

- DynamoDB → Stores bird sightings

- CloudFront → Distributes content securely


# 🧩 Key Steps

- Created a User Pool and added users (testuser, admin).

- Created an Administrators group and assigned the admin user.

- Updated app configuration in config.js and auth.js.

- Integrated Cognito Hosted UI for login.

- Configured Identity Pool for DynamoDB access.

- Tested user and admin login functionality.
  

# ⚙️ Technologies

- AWS Cognito

- AWS DynamoDB

- AWS Cloud9

- Amazon S3 & CloudFront

- Node.js


# 📸 Screenshots

Birds App login page
<img width="1297" height="675" alt="cl15" src="https://github.com/user-attachments/assets/c1774684-a98c-4949-86c4-2038c46e0c40" /> <img width="1365" height="653" alt="cl16" src="https://github.com/user-attachments/assets/5f2bb0f2-1f64-47fe-a66b-1adafa09251a" />

<img width="905" height="630" alt="cl17" src="https://github.com/user-attachments/assets/d53f44c6-c136-4c17-94f3-174527164d44" />


Cognito user pool setup
<img width="1349" height="463" alt="cl9" src="https://github.com/user-attachments/assets/dcb6a659-b4f9-4da2-8444-57c53e937a9e" />

<img width="1131" height="619" alt="cl12" src="https://github.com/user-attachments/assets/38cce1ad-009e-4134-ac3d-67ea15d180f6" />


Admin access validation
<img width="1349" height="616" alt="cl21" src="https://github.com/user-attachments/assets/74134030-ee2f-4c6e-8c89-a06c38f35a64" />


# 🏁 Result

✅ Authentication and authorization successfully implemented.
✅ Role-based access control enforced.
✅ Secure, token-based access to DynamoDB enabled.


# 🧠 Author

Joy Imarah
Medium Article → https://medium.com/@smartyjoy47/securing-the-birds-app-how-i-used-amazon-cognito-to-authenticate-and-authorize-users-on-aws-734037bf8dd7?postPublishedType=initial

LinkedIn → 
