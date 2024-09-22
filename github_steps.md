# GitHub Steps

Describe in your own words how to establish a connection between a local repository and a remote repository on GitHub.

### Establising a connection between local and remote repositories on GitHub.

- First off we need to create a directory via `Terminal` and create a file within that directory
- Then we can `Git Init` the repository in the directory just created
- Add the file by `git add <filename>` then `git commit -m "insert message"` 
After we completed the steps above locally we are now going to create a Github repository, remotly.
Get on the GitHub website and create new repository that matches the name of the directory we created in the first step.
git remote add origin git@github.com:USERNAME/REPO_NAME.git
git branch -M main
git push -u origin main
Refresh Github browser tab. Your newly created repostitory should be there