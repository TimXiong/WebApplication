# Using Github in VS Code

## Install 
- vs code 
- git
- referece: [using version control in vs code](https://code.visualstudio.com/Docs/editor/versioncontrol)

## Initial local
- Create a folder in local
- Open the new folder in vs code
- Go to source control function choose git and click initial repository

## Github access using HTTPS [optional]
1. [Caching github password in git](https://help.github.com/articles/caching-your-github-password-in-git/): Use a credential helper to tell Git to remember your GitHub username and password every time it talks to GitHub.

2. [Use personal access token](https://help.github.com/articles/creating-a-personal-access-token-for-the-command-line/): Use it in place of a password when performing Git operations over HTTPS with Git on the command line or the API.

## Connet to github
- Create a repository in github websie
- Copy the address of the new repository
- Use these command
    ```
    $git remote add origin xxxx (repository github address)
    $git pull origin master
    ```

## Clone 
It's another way

## FQ
+ Q: first pull code from github failed : fatal: refusing to merge unrelated histories
    - use this command option (-allow-unrelated-histories) eg: 
        ```
        $git pull origin master –allow-unrelated-histories
        ```
