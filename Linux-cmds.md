# Common Linux Commands for Admins, Network Engineers, and DevOps Engineers

## System Information
- `uname -a`: Display all system information
- `hostname`: Show or set the system's hostname
- `uptime`: Show how long the system has been running
- `top`: Display tasks and system status
- `htop`: Interactive process viewer

## File and Directory Management
- `ls`: List directory contents
- `cd`: Change directory
- `pwd`: Print working directory
- `mkdir`: Create directories
- `rm`: Remove files or directories
- `cp`: Copy files or directories
- `mv`: Move or rename files or directories
- `chmod`: Change file modes or Access Control Lists
- `chown`: Change file owner and group

## Disk Usage
- `df`: Report file system disk space usage
- `du`: Estimate file space usage
- `fdisk`: Partition table manipulator for Linux
- `mount`: Mount a file system
- `umount`: Unmount file systems

## Networking
- `ifconfig`: Configure a network interface
- `ip`: Show/manipulate routing, devices, policy routing, and tunnels
- `ping`: Send ICMP ECHO_REQUEST to network hosts
- `netstat`: Print network connections, routing tables, interface statistics, masquerade connections, and multicast memberships
- `traceroute`: Print the route packets take to the network host
- `nslookup`: Query Internet name servers interactively
- `dig`: DNS lookup
- `ssh`: OpenSSH SSH client (remote login program)
- `scp`: Secure copy (remote file copy program)
- `sftp`: Secure File Transfer Protocol

## Process Management
- `ps`: Report a snapshot of current processes
- `kill`: Send a signal to a process
- `pkill`: Send a signal to processes based on name and other attributes
- `killall`: Kill processes by name
- `bg`: Resume a suspended job in the background
- `fg`: Bring a job to the foreground

## Package Management
- `apt-get`: APT package handling utility (Debian-based)
- `yum`: Package manager (RPM-based)
- `dnf`: Next-generation version of `yum` (RPM-based)
- `zypper`: Command line interface of ZYpp package manager (openSUSE)

## User Management
- `useradd`: Create a new user or update default new user information
- `usermod`: Modify a user account
- `userdel`: Delete a user account and related files
- `passwd`: Update a user's authentication tokens (password)

## System Monitoring and Performance
- `vmstat`: Report virtual memory statistics
- `iostat`: Report CPU and I/O statistics
- `sar`: Collect, report, or save system activity information
- `free`: Display amount of free and used memory in the system

## Logs and Monitoring
- `tail`: Output the last part of files
- `tail -f`: Follow the output of a file in real-time
- `journalctl`: Query and display messages from the journal
- `dmesg`: Print or control the kernel ring buffer

## Miscellaneous
- `crontab`: Schedule periodic background jobs
- `at`: Schedule commands to be executed once at a particular time
- `alias`: Create an alias for a command
- `echo`: Display a line of text
- `history`: Show command history
