Processes and Signals
Project Overview
This project, part of the DevOps curriculum, focuses on processes and signals in the context of shell scripting and system administration. The tasks involve creating Bash scripts to manage processes, work with PIDs, handle signals, and understand essential concepts related to process management in Linux.

Project Details
Learning Objectives
At the end of this project, you should be able to:

Understand what a PID (Process ID) is.
Identify and explain the characteristics of a process.
Find a process' PID using various commands.
Terminate a process using signals.
Recognize different signals and their significance.
Write Bash scripts to perform process-related tasks.
Resources
Read or watch the following resources to gain a better understanding of the topics covered in this project:

Linux PID
Linux process
Linux signal
Process management in Linux
Man pages or help for commands: ps, pgrep, pkill, kill, exit, trap
For those interested in learning more about signals, check out this article.

Project Structure
The project is organized into several tasks, each focusing on specific aspects of process management and signals. The tasks include:

What is my PID

Write a Bash script that displays its own PID.
List your processes

Write a Bash script that displays a list of currently running processes.
Display all processes, for all users, including those without a TTY.
Present the information in a user-oriented format, showing process hierarchy.
Show your Bash PID

Write a Bash script that displays lines containing the word "bash" along with their PIDs.
Do not use pgrep and include a line to disable Shellcheck warning.
Show your Bash PID made easy

Write a Bash script that displays the PID and process name of processes containing the word "bash."
Do not use ps.
To infinity and beyond

Write a Bash script that displays "To infinity and beyond" indefinitely with a 2-second pause between each iteration.
Don't stop me now!

Write a Bash script that stops the process created in the previous task using the kill command.
Stop me if you can

Write a Bash script that stops the process created in task 5 without using kill or killall.
Highlander

Write a Bash script that displays messages and handles signals.
Another script should be created to kill the process created in task 5.
Beheaded process

Write a Bash script that kills the process created in task 7.
Process and PID file

Write a Bash script that creates a PID file, displays messages, and handles signals.
Manage my process

Write a Bash script and an init script to manage a background process.
Zombie

Write a C program that creates zombie processes and displays their PIDs.
How to Use
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/alx-system_engineering-devops.git
Navigate to the project directory:

bash
Copy code
cd alx-system_engineering-devops/0x05-processes_and_signals
Explore the task directories and corresponding files to understand each task's requirements.

Execute the provided Bash scripts and C programs to observe their behavior and fulfill the learning objectives.

Disclaimer
You are required to solve the tasks independently without copying or plagiarizing. Any form of plagiarism is strictly forbidden and will result in removal from the program.
