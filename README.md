[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15277611&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

5. Install Package Managers:
   If applicable, install package managers like pip (Python).

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 
ANSWER
Developer Environment Setup Documentation
Overview
This document outlines the steps I took to set up my developer environment on Windows eleven, along with configurations, customizations, and troubleshooting steps I encountered at some point of the procedure.

System Information
Operating System: Windows 11 was downloaded from https://www.microsoft.com/software-download/windows11
Primary Tools: Visual Studio Code, Git, Python
Additional Tools: MySQL
1. Installing and Configuring Git
Installation Steps:

I downloaded the Git installer from Git for Windows.
I ran the installer and followed the default setup commands.
I made positive that the choice "Git Bash Here" changed into checked for easy get entry to to Git commands.
Configuration:

I set my worldwide username and e-mail:
code;
git config --worldwide user.Name "My Name"
git config --international consumer.E-mail "my.Electronic mail@example.Com"
I tested the configuration:
code;
git config --list
Troubleshooting:

To make certain the git command was identified, I opened Git Bash or Command Prompt and typed git --version.

﻿2. Installing Python and pip
Installation Steps:

I downloaded the Python installer from Python.Org.
I ran the installer and made sure that the "Add Python to PATH" alternative become checked.
I followed the default setup commands to complete the installation.
Verification:

I opened Command Prompt and checked the Python model:
code;
python --model
I checked the pip version:
code;
pip --version
Troubleshooting:

If Python and pip were not delivered to the PATH, I manually introduced the Python set up directory to the PATH surroundings variable.

﻿3. Setting Up Visual Studio Code (VS Code)
Installation Steps:

I downloaded the installer from https://code.visualstudio.com/Download.
I ran the installer and accompanied the setup instructions.
Essential Extensions:

Python
GitLens
Prettier - Code Formatter
Configuration:

I opened VS Code and went to File > Preferences > Settings or pressed Ctrl   ,.
I configured person settings (e.G., enabled layout on store):
json
code;

    "editor.FormatOnSave": real,
    "python.PythonPath": "C:PathToPythonpython.Exe"

I set up the incorporated terminal to apply Git Bash:
json
code;

    "terminal.Included.Shell.Home windows": "C:Program FilesGitbinbash.Exe"

Troubleshooting:

For extension troubles, I reinstalled the extension or checked the extension logs.
For overall performance issues, I disabled useless extensions.

4. Installing MySQL
Installation Steps:

I downloaded the MySQL Installer for Windows from https://dev.mysql.com/downloads/installer/.
I ran the installer and selected the "Developer Default" setup type.
I followed the setup commands to put in MySQL Server, MySQL Workbench, and different components.
Configuration:

During set up, I installation a root password and configured MySQL as a Windows carrier.
I finished the installation and started the MySQL carrier.
Creating a New Database and User:

I opened MySQL Workbench and connected to the local MySQL server.
I created a new database and person:
sql.
code;
CREATE DATABASE mydb;
CREATE USER 'myuser'@'localhost' IDENTIFIED BY 'mypassword';
GRANT ALL PRIVILEGES ON mydb.* TO 'myuser'@'localhost';
FLUSH PRIVILEGES;
Verification:

I related to the MySQL database using MySQL Workbench or Command Prompt:
code;
mysql -u myuser -p mydb
Troubleshooting:

I ensured the MySQL provider became going for walks:
sh
code;
internet start MySQL
I checked MySQL Workbench logs for any mistakes.
Conclusion
This document covers the installation and configuration of essential tools for my developer environment on Windows 11, including Git, Python, Visual Studio Code, and MySQL. Following these steps helped me set up my environment efficiently and resolve common issues that arose.

#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
