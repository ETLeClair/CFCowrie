# CFCowrie
## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)

## General info
Cloudformation Template to automate setup of the SSH based honeypot Cowrie
	
## Technologies
Project is created using:
* AWS CloudFormation
* Cowrie v2.0.2 https://github.com/cowrie/cowrie 
	
## Setup
You can set this up either using `aws-cli` or using the AWS console. You will need to provide the following four pieces of information:

`SSHLocation` which is the IP you will want to access it in a management capability.\
`MGMTPort` which is the port you will manage the worker node with (For SSH access).\
`KeyName` which is the SSH keypair that you would like to be able to SSH to the server.\
`InstanceType` which is the size of the Honeypot you want to provision. As of now, I set the list of instances you can provision to be small.\
