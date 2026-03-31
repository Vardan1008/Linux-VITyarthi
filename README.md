# Linux-VITyarthi
Linux Kernel Open Source Audit
General Description

This is a detailed audit report on the Linux Kernel as a result of undertaking the Open Source Software course audit assignment. This audit report will discuss in detail the history, philosophy, license, and impact of the Linux kernel. Additionally, this audit report will discuss the interaction with the Linux system and shell programming.

Objectives
To comprehend the open source philosophy, focusing on freedom vs. cost
To comprehend the Linux kernel and its role in the operating system
To comprehend the Linux kernel and its role in the operating system
Key Concepts Covered
Open Source Philosophy: Freedom vs. Cost
Linux Kernel License: GPLv2 and Copyleft
Linux Kernel Architecture: Monolithic vs. Microkernel
System Directories:
/boot
/proc
/sys
/lib/modules
User space vs. Kernel space
Package Management using dpkg
Environment
OS: Ubuntu 24.04 LTS
Platform: WSL2 (Windows Subsystem for Linux)
Kernel: 6.6.x (Microsoft Standard WSL2)
Note: Since the Linux kernel is managed by the Windows host in WSL2, the Linux kernel is not directly accessible.
The /boot directory is empty.
Scripts Implemented
1. System Identity Report

This script will show the following:
OS information
Kernel version
User information
Uptime and date
2. FOSS Package Inspector
Checks whether the package is installed
Displays the version and description
Illustrates the use of the dpkg and grep commands
3. Disk and Permission Auditor
Analyses system directories
Displays information on permissions, ownership, and size
Checks the kernel module directory
4. Log File Analyzer
Reads the log file line by line
Calculates the keyword count
Displays the keyword count
5. Open Source Manifesto Generator
Asks the user for input
Generates the manifesto
Writes the manifesto to a file
Sample Output
Open Source Audit -- Vardan
OS        : Ubuntu 24.04 LTS
Kernel    : 6.6.x-microsoft-standard-WSL2
User      : vardan
License

This project is based on the principles of the GNU General Public License v2 (GPL v2).

Conclusion

This project is an example of the power of open-source systems. The project helps the user learn about Linux from the inside out. It is an excellent way to get experience with Linux.

Author

Vardan Somayajula
Aerospace Engineering Student
Open Source Software Course

Acknowledgment

Inspired by the global open-source community and the contributions of developers worldwide.
