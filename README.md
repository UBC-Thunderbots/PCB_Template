# PCB_Template
Template Github SVN repository for Altium project files. 

# How to link repository with Altium Designer
## Required software
1. git
2. github GUI (optional, I am using GitHub Desktop)
2. Altium Designer

## Instructions
1. Create a working branch of Master in github.
1. Clone your working branch of UBC-Thunderbots/`<repo name>` to your PC (i.e. C:/Documents/GitHub/`<repo name>`)
2. In Altium Designer, navigate to **Preferences** -> **Data Management** -> **Version Control** and ensure *SVN - Subversion* is enabled and Version 1.9 is selected.
4. In Altium Designer, navigate to **Preferences** -> **Data Management** -> **Design Repositories**.
5. Within **Design Repositories** click on on *Connect To* -> *SVN*.
6. In the dialogue box that comes up, fill in the following information:

Field | Selection/Input
--- | ---
Name | `<repo name>`
Default Checkout Path | *location of the cloned UBC-Thunderbots/`<repo name>` repository (i.e. C:/Documents/GitHub/`<repo name>`)*
Method | https
Server | github.com
Server Port | Default
Repository Subfolder | /UBC-Thunderbots/`<repo name>`
User Name | *your github login username*
Password | *your github login password*

7. Click *Test* and pray.
8. Celebrate!

After your repository is connected, you can add or remove files like a regular Altium Project folder and then commit them from within Altium Designer by right-clicking on any project files in the **Projects** and hovering the mouse cursor over **Version Control**. After you have finished making changes to your branch, submit a pull request to merge it with Master.

Reference page: https://forum.live.altium.com/#posts/235981/718003

