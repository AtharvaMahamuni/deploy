- Introduction to Linux and Unix
    Unix is a family of Operating systems.
    Linux is the family of Unix-like Operating systems. It contains multiple file systems and flavors. 
    Linux Kernel is core component
    

- Linux distro differences
    - System utilities
    - GUI
    - Shell commands
    - support types
    
- Five Layers of Linux
    1. UI
    2. Application (System daemons, Shells, User apps, Tools)
    3. Operating System
    4. Kernel
    5. Hardware

- `man` - commands used to see the manual for particular command

- Paths in the linux filesystem
    - “a/b” → This indicated the ‘b’ inside the ‘a’ directory
    - Special path
        - ‘~’  -  Home directory
        - ‘/’  -  Root directory
        - ‘..’  -  Parent of the current directory
        - ‘.’  - Current directory
    

 

- Changing the directory
    
    `cd`, `ls`, `pwd`, ‘tab autocomplete’, ‘up’ & ‘down’ arrows for command history.
    

 

- Text Editors
    - GNU nano
    - vi
    - vim

- Updating and installing S/W
    - .deb - for Debian based packages
    - .rpm - for RedHat based packages
    - To convert package use `alien` command
    - Many benefits of Package managers.
    - `apt` is command line tool for Debian based Linux.
    - `yum` is command line tool for RPM based systems
    - We can use this command line tools for installing the packages as well.

- Common shell commands
    
    `bash` command to select the bash shell.
    
    `whoami` - username
    
    `id` - user ID and group ID
    
    `uname` - operating system name
    
    `ps` - running processes
    
    `top` - resource usage
    
    `df` - mounted file systems
    
    `man` - reference manual
    
    `date` - today’s date
    
- Common commands to work with files
    
    `cp` - copy file
    
    `mv` - change file name or path
    
    `rm` - remove file
    
    `touch` - create empty file, update file timestamp
    
    `chmod` - change/modify file permissions
    
    `wc` - get count of lines, words, characters in file
    
    `grep` - return lines in file matching pattern
    
- Common commands to work with directories
    
    `ls` - list files and directories
    
    `find` - find files in directory tree
    
    `pwd`  - get present working directory
    
    `mkdir` - make directory
    
    `cd` - change directory
    
    `rmdir` - remove directory
    
- Common commands to printing file and string contents
    
    `cat` - printing file contents
    
    `more` - print file contents page-by-page
    
    `head` - print first N lines of file
    
    `tail` - print last N lines of file
    
    `echo` - print string or variable value
    
- Commands to wrangle with text in files
    
    `sort` - Sort lines in a file
    
    `uniq` (”unique”) - To filter out repeated lines
    
    `grep` (”global regular expression print”) - Return lines in file
    
    `cut` - Extracts a section from each line
    
    `paste` - Merge lines from different files
    
    `wc` - Prints the number of lines in file
    
- Networking
    
    `hostname` - print hostname
    
    `ifconfig` (Interface Configuration) - Display or configure the system network interfaces.
    
    `ping` - send ICMP packets to URL and print response
    
    `curl` (Client URL) - Transfer data to and from URL(s)
    
    `wget` (Web get) - Download file(s) from a URL
    
    - More focused than `curl`, supports recursive file downloads.
    
- Compress and archive
    
    `tar` - Archive and extract files
    
    `zip` - Compress files and directories to an archive
    
    `unzip` - Extract and decompress zipped archive