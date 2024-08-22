Automated Deployment and Management of a Secure Web Environment
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
Installation & Setup
Clone the Repository:

bash
Copy code
git clone <repository-url>
cd <repository-directory>
Configure Environment:

Update the .env file with the necessary credentials and settings, such as MySQL root password, phpMyAdmin credentials, and Nginx settings.

Run the Ansible Playbook:

Execute the Ansible playbook to set up the environment:

bash
Copy code
ansible-playbook -i hosts setup.yml
Deploy with Docker Compose:

Start the environment with Docker Compose:

bash
Copy code
docker-compose up -d
Access Services:

MySQL: http://<FQDN or IP>:3306
phpMyAdmin: http://<FQDN or IP>/phpmyadmin
Nginx (with HTTPS): https://<FQDN>
Automated Deployments with Jenkins
Ensure Jenkins is configured to monitor the Bitbucket repository. Upon code updates, Jenkins will automatically trigger a build and deploy the updated 
