Project: 0x0C Web Server
This project aims to familiarize you with web server setup and configuration using Bash scripting and Puppet manifests. You'll learn about installing and configuring Nginx, setting up domain names, redirection, and custom error pages.

Background Context
This project involves automating tasks related to configuring a web server, emphasizing the importance of automation in system administration and software engineering. By automating routine tasks, you can focus on more challenging and rewarding aspects of your work.

Learning Objectives
By completing this project, you'll gain knowledge on:

The main role of a web server
Child processes and their significance in web servers
Common HTTP requests and their purposes
Domain Name System (DNS) and its role
DNS record types such as A, CNAME, TXT, and MX
Resources
To enhance your understanding, you can refer to the following resources:

How the web works
Nginx documentation
HTTP specifications (RFC 7231, RFC 7540)
Linux man pages for commands like scp and curl
Requirements
Use vi, vim, or emacs as editors
All files must be interpreted on Ubuntu 16.04 LTS
Ensure files end with a newline character
Include a README.md file at the root of the project folder
Bash scripts must be executable and pass Shellcheck without errors
Use #!/usr/bin/env bash as the first line of all Bash scripts
Avoid using systemctl for restarting processes
Avoid plagiarism and follow copyright guidelines
Tasks Overview
Transfer a file to your server: Write a Bash script to transfer files securely using scp.
Install Nginx web server: Set up Nginx on your server to listen on port 80 and return "Hello World!" when queried at the root.
Setup a domain name: Configure DNS records to point your domain to your server's IP address.
Redirection: Configure Nginx to redirect /redirect_me to another page with a "301 Moved Permanently" status.
Not found page 404: Customize the Nginx server to display a custom 404 page containing the string "Ceci n'est pas une page".
Install Nginx web server (w/ Puppet): Use Puppet manifests to automate the installation and configuration of Nginx, including setting up redirection.
Copyright
© 2024 ALX. All rights reserved.

Note: This README provides an overview of the project tasks and requirements. For detailed instructions and scripts, refer to the respective files in the project directory.
