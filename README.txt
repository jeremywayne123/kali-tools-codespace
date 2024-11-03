# Kali Tools in GitHub Codespace

This repository provides a setup for running a cloud-based development environment on GitHub Codespaces with some commonly used penetration testing tools. While not a full Kali Linux VM, this configuration allows you to work with various tools that can perform security assessments directly in the GitHub cloud.

## Features

- Pre-configured environment with basic tools commonly used in penetration testing.
- Uses a Docker-based devcontainer for easy setup.
- Access to terminal commands for running security tools.

## Getting Started

### Prerequisites

- A GitHub account with access to GitHub Codespaces.
- Basic understanding of navigating the terminal and GitHub features.

### Creating Your Codespace

1. Clone this repository or simply click on the green "Code" button in this repository and choose **Open with Codespaces**.
2. Click on **+ New codespace**.
3. Wait for the environment to be built and ready.

### Default Tools Installed

The following tools are installed in your Codespaces environment:

- `nmap`: A powerful network scanning tool.
- `openvas`: Open Vulnerability Assessment System for scanning network vulnerabilities.
- `sqlmap`: An automated tool for SQL injection detection and exploitation.
- `nikto`: A web server scanner to find vulnerabilities.

### Usage

Once the setup is complete, open the terminal and you can use the installed tools. Here are examples of how to run some of them:

- **Nmap**:
  ```bash
  nmap -sP <target_ip>
