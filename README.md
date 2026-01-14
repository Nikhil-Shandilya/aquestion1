git init
git cofig --global user.name
git config --global user.email
git add .
git commit -m "New add"
git remote add origin
git branch -M main
git push -u origin main
git show HEAD:index.html | sed -n '1,50p'
git log --oneline
git remote -v

git checkout -b second-branch
gedit index.html
git add index.html
git commit -m "Second-change"
git checkout main
git merge new-branch
git push origin main
git brach -d second-branch
git push origin --delete second branch

java -jar jenkins.war
