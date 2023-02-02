# GitHub Steps

1. Create a local repository, initialize it with git, add, commmit
2. Create a remote reposity 
3. Connect the local repo & remote repo
    - $ `git remote add origin git@github.com:USERNAME/REPO_NAME.git`
4. Configure Git to name the default branch *main* 
    - $ `git branch -M main`
5. Push to remote repository (Be sure to add and commit before pushing) 
    - $ `git push -u origin main` 
6. Use `git push` for all following pushes thereafter