# Project: 0x09. Web Infrastructure Design

## Overview

This project focuses on designing various web infrastructures, exploring concepts such as DNS, monitoring, web servers, network basics, load balancers, and servers. The goal is to develop a deeper understanding of these components and their interactions in creating robust and scalable web environments.

## Team Members
- Sylvain Kalache
- Desire Bikorimana

## Project Timeline
Start: Dec 21, 2023, 6:00 AM  
End: Jan 2, 2024, 6:00 AM

## Learning Objectives

After completing this project, you are expected to:

- Draw a diagram covering the web stack developed in SysAdmin/DevOps track projects.
- Explain the role of each component in the infrastructure.
- Understand system redundancy and potential single points of failure.
- Be familiar with acronyms like LAMP, SPOF, QPS.

## Concepts

Concepts covered in this project include DNS, Monitoring, Web Server, Network basics, Load balancer, and Server. 

### Resources
Read or watch:

- [Network basics concept page](https://intranet.hbtn.io/concepts/33)
- [Server concept page](https://intranet.hbtn.io/concepts/67)
- [Web server concept page](https://intranet.hbtn.io/concepts/68)
- [DNS concept page](https://intranet.hbtn.io/concepts/12)
- [Load balancer concept page](https://intranet.hbtn.io/concepts/46)
- [Monitoring concept page](https://intranet.hbtn.io/concepts/62)
- [What is a database](https://searchsqlserver.techtarget.com/definition/database)
- [What’s the difference between a web server and an app server?](https://stackoverflow.com/questions/936197/whats-the-difference-between-a-web-server-and-an-app-server)
- [DNS record types](https://support.dnsimple.com/articles/dns-record-types/)
- [Single point of failure](https://searchdatacenter.techtarget.com/definition/single-point-of-failure)
- [How to avoid downtime when deploying new code](https://www.digitalocean.com/community/tutorials/5-common-server-setups-for-your-web-application#single-web-server-with-proxy-server)
- [High availability cluster (active-active/active-passive)](https://www.pulsesecure.net/blog/high-availability-active-passive-or-active-active/)
- [What is HTTPS](https://www.cloudflare.com/learning/ssl/what-is-https/)
- [What is a firewall](https://www.cisco.com/c/en/us/products/security/firewalls/what-is-a-firewall.html)

## Tasks

### Task 0: Simple web stack
- Design a one-server web infrastructure hosting www.foobar.com using a LAMP stack.
- Components: 1 server, 1 web server (Nginx), 1 application server, 1 application files (code base), 1 database (MySQL), 1 domain name (foobar.com) with a www record pointing to server IP.
- Explain specifics about the infrastructure and identify issues (SPOF, Downtime during maintenance, Cannot scale with high traffic).
  
[View Diagram](https://drive.google.com/file/d/1dZ-ytHyWfTtxIfKaXMmTW8HBbvNZv7CS/view?usp=sharing)
[GitHub Link](https://github.com/Desire-2/alx-system_engineering-devops/blob/master/0x09-web_infrastructure_design/0-simple_web_stack.md)

### Task 1: Distributed web infrastructure
- Design a three-server web infrastructure hosting www.foobar.com.
- Components: 2 servers, 1 web server (Nginx), 1 application server, 1 load balancer (HAproxy), 1 set of application files (code base), 1 database (MySQL).
- Explain specifics about the infrastructure and identify issues (SPOF, Security issues, No monitoring).

[View Diagram](https://github.com/Desire-2/alx-system_engineering-devops/blob/master/0x09-web_infrastructure_design/1-distributed_web_infrastructure.md)

### Task 2: Secured and monitored web infrastructure
- Design a three-server web infrastructure hosting www.foobar.com with security measures.
- Components: 3 firewalls, 1 SSL certificate for HTTPS, 3 monitoring clients.
- Explain specifics about the infrastructure and identify issues (SSL termination at the load balancer, Single MySQL server for writes, Uniform components on servers).

[View Diagram](https://drive.google.com/drive/u/0/folders/1LAYC0YcJmRu5Jom4K_SkQcMFoTgU53hh)
[GitHub Link](https://github.com/Desire-2/alx-system_engineering-devops/blob/master/0x09-web_infrastructure_design/2-secured_and_monitored_web_infrastructure.md)

### Task 3: Scale up (Advanced)
- Add components to the web infrastructure, including a server, load balancer (HAproxy), and separate servers for web server, application server, and database.
- Explain the rationale behind each addition.

[View Diagram](https://drive.google.com/drive/u/0/folders/1LAYC0YcJmRu5Jom4K_SkQcMFoTgU53hh)
[GitHub Link](https://github.com/Desire-2/alx-system_engineering-devops/blob/master/0x09-web_infrastructure_design/3-scale_up.md)

## Quiz Questions
Great! You've completed the quiz successfully! Keep going!

## Copyright - Plagiarism
- Plagiarism is strictly forbidden.
- Solutions for tasks must be original and developed independently.
- No content from this project can be published.

## Requirements
- A README.md file is mandatory at the root of the project folder.
- For each task, provide a picture/screenshot of the whiteboarded diagram.
- Manually review each task.
- Upload screenshots of completed tasks to an image hosting service.
- Share the image links and GitHub file links.
- Whiteboard each task during a session with a mentor, staff, or student.

---