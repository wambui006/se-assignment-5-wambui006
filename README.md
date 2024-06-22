[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15296657&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.
   Prerequisites-good connection and windows 11 installed
   download vscode from its official webpage, download its installer for windows and open, click yes to allow the installer to make changes to the device
   install- a  setuo wizard will open and click next to proceed , accept the licence agreement and follow all the steps until the button 'finish install' appears to close the setup wizard and launch vs code


2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.
   - initial configurations include;
-opening vs code
-choose a theme
settings include;
-configure the intergrated terminal such as default shell. it could be gitbash ,pwershell. CMD etc
-setting up auto save
-adjustingfont size
essential extensions include;
-prettier
-python
-dart
-flutter


3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.
   components of the vs code user interface include; activity bar, editor bar, side bar, status bar
   (a)activity bar- located on the far left side of the VS Code interface. It provides access to different features within the editor such as run and debugg, search, source control 
   (b) side bar- located immediately to the right of activity bar. its content is based on the actions taken in the activity bar. for example when you click on extensions in the activity bar, different extensions will show in the side bar where you choose your preferred extension from there
   (c)editor group- this is the cental area in the vs code where codes are written and viewed.
   (d) status bar- located at the bottom of the vs code window and it provides information about opened projects abd editors


4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.
   .command palette is a tool that gives access to commands and settings without the user needing to remember keyboard shortcuts or navigating through menus.
   it can be accessed by clicking the view menu >'command palette'
   common tasks using the command palette include opening and closing of files or folders, management of extensions, changing colour theme, and running and debugging

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.
   extensions enhance the funcyion of vscode and enables users to add features, intergrate with other tppls and support languages and frameworks.
   finding extensions- click the extension icon in the activity bar 
   installing extensions- after finding an extension of choice, click the 'install' button
   managing extensions- right click on an extension to enable , disable or delete an extension.
   example of essential extensions for web development include prettier and Eslint

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?
this is feature that allows user to run command-line operations within the editor itself

Opening the Integrated Terminal-Go to the View menu and select Terminal.

Using the Integrated Terminal in basic commands such as navigating directories, it can be used as split terminals where many panes are created by clicking on the split icon.

Advantages of Using the Integrated Terminal include having a seemless workflow as user is able to run commands without leaving editor, easy copy and paste betwen the editor and the terminal, intergrated terminal uses the ame environment variables and settings as the ones in the editor and intergration of extensions in the terminal makes enhanced functionality

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?
   -creating new files- click on file on the menu then click new file
   -creating new folder- click on file menu >open folder whwre a new window will open, then select new folder
   -opening files and folders- click on file menu > click open file to open a file or click open folder to choose a folder to open.
-managing files and folders, right click on the file or folder, select 'rename' to reme, select 'delete' to delete .
-navigating between different files and directories efficiently can be done by quick opening of files, having diffeent file tabs that can be easily accessed.


8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.
-finding settings in vs code- open file menu >preferences> settings where changes can be made as per users preferences.
-how to change theme open file menu > preferences> theme >colour theme> choose a theme such as default dark or a light theme 
-how to change font size - open file menu > preferences> settings> font size>  change font size eg from 12 to 14 
-how to change keyboardbindings - open file menu > preference> keyboard shortcuts

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?
   steps include ;
   -open vs code
   -open project
   -write a program eg a python program
   -configure the debugger
   -set breakpoint for example Set a breakpoint at print(greet(user_name)).
   -start debugging by pressing f5 key which will prompt the user name in intergratd terminal
   -enter name and the program will hit breakpoint
   -inspect the value of user_name and the result of greet(user_name) in the VARIABLES pane or by hovering over them.
   -Use F10 to step over the print statement and see the output in the terminal
key debugging features in vs code include;
-breakpoints
-watch expressions
-step through code
-call stack
-debug console


10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.
    -     how to intergrate git with vscode;
    - install Git
    -configure Git, on git bash by setting up user name and email 
    initializing repository;
    - open project
    - initialize a repository from the terminal- git init
    -commit changes on the terminal by writing git add . then enter then followed by git commit -m "message to commit" then click enter
    -on terminal, write git push to push commited changes to GitHub


 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

