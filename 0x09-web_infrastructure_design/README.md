Project README.md
Introduction
Welcome to our web infrastructure design project! In this project, we will be focusing on building and explaining different web infrastructure setups, starting from a simple web stack and progressing to more complex distributed, secured, monitored, and scalable setups. This project is part of our curriculum in the Software Engineering Foundations track, with a focus on DevOps and SysAdmin topics.

Team Members
Pascal Ndubi
Kelly NAMANO
Project Overview
Curriculum: SE Foundations
Average: 106.98%
Topic: Web infrastructure design
Weight: 1
Project Duration: Mar 21, 2024, 6:00 AM - Mar 25, 2024, 6:00 AM
Manual QA Review: Required

Learning Objectives
By the end of this project, we aim to achieve the following learning objectives:

Understand the basics of web infrastructure design.
Explain the roles of different components in a web stack.
Implement redundancy and high availability strategies.
Learn about DNS, load balancing, monitoring, security, and scalability in web infrastructure.
Resources
Before starting the project, make sure to review the following resources:

Network basics concept page
Server concept page
Web server concept page
DNS concept page
Load balancer concept page
Monitoring concept page
What is a database
What’s the difference between a web server and an app server?
DNS record types
Single point of failure
How to avoid downtime when deploying new code
High availability cluster (active-active/active-passive)
What is HTTPS
What is a firewall
Project Structure
The project is divided into several tasks, each focusing on a specific aspect of web infrastructure design. We will whiteboard each task, provide explanations, and document our solutions in this README.md file.

Tasks Overview
Simple web stack: Design a one-server web infrastructure with a LAMP stack.
Distributed web infrastructure: Design a three-server web infrastructure with load balancing.
Secured and monitored web infrastructure: Enhance the infrastructure with security measures and monitoring.
Scale up: Implement scalability by splitting components and using a load balancer cluster.
Task 1: Simple Web Stack
In this task, we will design a basic web infrastructure using a single server with a LAMP stack. We will include a web server (Nginx), an application server, a MySQL database, and configure the domain name www.foobar.com to point to our server's IP.

Diagram

Explanation
Server: The physical or virtual machine hosting our web infrastructure.
Domain Name: www.foobar.com is configured with a www record pointing to our server's IP.
Web Server (Nginx): Handles HTTP requests, serves static files, and can act as a reverse proxy.
Application Server: Executes application logic, processes dynamic content, and interacts with the database.
Database (MySQL): Stores and manages the website's data.
Issues
Single Point of Failure (SPOF): The entire infrastructure relies on a single server, leading to potential downtime if the server fails.
Downtime during maintenance: Deploying new code or restarting the web server may cause downtime.
Scalability: Limited scalability as traffic increases.
Task 2: Distributed Web Infrastructure
Coming soon...
