# Git Notes

## Pushing from Terminal
- Make sure you have a token with the appropiate permissions
- Commit changes first then push

## Gettting user info
- use git config user.name to get username
- use git config user.password to get password

## Guide to Pushing from terminal
- use "git add -A" to add all changes
- commit all changes first with git commit -m "-message-"
- finally "git push"

## git legacy tokens
- generate a token, this will act as the password when you want to clone or push
- to clone a repository use the follow command
git clone https://<username>:<tokenPassword>@github.com/<username>/<repoName>.git


- after you clone, save the token with git config user.password <password>
this will save the token password. To get it, just type git config user.password
