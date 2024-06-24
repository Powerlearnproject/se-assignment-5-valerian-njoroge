[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15319042&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.
   Prerequisites
   Windows 11 operating system: Ensure your system is running Windows 11.
   Internet Connection: Required to download the installer.
   Administrator Privileges: Needed to install software on your system.
   STEP ONE:Download Visual Studio:
   Visit the Visual Studio website and click on "Download Visual Studio."
   https://code.visualstudio.com/download
   ![alt text](image.png)
   That is how it will appear then click on download
   Follow the on-screen instructions to download the installer.
   STEP TWO:Run the Installer:
   Run the downloaded installer.
   Choose the "Visual Studio" workload during installation, which includes the necessary components for general development.
   Setup Wizard:

The VS Code Setup Wizard will open. Click "Next" to continue.
Read and accept the license agreement by checking the "I accept the agreement" box, then click "Next".
Select Installation Location:

Choose the destination folder where you want to install VS Code. The default location is usually fine. Click "Next".
Select Additional Tasks:

You'll be prompted to select additional tasks. These include:
Create a desktop icon.
Add "Open with Code" action to the Windows Explorer file context menu.
Add "Open with Code" action to the Windows Explorer directory context menu.
Register Code as an editor for supported file types.
Add to PATH (important for using VS Code from the command line).
Select the options that are useful for you and click "Next".
Install:

Review your selections and click "Install" to begin the installation process.
Finish Installation:

Once the installation is complete, you can choose to launch VS Code immediately by checking the "Launch Visual Studio Code" box.
Click "Finish" to exit the Setup Wizard.
Post-Installation Steps
First Launch:

If you didn't choose to launch VS Code immediately, you can start it from the Start menu or the desktop icon.
Initial Setup:

When you first launch VS Code, you may be prompted to customize your installation by choosing a theme and installing recommended extensions for your development environment.
Install Extensions:

You can install additional extensions to support various programming languages and tools. To do this, go to the Extensions view by clicking the Extensions icon in the Activity Bar on the side of the window or by pressing Ctrl+Shift+X.
Update VS Code:

VS Code regularly checks for updates. You can manually check for updates by going to Help > Check for Updates.

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

After installing Visual Studio Code (VS Code), there are several initial configurations and settings you should adjust to create an optimal coding environment. Here's a guide to help you get started:

Initial Configurations
Theme and Appearance:

Theme: Select a theme that suits your preference. Go to File > Preferences > Color Theme or press Ctrl+K Ctrl+T and choose from the available themes. Popular themes include "Dark+ (default dark)" and "Light+ (default light)".
Icon Theme: Choose an icon theme for a better visual distinction of file types. Go to File > Preferences > File Icon Theme.
Settings Sync:

Enable Settings Sync to sync your settings, keybindings, extensions, and snippets across multiple devices. Go to File > Preferences > Settings and search for "Settings Sync", then turn it on and sign in with your GitHub or Microsoft account.
Font and Font Size:

Adjust the font family and size for better readability. Go to File > Preferences > Settings and search for editor.fontFamily and editor.fontSize.
Auto Save:

Enable auto-save to automatically save your work. Go to File > Preferences > Settings and search for files.autoSave. Set it to afterDelay or onWindowChange.
Important Extensions
Language Support:

Python: Install the Python extension by Microsoft for Python development. It provides IntelliSense, linting, debugging, and more.
JavaScript and TypeScript: VS Code has built-in support, but additional extensions like ESLint can help with linting.
C/C++: Install the C/C++ extension by Microsoft for IntelliSense, debugging, and code browsing.
Version Control:

GitLens: Enhances Git capabilities in VS Code, providing insights into code changes and authorship.
GitHub Pull Requests and Issues: Integrates GitHub workflows into VS Code.
Code Quality and Formatting:

Prettier: An opinionated code formatter that supports many languages.
ESLint: A linter for JavaScript and TypeScript to help identify and fix problems in your code.
Productivity Tools:

Live Share: Collaborate in real-time with others directly within VS Code.
Path Intellisense: Autocompletes filenames in import statements.
Docker and Kubernetes: If you're working with containers, install the Docker and Kubernetes extensions for better integration and management.

Configuration for Extensions
Python Extension:

Configure the Python interpreter. Open a Python file, click on the interpreter status bar item in the bottom left corner, and select the appropriate interpreter.
Enable linting by going to File > Preferences > Settings and searching for python.linting.enabled. Set it to true.
Prettier Extension:

Set Prettier as the default formatter. Go to File > Preferences > Settings, search for editor.defaultFormatter, and set it to esbenp.prettier-vscode.
Enable format on save by searching for editor.formatOnSave and setting it to true.

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.
   1. Activity Bar
Location: Left side of the window.

Purpose:

The Activity Bar provides quick access to different views and functions within VS Code.
Each icon on the Activity Bar represents a different view or feature. The default icons include:
Explorer: Displays the file and folder structure of your workspace.
Search: Allows you to search and replace text within your project.
Source Control: Integrates version control, typically Git, showing changes and allowing commits.
Run and Debug: Provides tools for running and debugging your code.
Extensions: Manages extensions, allowing you to install, enable, disable, and uninstall extensions.
Usage:

Click on an icon to open the corresponding view in the Side Bar.
Right-click on the Activity Bar to customize which icons are displayed.
2. Side Bar
Location: Right next to the Activity Bar on the left side of the window.

Purpose:

The Side Bar shows the content related to the selected Activity Bar icon.
It dynamically changes its content based on the view selected from the Activity Bar.
Examples of views in the Side Bar:
Explorer: Shows the file and folder structure, allowing you to open, create, and manage files.
Search: Provides a search interface to find and replace text across files in your project.
Source Control: Displays the version control interface, showing changes, branches, and allowing you to commit code.
Run and Debug: Lists your debugging configurations and active debug sessions.
Extensions: Lists installed extensions and provides a marketplace to find new ones.
Usage:

Interact with the content specific to the current view, such as opening files from the Explorer or viewing changes in Source Control.
3. Editor Group
Location: Central area of the window.

Purpose:

The Editor Group is where you write and edit your code.
You can have multiple files open at once, each in its own tab within the Editor Group.
Supports split views, allowing you to view and edit multiple files side-by-side.
Usage:

Open a file to start editing in the Editor Group.
Drag tabs to rearrange them or to create a split view.
Close tabs when you're done with a file.
Features:

Syntax highlighting, IntelliSense, code completion, and other editor-specific tools enhance the coding experience.
Right-click within the editor for context-specific actions like formatting, refactoring, and running code snippets.
4. Status Bar
Location: Bottom of the window.

Purpose:

The Status Bar displays information about the current state of the workspace and the active file.
It provides quick access to commonly used settings and tools.
Information Displayed:

File Info: Shows details about the currently active file, such as line and column numbers, file encoding, and language mode.
Git Status: Indicates the current branch and shows changes.
Errors and Warnings: Displays the number of errors and warnings in the workspace.
Running Processes: Shows active tasks or debugging sessions.
Notifications: Displays status messages and alerts.
Usage:

Click on items in the Status Bar to perform actions, such as changing the language mode, opening the command palette, or checking the Git branch.
Hover over items for more detailed information.

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.
   The Command Palette in Visual Studio Code (VS Code) is a powerful feature that provides quick access to a wide range of commands and settings without needing to navigate through menus or remember complex keyboard shortcuts. It allows you to perform various tasks efficiently by simply typing the command you want to execute.

Accessing the Command Palette
Keyboard Shortcut: Press Ctrl+Shift+P (Windows/Linux) or Cmd+Shift+P (Mac) to open the Command Palette.
Menu: You can also access it via the menu by selecting View > Command Palette.
Using the Command Palette
When you open the Command Palette, a text input field appears at the top of the VS Code window. You can start typing to search for and execute commands.

Examples of Common Tasks
Here are some common tasks you can perform using the Command Palette:

Opening Files and Folders:

Open File: Type Open File to quickly open a specific file.
Open Folder: Type Open Folder to open a new folder in the workspace.
Running Commands:

Run Task: Type Run Task to execute a predefined task, such as building or testing your code.
Run Build Task: Type Run Build Task to run the default build task.
Working with Extensions:

Install Extensions: Type Extensions: Install Extensions to open the Extensions view and install new extensions.
Disable Extensions: Type Extensions: Disable to disable an extension.
Source Control:

Git: Commit: Type Git: Commit to commit your changes.
Git: Push: Type Git: Push to push your commits to a remote repository.
Editing and Formatting:

Format Document: Type Format Document to format the entire document according to your formatting settings.
Format Selection: Type Format Selection to format the selected text.
Debugging:

Start Debugging: Type Debug: Start Debugging to begin a debugging session.
Add Configuration: Type Debug: Add Configuration to add a new debug configuration.
Terminal:

Create New Integrated Terminal: Type Terminal: Create New Integrated Terminal to open a new terminal instance.
Run Active File in Terminal: Type Terminal: Run Active File to execute the current file in the terminal.
Settings and Preferences:

Open Settings: Type Preferences: Open Settings to open the Settings editor.
Open Keyboard Shortcuts: Type Preferences: Open Keyboard Shortcuts to view and modify keybindings.
Navigating:

Go to Definition: Type Go to Definition to navigate to the definition of a symbol in your code.
Find in Files: Type Find in Files to search for a string across your workspace.
View and Layout:

Toggle Sidebar Visibility: Type View: Toggle Sidebar Visibility to show or hide the sidebar.
Toggle Full Screen: Type View: Toggle Full Screen to switch between full-screen mode and windowed mode.
Tips for Using the Command Palette
Fuzzy Search: The Command Palette uses fuzzy search, so you don't need to type the exact command. Typing part of the command will usually be enough to find what you need.
Filtering by Category: You can filter commands by category by typing a prefix (e.g., git: to see all Git-related commands).
Command History: The Command Palette shows your most recently used commands at the top, making it easy to repeat frequent actions.

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.
   Finding, Installing, and Managing Extensions
Finding Extensions
Extensions View:

Open the Extensions view by clicking the Extensions icon in the Activity Bar on the side of the VS Code window.
You can also open it using the keyboard shortcut Ctrl+Shift+X (Windows/Linux) or Cmd+Shift+X (Mac).
Search for Extensions:

In the Extensions view, you can search for extensions by typing keywords, the name of the extension, or a specific functionality in the search bar.
VS Code Marketplace:

Visit the Visual Studio Code Marketplace in a web browser to browse and search for extensions.
Installing Extensions
From the Extensions View:

After finding an extension, click the Install button next to the extension name in the Extensions view.
The installation process will start, and the extension will be added to your VS Code setup.
From the Command Palette:

Open the Command Palette with Ctrl+Shift+P (Windows/Linux) or Cmd+Shift+P (Mac).
Type Extensions: Install Extensions and press Enter.
Search for the desired extension and install it.
Managing Extensions
View Installed Extensions:

In the Extensions view, the installed extensions are listed under the "Installed" section.
Enable/Disable Extensions:

Click on the installed extension to open its details page.
Use the Disable or Enable button to turn the extension off or on without uninstalling it.
Uninstall Extensions:

Click on the installed extension in the Extensions view.
Click the Uninstall button to remove the extension from VS Code.
Update Extensions:

VS Code will notify you when updates are available for your installed extensions.
You can manually check for updates by clicking the ... menu in the Extensions view and selecting Check for Extension Updates.
Essential Extensions for Web Development
Here are some highly recommended extensions for web development:

Language Support:

ESLint: Integrates ESLint into VS Code for identifying and reporting on patterns in JavaScript/TypeScript.
Prettier - Code formatter: An opinionated code formatter that supports many languages.
HTML, CSS, and JavaScript:

HTML Snippets: Provides a set of code snippets for HTML.
CSS Peek: Allows you to peek at the CSS code directly from the HTML file.
JavaScript (ES6) code snippets: Provides a collection of ES6 code snippets.
Frameworks and Libraries:

React Native Tools: Provides debugging and development support for React Native projects.
Vue.js Extension Pack: A collection of extensions for working with Vue.js.
Angular Essentials: A set of extensions to enhance Angular development.
Version Control:

GitLens: Enhances Git capabilities in VS Code, providing insights into code changes and authorship.
GitHub Pull Requests and Issues: Integrates GitHub workflows into VS Code.
Productivity:

Live Server: Launches a local development server with a live reload feature for static and dynamic pages.
Path Intellisense: Autocompletes filenames in import statements.
Bracket Pair Colorizer: Highlights matching brackets with different colors for better readability.
Debugging:

Debugger for Chrome: Debug your JavaScript code running in Google Chrome directly from VS Code.
Debugger for Firefox: Similar to the Chrome debugger, but for Firefox.

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?
   Opening the Integrated Terminal
Using the Menu:

Go to the top menu bar and select Terminal > New Terminal.
Using the Keyboard Shortcut:

Press Ctrl+`` (backtick) on Windows/Linux or Cmd+`` on Mac.
Using the Command Palette:

Open the Command Palette with Ctrl+Shift+P (Windows/Linux) or Cmd+Shift+P (Mac).
Type Terminal: Create New Integrated Terminal and press Enter.
Using the Integrated Terminal
Multiple Terminals:

You can open multiple terminal instances. Click the + icon in the terminal tab bar to open additional terminals.
Switch between terminals by clicking on the tabs or using the dropdown menu next to the + icon.
Splitting Terminals:

You can split the terminal view to have multiple terminals visible at the same time. Click the split icon (two overlapping rectangles) in the terminal tab bar.
Running Commands:

Type and execute commands just like you would in an external terminal.
The integrated terminal supports various shells, such as PowerShell, Command Prompt, Git Bash, and more.
Configuring the Shell:

To change the default shell, go to File > Preferences > Settings, search for terminal.integrated.shell, and set the path to your preferred shell.
You can also configure different shells for different platforms (Windows, Linux, Mac).
Customizing Appearance:

Customize the terminal's appearance, such as font size, cursor style, and background color, through the settings. Go to File > Preferences > Settings and search for terminal.integrated.
Advantages of Using the Integrated Terminal
Seamless Workflow:

The integrated terminal is embedded directly within VS Code, allowing you to stay within the same environment. This reduces context switching between the editor and an external terminal, streamlining your workflow.
Consistent Environment:

The integrated terminal shares the same workspace and environment as your editor. This ensures consistency in file paths and environment variables, making it easier to run scripts and commands related to your project.
Ease of Use:

Quickly access the terminal using keyboard shortcuts, the command palette, or the menu, without needing to open a separate application.
Customization and Configuration:

Customize the terminal to match your development needs. You can choose different shells, configure terminal appearance, and even run multiple terminals concurrently within the same window.
Terminal-Editor Integration:

The integrated terminal can interact with the editor. For example, you can open files in the editor from the terminal using commands like code filename, or navigate to files and directories easily.
Task Automation:

Use the integrated terminal to run build tasks, tests, and other scripts directly within your development environment. This allows for quick iteration and testing without leaving VS Code.
Output Viewing:

View the output of your scripts and commands within the same window, making it easier to debug and monitor your programs.
Extension Support:

Some extensions provide additional features or integrations within the integrated terminal. For instance, GitLens enhances Git capabilities, which can be utilized within the terminal.

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?
   Creating and Opening Files/Folders
Creating Files and Folders
Using the Explorer View:

Open the Explorer view by clicking on the Explorer icon in the Activity Bar on the side of the VS Code window.
Right-click on the parent directory where you want to create a new file or folder.
Select New File or New Folder from the context menu.
Enter the name for the file or folder and press Enter to create it.
Using the Command Palette:

Open the Command Palette with Ctrl+Shift+P (Windows/Linux) or Cmd+Shift+P (Mac).
Type New File or New Folder and press Enter.
Enter the name for the file or folder and press Enter again to create it.
Opening Files and Folders
Using the Explorer View:

Navigate to the file or folder you want to open in the Explorer view.
Double-click on a file to open it in the editor.
Double-click on a folder to expand its contents and view files within it.
Using the Command Palette:

Open the Command Palette with Ctrl+Shift+P (Windows/Linux) or Cmd+Shift+P (Mac).
Type Open File or Open Folder and press Enter.
Navigate to the file or folder you want to open in the file dialog that appears.
Managing Files and Folders
Renaming and Deleting
Renaming:

In the Explorer view, right-click on the file or folder you want to rename.
Select Rename from the context menu, or simply press F2.
Enter the new name and press Enter to save.
Deleting:

In the Explorer view, right-click on the file or folder you want to delete.
Select Delete from the context menu, or press Delete on your keyboard.
Confirm the deletion if prompted.
Moving and Copying
Moving (Cut and Paste):

In the Explorer view, right-click on the file or folder you want to move.
Select Cut from the context menu, or press Ctrl+X (Windows/Linux) or Cmd+X (Mac).
Navigate to the destination folder, right-click, and select Paste, or press Ctrl+V (Windows/Linux) or Cmd+V (Mac).
Copying (Copy and Paste):

In the Explorer view, right-click on the file or folder you want to copy.
Select Copy from the context menu, or press Ctrl+C (Windows/Linux) or Cmd+C (Mac).
Navigate to the destination folder, right-click, and select Paste, or press Ctrl+V (Windows/Linux) or Cmd+V (Mac).
Navigating Between Files and Directories Efficiently
Using the Explorer View:

Click on folders in the Explorer view to navigate through different directories.
Double-click on files to open them in the editor.
Keyboard Shortcuts:

Switch Between Tabs: Use Ctrl+Tab (Windows/Linux) or Cmd+Shift+] to cycle through open files.
Go to File: Use Ctrl+P (Windows/Linux) or Cmd+P (Mac) to quickly open files by typing their name.
Breadcrumbs Navigation:

Enable breadcrumbs at the top of the editor window (View > Show Breadcrumbs) for easy navigation within files and directories.
Search and Go To:

Use the Search functionality (Ctrl+Shift+F or Cmd+Shift+F) to search for files across your workspace.
Use Go to File (Ctrl+P or Cmd+P) to quickly navigate to a specific file by typing its name.
Navigation History:

Use Alt+Left Arrow (Windows/Linux) or Cmd+[ (Mac) to go back to previous locations in your navigation history.
Use Alt+Right Arrow (Windows/Linux) or Cmd+] (Mac) to go forward.

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.
   Finding and Customizing Settings
Settings Location:

Open the Settings by either:
Pressing Ctrl+, (comma) on Windows/Linux or Cmd+, (comma) on Mac.
Navigating through the menu: File > Preferences > Settings.
This opens the Settings tab in the Side Bar, where you can modify various settings.

Search Settings:

Use the search bar at the top of the Settings tab to find specific settings. For example, type theme to find settings related to themes.
Settings Categories:

Settings are organized into categories like Workbench, Editor, Extensions, etc., which you can navigate through on the left-hand side of the Settings tab.
Examples of Customizations
Changing the Theme
From Settings:

Open the Settings (Ctrl+, or Cmd+,).
Search for Color Theme.
Click on the Color Theme dropdown to select a theme like "Dark+ (default dark)" or "Light+ (default light)".
From Command Palette:

Open the Command Palette (Ctrl+Shift+P or Cmd+Shift+P).
Type Color Theme and press Enter.
Select a theme from the list.
Adjusting Font Size
From Settings:

Open the Settings (Ctrl+, or Cmd+,).
Search for editor.fontSize.
Adjust the value to change the font size. For example, set editor.fontSize to 14.
Using Keyboard Shortcuts:

Press Ctrl+ (plus) or Ctrl- (minus) to increase or decrease the font size in the editor window.
Modifying Keybindings
From Settings:

Open the Settings (Ctrl+, or Cmd+,).
Search for keybindings.
Click on Open Keyboard Shortcuts (or go to File > Preferences > Keyboard Shortcuts).
Use the search box to find the keybinding you want to change (e.g., workbench.action.toggleSidebarVisibility).
Click on the pencil icon next to the keybinding to edit it and enter your desired key combination.
Adding Custom Keybindings:

Click on keybindings.json (found at the top-right corner in the Keyboard Shortcuts tab) to directly edit keybindings in JSON format.
Add your custom keybindings following the JSON structure provided.

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?
   Setting Up and Starting Debugging
1. Install Required Extensions (if needed)
Ensure you have any necessary debugging extensions installed for your specific programming language or framework (e.g., Python, Node.js). You can find and install extensions through the Extensions view (Ctrl+Shift+X or Cmd+Shift+X).
2. Configure Launch Configuration
VS Code uses launch configurations to define how to start a debugging session for your project. Here’s how to set up a basic launch configuration:

Manual Configuration:

Click on the debug icon in the Activity Bar on the side of the VS Code window (or press Ctrl+Shift+D).
Click on the gear icon (create a launch.json file) or select Add Configuration... from the dropdown menu.
Select the environment and configuration template that matches your project (e.g., Node.js, Python, etc.).
Automatic Configuration (for certain frameworks):

Some extensions may automatically generate a launch.json file for popular frameworks like Node.js or Python when you open a project.
3. Start Debugging
Once your launch configuration is set up:

Place breakpoints in your code where you want to pause execution to inspect variables or check the flow of execution. You can set breakpoints by clicking in the gutter next to the line numbers in the editor.

Press F5 or click the green play button (Start Debugging) in the debug sidebar to start your debugging session. Alternatively, use Ctrl+F5 to start debugging without attaching the debugger.

VS Code will switch to the Debug view and start running your program, pausing at the breakpoints you've set.

4. Debugging Session
During the debugging session:

Use the debug toolbar to control the execution of your program (Continue, Step Over, Step Into, Step Out, Restart, Stop).

Inspect variables and their values in the Variables pane.

View call stacks and navigate through function calls in the Call Stack pane.

Use the Debug Console to execute commands and view output directly from your application.

5. Stop Debugging
To stop debugging, either:

Click the red square (Stop) in the debug toolbar.

Press Shift+F5 or use the Stop option in the Debug view.

Key Debugging Features in VS Code
Breakpoints:

Set breakpoints in your code to pause execution and inspect variables and program state.
Variable Watching:

View and monitor the values of variables and expressions as you step through your code.
Call Stack Navigation:

Navigate through the call stack to understand the flow of execution and see the chain of function calls.
Debug Console:

Use the Debug Console to execute commands, interact with your application, and view output messages.
Conditional Breakpoints:

Set breakpoints that only trigger based on specified conditions, improving efficiency in debugging complex logic.
Multi-threaded Debugging:

Debug applications with multiple threads, inspecting each thread's state independently.
Exception Handling:

Configure VS Code to break execution when exceptions occur, allowing you to investigate errors and exceptions in detail.
Debugging Configuration:

Customize launch configurations for different scenarios (e.g., running specific scripts, attaching to a running process, remote debugging).

10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.
    1. Installing Git
Before getting started, ensure Git is installed on your system. You can download it from the official Git website, and follow the installation instructions for your operating system.

2. Integrating Git with VS Code
Open VS Code:

Launch Visual Studio Code on your computer.
Open a Project Folder:

Open the folder of your project in VS Code. You can do this by selecting File > Open Folder... and navigating to your project directory.
Initialize Git Repository:

To initialize a new Git repository for your project:

Open the Command Palette (Ctrl+Shift+P or Cmd+Shift+P).
Type Git: Initialize Repository and press Enter.
Select the folder you want to initialize as a Git repository.
Alternatively, if you have an existing Git repository, VS Code will automatically recognize it when you open the folder.

3. Making Commits
Stage Changes:

In the Source Control view (Ctrl+Shift+G or Cmd+Shift+G), you'll see a list of changed files.
Click the + button next to each file you want to include in the commit to stage them.
Commit Changes:

Enter a commit message in the text box at the top of the Source Control view that describes the changes you are committing.
Press Ctrl+Enter or click the checkmark icon to commit the changes.
4. Pushing Changes to GitHub
Linking to GitHub:

Ensure your project is hosted on GitHub and you have a repository set up there.
Set Remote (if not already done):

If your local repository is not already linked to a remote repository (like GitHub), you'll need to set the remote URL.
Open the Command Palette (Ctrl+Shift+P or Cmd+Shift+P).
Type Git: Add Remote and press Enter.
Enter the remote repository URL (e.g., https://github.com/username/repository.git).
Push Commits:

After committing your changes locally:

Click the ... menu in the Source Control view and select Push.
Alternatively, you can use the shortcut Ctrl+Shift+P to open the Command Palette and type Git: Push.
VS Code will prompt you to select the remote branch (typically main or master) and authenticate if necessary.

View Push Status:

Check the Output view (Ctrl+Shift+U or Cmd+Shift+U) for the status of your push operation. Any errors or messages from Git will be displayed here.
Additional Tips
Pull Changes: Use Git: Pull from the Command Palette to fetch and merge changes from the remote repository into your local branch.

Branching: Manage branches using commands like Git: Create Branch, Git: Checkout to..., and Git: Merge Branch from the Command Palette.

Git History: View commit history and changes by clicking on the Source Control view's clock icon or using Git: Show History from the Command Palette.
   

 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

