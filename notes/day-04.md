# Day 04 - Linux and Windows CLI Basics

## Linux CLI Basics

### What I Learned

* Navigate the Linux filesystem.
* Search for files.
* Inspect system information.
* Read important configuration files.
* Follow clues and complete tasks inside a Linux environment.

### Basic Commands

#### `pwd`

Prints the current working directory.

#### `ls`

Lists the files and directories in the current working directory.

#### `ls -l`

Shows detailed information about files and directories, such as permissions, size, and modification date.

#### `ls -al`

Shows detailed information, including hidden files.

In Linux, hidden files usually start with a dot (`.`).

#### `cd`

Changes the current working directory.

#### `cd ..`

Moves to the parent directory.

#### `find <starting_point> -name <filename>`

Searches for a file by name starting from the specified location.

#### `cat`

Displays the contents of a file.

#### `whoami`

Shows the user I am currently logged in as.

#### `uname -a`

Displays detailed information about the system and kernel, including the kernel version and system architecture.

#### `df -h`

Displays filesystem disk space usage in a human-readable format.

### Linux Configuration Files

I learned that `/etc` contains important configuration files and system information.

One of the files is:

```bash
/etc/os-release
```

I can use `cat` to read it:

```bash
cat /etc/os-release
```

It shows information about the Linux distribution and other system details.

---

## Windows CLI Basics

I also learned some basic Windows command-line commands.

### `cd`

Used to navigate between directories. Running `cd` without a path can also show the current directory.

### `dir`

Lists the contents of the current directory.

### `dir /a`

Lists the contents of the current directory, including hidden files.

### `dir /s <filename>`

Searches for a specific file in the current directory and all of its subdirectories, and shows the full path if the file is found.

### `type`

Displays the contents of a text file.

### `whoami`

Shows the user I am currently logged in as.

### `hostname`

Shows the computer's hostname.

### `systeminfo`

Displays detailed information about the Windows system.

### `ipconfig`

Displays the computer's network configuration.
