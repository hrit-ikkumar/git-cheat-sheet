## git clone https://github.com/hrit-ikkumar/git-cheat-sheet.git
For cloning a github repo
Some of the files required in git repo:
    - `README`: All the details regarding the project.
    - `LICENSE`: About license of the software
    - `.gitignore`: all the details like which file should not be added in git repo

## echo "# git-cheat-sheet" >> README.md
Writing something in README.md file 

## git init
initialize current directory as git repo

## git add README.md
add README.md file to git repo

## git commit -m "first commit"
save (commit) all the changes to github server and send message as "first commit"

## git branch -M main
select branch as main and also default

## git remote add origin https://github.com/hrit-ikkumar/git-cheat-sheet.git
add origin to the current git repo folder in local computer

## git push -u origin main
push all the changes to git server and branch should be main

## git add .
add all the files' changes into git repo.

## git commit 
commit or save all the changes

## git push
push all the changes to github server

## git rm --cached index.html 
discard all the changes of a file or simply removes the file from the current git repo

## git status
see the status of the git repo 

## git restore index.html
discard all the changes in working directory // doesn't work after the commit only before commit it will work

## git push -u origin master 
pushing to a particular branch in git repo

## git restore --staged index.html
to unstage index.html file // won't discard the changes (In simple words, It will only unstage the file from current git add index.html & won't work after the commit)