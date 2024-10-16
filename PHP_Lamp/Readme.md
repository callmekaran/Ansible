# Ansible Role: PHP_LAMP Setup

This Ansible role sets up a LAMP (Linux, Nginx, MySQL, PHP) stack on Ubuntu servers, along with phpMyAdmin and necessary configurations for Nginx, Letsencrypt SSL, Linux Permission and Basic Commands.

## Requirements

- Ansible 2.9 or later
- Ubuntu 22.04 or later
  
**Usage**
  
- **Clone this repository or download the role into your Ansible roles directory.**

- **Customize the variables in your playbook or create a vars.yml file with your specific configurations.**

- **Run your playbook with Ansible:**

ansible-playbook main.yml **or**  ansible-playbook -i 'publicip,' -u user --private-key ./keypath main.yml




