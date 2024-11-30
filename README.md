echo "# git" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M homepage
git remote add origin https://github.com/a2lost/git.git
git push -u origin homepage
