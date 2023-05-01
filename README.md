# New Project

1. Clone the repository to your local machine using the command:
```
git clone https://github.com/volodymyr-Vedula/new-project.git
```
2. Navigate to the local repository on your machine using the command:
```
cd new-project
```
3. Make sure you are on the 'development' branch by using the command:
```
git branch
```
If the output shows the 'development' branch with an asterisk (*), you are currently on the 'development' branch. If not, switch to it using the command:
```
git checkout development
```
4. Make changes to the code or files in the repository as needed.

5. Once you have made changes, stage them for committing using the command:
```
git add .
```
6. Commit the changes with a meaningful commit message using the command:
```
git commit -m "Meaningful commit message"
```
7. Push the changes to the 'development' branch using the command:
```
git push origin development
```
8. If you encounter merge conflicts, resolve them before pushing your changes to the 'development' branch.
9. If you want to fetch the latest changes from the remote repository, use the command:
```
git fetch
```
10. If you want to merge the latest changes from the 'main' branch into your 'development' branch, use the command:
```
git merge origin/main
```
11. If you are ready to merge your changes from the 'development' branch into the 'main' branch, first ensure that the 'development' branch is up to date with the latest changes from the 'main' branch. You can do this by following steps 9 and 10 above.
12. Once the 'development' branch is up to date, switch to the 'main' branch using the command:
```
git checkout main
```
13. Merge the changes from the 'development' branch into the 'main' branch using the command:
```
git merge development
```
14. Push the changes to the 'main' branch using the command:
```
git push origin main
```
