# Linux filesystem hierarchy

✍🏻by Natnael W.

**The Filesystem Hierarchy Standard** is a reference describing the conventions used for the layout of a UNIX system.
 Linux/UNIX have a specialfile system than windows.
 File system is a directory structure that the **os** uses.

 ## File structures in detail

 1.**/bin**-**Binary** : contain the commands of the computer.
 
 2.**/boot**-**Bootfiles** :contain the operating system startup configures.

 3.**/dev**-**Devices** :contain the PC's main files.

 4.**/etc**-**etcetera** :contain software configurations.

 5.**/media** : contain mounted files.

 6.**/root** : The administrator of the computer.

 7.**/sbin**-**system binary** :contain commands that ask root 
 access.

8.**/usr**-**users** : contain users informations.

9.**/mnt** : contain temporary mounted files.

## Text Editors

They are programs that used for text processing.

- Linux commmand line text editors 
    
    **Vim**

    **Nano**

    **Emacs**

-Linux Graphical Text editors
   
   **sublime**

   **VS Code**

   **Gedit**

### Vim

The vi editors improved and developed Vim after the primary editor used on Unix. Vim is by default on **command mode** when you open it.To get on **insert mode** type the letter *i*.
To save and quit type **:wq!**.

### NANO

The **GNU nano** text editor is a user-friendly,
free and open-source text editor that
usually comes pre-installed in modern Linux
systems.

#### options
- Ctrl + S - save
- Alt + U - Undo 
- Alt + E - Redo
- Ctrl + X - Exit

Paste,Copy & paste all over the linux is
- Ctrl+shift+C - copy
- Ctrl+shift+X - Cut
- Ctrl+shift+V - Paste

## Linux User Managment

On Computer system, person who uses the computer is called “user”. Every Users have Group.
The root user have the power to do everything on linux ,
but if users want to have a root access they add **sudo** in front of the command .

## Creating Users

On linux, to create users you can use the following commands
- Useradd -> simple
- Adduser -> Detailed
