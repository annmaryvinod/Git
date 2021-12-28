# Git
Git step by step



1. Initial Setup in Local :
  
  * Setting up username and email in local :
     
     1. git config --global user.name annmaryvinod

     2. git config --global user.email annmary@gmail.com

 * Checking :
     
     1. git config user.name

     2. git config user.email




2. Some Basic Command Lines and their usage :

  * Change Directory "cd .." : to go back to the adjacent parent directory.

  * Change Directory "cd Documents" : to dive into 'Documents' directory.

  *  List : " ls " / " dir " : to list the contents of the current directory.
       
       Note: "dir" is for Windows.
       " ls " also works for Windows.

  * Make Directory : " mkdir Playground " : creates a new directory named Playground.

  * Creating a file in mac or cmd(windows) : " touch index.html " : creates an index.html file.

  * Remove a file : " rm index.html " : deletes the index.html file

  *  Remove a directory : " rmdir Playground " : deletes the directory named Playground.      






3. Some real GIT commands :

   * Initialising a git repo in the local :

       command :   " git init "

       this can be used to initialise or create a new repo in an empty or non empty folder in the local 

   * Checking the status of a repo ( to find the staging,committed files etc) :

      command : " git status "

      this shows the unstaged files (untracked files),committed files etc.

   * To stage a file :

      command : " git add index.html"    

      index.html is added to the staging area (can be checked with " git status ")

   * To unstage a staged file :

     command : " git rm --cached index.html "

     removes index.html from the staging area (can be checked using " git status ")   



   * To add multiple files to the staging area :

     command : " git add . "



   * Commiting :

     command : git commit -m "fixed a bug in the header"    



  * Commit History :

    1. To see all info :
    
    command : " git log "   

    2. To get a condensed form (crisp):

    command : " git log --oneline "






  * Undoing Things :

   <img src = "undo.png">



    

 



