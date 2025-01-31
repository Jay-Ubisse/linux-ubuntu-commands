# Ubuntu Linux Commands List

## Basic Commands
| Command | Description |
|---------|-------------|
| `pwd` | Displays the current working directory. |
| `ls` | Lists files and directories in the current directory. |
| `cd [directory]` | Changes to the specified directory. |
| `mkdir [directory]` | Creates a new directory. |
| `rmdir [directory]` | Removes an empty directory. |
| `rm [file]` | Deletes a file. |
| `rm -r [directory]` | Deletes a directory and its contents recursively. |
| `cp [source] [destination]` | Copies files or directories. |
| `mv [source] [destination]` | Moves or renames files and directories. |
| `touch [file]` | Creates a new empty file. |
| `cat [file]` | Displays the content of a file. |
| `nano [file]` | Opens the **nano** text editor to edit a file. |
| `vim [file]` | Opens the **vim** text editor to edit a file. |

## User Management
| Command | Description |
|---------|-------------|
| `whoami` | Displays the current logged-in user. |
| `who` | Shows all users currently logged into the system. |
| `id [username]` | Displays user ID (UID) and group ID (GID). |
| `adduser [username]` | Creates a new user. |
| `deluser [username]` | Deletes a user. |
| `passwd [username]` | Changes the password of a user. |
| `usermod -aG [group] [user]` | Adds a user to a group. |
| `groups [username]` | Shows the groups a user belongs to. |

## File Permissions & Ownership
| Command | Description |
|---------|-------------|
| `chmod [permissions] [file]` | Changes file permissions (e.g., `chmod 755 file`). |
| `chown [user]:[group] [file]` | Changes ownership of a file. |
| `chgrp [group] [file]` | Changes the group ownership of a file. |
| `ls -l` | Lists files with detailed permissions. |

## Process Management
| Command | Description |
|---------|-------------|
| `ps aux` | Displays all running processes. |
| `top` | Shows real-time resource usage and running processes. |
| `htop` | Similar to `top`, but with a better UI (needs installation). |
| `kill [PID]` | Terminates a process by its Process ID (PID). |
| `killall [process]` | Terminates all processes by name. |
| `pkill [name]` | Kills a process by name. |
| `nohup [command] &` | Runs a command in the background. |
| `jobs` | Lists background jobs. |
| `fg [job_id]` | Brings a background job to the foreground. |
| `bg [job_id]` | Resumes a background job. |

## Disk & Storage Management
| Command | Description |
|---------|-------------|
| `df -h` | Shows disk usage in human-readable format. |
| `du -sh [directory]` | Shows the size of a directory. |
| `lsblk` | Lists available disk devices and partitions. |
| `mount [device] [mountpoint]` | Mounts a storage device. |
| `umount [device]` | Unmounts a storage device. |
| `fdisk -l` | Lists partitions on all drives. |

## Networking
| Command | Description |
|---------|-------------|
| `ifconfig` | Displays network interfaces (deprecated, use `ip a`). |
| `ip a` | Shows network interfaces and IP addresses. |
| `ping [host]` | Checks connectivity to a host. |
| `wget [URL]` | Downloads a file from a URL. |
| `curl [URL]` | Fetches content from a URL. |
| `netstat -tulnp` | Displays open ports and listening services. |
| `ss -tulnp` | Similar to `netstat`, but modern and faster. |

## Package Management (APT)
| Command | Description |
|---------|-------------|
| `sudo apt update` | Updates package lists. |
| `sudo apt upgrade` | Upgrades all installed packages. |
| `sudo apt install [package]` | Installs a package. |
| `sudo apt remove [package]` | Removes a package. |
| `sudo apt autoremove` | Removes unused packages. |
| `sudo apt search [package]` | Searches for a package. |

## System Monitoring & Logs
| Command | Description |
|---------|-------------|
| `uptime` | Shows system uptime. |
| `free -h` | Displays memory usage. |
| `dmesg` | Shows system logs (useful for debugging hardware issues). |
| `journalctl -xe` | Displays system logs for troubleshooting. |
| `history` | Shows command history. |
| `clear` | Clears the terminal screen. |

## System Management
| Command | Description |
|---------|-------------|
| `uname -a` | Displays system information. |
| `lsb_release -a` | Shows Ubuntu version details. |
| `hostname` | Displays the system's hostname. |
| `reboot` | Restarts the system. |
| `shutdown -h now` | Shuts down the system immediately. |
| `shutdown -r now` | Restarts the system immediately. |

## Compression & Archiving
| Command | Description |
|---------|-------------|
| `tar -cvf archive.tar [files]` | Creates a tar archive. |
| `tar -xvf archive.tar` | Extracts a tar archive. |
| `tar -czvf archive.tar.gz [files]` | Creates a compressed tar archive. |
| `tar -xzvf archive.tar.gz` | Extracts a compressed tar archive. |
| `zip -r archive.zip [files]` | Creates a zip archive. |
| `unzip archive.zip` | Extracts a zip archive. |


---

Produced with ❤️ por [Jay-Ubisse](https://github.com/Jay-Ubisse/).
