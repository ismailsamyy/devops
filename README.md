#Automated Deployment and Management of a Secure Web Environment
This project demonstrates the automated deployment and management of a secure web environment using Docker, MySQL, phpMyAdmin, Nginx, Git (Bitbucket), Jenkins, and Ansible. The environment is designed to ensure secure, efficient, and scalable web services with automated deployments.

Project Overview
This project includes:

Docker & Docker Compose: Installed and configured Docker engine and Docker Compose to streamline the management of multiple containers.

MySQL & phpMyAdmin: Built and deployed a MySQL container with custom user credentials and a default database. A phpMyAdmin container was also deployed to allow easy graphical interaction with the MySQL database.

Nginx: Configured a secure Nginx proxy container to manage incoming traffic. HTTPS is enforced on port 443, and access is restricted to the Fully Qualified Domain Name (FQDN).

Bitbucket & Jenkins: Uploaded the codebase to a Bitbucket repository and implemented automated deployments using Jenkins. Code changes are automatically deployed upon upload, ensuring continuous delivery.

Ansible: Developed an Ansible playbook to automate the entire environment setup. This includes Docker installation, container orchestration, and the deployment of services.

Getting Started
Prerequisites
Ensure that the following are installed on your system:

Docker
Docker Compose
Ansible
Jenkins (for CI/CD)
Git
