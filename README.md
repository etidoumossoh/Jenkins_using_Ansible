# Jenkins_using_Ansible
Installing Jenkins on EC2 Ubuntu


This Ansible playbook automates the installation of Jenkins on an EC2 Ubuntu instance.

Follow the steps below to set up Jenkins on your machine:

# Prerequisites:

Ansible is installed on your local machine.


Access to an EC2 Ubuntu instance with sudo privileges.

# Steps:

Clone the Repository: git clone https://github.com/your-username/your-repo.git


Navigate to the Ansible Playbook Directory: cd your-repo


Edit Inventory File: Open the inventory.ini file and replace your-ec2-instance-ip with the actual IP address of your EC2 instance.


Move your Pem key into the directory and include it in the ansible.cfg document 


Run the Ansible Playbook: ansible-playbook jenkins-setup.yaml
