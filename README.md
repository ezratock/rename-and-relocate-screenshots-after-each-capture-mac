# rename-and-relocate-screenshots-after-each-capture-mac
A script that takes a screenshot in interactive mode and prompts the user to rename and relocate it.  Easy to trigger with a custom keyboard shortcut or function key!  The default name and location for screenshots stored on your Mac are still easily accessible during use.  Compatible with MacOS 10.6 or later.

# Installation
### Clone the repository to your computer
1) open a terminal
2) navigate to the folder you'd like to temporarily put the installation directory in (e.g. ~/Downloads) with ``cd path/to/folder``
3) run ``git clone https://github.com/ezratock/rename-and-relocate-screenshots-after-each-capture-Mac.git``
### Install the script
1) navigate to the newly created rename-and-relocate-screenshots-after-each-capture-mac folder in a finder window
2) double click on the named-screenshots Quick Action workflow  
   ![named-screenshots workflow](img/named-screenshots_Workflow.png?raw=true "named-screenshots workflow")
3) in the resulting "Quick Action Installer" click "Install"  
   ![Quick Action Installer](img/QuickActionInstaller.png?raw=true "Quick Action Installer")
### Set custom keyboard shortcut or function key (MacOS 14)
1) if a settings window doesn't automatically pop up, open System Settings, navigate to "Keyboard" and press "Keyboard Shortcuts..."  
![Keyboard Shortcuts](img/keyboard-shortcuts.png?raw=true "keyboard shortcuts")
2) in the left sidebar, select "Services" and drop down the menu for "General"
3) ensure the "named-screenshots" box is checked and then double click where it says "none" to set your custom keyboard shortcut or function key  
   ![none](img/none.png?raw=true "none")
4) Type the custom keyboard shotcut or function key you'd like to trigger screenshots.  Make sure the shortcut you choose is not already in use.  If you'd like to set the shortcut to be command + shift + 4 as usual, select "Screenshots" from the left sidebar and DEselect "Save picture of selected area as a file" before proceeding.
5) click "Done"
6) note: custom keyboard shortcuts do not work on apps like System Settings, so close out of System Settings before testing your new screenshot shortcut
