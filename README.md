# Install first the Git on Linux with a command:

```
sudo apt update
sudo apt install git
```
- check the git ver
```
git --version
```
## Integrate GitHub with the WSL
``` 
GitHub
  - your settings
  - Scroll to the bottom and select Developer Settings
  - Personbal access tokens
    -   Tokens(classic)
      - generate a token
git remote set-url origin https://_______________@github.com/username/<repo>
-------------------------------------
- git status // shows you the status of your repo
- git add "file_name" // to add the new piece of work to the repo
- git commit -m "add the message/expalanation" // commit your change
- git push origin main // add back to the main 

## Git TAGS

```
git tag 0.1.0
```
`
git push --tags
`



## Connect with Git

```
 git config --global user.name "name"
 git config --global user.email "email"
 git config --list
```
