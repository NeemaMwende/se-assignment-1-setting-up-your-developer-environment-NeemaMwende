[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15247491&assignment_repo_type=AssignmentRepo)
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

MY DOCUMENT : NEEMA MWENDE
1. Introduction
This document outlines the steps taken to set up a development environment on Ubuntu, including installing necessary tools, configuring version control, setting up a database, and optimizing the IDE for development.

2. Operating System
Ubuntu - We used Ubuntu as our operating system for setting up the development environment.

3. Text Editor/IDE - Visual Studio Code
Steps to Install and Configure Visual Studio Code:
   Update the package index:
      sudo apt update
   Install the required dependencies: 
      sudo apt install software-properties-common apt-transport-https wget
   Import the Microsoft GPG key: 
      wget -q https://packages.microsoft.com/keys/microsoft.asc -O- | sudo apt-key add -
   Enable the Visual Studio Code repository:
      sudo add-apt-repository "deb [arch=amd64] https://packages.microsoft.com/repos/vscode stable main"
   Install Visual Studio Code:
      sudo apt update
      sudo apt install code
   Launch Visual Studio Code:
      code

4. Version Control System - Git
Steps to Install and Configure Git:
      Install Git:
         sudo apt update
         sudo apt install git
      Configure Git:
         git config --global user.name "Your Name"
         git config --global user.email "your.email@example.com"


Creating and Initializing a GitHub Repository:
      Create a GitHub account:
         Visit GitHub and sign up.
      Create a new repository on GitHub:
         Go to your GitHub profile, click on "Repositories," and then "New."
      Clone the repository to your local machine:
         git clone https://github.com/yourusername/your-repository.git
         cd your-repository
      Initialize a Git repository:
         git init
      Make your firsy Commit:
         echo "# Your Project" >> README.md
         git add README.md
         git commit -m "Initial commit"
         git push origin main

5. Programming Languages and Runtimes - Python
Steps to Install Python:

      Install Python:
         sudo apt update
         sudo apt install python3 python3-pip
      Verify the installation:
         python3 --version
         pip3 --version

6. Package Managers - pip for Python
Steps to Install pip:

      Install pip:
         sudo apt install python3-pip
      Verify pip installation:
         pip3 --version

7. Database Configuration - MySQL
Steps to Install MySQL:

      Install MySQL:
         sudo apt update
         sudo apt install mysql-server
      Secure the MySQL installation:
         sudo mysql_secure_installation
      Start the MYSQL service:
         sudo systemctl start mysql
         sudo systemctl enable mysql
      Log into MYSQL: 
         sudo mysql -u root -p

8. Development Environments and Virtualization : Docker (Optional)
Steps to Install Docker:

      Install Docker:
         sudo apt update
         sudo apt install docker.io
      Start and enable Docker:
         sudo systemctl start docker
         sudo systemctl enable docker
      Verify Docker installation:
         docker --version

9. . Extensions and Plugins :  Visual Studio Code Extensions
Steps to Install Extensions:

      Open Visual Studio Code and navigate to the Extensions view:
      Click the Extensions icon in the Activity Bar on the side of the window or press Ctrl+Shift+X.

      Search for extensions:
      For example, search for "Python" to install the Python extension.

      Install the desired extensions:
      Click the Install button next to the extension name.

Essential Extensions:

      Prettier: Code formatter.
      ESLint: JavaScript/TypeScript linting.
      Python: Python language support.
      Docker: Docker integration.

10. Challenges and Solutions
Challenges Faced:

      Git Configuration Issues:
      Solution: Double-check the email and username configurations using git config --global --list and ensure they match the GitHub account.

      MySQL Installation Problems:
      Solution: Run sudo apt update before attempting installation and follow the prompts carefully during mysql_secure_installation.

      Extension Compatibility:
      Solution: Ensure that Visual Studio Code and the extensions are up to date to avoid compatibility issues.

11. My sample project: I attempted to create a dart simple project for taking in using details: 
Here is the github Link for the sample project : https://github.com/NeemaMwende/dart.git
