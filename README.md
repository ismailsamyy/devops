# Automated Deployment and Management of a Secure Web Environment

This project demonstrates the automated deployment and management of a secure web environment using Docker, MySQL, phpMyAdmin, Nginx, Git (Bitbucket), Jenkins, and Ansible. The environment is designed to streamline container management, ensure secure access, and automate deployment processes.

## Features

- **Docker and Docker Compose**: Installed and configured Docker engine and Docker Compose to simplify container management.
- **MySQL and phpMyAdmin**: Deployed a MySQL container with custom user credentials and a default database, alongside a phpMyAdmin container for easy graphical interaction with the MySQL database.
- **Secure Nginx Proxy**: Configured an Nginx proxy container to manage incoming traffic, enforcing HTTPS on port 443 and restricting access to the Fully Qualified Domain Name (FQDN).
- **Automated Deployments**: Uploaded the codebase to a Bitbucket repository and implemented automated deployments via Jenkins, ensuring that code changes are automatically deployed upon upload.
- **Ansible Playbook**: Developed an Ansible playbook to automate the entire environment setup, including Docker installation and container orchestration.

## Getting Started

### Prerequisites

- **Docker**: Ensure Docker and Docker Compose are installed on your system.
- **Jenkins**: A running Jenkins instance with access to your Bitbucket repository.
- **Ansible**: Ansible installed on the control machine to execute playbooks.

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
