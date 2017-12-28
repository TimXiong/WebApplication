# VS Code

## Install 
vs code 
git
referece: using version control in vs code  https://code.visualstudio.com/Docs/editor/versioncontrol

## Initial local
create a folder in local
open vs code
open the new folder in vs code
click git ico
click initial repository

## Connet to github
create a repository in github websie
copy the address of the new repository
git remote add origin xxxx (repository github address)
git pull origin master

## Clone 
It's another way

## FQ
Q: first pull code from github failed : fatal: refusing to merge unrelated histories
A: use this command option (-allow-unrelated-histories) eg: $git pull origin master –allow-unrelated-histories