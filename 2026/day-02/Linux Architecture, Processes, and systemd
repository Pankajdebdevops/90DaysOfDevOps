Understanding Linux Internals

Today I explored how Linux works behind the scenes.
These concepts are fundamental for anyone learning DevOps, Cloud Computing, or System Administration because most production servers run on Linux.

Main Parts of Linux
1. Linux Kernel
The kernel is the core component of the Linux operating system.
It acts as a bridge between hardware and software.
The kernel is responsible for:
CPU scheduling
Memory management
Process handling
Device communication
File system operations
2. User Space
User space is the environment where users interact with applications and commands.
Utilities such as ls, pwd, top, and ps execute in user space.
Applications communicate with the kernel through system calls.
3. systemd and the Boot Process
systemd is the first process launched during system startup.
It always runs with PID 1.
It controls system services and background daemons.
It also handles boot management, service monitoring, and system logs.
Linux Process Management
Process Creation
Linux creates new processes using fork().
After creation, the child process can replace itself with another program using exec().
Each process receives a unique Process ID (PID).
Common Process States
State	Description
Running	The process is actively executing
Sleeping	The process is waiting for an event or resource
Stopped	The process execution has been paused
Zombie	The process has completed execution but still has an entry in the process table
Responsibilities of systemd
Starts services during system boot
Stops or restarts services when required
Manages long-running background processes
Stores and manages logs through journalctl
Linux Commands Used Frequently
ps aux
top
systemctl
journalctl
kill -9 PID

These commands are essential for monitoring processes, troubleshooting services, viewing logs, and managing Linux systems efficiently.
