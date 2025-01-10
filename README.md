# Ansible Web Server Configuration

This repository contains an Ansible playbook to configure a web server on remote nodes. 
The playbook installs and configures Apache HTTPD, opens the necessary firewall port, 
and copies the web content to the server. The configuration is applied to all nodes listed in the Ansible inventory file.

## Prerequisites

1. **Ansible Installed**: Ensure you have Ansible installed on your local machine. You can install it via pip:
   ```bash
   yum install ansible
