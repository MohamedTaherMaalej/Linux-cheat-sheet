# Basic Linux Commands

This Markdown file provides a list of some common Linux commands and their descriptions.

---

## Navigation Commands

### `pwd`
Print the current working directory.

### `ls`
List files and directories in the current directory.

### `cd`
Change the current directory.

- `cd <directory>`: Change to a specific directory.
- `cd ..`: Move up one directory.
- `cd ~`: Change to the home directory.

---

## File and Directory Operations

### `touch`
Create an empty file.

### `mkdir`
Create a new directory.

### `cp`
Copy files or directories.

- `cp <source> <destination>`: Copy a file or directory.

### `mv`
Move or rename files or directories.

- `mv <source> <destination>`: Move or rename a file or directory.

### `rm`
Remove files or directories.

- `rm <file>`: Remove a file.
- `rm -r <directory>`: Remove a directory and its contents (use with caution).

---

## File Viewing and Editing

### `cat`
Display the content of a file.

### `more` / `less`
View the contents of a file one screen at a time.

### `nano` / `vim` / `emacs`
Text editors for creating and editing files.

---

## File Permissions

### `chmod`
Change file permissions.

- `chmod <permissions> <file>`: Modify the permissions of a file.

### `chown`
Change file ownership.

- `chown <user>:<group> <file>`: Change the owner and group of a file.

---

## Process Management

### `ps`
List currently running processes.

### `top` / `htop`
Display real-time system statistics and process information.

### `kill`
Terminate a running process.

- `kill <process_id>`: Terminate a process by its ID.

---

## Package Management

### `apt` (Debian/Ubuntu) / `yum` (CentOS/Fedora)
Package managers for installing, updating, and removing software packages.

- `apt-get install <package>`: Install a package.
- `apt-get update`: Update the package list.
- `apt-get upgrade`: Upgrade installed packages.
- `apt-get remove <package>`: Remove a package.

---

## Network Commands

### `ifconfig`
Display network interface configuration.

### `ping`
Test network connectivity to a remote host.

- `ping <hostname or IP>`: Send ICMP echo requests to a host.

### `netstat`
Display network statistics and routing table.

---

These are just a few of the many Linux commands available. You can access the manual pages for each command by using `man <command>` for more detailed information.
