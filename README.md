# CS 320 Week 6 Lab - WordPress Automation

This repository contains a modular, multi-role Ansible architecture designed to automate the deployment and configuration of a WordPress stack.

## 📂 Project Architecture
- **site.yml** - The main playbook that orchestrates the deployment.
- **hosts** - The inventory file defining target servers.
- **group_vars/all.yml** - Centralized variables for the automation.

## 🛠️ Ansible Roles Included
* **stack_install**: Handles package installation for the web and database infrastructure.
* **stack_config**: Manages system configurations, security, firewall rules, and service tuning.
* **wordpress**: Deploys WordPress core files, configures database links, and sets up templates.
