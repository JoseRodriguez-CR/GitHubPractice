
GitBash Commands

    ls - It show everything under the current folder

    cd  - Open a folder you are calling, use: cd_folder's_name

    cd .. -Go up one directory

    mkdir -Create a new director

    touch Create a new file 

    rm -Remove a folder and/or files

Git commands 

//initializes the local directory as a repository
    1) git init

//start tracking files
    2) git add "NameOfFile.ext" or it could be "git add ." to add everything under the folder


// Save point (commit)
    3) git commit -m "Adding README with some commands"

//Link the repositories
    4) git remote add origin url-to-github-here

//Uploads every change to github
5) git push -u origin master  or git push -u origin main

// Show the current file tracking status
*git status

//this command will remove the exist reference from GitHub
rm -rf .git

//To update every change on GitHub we need to follow steps 2,3 and 5.