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
<img width="1358" height="545" alt="image" src="https://github.com/user-attachments/assets/72cfe685-687a-4d72-86ff-79e54aa1c5f6" />

Cognito user pool setup

Admin access validation


# 🏁 Result

✅ Authentication and authorization successfully implemented.
✅ Role-based access control enforced.
✅ Secure, token-based access to DynamoDB enabled.


# 🧠 Author

Joy Imarah
Medium Article → https://medium.com/@smartyjoy47/securing-the-birds-app-how-i-used-amazon-cognito-to-authenticate-and-authorize-users-on-aws-734037bf8dd7?postPublishedType=initial

LinkedIn → 
