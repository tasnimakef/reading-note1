# The Command Line
What is Windows Terminal?
Windows Terminal is a modern terminal application for users of command-line tools and shells like Command Prompt, PowerShell, and Windows Subsystem for Linux (WSL). Its main features include multiple tabs, panes, Unicode and UTF-8 character support, a GPU accelerated text rendering engine, and the ability to create your own themes and customize text, colors, backgrounds, and shortcuts.
![te](https://raw.githubusercontent.com/mobilemancer/windows-terminal-aurelia/master/demo.jpg)

# Practice navigating from the terminal
The filesystem on your computer is like a tree made up of folders (also called "directories") and files. The filesystem is divided between drives, each named with a letter; the main drive has a root directory called C:\, and everything on this drive lives in subdirectories of this root directory.

We often navigate the filesystem graphically by clicking on graphical folders. We can do the exact same navigation from the terminal.

There are two commands that we'll be using in the PowerShell terminal to navigate the filesystem on your computer:

ls
cd
ls lists the contents of a directory.
cd moves you into a new directory (it stands for "change directory").

# What’s in a folder
When you first get to the command line, you’re in your home folder. While you’re there—or when you’re in any folder (directory in Unix-speak)—you might want to know what’s in it. To do that you use the ls (or list) command. Type ls and press the Return key, and you’ll see the folders (and/or files) in the current directory.
