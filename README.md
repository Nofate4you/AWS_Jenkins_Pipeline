
# Project Title: Nginx_Apache_Jenkins_Pipeline

## Overview
Deploy an automated CI/CD pipeline on Jenkins to streamline deployment using Jenkins, Apache2/Nginx, and GitHub Webhooks.

## How to Replicate the Project
1.First, set up your Jenkins environment on the localhost IP.

2.Open the GitHub repository you want for CI/CD and create a webhook.

3.Configure the webhook to match the Jenkins settings inside the pipeline.

4.Download Windows Subsystem for Linux (WSL) and install Ubuntu and Nginx.

5.Configure WSL to connect to your public IP address, and ensure Apache2 web server launches on your Windows OS.

6.In Jenkins configurations, add a build step using Windows Batch commands to make it work on a Windows system.

7.Set configurations that allow Apache2 to work on Windows OS, and configure these settings in WSL.

8.Verify that your pipeline successfully triggers when you update your code in GitHub.

9.Open the Apache2 website and verify that the Jenkins pipeline is linked.

## Highlights- **Technologies Used**:
-  Jenkins, SonarQube, Docker, GitHub Webhooks, Ubuntu, Apache2, Nginx

## Key Functionality
- Automated deployment pipeline.
- Continuous Integration and Continuous Delivery setup.
- Launching a site on Apache2/Nginx

## Challenges Overcome
- Setting up Jenkins and Ubuntu to run on WSL and Windows OS.
- Configuring the pipeline to be compatible with the public localhost IP.
- Configuring secure Webhooks.

## Screenshots
![image](https://github.com/user-attachments/assets/583a70b3-fe7a-4def-b794-a11a2624668c)
![image](https://github.com/user-attachments/assets/f5cb525c-175f-4728-876f-c08c761998de)
![image](https://github.com/user-attachments/assets/684dad8f-c189-4c7f-acc8-381df730c1c4)
![image](https://github.com/user-attachments/assets/c8b1e269-3f12-4139-9873-c138188e8d8a)
![image](https://github.com/user-attachments/assets/d52ed5a3-746a-4274-85d8-8bb31fa3eb74)
![image](https://github.com/user-attachments/assets/b7a2b51d-ed77-4908-bce6-41bf5e172049)


