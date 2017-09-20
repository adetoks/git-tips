1. Create new repo
2. Open command prompt
3. cd to project folder
4. Initialize the local directory as a Git repository.
```
  git init
```
5. Add the files in your new local repository. This stages them for the first commit.
```
  git add .
  # to add all files in local repo for commit.
```
6. Commit the files that you've staged in your local repository.
```
  git commit -m "comment"
```
7. In the Command prompt, add the URL for the remote repository where your local repository will be pushed.
```
  git remote add origin [repository github URL]
  # Sets the new remote
  git remote -v
  # Verifies the new remote URL
```
8. Push the changes in your local repository to GitHub.
```
  git push origin master
  # Pushes the changes in your local repository up to the remote repository you specified as the origin
```
