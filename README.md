[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15293458&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11
   
  # Download and install of windows

   # Step 1: Purchase a Windows License
 . Obtain a valid Windows license: You can purchase a Windows license from the Microsoft Store or an authorized retailer.

   # Step 2: Download Windows Installation Media
 . Go to the Microsoft Windows download page: Visit [Microsoft's Windows 10 Download page](https://www.microsoft.com/en-us/software-download/windows10).
 . Download the Media Creation Tool: Click on "Download tool now" to download the Media Creation Tool.
 . Run the Media Creation Tool: Follow the on-screen instructions to create installation media on a USB drive or DVD.

   # Step 3: Prepare Installation Media
 . Insert a USB drive: Ensure the USB drive has at least 8GB of space and is empty.
 . Use the Media Creation Tool: Select "Create installation media for another PC" and follow the instructions to create the installation media on your USB drive.

   # Step 4: Install Windows
 . Insert the USB drive into the target PC: Make sure the PC is powered off before inserting the USB drive.
 . Boot from the USB drive: Restart the PC and enter the BIOS/UEFI settings (usually by pressing a key like F2, F12, Delete, or Esc during     startup). Set the USB drive as the first boot device.
 . Follow the installation prompts: The Windows Setup will launch. Follow the on-screen instructions to install Windows. You'll need to select your language, time, and keyboard preferences, and enter your Windows license key when prompted.

   # Step 5: Complete the Installation
 . Set up Windows: After installation, follow the on-screen setup instructions to configure Windows settings.
 . Install drivers and updates: Once Windows is installed, ensure you install all necessary drivers and run Windows Update to get the latest updates and patches.

Notes:
- Backup your data: Before installing Windows, ensure you back up all important data as the process will erase everything on the target drive.
- Compatibility check: Make sure your PC meets the minimum system requirements for the version of Windows you plan to install.

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

   # Download Visual Studio Code:
   - Go to the [Visual Studio Code download page](https://code.visualstudio.com/Download). 
   - Click on the Windows download button to download the installer.(<Screenshot (3).png>)
   -  Run the Installer: - Open the downloaded `.exe` file.
     Follow the installation prompts:
     Accept the agreement and click "Next". 
     Choose the installation location and click "Next".
     Select additional tasks (e.g., creating a desktop icon, adding to PATH), then click "Next". 
     Click "Install" to start the installation. 
     Once the installation is complete, click "Finish" to launch Visual Studio Code
     Launch Visual Studio Code: - Open the applications menu or by typing code in the terminal

   # Setting Up Visual Studio Code: 
      1.Install Python Extension: 
      - Open Visual Studio Code. 
      - Go to the Extensions view by clicking the square icon on the sidebar or pressing `Ctrl+Shift+X`. 
      - Search for "Python" and click "Install" on the Python extension by Microsoft. 
      2.Configure Python Interpreter: 
      - Open the Command Palette by pressing `Ctrl+Shift+P`. 
      - Type `Python: Select Interpreter` and select the appropriate Python interpreter for your project. 
      3.Create a New Project:
      - Open a new folder or workspace for your project by clicking on "File" > "Open Folder".
      - Create a new Python file by clicking on "File" > "New File" and save it with a '.py' extension.
      4.Run Python Code: 
      - Write a simple Python script to test the setup, for example: python print("Hello, Visual Studio Code!") 
      - Run the script by right
       -clicking in the editor and selecting "Run Python File in Terminal" or by pressing `F5`. By following these steps, you can download, install, and set up Visual Studio Code for your Python development needs.

3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

    # Installation of Git:

   # Step 1: Go to the Git Download page
   - Open a web browser(e.g Google Chrome ,Mozilla Firefox ,Microsoft Edge)
   - Go to the official Git website: git-scm.com

   # Step 2: Select the operating system
   - Clink on the appropiate operating system(Windows ,macOS or Linux)
   - Select the architecture(32-bi![alt text](<Screenshot (11).png>)t or 64-bit) that matches your system ![alt text](<Screenshot (2).png>)
    

   # Step 3: Choose the installation package
   - Select the installation package(installer or zip archive)that suits your needs
   - For Windows ,choose the "Git for windows" installer(git-install.exe)
   - For macOS choose the "Git for macOS" installer (git-install.pkg)
   - for Linux,choose the appropriate package for your distribution(e.g Ubuntu,Debian,Fedora)

   # Step 4: Download Git
   - Click on the "Download" button start to the dwonload process
   - Wait for the dwonload to complete(depending on your internet connection)

   # Step 5:  Run installer (Windowns and macOS)
   - Once the download is complete, run the installer
   - Follow the prompts to accept the licensing agreement and choose the installation location
   - Select the components to install(e.g Git Bash,Git GUI)
   - Follow the prompts to complete the installatiom process

    # Configure Git:
   - Open a Git bash run as administrator (it gets installed with Git for windows)
   - Verify installation
     git --version
   - Set your username and email adress
     git config --global user.name "Your Name"
     git config --global user.email"youremail@example.com"
   - Run command 
     git config --global core.editor "your_preferred_editor"(replace "your_preferred_editor with your actual preferred editor for Gite.g VS Code)
   
    # Create a Github Account:
   - Go to the github.com on your web browser and Click on sign up
   - Choose plan (free or paid) and entre your email adress
   - Create a username and password
   - Provide some basic information(name,email,etc)
   - click on "Create account"

    # Initialize a Git Repository:
   - Log in your Github account
   - Click on the + icon in the top right corner and select "New repository"
   - Entre a name and description for your repository
   - Choose the respository type(pulic or private)
   - Click on "Create repository"

    # Initialize a Git Repository on Your Local Machine:
   - Open Git Bash (or a terminal)
   - Navigate to the directory where you want to create your repository
   - Run the command `git init` to initialize a new Git repository
   - Run the command `git add .` to stage all files in the directory.
   - Run the command `git commit -m "Initial commit"` to commit the changes. 

     # Link Your Local Repository to GitHub:
   - Run the command `git remote add origin https://github.com/yourusername/your-repo-name.git
   - Run the command `git push -u origin master` to push your changes to GitHub and set the upstream tracking information. 

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.\
   
   # Step 1: Download Python
   - Go to the official Python website:http://www.python.org!
   - Click on the "Download  Python" button![check](<Screenshot (5).png>)
   - Select the appropriate version for your operating system(windows)
   - Click on the "Download "button to start the download process

   # Step 2: Install Python
   - Once the download is complete ,run the installer(python-install exe)
   - Follow the prompts to accept the licensing agreement and choose the installation location
   - select the components to install(e.g IDLE,pip)
   - Follow the prompts to the complete the installation process
   
   # Step 3: Configure Python
   - After installation , open terminal or command prompt
   - Run the command 'python --version' to verify the installation![command prompt example](<Screenshot (7).png>)
   - Run the command 'pip --version' to verify the installation of pip(the package manager for python)
   - Configure your Python environment by setting the 'PATH' veriable(optional)
     For windowns:
     Right-click on "Computer" or "This PC" and select "Properties"
     Click on "Advanced system settings"
     Click on "Environment Variables"
     Under "System Variables", scroll down and find the "Path" variable, then click "Edit"
     Click "New" and add the path to the Python executable (usually `C:\Python3x\bin`)

     challenges can be incorrect version (e.g 32-bit instead of 64-bit)and slow internet connection(Python can take alot of time if u have a slow internet)

   Python installed and configured on the machine

5. Install Package Managers:
   If applicable, install package managers like pip (Python).
   
  # Open Command Line Interface:
   - Windows: Open Command Prompt.
   

  #  Install a Package:
   - Use the following command to install a package. Replace `package-name` with the name of the package you want to install:
     ```bash
     pip install package-name
     ```
   - For example, to install the `requests` package:
     ```bash
     pip install requests
     ```

  # Verify Installation:
   - You can verify that the package is installed by trying to import it in a Python script or interactive shell:
     ```python
     import requests
     print(requests.__version__)
     ```

By following these steps, you can download, install, and use pip to manage Python packages on your system.



6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

# Download MySQL Installer:
   - Go to the [MySQL Downloads page](https://dev.mysql.com/downloads/installer/).
   - Choose the "MySQL Installer for Windows".![alt text](<MYSQL WEBSEITE-1.png>)
   - Click on "Download" and select "No thanks, just start my download".

# Run the Installer
   - Once the download is complete, run the installer.

# .Choose Setup Type:
   - You will be prompted to choose a setup type. The "Developer Default" is suitable for most purposes, but you can choose another type if it better suits your needs.

# .Install:
   - Click on "Execute" to download and install MySQL server and other components.

# .Configuration:
   -  After the installation is complete, you will need to configure the MySQL server.
   -  Follow the prompts to set the server configuration type, port number, and root password.
   - Optionally, you can create a MySQL user account.

# .Complete Installation:
   - Finish the installation and configuration.
   verify Installation:
Regardless of the operating system, you can verify the installation by logging into the MySQL shell:

```bash
mysql -u root -p
``` 
Enter the root password you set during the installation process.

These steps should guide you through the installation of MySQL on your system.



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
