  ### Initialize Git
    git init
  ### adds a change in the working directory to the staging area
    git add .
  ###  captures a snapshot of the project's currently staged changes
    git commit -m "Add existing project files to Git"
  ### URL a local Git repository was originally cloned from
    git ls-remote --get-url origin
  ### Add remote origin
    git remote add origin "Github link"
  ### obtain more information about the remote repository
    git remote show origin
  ### lets you navigate between the branches created by git branch
    git checkout -b main
  ### allows you to set the default remote branch for your current local branch
    git push --set-upstream origin main(If you face any problem)
  ### used to upload local repository content to a remote repository
    git push -u -f origin main
  ### View your commit history
    git log
