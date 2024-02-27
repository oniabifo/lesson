# CREATING AN EC2 INSTANCE
The first step is to register an account on AWS. 

Once an account has been created, You will create an ec2 instance using an Ubuntu Image


Follow the images below to create an ec2 instance on AWS

![alt text](<Screenshot 2024-02-27 at 9.35.11 AM.png>) 


![alt text](<Screenshot 2024-02-27 at 9.35.47 AM.png>)


![alt text](<Screenshot 2024-02-27 at 9.35.58 AM.png>)



Changes to Note: 
```
Give the ec2 instance a name you like
Also create a new key pair and call it a name. This key pair will be used to connect to the ec2 instance from your local server
```

Once the ec2 instance has been succesfully launched, You will ssh into the instance using a command like this

# CONNECTING TO AN EC2 INSTANCE FROM LOCAL
ssh -i abi2.pem ubuntu@public-ip-address


# ANSIBLE PLAYBOOK INSTRUCTIONS