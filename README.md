# Project Details

This particular cloud devops project aims to show how ansible can be used to deploy infrastructure in while deploying AWS cloudformation templates.

## Useful skills
IaC with Ansible and CloudFormation, bash scripting, cloud infrastructure.

## Specific configuration

This particular project has two files with one as a cloudformation template (.cfn) and the other is an ansible file (.asb). The idea of the work is that we run the cloud formation template then the creation of the server that manages the application in the user data of the config in cloudformation makes a call to the main ansible file which then performs the tasks in the folder. 

There are two tasks name:

- roleos
- rolebackend
