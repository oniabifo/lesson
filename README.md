# ANSIBLE PLAYBOOK INSTRUCTIONS
The first step is to register an account on AWS. 

Once an account has been created, You will create an ec2 instance using an Ubuntu Image


Follow the images below to create an ec2 instance on AWS

![alt text](<Screenshot 2024-02-27 at 9.35.11 AM.png>) 

Changes to Note: 
a. give the ec2 instance a name
b. also create a new key pair and call it a name. This key pair will be used to connect to the ec2 instance from local server

Once the ec2 instance has been succesfully launched, You will ssh into the instance using a command like this
ssh -i abi2.pem ubuntu@public-ip-address