+++
title = "Pre-requisites"
weight = 11
+++

## 1. Source code downloaded and deployed ##
In this section you will be directly with the source code used in the infrastructure setup for both the [AWS Hosted](/0-setup/1-aws-hosted.html) or [Self Hosted](/0-setup/1-self-hosted.html) method.
To do this please complete the [Get the code from GitHub](../99-the-code/5-deploy.html) section before proceding.

## 2. A valid Cognito user account ##
All the API endpoints are authenticated using Amazon Cognito. You will need to have the user credentials created from completing the section [3. Configuring the frontends](../3-web-apps/3-frontends/1-displayapp.html).

You will need to know the user name and password used to access the API. In this section of the workshop we will be securely storing the credentials into AWS Secrets Manager.