# Processes and signals
DevOps
Shell
Bash
Syscall
Scripting

### Processes:
In computing, a process is a program in execution. It represents a unit of work that the operating system manages. When you run a program on your computer, it creates a process. A process includes the program code, its data, and the resources (such as memory, CPU time, files, etc.) it needs to execute.

Key aspects of a process include: 
* Memory Space: A process has its own memory space, allowing it to run independently without interfering with other processes.
* Execution State: The current state of the program, including the values of variables, registers, and the program counter.
* Resources: Processes have access to various resources such as file handles, network connections, and input/output streams.

Processes enable concurrent execution, enabling multiple programs to run simultaneously, which is essential for multitasking operating systems.

## Resources
* [Linux PID](https://intranet.alxswe.com/rltoken/qVGxUt1QMIV4B4oVrQBlQg)
* [Linux process](https://intranet.alxswe.com/rltoken/px2TdWSjVO8i9SB5gHchAw)
* [Linux signal](https://intranet.alxswe.com/rltoken/qQSGz9CN52PVF3IPCuaRiw)
* [Process management in linux](https://intranet.alxswe.com/rltoken/XlYrlghzNZ6Z1cbI_IPaiA)

  ## Learning Objectives
- What is a PID
- What is a process
- How to find a process’ PID
- How to kill a process
- What is a signal
- What are the 2 signals that cannot be ignored

### man or help:

- ps
- pgrep
- pkill
- kill
- exit
- trap

## More to Read on


* [more about Signals](https://intranet.alxswe.com/rltoken/BOU-KVNMqfKEIBo_VOI26A)
* [ignoring shellcheck error](https://intranet.alxswe.com/rltoken/vErRT8QGU2bwJ6FLvPLzxw)
* [&](https://intranet.alxswe.com/rltoken/R4YSgPT1k0PhWCrB0TYzoQ)
* [init.d](https://intranet.alxswe.com/rltoken/sVqN4oNYYO6ojS4ctT02Jw)
* [Daemon](https://intranet.alxswe.com/rltoken/kCoQ5aYO3towdDQFVPcfNg) Programs that are detached from the terminal and running in the background are called daemons or processes, need to be managed. The general minimum set of instructions is: start, restart and stop. The most popular way of doing so on Unix system is to use the init scripts.
* [Positional parameters](https://intranet.alxswe.com/rltoken/TJ2rxUwRsnM1mJQHSCnOQA)
* Read [what a zombie process is.](https://intranet.alxswe.com/rltoken/Tb86ZoSxR6ORCKYlZaYzHw)


## Requirements
### General
- Allowed editors: [](vi), [](vim), [](emacs)
- All your files will be interpreted on Ubuntu 20.04 LTS
- All your files should end with a new line
- A [](README.md) file, at the root of the folder of the project, is mandatory
- All your Bash script files must be executable
- Your Bash script must pass [](Shellchec)k (version [](0.7.0) via [](apt-get)) without any error
- The first line of all your Bash scripts should be exactly [](#!/usr/bin/env bash)
- The second line of all your Bash scripts should be a comment explaining what is the script doing

## Author

"""John Mbithi
Jellyjones-pixel
"""