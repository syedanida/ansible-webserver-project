# Ansible Webserver Deployment Project

This repository contains the configuration and deployment scripts for setting up and managing webservers using Ansible. The project demonstrates the use of Ansible to deploy an Apache web server on multiple virtual machines (VMs), configure it to listen on port 8080, and serve a simple HTML page.

## Repository Contents:
playbook.yml: Ansible playbook that installs and configures Apache on the VMs.
inventory: Ansible inventory file specifying the target VMs.
Documentation: A Word document with screenshots, setup instructions, and a demo of the project.

## Features:
Installation of Apache web server
Configuration of Apache to listen on a non-default port (8080)
Deployment of a custom HTML page to the web server root

## How to Run:
- To deply the webserver, use: 
> ansible-playbook -i inventory deploy.yml

- To undeploy the webserver, use:
> ansible-playbook -i inventory undeploy.yml

- To run the playbook, use:
> ansible-playbook -i inventory playbook.yml

## Result:
VM1: 
<img width="604" alt="image" src="https://github.com/user-attachments/assets/421a857e-fd1b-427e-aeb0-5afa9d7cb4a6">  


VM2:
<img width="599" alt="image" src="https://github.com/user-attachments/assets/c6177f2a-db3d-4e22-94b1-d9cc5a4c3eec">

