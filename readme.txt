Steps taken to prepare GitHub
1. install git and create a github account
2. Create a local repository: to begin open the terminal and add command about the location where you want to create the project folder
     $ cd ~/Desktop
     $ mkdir myproject
     $ cd myproject /
To initialize a git repository in root of the folder;
     $ git init
  
 3. Add a new file to the repo
   add a new file by running touch command 'touch newfile.txt' just creates and saves a blank file named newfile.txt.
     $ touch newfile.txt
     $ ls
   After creating new file you can use git status command to see which files git knows exist
     $ git status

4. Add a file to the staging environment using git add command
5. Create a commit
      $ git commit -m"This is my first commit!"
6. Create a new branch
      $ git branch 
7. Create a new repository on GitHub.Create a new repo locally .here we already created so,after that we want to push that onto GitHub
      $ git remote add origin https://github.com/shalima2209/webprogramming.git
      $ git push -u origin master
 8.Push a branch to GitHub
      $ git push origin my-new-branch
 9.Create a pull request 
   It done in github page.a pull request is a way to alert a repo's owner that you want to make some changes to their code.
 10. Merge the pull request  by clicking the green mell pull request button.This will merge the changes into the primary branch.
 11.Next generate a new ssh key 
    open terminal 
        $ ssh-keygen -t ed25519 -C "your emailid.com"
          > enter
     type a secure passphrase 
     Add your ssh key to the ssh agent to manage your keys,
        $ eval "$(ssh-agent-s)"
       > Agent pid 59566
  12. Add the SSH key to the GitHub account.  

 13.Make some changes to local repo again.And push again 







    
