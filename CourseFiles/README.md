# 2023-RTT-74
https://code.visualstudio.com/api/ux-guidelines/overview
https://code.visualstudio.com/docs/getstarted/userinterface
https://code.visualstudio.com/api/extension-capabilities/extending-workbench

"Workbench" refers to the overall Visual Studio Code UI that encompasses the following UI components:

Title Bar
Activity Bar
Side Bar
Panel
Editor Group
Status Bar

![Containers](https://github.com/vbossPS/2023-RTT-74/assets/140511338/aa70be0f-2fa1-458a-991b-7ecee2fdd45c)
![Items](https://github.com/vbossPS/2023-RTT-74/assets/140511338/aee432a4-2a01-436c-8d8f-6d8970a98c2a)

Basic Layout
VS Code comes with a simple and intuitive layout that maximizes the space provided for the editor while leaving ample room to browse and access the full context of your folder or project. The UI is divided into five main areas:

Editor - The main area to edit your files. You can open as many editors as you like side by side vertically and horizontally.
Primary Side Bar - Contains different views like the Explorer to assist you while working on your project.
Status Bar - Information about the opened project and the files you edit.
Activity Bar - Located on the far left-hand side, this lets you switch between views and gives you additional context-specific indicators, like the number of outgoing changes when Git is enabled.
Panel - An additional space for views below the editor region. By default, it houses output, debug information, errors and warnings, and an integrated terminal. Panel can also be moved to the left or right for more vertical space.

Views
The File Explorer is just one of the Views available in VS Code. There are also Views for:

Search - Provides global search and replace across your open folder.
Source Control - VS Code includes Git source control by default.
Run - VS Code's Run and Debug View displays variables, call stacks, and breakpoints.
Extensions - Install and manage your extensions within VS Code.
Custom views - Views contributed by extensions.
