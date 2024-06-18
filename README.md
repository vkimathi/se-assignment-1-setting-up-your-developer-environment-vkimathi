[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15284722&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

Select the Download Method:

Windows 11 Installation Assistant: This tool is the fastest way to install Windows 11 on the device you're currently using.
Create Windows 11 Installation Media: This option allows you to create a bootable USB drive or DVD.
Download Windows 11 Disk Image (ISO): You can download the ISO file to use for a clean installation.
Using the Windows 11 Installation Assistant:

Click on "Download Now" under the Windows 11 Installation Assistant.
Run the downloaded file and follow the on-screen instructions to upgrade your current version of Windows to Windows 11.
Creating Installation Media:

Click on "Download Now" under Create Windows 11 Installation Media.
Run the Media Creation Tool and follow the instructions to create a bootable USB drive or DVD.
Boot from the USB drive or DVD to install Windows 11.
Downloading the ISO File:

Select "Download" under Download Windows 11 Disk Image (ISO).
Choose your preferred language and click "Confirm".
Select the 64-bit Download to start downloading the ISO file.
You can then create a bootable USB drive using tools like Rufus or use the ISO file in a virtual machine.
Installing Windows 11:

If you used the Installation Assistant, follow the on-screen instructions.
If you created a bootable USB drive or DVD, insert it into your computer, restart the system, and boot from the media. Follow the installation prompts.
Ensure your device meets the minimum system requirements for Windows 11, including TPM 2.0 and Secure Boot enabled in your BIOS settings. You can check these requirements and compatibility using the PC Health Check tool provided on the same page.

![alt text](<Screenshot 2024-06-18 234520.png>)

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

Visit the Official Visual Studio Code Download Page: Go to the Visual Studio Code Download Page.

Select Your Operating System:

Choose the appropriate version of VS Code for your operating system (Windows, macOS, or Linux).
Download the Installer:

For Windows:
Click on the Windows download link. This will download the installer (e.g., VSCodeSetup-x64-<version>.exe).
For macOS:

Install Visual Studio Code:

Windows:
Run the downloaded installer (VSCodeSetup-x64-<version>.exe).
Follow the installation wizard, accepting the license agreement and choosing the desired installation options.
Once the installation is complete, launch Visual Studio Code.

Initial Setup:

When you first launch Visual Studio Code, you may be prompted to install additional components or extensions depending on your development needs.
Customize your settings and install necessary extensions from the Extensions marketplace to enhance your workflow.

![alt text](<Screenshot 2024-06-19 002358.png>)

3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

Download Git from git-scm.com.
Run the installer and follow the setup instructions. You can accept the default settings for most options.

Configure Git
After installing Git, configure it with your name and email address. Open a terminal or command prompt and run:
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"

Create a GitHub Account
Go to GitHub and sign up for a new account if you don’t have one.
Follow the on-screen instructions to complete the registration process.

Initialize a Git Repository and Make Your First Commit
Step 1: Create a New Project Directory
Navigate to the directory where you want to create your project, then create and enter a new directory:
mkdir my-project
cd my-project

   ![alt text](<Screenshot 2024-06-19 004944.png>)
   ![alt text](<Screenshot 2024-06-19 010957.png>)
   ![alt text](<Screenshot 2024-06-19 010309.png>)

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

Install Python:
Go to the official Python download page.
Download the latest stable release of Python for Windows.
Run the installer and make sure to check the box that says "Add Python to PATH".
Follow the installation instructions, ensuring you select the option to install the pip package manager.

Verify the Installation
To verify that Python and pip have been installed correctly, open a terminal or command prompt and run:
python --version

Install Virtual Environment Tool
It's a good practice to use virtual environments for your projects to manage dependencies. Install virtualenv using pip:
pip install virtualenv

Set Up a Virtual Environment
Navigate to your project directory and create a virtual environment:
cd my-project
virtualenv venv

Activate the virtual environment:
venv\Scripts\activate

![alt text](<Screenshot 2024-06-19 012659.png>)

5. Install Package Managers:
   If applicable, install package managers like pip (Python).

   When you install Python from the official sources, pip is typically included. However, you can verify its installation and install it if necessary.

Windows, macOS, and Linux:
Check if pip is installed:
pip --version

![alt text](<Screenshot 2024-06-19 012937-1.png>)

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

Download MySQL Installer
Visit the MySQL Installer download page.
Choose the appropriate installer based on your system (either the web installer or the full installer).

Install MySQL
Run the Installer:

If you downloaded the web installer, run mysql-installer-web-community-5.7.x.x.exe.
If you downloaded the full installer, run mysql-installer-community-5.7.x.x.msi.
Choose a Setup Type:

Select the setup type that suits your needs. For most users, the "Developer Default" is sufficient as it includes MySQL Server, MySQL Workbench, and other useful tools.
Check Requirements:

The installer will check for any missing requirements. Install any required software (like Visual C++ Redistributable) if prompted.
Installation:

Click Execute to download and install the selected MySQL products.

Configure MySQL
Configuration Type:

Choose "Standalone MySQL Server / Classic MySQL Replication" for a standard single-server setup.
Server Configuration:

Select "Development Machine" for a low-resource usage setup suitable for development.
Keep the default settings for TCP/IP networking, ensuring that port 3306 is selected.
Optionally enable "Open Windows Firewall port for network access".
Authentication Method:

Choose "Use Strong Password Encryption" (recommended) or "Use Legacy Authentication Method" if needed for compatibility with older applications.
Set the Root Password:

Enter and confirm a strong password for the root user. You can also create additional user accounts if desired.
Windows Service:

Ensure "Configure MySQL Server as a Windows Service" is selected.
Optionally, select "Start the MySQL Server at System Startup".
Apply Configuration:

Click Execute to apply the configuration settings and complete the setup.

Verify Installation
Start MySQL Workbench:

Open MySQL Workbench (installed during the MySQL installation process).
Connect to the local MySQL server using the root account and password you set during configuration.
Test Connection:

Ensure that you can connect to the MySQL server and run queries.

![alt text](<Screenshot 2024-06-19 013455.png>)

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

![alt text](<Screenshot 2024-06-19 013959.png>)

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

Developer Environment Setup Documentation
Introduction
Purpose: Explain the purpose of the document—providing a guide to setting up a development environment for a specific project or general use.
Audience: Specify who the document is intended for (e.g., team members, collaborators, or yourself).

2. Environment Overview
Operating System: Specify the OS used (e.g., Windows 10, macOS Catalina, Ubuntu 20.04).
Tools and Software: List the essential tools and software installed (e.g., text editor/IDE, version control system, databases).

3. Setup Steps
3.1. Operating System Configuration
Outline any OS-specific configurations or settings relevant to your development workflow (e.g., firewall rules, user permissions).

3.2. Text Editor or IDE Setup
Text Editor/IDE: Describe the chosen editor/IDE (e.g., Visual Studio Code, IntelliJ IDEA).
Extensions/Plugins: List and briefly describe installed extensions/plugins for syntax highlighting, linting, etc.
Customizations: Document any editor-specific configurations or themes applied.

3.3. Version Control System (e.g., Git)
Installation: Provide steps for installing Git on the respective OS.
Configuration: Document Git configuration steps, including setting up SSH keys, global settings (name, email), and repository initialization.

3.4. Programming Languages and Runtimes
Python (if applicable):
Steps for installing Python, verifying the installation, and setting up a virtual environment.
Java, Node.js, etc.: Document installation steps for other required languages or runtimes.

3.5. Database Setup (e.g., MySQL)
Installation: Steps for downloading, installing, and configuring the database system.
Configuration: Outline configuration steps (e.g., setting up users, permissions).
3.6.


5. Conclusion
Recap the setup process and emphasize key points or considerations.
Invite feedback or suggestions for improving the documentation.


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
