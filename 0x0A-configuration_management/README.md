0x0A Configuration Management
DevOps, SysAdmin, Scripting, CI/CD

Weight: 1
Project Duration: Apr 19, 2024, 6:00 AM - Apr 20, 2024, 6:00 AM
Checker Release: Apr 19, 2024, 12:00 PM
Auto Review: Launched at deadline
Background Context
During my time at SlideShare, I developed an auto-remediation tool called Skynet. Skynet was designed to monitor, scale, and fix Cloud infrastructure automatically. It utilized MCollective, a parallel job-execution system, to execute commands across servers simultaneously. However, a bug in the code caused unexpected server terminations, leading to a critical incident. This experience highlighted the importance of configuration management tools like Puppet in maintaining stable and reliable infrastructure.


Resources
Read or watch:
Intro to Configuration Management
Puppet resource type: file
Puppet’s Declarative Language
Puppet lint
Puppet emacs mode
Requirements
General:
Files interpreted on Ubuntu 20.04 LTS
Files end with a new line
Mandatory README.md file
Puppet manifests pass puppet-lint 2.1.1 without errors
Puppet manifests run without errors
Puppet manifests start with a comment explaining their purpose
Puppet manifest files have .pp extension
Versioning Note:
Ubuntu 20.04 VM with Puppet 5.5 preinstalled
Install puppet-lint using $ gem install puppet-lint
Tasks
0. Create a file
Objective: Create a file using Puppet.

File path: /tmp/school
File permission: 0744
File owner: www-data
File group: www-data
File content: "I love Puppet"
Repo:
GitHub: alx-system_engineering-devops
Directory: 0x0A-configuration_management
File: 0-create_a_file.pp
1. Install a package
Objective: Install Flask package from pip3 using Puppet.

Package: Flask
Version: 2.1.0
Repo:
GitHub: alx-system_engineering-devops
Directory: 0x0A-configuration_management
File: 1-install_a_package.pp
2. Execute a command
Objective: Create a Puppet manifest to kill a process named killmenow.

Use the exec Puppet resource
Utilize pkill command
Repo:
GitHub: alx-system_engineering-devops
Directory: 0x0A-configuration_management
File: 2-execute_a_command.pp
Conclusion
Configuration management tools like Puppet are crucial for maintaining infrastructure reliability and automating tasks efficiently. This project aims to familiarize users with Puppet's basic syntax and demonstrate its capabilities in managing files, installing packages, and executing commands. Happy scripting! 😊
