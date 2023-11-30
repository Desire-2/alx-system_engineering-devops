
0x08. Networking basics #1
Overview
This project focuses on networking basics, covering fundamental concepts related to IP addresses, localhost, and network interfaces. The tasks involve writing Bash scripts to configure IP resolutions, display active IPv4 IPs, and create a script to listen on a specific port.

Project Details
Author: Sylvain Kalache
Weight: 1
Start Date: Nov 29, 2023 6:00 AM
End Date: Dec 1, 2023 6:00 AM
Checker Release: Dec 1, 2023 6:00 AM
Auto Review: Will be launched at the deadline
Learning Objectives
Upon completion of this project, participants should be able to:

General
Understand what localhost/127.0.0.1 is
Recognize 0.0.0.0 as a special address
Comprehend the purpose of the /etc/hosts file
Display active network interfaces on their machine
Copyright - Plagiarism
Participants must develop their solutions to meet the learning objectives. Plagiarism is strictly forbidden and will result in removal from the program.

Resources
Read or watch the following to aid your learning:

What is localhost
What is 0.0.0.0
What is the hosts file
Netcat examples
Man or help for the following commands:

ifconfig
telnet
nc (netcat)
cut
Requirements
General
Allowed editors: vi, vim, emacs
Interpretation on Ubuntu 20.04 LTS
Files should end with a new line
A README.md file at the root of the project folder is mandatory
All Bash script files must be executable
Bash scripts must pass Shellcheck (version 0.7.0 via apt-get) without any errors
The first line of Bash scripts should be #!/usr/bin/env bash
The second line of Bash scripts should be a comment explaining the script's purpose
Tasks
0. Change your home IP
Objective: Write a Bash script to configure an Ubuntu server to meet the following requirements:

localhost resolves to 127.0.0.2
facebook.com resolves to 8.8.8.8.
See the example provided in the task description for reference.

Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x08-networking_basics_2
File: 0-change_your_home_IP
1. Show attached IPs
Objective: Write a Bash script to display all active IPv4 IPs on the machine it's executed on.

See the example provided in the task description for reference.

Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x08-networking_basics_2
File: 1-show_attached_IPs
2. Port listening on localhost (Advanced)
Objective: Write a Bash script that listens on port 98 on localhost. This script can be used for debugging socket connection issues, testing firewall rules, etc.

See the example provided in the task description for reference.

Repo:

GitHub repository: alx-system_engineering-devops
Directory: 0x08-networking_basics_2
File: 100-port_listening_on_localhost
