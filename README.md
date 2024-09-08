# Website-Blocker
Overview:

This Python-based Website Blocker allows users to block distracting websites on their local machine for specified periods. The project modifies the hosts file on the system to reroute the domain names of the websites to a local address, effectively preventing the browser from accessing them.

Features:

Add websites to block.
Define blocking schedule (e.g., work hours or study time).
Automatic unblocking after the specified period.
Easy to configure and modify blocked website lists.
How it works:

The program modifies the system's hosts file, mapping specified websites to 127.0.0.1, which is the local loopback IP.
During the blocking period, any attempts to access the blocked websites will result in a failure to load.
After the scheduled blocking time ends, the program restores the original hosts file, allowing access again.
Usage:

Run the script with sudo or administrator privileges (required to modify system files).
Configure the websites to block and the time interval for blocking.
The script will run in the background and block the websites for the specified period.
Technologies Used:

Python
System's hosts file manipulation
