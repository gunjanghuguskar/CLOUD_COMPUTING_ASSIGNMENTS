# Practical 1
## LINUX COMMAND FOR FILE SYSTEM
> 1. **ls - List Files:**
>    Lists the files and directories in the current directory.
>    ```bash
>    ls
>    ```

> 2. **mkdir - Create Directory:**
>    Creates a new directory.
>    ```bash
>    mkdir directory_name
>    ```

> 3. **touch - Create Empty File:**
>    Creates a new empty file.
>    ```bash
>    touch filename
>    ```

> 4. **cp - Copy Files/Directories:**
>    Copies files or directories.
>    ```bash
>    cp source_file destination
>    ```

> 5. **mv - Move/Rename Files or Directories:**
>    Moves or renames files or directories.
>    ```bash
>    mv source destination
>    ```

> 6. **rm - Remove/Delete Files or Directories:**
>    Removes or deletes files or directories. Be cautious with this command.
>    ```bash
>    rm file_or_directory
>    ```

> 7. **rmdir - Remove Empty Directory:**
>    Removes an empty directory.
>    ```bash
>    rmdir directory_name
>    ```

> 8. **chmod - Change File Permissions:**
>    Changes the permissions of a file.
>    ```bash
>    chmod permissions filename
>    ```

> 9. **chown - Change File Owner:**
>    Changes the owner and group of a file.
>    ```bash
>    chown new_owner:new_group filename
>    ```

> 10. **chgrp - Change Group Ownership:**
>     Changes the group ownership of a file.
>     ```bash
>     chgrp new_group filename
>     ```

> 11. **find - Find Files:**
>     Searches for files based on certain criteria.
>     ```bash
>     find /path/to/search -name "filename"
>     ```

> 12. **grep - Search Text in Files:**
>     Searches for a specific pattern in a file.
>     ```bash
>     grep "pattern" filename
>     ```

> 13. **cat - Concatenate and Display File Content:**
>     Displays the content of a file.
>     ```bash
>     cat filename
>     ```

> 14. **nano or vim - Text Editors:**
>     Opens a text file for editing.
>     ```bash
>     nano filename
>     ```
>     or
>     ```bash
>     vim filename
>     ```

> 15. **ln - Create Symbolic Links:**
>     Creates a symbolic link to a file.
>     ```bash
>     ln -s target_file link_name
>     ```

> 16. **df - Display Disk Space Usage:**
>     Displays disk space usage in a human-readable format.
>     ```bash
>     df -h
>     ```

> 17. **du - Display File/Directory Space Usage:**
>     Displays the disk usage of files or directories in a human-readable format.
>     ```bash
>     du -h file_or_directory
>     ```

> 18. **tar - Archive and Unarchive Files:**
>     Creates or extracts tar archives.
>     ```bash
>     tar -cvf archive.tar files
>     ```

> 19. **gzip - Compress Files:**
>     Compresses a file.
>     ```bash
>     gzip filename
>     ```

> 20. **unzip - Unzip Files:**
>     Unzips a compressed file.
>     ```bash
>     unzip archive.zip
>     ```

These commands are fundamental for managing files and directories in a Linux environment. Always exercise caution, especially when using commands that modify or delete files, to avoid unintended data loss.


## LINUX COMMAND FOR MEMORY MANAGEMENT
> 1. **free - Display Memory Usage:**
>    Display information about total, used, and free memory in the system.
>    ```bash
>    free
>    ```

> 2. **top - Display System Resources:**
>    Interactive process viewer that shows real-time information about system resources, including memory usage.
>    ```bash
>    top
>    ```

> 3. **htop - Improved top:**
>    An interactive process viewer that provides a more user-friendly interface compared to `top`.
>    ```bash
>    htop
>    ```

> 4. **ps - Report Process Status:**
>    Display information about currently running processes, including memory usage.
>    ```bash
>    ps aux
>    ```

> 5. **pmap - Display Memory Map of a Process:**
>    Display the memory map of a process, showing memory allocations.
>    ```bash
>    pmap <process_id>
>    ```

> 6. **vmstat - Virtual Memory Statistics:**
>    Display virtual memory statistics, including swap usage.
>    ```bash
>    vmstat
>    ```

> 7. **swapon - Enable Swap:**
>    Activate a swap device or file.
>    ```bash
>    swapon /path/to/swapfile
>    ```

> 8. **swapoff - Disable Swap:**
>    Deactivate a swap device or file.
>    ```bash
>    swapoff /path/to/swapfile
>    ```

> 9. **sync - Flush File System Buffers:**
>    Synchronize the file system by writing data to disk.
>    ```bash
>    sync
>    ```

> 10. **sysctl - Configure Kernel Parameters:**
>     Adjust various kernel parameters, including those related to memory management.
>     ```bash
>     sysctl -a
>     ```

> 11. **ulimit - Set User Limits:**
>     Set or display user-level resource limits, including memory limits.
>     ```bash
>     ulimit -a
>     ```

> 12. **malloc - Allocate Memory:**
>     A command-line tool for testing and debugging memory allocation.
>     ```bash
>     malloc -s 100M
>     ```

> 13. **mtrace - Memory Leak Detection:**
>     Trace and diagnose memory leaks in a program.
>     ```bash
>     mtrace <executable>
>     ```

> 14. **pmap - Display Process Memory Usage:**
>     Display detailed information about a process's memory usage.
>     ```bash
>     pmap <process_id>
>     ```

> 15. **numactl - Control NUMA Policy:**
>     Control process NUMA (Non-Uniform Memory Access) policy and placement.
>     ```bash
>     numactl --hardware
>     ```

> 16. **uptime - Display System Uptime:**
>     Show how long the system has been running, along with load averages.
>     ```bash
>     uptime
>     ```

> 17. **ipcs - Display IPC Information:**
>     Display information about interprocess communication (IPC) facilities, including shared memory.
>     ```bash
>     ipcs -m
>     ```

> 18. **sync - Flush File System Buffers:**
>     Synchronize the file system by writing data to disk.
>     ```bash
>     sync
>     ```

> 19. **slabtop - Display Kernel Slab Caches:**
>     Display kernel slab cache information, including memory usage.
>     ```bash
>     slabtop
>     ```

> 20. **atop - Advanced System Monitor:**
>     An advanced performance monitor that provides detailed information on memory usage, among other system metrics.
>     ```bash
>     atop
>     ```

 These commands can help you monitor, manage, and troubleshoot memory-related aspects of a Linux system. Always use caution and refer to the respective command's man pages for detailed information.

## LINUX COMMAND FOR PROCESS MANAGEMENT
> 1. **ps - Process Status:**
>    Display information about currently running processes.
>    ```bash
>    ps
>    ```

> 2. **top - Display System Resources:**
>    Interactive process viewer that shows real-time information about system resources and processes.
>    ```bash
>    top
>    ```

> 3. **htop - Improved top:**
>    An interactive process viewer with a user-friendly interface.
>    ```bash
>    htop
>    ```

> 4. **kill - Terminate a Process:**
>    Terminate a process by sending a signal.
>    ```bash
>    kill <process_id>
>    ```

> 5. **killall - Terminate Processes by Name:**
>    Terminate processes by their name.
>    ```bash
>    killall <process_name>
>    ```

> 6. **pkill - Signal Processes Based on Name:**
>    Signal processes based on their name.
>    ```bash
>    pkill <process_name>
>    ```

> 7. **kill -9 - Forcefully Kill a Process:**
>    Forcefully terminate a process using signal 9.
>    ```bash
>    kill -9 <process_id>
>    ```

> 8. **renice - Change Process Priority:**
>    Alter the priority of a running process.
>    ```bash
>    renice <priority> <process_id>
>    ```

> 9. **nice - Run a Command with Modified Priority:**
>    Run a command with a specified priority.
>    ```bash
>    nice -n <priority> <command>
>    ```

> 10. **pgrep - List Processes by Name:**
>     List processes based on their name.
>     ```bash
>     pgrep <process_name>
>     ```

> 11. **pmap - Display Memory Map of a Process:**
>     Display the memory map of a process, showing memory allocations.
>     ```bash
>     pmap <process_id>
>     ```

> 12. **uptime - Display System Uptime:**
>     Show how long the system has been running and the current system load.
>     ```bash
>     uptime
>     ```

> 13. **atop - Advanced System Monitor:**
>     An advanced performance monitor providing detailed information on processes.
>     ```bash
>     atop
>     ```

> 14. **pstree - Display Process Hierarchy:**
>     Display processes in a tree-like structure, showing parent-child relationships.
>     ```bash
>     pstree
>     ```

> 15. **ps aux - Detailed Process Information:**
>     Display detailed information about all processes running on the system.
>     ```bash
>     ps aux
>     ```

> 16. **pidof - Display Process ID of a Running Program:**
>     Display the process ID of a running program.
>     ```bash
>     pidof <program_name>
>     ```

> 17. **nice - Run a Command with Altered Priority:**
>     Run a command with a modified scheduling priority.
>     ```bash
>     nice -n <priority> <command>
>     ```

> 18. **pgrep -o - Display Oldest Process ID by Name:**
>     Display the oldest (first started) process ID based on its name.
>     ```bash
>     pgrep -o <process_name>
>     ```

> 19. **ps -eF - Display Full Format Process Information:**
>     Display full-format information about all processes.
>     ```bash
>     ps -eF
>     ```

> 20. **at - Schedule a One-Time Task:**
>     Schedule a one-time task or command to run at a specified time.
>     ```bash
>     at <time> <command>
>     ```

 These commands are useful for monitoring, managing, and controlling processes on a Linux system. Always use caution, especially when terminating processes, to avoid unintended consequences. Refer to the respective command's man pages for detailed information.

 ## LINUX COMMANDS FOR NETWORKING

> 1. **ping - Test Network Connectivity:**
>    Send ICMP Echo Request messages to check if a host is reachable.
>    ```bash
>    ping -c 1 <hostname_or_ip>
>    ```

> 2. **traceroute - Trace Route to a Destination:**
>    Display the route that packets take to reach a network host.
>    ```bash
>    traceroute <hostname_or_ip>
>    ```

> 3. **curl - Command-Line Tool for URL Data Transfer:**
>    Transfer data with URLs, supporting various protocols.
>    ```bash
>    curl -O <url>
>    ```

> 4. **wget - Download Files from the Web:**
>    Retrieve files from the internet using HTTP, HTTPS, or FTP.
>    ```bash
>    wget <url>
>    ```

> 5. **netstat - Network Statistics:**
>    Display network connections, routing tables, interface statistics, masquerade connections, and multicast memberships.
>    ```bash
>    netstat -tunap
>    ```

> 6. **ip - Show or Manipulate Routing, Devices, Policy Routing, and Tunnels:**
>    A versatile command for network configuration, routing, and tunneling.
>    ```bash
>    ip route show
>    ```

> 7. **ifconfig - Network Interface Configuration:**
>    Display information about network interfaces and configure them.
>    ```bash
>    ifconfig eth0
>    ```

> 8. **arp - Address Resolution Protocol:**
>    Display and manipulate the ARP cache.
>    ```bash
>    arp -a
>    ```

> 9. **dig - DNS Lookup:**
>    Perform DNS lookups and display the results.
>    ```bash
>    dig +short <domain_name>
>    ```

> 10. **hostname - Print or Set System Hostname:**
>     Display or set the system's hostname.
>     ```bash
>     hostname
>     ```

> 11. **route - Display and Modify the IP Routing Table:**
>     Display or modify the kernel routing table.
>     ```bash
>     route -n
>     ```

> 12. **iptables - Administration Tool for IPv4 Packet Filtering:**
>     Configure rules for packet filtering in the Linux kernel.
>     ```bash
>     iptables -L
>     ```

> 13. **ss - Socket Statistics:**
>     Display information about sockets, both incoming and outgoing.
>     ```bash
>     ss -tun
>     ```

> 14. **nc - Netcat:**
>     Read and write data across network connections.
>     ```bash
>     nc -zv <hostname_or_ip> <port>
>     ```

> 15. **sed - Stream Editor:**
>     Perform basic text transformations on input.
>     ```bash
>     echo "Hello" | sed 's/Hello/Hi/'
>     ```

> 16. **awk - Text Processing Tool:**
>     A versatile tool for pattern scanning and processing.
>     ```bash
>     echo "1 2 3" | awk '{print $2}'
>     ```

> 17. **grep - Search Text in Files:**
>     Search for a specific pattern in files.
>     ```bash
>     grep "pattern" filename
>     ```

> 18. **cut - Extract Sections from Lines:**
>     Cut out selected portions of each line.
>     ```bash
>     echo "1,John,Doe" | cut -d ',' -f 2
>     ```

> 19. **sort - Sort Lines of Text:**
>     Sort lines of text files.
>     ```bash
>     sort filename
>     ```

> 20. **awk - Extract Specific Fields:**
>     Use `awk` to extract specific fields from text data.
>     ```bash
>     echo "1 John Doe" | awk '{print $2, $3}'
>     ```

> These commands are useful for networking tasks within shell scripts, such as checking connectivity, retrieving data, and configuring network settings. Always refer to the respective command's man pages for more detailed information.
