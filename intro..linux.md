##  Table of Contents:
1. **What is Linux?**
2. **CentOS Installation in VirtualBox**
3. **Linux Distributions**
4. **Linux Filesystem Structure**
5. **Basic Linux Commands**
6. **Understanding the Linux Terminal**
7. **Working with Files and Directories**
8. **Permissions and Ownership**
9. **Package Management**
10. **Process Management**
11. **Networking Commands**
12. **Shell Scripting Basics**

---

##  1. **What is Linux?**

Linux is an open-source operating system (OS) that's based on the Linux kernel. It's used in servers, desktops, mobile devices, and embedded systems. Unlike Windows or macOS, Linux is free to use, modify, and distribute. It’s known for being secure, stable, and versatile.

---

##  2.**CentOS Installation in VirtualBox**

## 📹 **Installation Video**
To watch the full installation video, click on the link below:  
### *[CentOS Installation in VirtualBox](https://www.youtube.com/watch?v=ZqyVrfW2c6g)*

###⚡ *Congratulations!* 
You have successfully installed CentOS on VirtualBox! Enjoy exploring your new virtual machine and getting familiar with CentOS.

---

##  3. **Linux Distributions**

A Linux **distribution** (or **distro**) is a version of Linux that includes the Linux kernel and various software packages to make the OS functional.

- **Ubuntu**: User-friendly, great community support.
- **Debian**: Known for its stability.
- **CentOS/RedHat**: Used in enterprise environments.
- **Fedora**: Cutting-edge features, often used by developers.

---

##  4. **Linux Filesystem Structure**

In Linux, everything is a file, and the entire filesystem is organized in a hierarchical tree-like structure, starting from the root directory (/). 

#### Common directories:
- /: The root directory, where everything starts.
- /bin: Essential command binaries.
- /etc: Configuration files.
- /home: User home directories.
- /var: Variable files, such as logs and mail.
- /tmp: Temporary files.
- /dev: Device files.
- /usr: User applications and utilities.

---

##  5. **Basic Linux Commands**

Here are some basic commands that every Linux user should know:

- **ls**: Lists files in the current directory.
  - Example: ls -l (detailed listing)
  
- **pwd**: Prints the current working directory.
  
- **cd**: Changes the current directory.
  - Example: cd /home/user/ (navigate to /home/user/)
  
- **cp**: Copies files or directories.
  - Example: cp file1.txt /home/user/
  
- **mv**: Moves or renames files.
  - Example: mv oldfile.txt newfile.txt
  
- **rm**: Removes files or directories.
  - Example: rm file.txt
  
- **cat**: Displays the contents of a file.
  - Example: cat file.txt
  
- **man**: Displays the manual for a command.
  - Example: man ls

---

##  6. **Understanding the Linux Terminal**

The **terminal** is the command-line interface (CLI) in Linux. It's where you type commands to interact with the system.

- **Prompt**: The terminal shows a prompt indicating it’s ready to accept commands.
  Example: username@hostname:~$
  
- **Root User**: The system administrator account with full privileges, denoted by root. You can switch to root by using sudo or su.

- **Bash**: The default shell for most Linux systems. It allows users to interact with the OS via commands.

---

##  7. **Working with Files and Directories**

#### Navigating Directories:

- **ls**: Lists files and directories.
- **cd**: Change directories.
- **pwd**: Print working directory.

#### File Operations:

- **cp**: Copy files and directories.
- **mv**: Move or rename files and directories.
- **rm**: Remove files or directories.

#### Example:

bash
mkdir myfolder          # Creates a directory
cd myfolder             # Navigates into the folder
touch file.txt          # Creates an empty file
ls                       # Lists files
rm file.txt              # Deletes the file



---

##  8. **Permissions and Ownership**

Linux uses a system of permissions to control who can read, write, and execute files.

- **Owner**: The user who created the file.
- **Group**: Users who belong to the same group.
- **Others**: Everyone else.

#### Commands to manage permissions:

- **chmod**: Change file permissions.
  - Example: chmod +x file.sh (gives execute permission)
  
- **chown**: Change file owner and group.
  - Example: chown user:group file.txt

- **chgrp**: Change the group ownership of a file.
  - Example: chgrp group file.txt

#### Understanding Permissions:
File permissions are displayed as a string of characters like -rwxr-xr--. The first character denotes the file type, followed by three sets of three characters each representing owner, group, and others' permissions.

- **r**: Read
- **w**: Write
- **x**: Execute

---

##  9. **Package Management**

In Linux, software is managed through **package managers**. Package managers allow you to install, update, and remove software.

#### For Ubuntu/Debian (APT):
- **apt-get install <package>**: Install a package.
- **apt-get update**: Update package lists.
- **apt-get upgrade**: Upgrade installed packages.

#### For CentOS (YUM):
- **yum install <package>**: Install a package.
- **yum update**: Update installed packages.

---

##  10. **Process Management**

Processes in Linux are managed through commands that allow you to see running programs and control their execution.

- **ps**: Lists current running processes.
  - Example: ps aux (shows all processes)
  
- **top**: Displays real-time system information and running processes.
  
- **kill**: Terminates a process.
  - Example: kill 1234 (kills process with PID 1234)

- **nohup**: Runs a command even if the terminal is closed.
  - Example: nohup command &

---

##  11. **Networking Commands**

Linux provides various networking tools for configuration and troubleshooting:

- **ifconfig**: Shows or configures network interfaces.
- **ping**: Tests connectivity to a host.
  - Example: ping google.com
  
- **netstat**: Displays network connections and listening ports.
- **ssh**: Secure shell for remote login.
  - Example: ssh username@hostname

---

##  12. **Shell Scripting Basics**

Shell scripting allows you to automate tasks using a sequence of commands.

#### Basic Script Example:

bash
#!/bin/bash
echo "Hello, World!"



- **#!/bin/bash**: Specifies the shell to use.
- **echo**: Prints text to the terminal.

#### Making a script executable:

bash
chmod +x script.sh    # Makes the script executable
./script.sh           # Runs the script

---

##      **by krishna kushwah**          *[LinkedIn](https://www.linkedin.com/in/krishna-kushwah-382812317/)*
