[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15283648&assignment_repo_type=AssignmentRepo)

# SE-Assignment-5

Installation and Navigation of Visual Studio Code (VS Code)
Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.

Download VS Code:

- Visit the [VS Code download page](https://code.visualstudio.com/download).
- Choose the version specific to your OS in this case (Windows).
- The download will start automatically.
  Run the Installer:
- Once the download is complete, run the installer (usually named `VSCodeUserSetup-{version}.exe`).
- Follow the installation prompts.
  Accept the Agreement:
- Accept the license terms and conditions during installation.
  Choose Installation Location:
- By default, VS Code is installed under `C:\Users\{Username}\AppData\Local\Programs\Microsoft VS Code`.
- Alternatively, you can download the `.zip` archive, extract it, and run VS Code from there.
  Launch VS Code:
- After installation, click the "Launch" button to open VS Code.
  Prerequisites:
- Make sure you have a working internet connection.
- Ensure your system meets the minimum requirements for VS Code.
  References:
  https://apps.microsoft.com/detail/XP9KHM4BK9FZ7Q?launch=true&mode=full&hl=en-us&gl=us

2. First-time Setup:

   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

   a) Extensions:
   Install relevant extensions from the VS Code Marketplace.
   Some popular extensions include:
   i. GitLens: Enhances Git integration.
   ii. Live Share: Enables collaborative coding.
   iii. Prettier: Auto-formats code.
   iv. Code Runner: Runs code snippets directly in VS Code.
   v. Python, Java, or other language-specific extensions.
   b) User Settings:
   Configure global settings by going to File > Preferences > Settings.
   Customize font size, theme, and keybindings.
   Adjust editor preferences (e.g., tab size, word wrap, line numbers).
   Explore IntelliSense and language-specific settings.
   c) Workspace Settings:
   For project-specific settings, create a .vscode folder in your workspace.
   Add a settings.json file inside this folder to override user settings.
   d) Keybindings:
   Customize keyboard shortcuts to match your workflow.
   Access keybindings via File > Preferences > Keyboard Shortcuts.
   e) Version Control Integration:
   Connect VS Code to Git repositories.
   Use the integrated Git features for version control.
   f) Debugging Configuration:
   Set up debugging configurations for your specific language or framework.
   Access debug configurations via the debug sidebar.
   References:
   https://code.visualstudio.com/docs/getstarted/settings
   https://marketsplash.com/how-to-configure-settings-in-visual-studio-code/

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

The main components of the Visual Studio Code (VS Code) user interface are:
a) Activity Bar: Located on the far left, it allows you to switch between different views and features, like the Explorer, Search, Source Control, and Extensions.
b) Side Bar: This vertical panel on the left side provides access to various features depending on the selected view in the Activity Bar, such as file explorer or search results.
c) Editor Group: The central area where you can open and edit files. You can have multiple editor groups for side-by-side editing.
d) Status Bar: At the bottom, it displays information about the opened project and files, such as line number, encoding, language, and Git branch.

4. Command Palette:

   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

   a) Keyboard Shortcut:
   Press `Ctrl + Shift + P` (Windows/Linux) or `Cmd + Shift + P` (macOS) to open the Command Palette.
   b) Menu Option:
   Click on the gear icon in the lower-left corner (or press `Ctrl + ,`) to open the Settings.
   In the search bar at the top of the Settings, type "Command Palette" and select "Preferences: Open Settings (JSON)."
   Add `"keyboard.dispatch": "keyCode"` to your settings.json file to enable keyboard shortcuts for the Command Palette.
   Common tasks you can perform using the Command Palette include:

- Opening Files: Type the name of a file to quickly open it.
- Running Commands: Search for and execute various VS Code commands (e.g., "Format Document," "Toggle Line Comment," "Git: Pull," etc.).
- Changing Themes: Search for "Color Theme" and choose a different theme.
- Installing Extensions: Search for "Extensions: Install Extensions" to browse and install VS Code extensions.
- Changing Settings: Search for specific settings (e.g., "Editor: Tab Size") and modify them directly.
- Navigating to Symbols: Search for a symbol (function, class, variable) within your codebase.

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

a) Finding Extensions:

- Open VS Code and click on the Extensions icon in the Activity Bar (`Ctrl+Shift+X` on Windows/Linux).
- Browse the Visual Studio Code Marketplace to discover extensions.
- Each extension includes a brief description, publisher details, download count, and a rating.
  b) Installing Extensions:
- Once you find an extension you want, click the "Install" button.
- After installation, the button changes to a "Manage" gear icon.
- For example, you can install the "TODO Highlight" extension, which highlights "TODO:" and "FIXME:" comments in your code.
  c) Essential Extensions for Web Development:
- Here are some must-have extensions for web developers:
  - Wappalyzer: Identifies the technologies used on any website.
  - HTML Validator: Checks HTML code for errors and syntax issues.
  - JSON Viewer: Renders JSON data in a human-readable format.
  - Web Developer Checklist: Provides best practices for web development.
  - React Developer Tools: Helps with React development.

References:
(1) Managing Extensions in Visual Studio Code. https://code.visualstudio.com/docs/editor/extension-marketplace?ref=tomeofzeal.com.
(2) Mastering VS Code Extension API Commands: A Hands-On Guide. https://medium.com/@lnakhul/mastering-vs-code-extension-api-commands-a-hands-on-guide-de679bd07cc9.
(3) 15 Must-Have VSCode Extensions for Web Development - Medium. https://medium.com/@Frontendgeek/15-must-have-vscode-extensions-for-web-development-9feb43978b1d.

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

a) Opening the Integrated Terminal:

- Press `Ctrl + ` (backtick) or go to `View > Terminal` to open the integrated terminal.
- You'll see a terminal panel at the bottom of the VS Code window.
  b) Running Commands:
- Type any command (e.g., `npm install`, `git status`, `python my_script.py`) directly into the terminal.
- Press `Enter` to execute the command.
- Output from the command will appear in the terminal.
  c) Advantages of the Integrated Terminal:
- Seamless Workflow: No need to switch between VS Code and an external terminal.
- Contextual: The terminal opens in the workspace directory, so you're always in the right context.
- Customizable: You can choose your preferred shell (e.g., PowerShell, Bash, Command Prompt).
- Integrated Debugging: Debug your code directly from the terminal.

7. File and Folder Management:

   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

a) Creating Files and Folders:

- To create a new file, use the following steps:
  - Click the Explorer icon in the Side Bar (or press `Ctrl + Shift + E`).
  - Right-click in the file list and choose "New File."
  - Enter the desired filename (e.g., `index.html`) and press `Enter`.
- To create a new folder: - Right-click in the file list and choose "New Folder." - Name the folder as needed.
  b) Opening Files:
- Use any of the following methods: - Click on a file in the Explorer to open it. - Use the Command Palette (`Ctrl + Shift + P`) and search for "File: Open File." - Use the keyboard shortcut (`Ctrl + P`) and type the filename to open it.
  c) Navigating Between Files and Directories:
- Use the Explorer:
  - Navigate through folders by clicking on them.
  - Use the breadcrumbs at the top to move up the directory tree.
- Use the keyboard shortcuts:
  - `Ctrl + Tab`: Cycle through open files.
  - `Ctrl + 1`, `Ctrl + 2`, etc.: Jump to specific editor groups.
  - `Ctrl + \`` (backtick): Toggle between the last two active files.
- Use the Command Palette:
  - Search for "File: Open Recent" to quickly access recently opened files.

8. Settings and Preferences:

   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

a) Open the Settings Editor:

- Navigate to File > Preferences > Settings.
- Alternatively, use the keyboard shortcut:’’Ctrl + ,”(Windows/Linux) or “Cmd + ,”(macOS).
  b) Examples of Customization:
- Change Theme:
  - Search for "Color Theme" in the search bar.
  - Choose a theme from the dropdown (e.g., "Dark+ (default dark)" or "Light+ (default light)").
- Adjust Font Size:
  - Search for "Font Size" in the search bar.
  - Modify the font size value (e.g., "14").
- Modify Keybindings:
  - Search for "Keybindings" in the search bar.
  - Click "Edit Keybindings.json" to customize keybindings.

References:
(1) VS Code text editor: How to customize settings and add extensions. https://www.youtube.com/watch?v=Dd1ZJiCveGY.
(2) Visual Studio Code User and Workspace Settings. https://code.visualstudio.com/docs/getstarted/settings.
(3) How I Setup And Customize VSCode. https://www.youtube.com/watch?v=VknMxAIbJj4.

9. Debugging in VS Code:

   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

a) Open the Run and Debug View:

- Click on the (Run and Debug) icon in the Activity Bar on the side of VS Code.
- Alternatively, use the keyboard shortcut: `Shift + Ctrl + D` (Windows/Linux) or `Shift + Cmd + D`(macOS).
  b) Configure a Launch Configuration:
- If you haven't already, VS Code will prompt you to create a `launch.json` file.
- This file defines how your program should be launched for debugging.
- Choose your runtime (e.g., Node.js) and specify the entry point (e.g., your main script).
  c) Set Breakpoints:
- Click in the gutter next to the line of code where you want to pause execution (a red dot will appear).
- Breakpoints allow you to inspect variables and step through your code.
  d) Start Debugging:
- Click the green play button (or press `F5`).
- VS Code will launch your program in debug mode.
- It will stop at the breakpoints you set.
  e) Debugging Features:
- Watch Inspect variables and expressions while debugging.
- Call Stack: See the order of function calls.
- Step Over/Into/Out: Navigate through your code line by line.
- Variables: View and modify variable values.
- Console: Execute commands and evaluate expressions.

References:
(1) Debugging in Visual Studio Code. https://code.visualstudio.com/Docs/editor/debugging.
(2) Introduction to Debugging in Visual Studio Code. https://code.visualstudio.com/docs/introvideos/debugging.

10. Using Source Control:

    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

a) Initialize a Local Git Repository:

- Open your project folder in VS Code.
- If it's not already a Git repository, click the "Initialize Repository" button in the Source Control view.
- This creates a new Git repository in the current folder, allowing you to start tracking code changes.
  b) Make Commits:
- Make changes to your files (e.g., modify code, add new files).
- Save your changes (Ctrl+S or Cmd+S).
- In the Source Control view, stage the changes by clicking the "+" icon next to the file(s) you want to commit.
- Add a commit message describing your changes.
- Click the checkmark icon to commit the changes.
  c) Push Changes to GitHub:
- If you haven't already, create a remote repository on GitHub.
- In VS Code, click the three dots icon in the Source Control view and select "Push to..."
- Enter the URL of your GitHub repository and press Enter.
- VS Code will push your local code changes to the remote repository on GitHub.

References:
(1) How to use GIT Source Control with VSCode - Tutorial. https://www.youtube.com/watch?v=EjHJNjLxE_U.
(2) Version control in Visual Studio Code. https://code.visualstudio.com/docs/introvideos/versioncontrol.
(3) Source Control with Git in Visual Studio Code. https://code.visualstudio.com/docs/sourcecontrol/overview.

Submission Guidelines:

- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July
