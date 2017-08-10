git init
git status --> Check branch etc.
git add . --> All Files
git add *.htm --> All files With ext
git config --global --edit
git config --global user.email 92amankumar@gmail.com
git commit -m "Done" --> Commit with comments
git commit -a -m "Done" --> Commit with comments and without adding to stage
git log
echo.>.gitignore
git branch MyBranch
git checkout MyBranch
git checkout master --> main branch
git merge MyBranch
git stash
git stash apply
git remote --> TO check repository will show origin
git remote -v --> TO check repository will show URL
git remote add RepoName URL --> TO add more repository
git clone URL --> TO clone from repository
git fetch origin --> Update but not merge
git pull origin --> Update and merge
git push origin master --> Push


https://github.com/92amankumar/GITtutorial.git

We recommend every repository include a README, LICENSE, and .gitignore.
…or create a new repository on the command line

echo "# GITtutorial" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/92amankumar/GITtutorial.git
git push -u origin master
…or push an existing repository from the command line

git remote add origin https://github.com/92amankumar/GITtutorial.git
git push -u origin master

