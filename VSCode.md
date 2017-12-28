# VS Code

## Install 
- vs code 
- git
- referece: using version control in vs code  https://code.visualstudio.com/Docs/editor/versioncontrol

## Initial local
- create a folder in local
- open vs code
- open the new folder in vs code
- click git ico
- click initial repository

## github [optional]
1. Caching github password in git.
If you're cloning GitHub repositories using HTTPS, you can use a credential helper to tell Git to remember your GitHub username and password every time it talks to GitHub
https://help.github.com/articles/caching-your-github-password-in-git/

2. use personal access token
You can create a personal access token and use it in place of a password when performing Git operations over HTTPS with Git on the command line or the API.
https://help.github.com/articles/creating-a-personal-access-token-for-the-command-line/

## Connet to github
- create a repository in github websie
- copy the address of the new repository
- git remote add origin xxxx (repository github address)
- git pull origin master

## Clone 
It's another way

## FQ
- Q: first pull code from github failed : fatal: refusing to merge unrelated histories
- A: use this command option (-allow-unrelated-histories) eg: $git pull origin master –allow-unrelated-histories