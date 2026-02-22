# Viewing and managing Linux processes

# what a process is
- a running instance of a program

# What ps aux means
- display a snapshot of all running processes on the system in a detailed, user-oriented format

USER: The effective username of the process owner.
PID: The unique Process ID.
%CPU: The CPU utilization of the process.
%MEM: The percentage of real memory (RAM) used by the process.
VSZ: Virtual memory size in kilobytes.
RSS: Resident Set Size, the amount of real memory used in kilobytes.
TTY: The controlling terminal associated with the process, if any.
STAT: The current process state (e.g., 'S' for sleeping, 'R' for running, 'Z' for zombie).
START: The time the command started.
TIME: The total cumulative CPU time the process has used.
COMMAND: The command name and its arguments that launched the

#  When you'd use top
- Continously displays process statistics until stopped
- ps aux takes a snapshot
- top: process list with live updates

# Why killing a process might fix a server
- if a costly process or a bad process is running, killing it will stop it for causing further damage

# Steps to find a kill a process
## ps aux OR top: identify the bad process
## kill pidNumber: kills the process based on it's pid number
