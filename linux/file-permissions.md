# Day 5: Linux File permissions

## What do these bash commands do?

- ls -l: similar to ls, displyas all the files in a directory with extra information.
d or - if it is a directory, file permissions, number of hard links to the file or directory, 
owner name, group name, file size, and modification time.

- chmod: changes the permissions of a file

- chown: changes the owner of a file

## File Permissions

- using ls -l we can see file permssions. Aside from the first - or d, we see 9 digits that read -, r, w, or x.
- the first 3 are for the owner, the second 3 are for the group, and the last 3 are for others.
- a typical script permission is 755 because it allows everyone to read and execute it, but only the owner could modify it.
- the default permission is 644. I think this is assuming that the file is not a script file, so it shouldn't be executable.

## Why permissions matter on servers

- linux file permissions act as the primary barrier against unauthoriez access, malicious tampering, and accidental data loss.
- They define who can read, write, and execute, ensuring that only autorized people can modify sensitive information.

## One thing that confused me

- what's the difference in permissions between group and others? I would assume that everyone at a job would be in the same group.
- Guess: If someone were to access the linux server(?) then they would be placed in the other group. 
