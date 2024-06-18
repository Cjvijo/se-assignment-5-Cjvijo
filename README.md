[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15276225&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
# Installation and Navigation of Visual Studio Code (VS Code)
# Instructions:
# Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.
 
 # Answer:
## Prerequisites
## Before installing Visual Studio Code, ensure your Windows 11 system meets the following requirements:

Operating System: Windows 7 or later (including Windows 11).
Disk Space: At least 350 MB of free disk space.
Internet: An active internet connection is required for downloading the installer.
Steps to Download and Install Visual Studio Code on Windows 11

## Step 1: Download the Installer
Open a web browser (like Microsoft Edge or Google Chrome).
Go to the official Visual Studio Code website: https://code.visualstudio.com/Download.
The website should automatically detect your operating system and provide a download link for Windows. Click on the "Download for Windows" button.
Save the installer file (VSCodeSetup-x64-{version}.exe) to your computer.

## Step 2: Run the Installer
Once the download completes, locate the downloaded VSCodeSetup-x64-{version}.exe file. Usually, you can find it in your browser's download folder or wherever you chose to save it.
Double-click on the installer file to start the installation process.
If prompted by the User Account Control (UAC) dialog box, click "Yes" to allow the installer to make changes to your device.

## Step 3: Install Visual Studio Code
The VS Code Setup Wizard will launch. Click "Next" to begin the installation.
Choose the destination folder where you want to install Visual Studio Code. The default location is usually C:\Users\Eng John M\AppData\Local\Programs\Microsoft VS Code. You can change this if needed by clicking on "Browse...".

Click "Next" to proceed.

Optionally, you can select additional tasks such as creating a desktop shortcut and adding to the PATH. These are optional but can be helpful for quick access.

Click "Next" again.

Finally, click "Install" to start the installation process.

## Step 4: Complete the Installation
Wait for the installation process to complete. This may take a few moments.

Once done, you will see a "Completing the Visual Studio Code Setup Wizard" screen. Ensure the "Launch Visual Studio Code" checkbox is checked if you want to open VS Code immediately after installation.

Click "Finish" to exit the setup wizard.

Visual Studio Code is now installed and ready to use on your Windows 11 system.

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

   # Answer
   After installing Visual Studio Code (VS Code), here are some initial configurations and settings you should consider adjusting for an optimal coding environment:

### a. Set Up Integrated Terminal
VS Code comes with an integrated terminal that allows you to run shell commands directly within the editor. Configure the default shell (like Command Prompt, PowerShell, or Git Bash) that you prefer to use:

Press `Ctrl + `` to open the integrated terminal.
Click on the dropdown arrow at the top-right corner of the terminal panel.
Select "Select Default Shell" and choose your preferred shell.

### b. Adjust Font and Theme
Customize the editor's appearance for better readability:

Go to File > Preferences > Settings (or press Ctrl + ,).
Search for "Font Family" and "Font Size" to adjust the text appearance.
Choose a theme (Color Theme) that suits your preference under File > Preferences > Color Theme.

### c. Install Essential Extensions
Extensions enhance VS Code's functionality. Here are some essential extensions:

GitLens: Provides Git integration with advanced features.
Bracket Pair Colorizer: Colorizes matching brackets to improve code readability.
ESLint or Pylint: For JavaScript or Python, respectively, to lint your code for errors.
Live Server: Launches a local development server with live reload feature.

To install extensions:
Go to the Extensions view (Ctrl + Shift + X).
Search for the extension name and click "Install".

### d. Customize Keyboard Shortcuts
Adjust keyboard shortcuts to streamline your workflow:

Go to File > Preferences > Keyboard Shortcuts (or press Ctrl + K Ctrl + S).
Modify existing shortcuts or create your own by clicking on the pencil icon next to a command.

### e. Configure Workspace Settings
Modify workspace-specific settings if needed:

Create a settings.json file in the .vscode directory of your project.
Add settings like file associations, editor settings, or language-specific configurations.

### f. Set Up Git Integration
If you're working with Git repositories:

Ensure Git is installed on your system and accessible from the command line.
Open a folder with a Git repository to automatically enable Git features in VS Code.

### g. Enable Auto Save (Optional)
Consider enabling Auto Save for automatic saving of changes:

Go to File > Auto Save and choose your preferred option (onWindowChange, afterDelay, or onWindowChange).

### h. Explore Additional Settings
Explore other settings and configurations based on your specific needs:

Adjust editor behavior (editor.tabSize, editor.formatOnSave).
Customize language-specific settings ([languageId].*).

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

   # Answer
   Visual Studio Code (VS Code) has a user-friendly interface designed to enhance productivity and ease of use for developers. Here are the main components of the VS Code user interface:

## a. Activity Bar
Purpose: 
The Activity Bar is located on the far left side of the VS Code window. It provides quick access to different views and functionalities within the editor. By default, it includes icons for the following sections:

## Explorer: 
Allows navigation through your project files and folders.

## Search: 
Provides tools for searching across your project.

## Source Control: 
Integrates with version control systems like Git.

## Run and Debug: 
Enables running and debugging of your code.

## Extensions: 
Manages VS Code extensions.
Clicking on any of these icons switches the content of the Side Bar to the corresponding view.

## b. Side Bar
## Purpose: 
The Side Bar is located next to the Activity Bar and displays contextual information and controls based on the selected view (e.g., Explorer, Search, Source Control). Key components include:

## File Explorer: 
Shows a hierarchical view of your project's files and folders.

## Search Results: 
Displays search results when searching within your project.

## Git Changes: 
Lists changes made to files tracked by Git.

## Debug Controls: 
Provides controls for debugging sessions.

## Extensions: 
Shows installed extensions and their configurations.

## c. Editor Group
## Purpose: T
he Editor Group occupies the central area of the VS Code window and consists of one or more editor tabs where you can open and edit files. Key features include:

## Tabs: 
Each tab represents an open file or editor session.

## Split View: 
Allows splitting the editor horizontally or vertically to view and edit multiple files simultaneously.

## Focus Mode: 
Maximizes the editor to remove distractions from other UI elements.
You can switch between open files by clicking on their respective tabs or using keyboard shortcuts (Ctrl + Tab to cycle through tabs).

## d. Status Bar
## Purpose: 
Located at the bottom of the VS Code window, the Status Bar provides information about the current file and workspace, along with useful actions and settings. 
Key components include:

## Language Mode: 
Displays the programming language associated with the active file.

## Line Endings: 
Indicates the line endings used in the active file (e.g., LF for Unix, CRLF for Windows).

## Encoding: 
Shows the character encoding used for the active file (e.g., UTF-8).

## Git Branch: 
Displays the current Git branch and status (e.g., changes to commit).

## Notifications: 
Provides quick access to notifications and updates from extensions.
Additional settings and actions such as indentation type, language selection, and view modes can also be accessed from the Status Bar.

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

# Answer
The Command Palette in Visual Studio Code (VS Code) is a powerful feature that allows users to access various commands and functionalities through a text-based interface. It provides a quick and efficient way to execute commands, search for actions, and navigate within VS Code without relying on menus or toolbar buttons.

## Accessing the Command Palette
To access the Command Palette in VS Code, you can use the following methods:

## Keyboard Shortcut: 
Press Ctrl + Shift + P (Windows/Linux) or Cmd + Shift + P (Mac). This shortcut opens the Command Palette at the top of the editor window.

## Menu Option: 
Click on View in the top menu bar, then select Command Palette.

# Common Tasks Using the Command Palette
Here are some examples of common tasks that can be performed using the Command Palette in VS Code:

## File Operations:
- Create New File: Type File: New File and press Enter to create a new file.
- Open File: Type File: Open File and start typing the file name to open an existing file.
- Save All: Type File: Save All to save all open files.

## Search and Navigation:
- Search for Symbols: Type Go to Symbol and enter the symbol name to navigate to a specific function or method in the current file.
- Navigate to File: Type Go to File and start typing the file name to quickly navigate to any file in the workspace.

## Source Control (Git):
- Git Commit: Type Git: Commit to commit changes to the repository.
- Git Pull: Type Git: Pull to pull changes from the remote repository.

## Extensions Management:
- Install Extensions: Type Extensions: Install Extensions to search for and install new VS Code extensions.
- Manage Extensions: Type Extensions: Show Installed Extensions to manage installed extensions, enable/disable or uninstall them.

## Settings and Preferences:
- Open Settings: Type Preferences: Open Settings to open the settings.json file for configuring VS Code preferences.

## Debugging:
- Start Debugging: Type Debug: Start Debugging to start debugging the active file.

## Tasks and Runners:
- Run Task: Type Tasks: Run Task to execute predefined tasks or scripts configured in tasks.json.

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.
# Answer
Extensions in Visual Studio Code (VS Code) play a crucial role in extending its functionality and customizing the development environment according to specific needs. They allow users to add new features, support for different programming languages, enhance productivity, and integrate with external tools seamlessly. Here’s a detailed look at the role of extensions and how users can find, install, and manage them in VS Code:

# 1. Role of Extensions in VS Code
## a. Extending Functionality: 
Extensions add capabilities beyond the core features of VS Code. They can provide support for additional programming languages, frameworks, build systems, debuggers, and more.

## b. Enhancing Productivity: 
Many extensions automate repetitive tasks, improve code quality with linters and formatters, integrate with version control systems like Git, enable task running and debugging, and enhance the overall development workflow.

## c. Customization: 
Users can customize their editing experience with themes, icons, and personalized settings through extensions.

# 2. Finding and Installing Extensions
To find and install extensions in VS Code:

## a. Extensions View: 
Click on the Extensions icon in the Activity Bar on the side of the VS Code window (or use Ctrl + Shift + X shortcut). Here, you can search for extensions by name, category, or functionality.

## b. Marketplace: 
VS Code extensions are available on the Visual Studio Code Marketplace (https://marketplace.visualstudio.com/). Users can browse through categories, view ratings, reviews, and installation instructions.

## c. Installation: 
Once you find an extension you want, click the Install button next to it. VS Code will download and install the extension automatically.

# 3. Managing Extensions
Users can manage extensions in several ways:

## a. Enable/Disable: I
n the Extensions view, toggle the switch next to each extension to enable or disable it.

## b. Update: 
VS Code automatically checks for updates to installed extensions. Users can manually update extensions from the Extensions view if needed.

## c. Uninstall: 
To remove an extension, click on the gear icon next to it and select Uninstall.

# 4. Examples of Essential Extensions for Web Development
## a. Live Server: 
Launches a local development server with live reload feature for static and dynamic pages.

- Installation: Search for "Live Server" in the Extensions view.

## b. ESLint: 
Integrates ESLint for JavaScript/TypeScript linting to maintain code quality and consistency.

- Installation: Search for "ESLint" in the Extensions view.

## c. Prettier - Code formatter: 
Automatically formats code according to predefined rules for consistent code styling.

- Installation: Search for "Prettier - Code formatter" in the Extensions view.

## d. Debugger for Chrome: 
Enables debugging JavaScript/TypeScript code in Google Chrome directly from VS Code.

- Installation: Search for "Debugger for Chrome" in the Extensions view.

## e. CSS Peek: 
Allows peeking into CSS definitions to quickly navigate and edit CSS code.

- Installation: Search for "CSS Peek" in the Extensions view.

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

# Answer
The integrated terminal in Visual Studio Code (VS Code) provides a convenient way for developers to execute shell commands, run scripts, and interact with command-line tools directly within the editor. Here’s how you can open and use the integrated terminal, along with its advantages over using an external terminal:

# Opening the Integrated Terminal
To open the integrated terminal in VS Code:

## a. Using Menu Options:
- Click on View in the top menu.
- Select Terminal from the dropdown menu.
- Choose New Terminal to open a new integrated terminal pane.

## b. Using Keyboard Shortcut:
- Press Ctrl + (backtick/grave accent) on Windows/Linux or Cmd + on macOS.

## c. Using Command Palette:
- Open the Command Palette (Ctrl + Shift + P on Windows/Linux, Cmd + Shift + P on macOS).
- Type "Terminal: Create New Integrated Terminal" and select it.

# Using the Integrated Terminal
Once the integrated terminal is open:

- Navigating Directories: Use commands like cd to navigate through directories.
- Running Commands: Execute shell commands, run scripts (e.g., npm start for Node.js projects), or compile code directly.
- Interacting with Tools: Use command-line tools such as Git, npm, Python, or any other installed tool available in your system PATH.
- Output and Error Handling: View command output and error messages directly in VS Code.
- Input Handling: Some commands might require user input, which can be handled within the terminal.

# Advantages of the Integrated Terminal
## a. Convenience: 
No need to switch between VS Code and an external terminal window. Everything happens within the same editor interface.

## b. Contextual Awareness: 
The terminal inherits the current working directory of the open file or project in VS Code, making it easier to navigate and execute commands relevant to your project.

## c. Productivity: 
Quickly access terminal commands without leaving the editor, reducing context-switching time and improving workflow efficiency.

## d. Integration with VS Code Features: 
The integrated terminal can interact with other VS Code features and extensions, enhancing functionality like debugging, task running, and version control directly from the terminal.

## e. Customization: 
Configure shell preferences, fonts, colors, and other terminal settings to match your preferences directly within VS Code.

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

# Answer
Creating, opening, and managing files and folders in Visual Studio Code (VS Code) is straightforward and user-friendly. Here’s a detailed guide on how to perform these tasks and navigate efficiently between different files and directories:

# Creating Files and Folders
## a. Creating a New File:

- Using Menu Options:
   - Click on File in the top menu.
   - Select New File.
- Using Keyboard Shortcut:
   - Press Ctrl + N (Windows/Linux) or Cmd + N (macOS).

## b. Creating a New Folder:

- Using the Explorer Sidebar:
   - Right-click on the folder or workspace in the Explorer sidebar where you want to create a new folder.
   - Select New Folder from the context menu.
   - Enter the folder name and press Enter.

# Opening Files and Folders
## a. Opening an Existing File:

- Using Menu Options:
   - Click on File in the top menu.
   - Select Open File.
   - Navigate to the file you want to open and click Open.
- Using Keyboard Shortcut:
   - Press Ctrl + O (Windows/Linux) or Cmd + O (macOS).

## b. Opening a Folder or Workspace:

- Using Menu Options:
   - Click on File in the top menu.
   - Select Open Folder or Open Workspace.
   - Navigate to the desired folder or workspace and click Open.
- Using Keyboard Shortcut:
   - Press Ctrl + K followed by Ctrl + O (Windows/Linux) or Cmd + K followed by Cmd + O (macOS).

# Managing Files and Folders
## a. Renaming Files and Folders:

- Using the Explorer Sidebar:
   - Right-click on the file or folder you want to rename.
   - Select Rename.
   - Enter the new name and press Enter.

## b. Deleting Files and Folders:

- Using the Explorer Sidebar:
   - Right-click on the file or folder you want to delete.
   - Select Delete.
   - Confirm the deletion when prompted.

# Navigating Between Files and Directories
## a. Explorer Sidebar:
- Use the Explorer sidebar to view and navigate the file structure of your project. Click on files and folders to open and explore them.

## b. Quick Open:
- Press Ctrl + P (Windows/Linux) or Cmd + P (macOS) to open the Quick Open dialog.
- Start typing the name of the file you want to open. The dialog will filter the results as you type.
- Select the file from the list and press Enter to open it.

## c. Tabs and Editor Groups:
- Open files are displayed in tabs at the top of the editor. Click on a tab to switch between open files.
- Split the editor into multiple groups by right-clicking on a tab and selecting - Split Right or Split Down.

## d. Breadcrumb Navigation:
- The breadcrumb navigation at the top of the editor allows you to quickly navigate to parent directories and files within the current file’s path. Click on any part of the breadcrumb to navigate to that location.

## e. Go to Definition/Declaration:
- Right-click on a symbol (e.g., a function or variable) and select Go to Definition or Go to Declaration, or press F12. This will open the file where the symbol is defined.

## f. File and Symbol Search:
- Press Ctrl + Shift + F (Windows/Linux) or Cmd + Shift + F (macOS) to open the search pane.
- Enter search terms to find files and symbols matching the search criteria.

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

# Answer
In Visual Studio Code (VS Code), users can find and customize settings through the Settings menu. Here’s how to access and change various settings like the theme, font size, and keybindings:

# Accessing Settings

## a. Settings Menu:
- Using the Menu Bar:
   - Click on File in the top menu.
   - Select Preferences.
   - Click on Settings.
- Using Keyboard Shortcut:
   - Press Ctrl + , (Windows/Linux) or Cmd + , (macOS).

## b. Settings UI:
- This opens the Settings UI, where you can search for and adjust various settings.

# Changing the Theme

## a. Access Color Theme:

- Open the Command Palette by pressing Ctrl + Shift + P (Windows/Linux) or Cmd + Shift + P (macOS).
- Type Preferences: Color Theme and select it.
- You’ll see a list of available themes.

## b. Select a Theme:
- Scroll through the list and click on a theme to apply it immediately.
- The theme will change as you select different options, allowing you to preview them.

# Changing the Font Size

## a. Search for Font Size:
- In the Settings UI, type font size in the search bar at the top.

## b. Adjust Font Size:
- Look for the setting labeled Editor: Font Size.
- Enter a new value (e.g., 14) to change the font size.
- The change takes effect immediately.

# Changing Keybindings

## a. Access Keyboard Shortcuts:
- Open the Command Palette by pressing Ctrl + Shift + P (Windows/Linux) or Cmd + Shift + P (macOS).
- Type Preferences: Open Keyboard Shortcuts and select it.

## b. Modify Keybindings:
- This opens the Keybindings editor.
- Search for the command you want to change (e.g., toggle terminal).
- Click the pencil icon next to the command to change its keybinding.
- Press the new key combination you want to assign to the command.
- Click Enter to save the new keybinding.

# Example Customizations

## a. Changing the Theme
- Open Command Palette:
   - Ctrl + Shift + P (Windows/Linux) or Cmd + Shift + P (macOS).
- Select Color Theme:
   - Type Preferences: Color Theme.
   - Select Dark+ (default dark) or any other preferred theme.

## b. Changing the Font Size
- Open Settings:
   - Ctrl + , (Windows/Linux) or Cmd + , (macOS).
- Search and Adjust:
   - Type font size in the search bar.
   - Set Editor: Font Size to 16.

## c. Changing Keybindings
- Open Keyboard Shortcuts:
   - Ctrl + Shift + P (Windows/Linux) or Cmd + Shift + P (macOS).
- Modify Toggle Terminal Keybinding:
   - Search for toggle terminal.
   - Click the pencil icon next to View: Toggle Terminal.
   - Press Ctrl + T (or any preferred combination).
   - Press Enter to save.

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

# Answer

# Setting Up and Starting Debugging in Visual Studio Code

# Step-by-Step Guide to Debug a Simple Program

# a. Install Visual Studio Code:
- Ensure you have Visual Studio Code installed. If not, download and install it from VS Code Download.

# b. Install Necessary Extensions:
- Depending on the programming language you are using, you may need to install specific extensions.
- For example, for Python, install the Python extension by Microsoft:
   - Go to the Extensions view (Ctrl + Shift + X).
   - Search for Python and install the extension by Microsoft.

## c. Open Your Project Folder:
- Open VS Code.
- Go to File > Open Folder and select the folder containing your project files.

## d. Create or Open Your Code File:
- Create a new file (Ctrl + N) and save it with the appropriate file extension (e.g., .py for Python, .js for JavaScript).
- Alternatively, open an existing file by navigating to it in the Explorer sidebar.

## e. Add a Launch Configuration:
- Open the Run view by clicking on the Run icon in the Activity Bar on the side or using Ctrl + Shift + D.
- Click on the create a launch.json file link.
- Select the appropriate environment (e.g., Python, Node.js) from the list.
- VS Code generates a launch.json file with default configurations.

## f. Set Breakpoints:
- Click in the left margin next to the line numbers in your code file to set breakpoints.
- A red dot will appear indicating where the execution will pause.

## g. Start Debugging:
- In the Run view, click the green play button or press F5 to start debugging.
- Your program will start executing and pause at the breakpoints.

# Key Debugging Features in VS Code
## a. Breakpoints:
- Set breakpoints to pause execution at specific lines.
- Conditional breakpoints allow you to pause execution when certain conditions are met.

## b. Watch Expressions:
- Add expressions to the Watch panel to evaluate variables and expressions in the current execution context.

## c. Call Stack:
- View the call stack to see the sequence of function calls that led to the current breakpoint.
- Navigate through the call stack to examine different levels of function calls.

## d. Variables:
- Inspect variables in the Variables panel.
- View and edit variable values while debugging.

## e. Step Controls:
- Use the step controls to navigate through your code:
- Step Over (F10): Execute the next line of code, but don’t step into functions.
- Step Into (F11): Step into functions to debug inside them.
- Step Out (Shift + F11): Step out of the current function.
- Continue (F5): Resume execution until the next breakpoint.

## f. Debug Console:
- Use the Debug Console to evaluate expressions and interact with the debugged program.
- Execute commands and view output directly in the console.

## g. Inline Variable Values:
- See variable values inline in your code during debugging.
- Helps in quickly understanding the state of variables without switching context.

# Example: Debugging a Python Program
## a. Install Python Extension:
- Ensure the Python extension is installed.

## b. Open Your Python File:
- Create a new file example.py and add some sample code:

      def greet(name):
         message = f"Hello, {name}!"
         return message

      user_name = "Alice"
      print(greet(user_name))

## c. Set Up Launch Configuration:
- Click the Run icon, then create a launch.json file, and select Python.
- A launch.json file is created with default configurations.

## d. Set Breakpoints:
- Click next to the line message = f"Hello, {name}!" to set a breakpoint.

## e. Start Debugging:
- Click the green play button or press F5.

## f. Use Debugging Features:
- The program will pause at the breakpoint.
- Inspect the value of name and message in the Variables panel.
- Use the step controls to navigate through the code.

10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.
 # Answer
Integrating Git with Visual Studio Code (VS Code) for version control is a straightforward process that significantly enhances your development workflow. Below are the detailed steps to initialize a Git repository, make commits, and push changes to GitHub using VS Code.

# Prerequisites
- Git Installation: Ensure Git is installed on your system. You can download it from Git.
- GitHub Account: Have a GitHub account to host your repositories. Sign up at GitHub.
# Step-by-Step Guide
1. Open VS Code and the Project Folder
- Launch VS Code.
- Open your project folder by navigating to File > Open Folder.

2. Initialize a Git Repository
- Open the integrated terminal in VS Code by navigating to View > Terminal or using the shortcut Ctrl + `.
- In the terminal, run the following command to initialize a Git repository in your project folder: "git init"

3. Stage and Commit Changes
- Make changes to your project files.
- Open the Source Control view by clicking on the Source Control icon in the Activity Bar on the side of the window.
- In the Source Control view, you will see a list of changes. Stage the changes by clicking the + icon next to each file or click the + icon in the Changes header to stage all changes.
- Enter a commit message in the text box above and click the checkmark icon to commit the changes.

4. Connect to GitHub
- If this is your first time pushing to GitHub, you need to set up a remote repository.
- Go to GitHub, log in, and create a new repository by clicking the + icon in the upper right corner and selecting New repository.
- Give your repository a name and click Create repository.
- Copy the repository URL (HTTPS link).

5. Add Remote Repository
- In VS Code, open the integrated terminal and run the following command to add the remote repository: "git remote add origin https://github.com/your-username/your-repository.git". (Replace https://github.com/your-username/your-repository.git with your repository URL.)

6. Push Changes to GitHub
- Push your committed changes to GitHub by running the following command in the terminal: "git push -u origin main"

Note: If your default branch is master instead of main, replace main with master.

# Key Commands and Actions in VS Code
1. Stage and Commit Changes
- In the Source Control view, stage changes by clicking the + icon.
- Enter a commit message and commit by clicking the checkmark icon.

2. Viewing Commit History
- You can view the commit history by clicking on the ... menu in the Source Control view and selecting View History.

3. Pulling Changes
- To pull changes from the remote repository, open the terminal and run: "git pull origin main". (Replace main with your branch name if necessary.)

4. Sync Changes
- Use the Sync Changes button in the Source Control view to automatically pull and then push changes.

# Example Workflow
1. Make Changes: Edit files in your project.
2. Stage Changes: Go to Source Control view and stage the changes.
3. Commit Changes: Enter a commit message and commit the changes.
4. Push Changes: Open the terminal and push the changes to GitHub.

 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

