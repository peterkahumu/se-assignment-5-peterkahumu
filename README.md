[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15277658&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

---

 Questions:

1. Installation of VS Code:
   - <u>Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.</u>

      #### **PREREQUISITES**
      a. 1.6 GHZ or faster processor.
      b. 1 GB RAM Minimum, 2 GB recommended.
      c. 200  MB of available hard disk space.

      #### *Installation Steps.*
      a. Visit the official download page: [VS Code Download Link](https://code.visualstudio.com/) and download the installer for windows  11. 

      b. Locate the installer and run it as an administrator.

      c. Accept the terms and conditions for the VS code.

      ![screenshot 1](./screenshots/Accept%20the%20terms%20and%20conditions.png)

      d. Select the default folder or leave it as default.

      ![screenshot 2](./screenshots/Select%20the%20start%20menu%20folder.png)

      e. Customize the installation settings if necessary or leave them as default.

      ![screenshot](./screenshots/Customize%20the%20installation%20settings%20if%20need%20be.png)

      f. Click next than install.

      ![screenshot](./screenshots/click%20next%20to%20install.png)

      g. Wait for the Vs Code to install.

      ![screenshot](./screenshots/wait%20for%20the%20visual%20studio%20to%20install.png)

      h. After the installation is complete, click finish, and wait for the welcome page to appear on the screen.

      ![screenshot](./screenshots/Wait%20for%20vs%20code%20to%20launch%20and%20display%20the%20welcome%20screen.png)

---
2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

      - ***Settings***
         - Enable autosaving.
         
         - Configure the tab size to the appropriate number of spaces.

         - Enable word wrap.

         - Set the default terminal to `git bash`.

         - Adjust the themes to your liking.
      
      - ***Extensions***
         - Install intelliscence for the different languages that you might need to use.

         - Install the extensions to the programming languages you want to use. This includes:

            - HTML/ CSS extensions.

            - Live server and live preview files.

            - Python extensions.

            - Flutter.

            - Dart.

            - SQLite viewer.

         - *NB*: ENSURE TO INSTALL VERIFIED EXTENSIONS

      

---
3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

      ![vs code parts](./screenshots/VScode%20parts.png)

      #### *Functions of the Different parts of the VS CODE.*
      i. **Activity Bar** - The Activity Bar in VS Code provides quick access to essential views and functionalities like file navigation, search, source control management, debugging, and extensions management. It organizes core features into easily accessible icons, enhancing workflow efficiency within the editor.

      ii. **Side Bar** - The VS Code Side Bar displays detailed information and interactive controls for the currently selected view from the Activity Bar, such as file navigation, search results, source control management, and debugging. It enhances productivity by providing easy access to essential tools and functionalities within the editor.

      iii. **Editor Group** - The Editor Group in VS Code is the central workspace where multiple files can be opened simultaneously in tabs or split views, facilitating efficient code editing and navigation within the editor. It supports syntax highlighting, code completion, and seamless integration with various programming languages and extensions for enhanced development productivity.
      
      iv. **Status Bar** - The Status Bar in VS Code, located at the bottom of the window, provides real-time information about the current workspace, including Git branch status, file encoding, line and column numbers, and debugging information. It also offers controls for settings like language mode and provides notifications for background tasks and errors, enhancing user awareness and productivity while coding.
---
4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

      - Allows users to execurte commands quickly without navigating through the menus or remembering keyboard shortcuts
      - It can be accessed through:
         - **Keyboard shortcuts**: `Ctrl+Shift+P`.
         - **Menu**: click on `view -> Command Palette`
      - Main tasks  include:
         - Open files and commands.
         - Change Language Modes
         - Git Operations
         - Debugging
         - Extensions Management
---
5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

      - The role of extensions is to:
         - Add new features, languages, themes, integrations, and allow users to customize development environment to suit specific needs.

      - **Extensions:** can be found using the `Extensions bar in the Activity bar` or using shortcuts `Ctrl+Shift+X`. 
      - **Installation:** Browse on the search bar for the desired extension and click `install`.
      - **Managing extensions:** Enable or disable the extensions, uninstall extensions or updating from the `Extensions View.` 

      - Examples of extensions for web development are:
         - Live server for local server and live reload
         - Prettier for code formatting
         - Eslint for Javascript and TypeScript linting.
         - HTML CSS for enhanced editing capabilities.
---   
6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

      - Opening the Integrated Terminal.
         - **Keyboard Shortcut:** `Ctrl+\``
         - **Menu:** `view -> terminal` or `Terminal -> New Terminal`
      - **Using the terminal:** Type commands and interact with the system as per your needs.

      - **Advantages of Internal Terminal over the External Terminal.**
         - Eliminates the need for switching between windows.
         - Integrated features like error detection and clickable links within the terminal output, improving the workflow.
         - Enables opening multiple terminals if working with different directories.
---
7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

      - **Creating files and folders** - Right click in the file explorer and select `new file` or `new folder.` Give the required name and or extension for files.

      - **Opening files and folders** -  Double-click the file or folder you want to open in the File Explorer.

      - **Managing Files and Folders** - Right-click on a file or folder to access various options for renaming, deleting, copying, cutting, pasting, and more. Drag and drop functionality is also available within the File Explorer**

      - **Efficient Navigation** - VS Code offers powerful search and switch features like Quick Access (Cmd/Ctrl + P) to find files and symbols, and file switching (Ctrl/Cmd + Tab) to navigate between recently opened files.
---
8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings. 

      - **Open Settings** - `Click on the setting Icon at the bottom of the action bar, just above the Status bar.` or use the keyboard shortcut `Ctrl + ,` to customize the settings.
      
      - **Changing the theme** - Search for "Color Theme" and select your desired theme from the dropdown.
      - ** Adjust the Font size ** - Search for "Font Size" and adjust the slider or enter a specific pixel value.
      - **Modify keybindings** - Search for "Keyboard Shortcuts" to open a comprehensive list of keybindings. You can modify existing ones or create new ones by clicking the edit icon next to the desired action.
---
9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

      - To start debugging in VS Code, first set up by installing necessary extensions and configuring launch settings in `launch.json`. Place breakpoints in your code to pause execution where needed, then start debugging with the play button or `F5`. Use intuitive controls to step through code (`F10`, `F11`), inspect variables and the call stack, and utilize the debug console for interactive debugging. VS Code supports multiple languages, offers flexible debugging configurations, and enhances code quality with features like conditional breakpoints and exception handling.
---
10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

      - To integrate Git with VS Code for version control:

      1. **Initializing a Repository**:
         - Open your project folder in VS Code.
         - Click on the Source Control icon in the Activity Bar (Ctrl+Shift+G).
         - Initialize a Git repository by clicking "Initialize Repository" and follow the prompts.

      2. **Making Commits**:
         - Stage changes by clicking the "+" button next to modified files in the Source Control view.
         - Enter a commit message and click the checkmark icon to commit changes.

      3. **Pushing Changes to GitHub**:
         - Set up a remote repository on GitHub.
         - Add the GitHub repository as a remote using `git remote add origin <remote_repository_url>`.
         - Push changes to GitHub using `git push -u origin master` or your branch name.

---
 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

