# URL Shortener Application Deployment with AWS Elastic Beanstalk
<p>Done By: Junior Developer Nehemiah Monrose</p> 
<p>Date: 11/11/2023</p>

## Table of Contents
-[Introduction](#introduction)
-[Requirements](#requirements)
-[Steps](#steps)
-[Diagram-Link](#diagram-link)


## Introduction
<p>This deployment demonstrates my basic understanding of Jenkins, which I use to run a Continuous Integration/Continuous deployment(CI/CD)pipeline and AWS Elastic Beanstalk to deploy my application Manually.</p>

## Requirements

- Jenkins
- AWS Elastic Beanstalk

# Steps

Step 1: I Navigated to AWS Console and searched EC2

Step 2: Created and Launched an EC2 Instance

Step 3: On the EC2 Instance, I created a bash script to install Jenkins and it's dependencies.

Step 4: After Jenkins is installed, I checked to see if Jenkins server is running using: ```bash sudo systemctl status jenkins ```.
 To start Jenkins I used this command ```bash sudo systemctl start jenkins```
 
Step 5: In a new tab to be able to access the Jenkins server I typed the public IP address of the ec2 instance, ":", 8080 e.g ```172.16.9.0:8080```

Step 6: Configured Jenkins following these steps :

Step 7: After Jenkins initial configuration it was time to create and run a build for the URl Shortener Application.See steps here:

