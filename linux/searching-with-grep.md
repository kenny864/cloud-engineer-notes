# Searching with grep

## What grep does
- searches a file for a keyword 
- case sensitive unless use -i

## What pipes do
- |: takes the output from one command and uses it as input for another

## Why searching logs matters in cloud systems
- Helps to quickly troubleshoot a system (security, errors, etc)

## Command Combos
- grep -in: ignores case + line number
- grep -ic: ignores case + counts appearance
- ls | grep: search directories for specific file types or names
- cat | grep: search multiple files at once and display the search results without filename
This is inefficient for a single file
- tail -f | grep -in : live monitoring the last 25 lines for specific event
