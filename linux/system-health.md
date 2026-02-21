# System Health

## What df -h shows
- used to report file system disk space usage in a "human-readable" format
- shows the size, how much is used, how much is available, and the Use%
- Good to check if system is running out of space

## What du -sh shows
- shows the size of the current directory
- du -sh *: lists all the files/directories and displays the size of each one

## Why disk space matters in cloud servers
- cloud servers like aws are charged by how much space they use
- if a cloud server runs out of space, issues can arise

## Combos
- du -sh * | sort -h: sorts file size (ascending order)
- du -sh * | sort -rh: sorts file size (descending order)
