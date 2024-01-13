1)
cd /path
git init
git checkout -b feature-login, Made changes
git add .
git commit -m "Implement login functionality"
git checkout main
git checkout -b feature-logout and made changes
git add .
git commit -m "Implement logout functionality"
git push -u origin feature-login
git push origin feature-logout

2)
git checkout main
git checkout -b develop
git add .
git commit -m "Implement login functionality in develop branch"
git add .
git commit -m "Implement logout functionality in develop branch"
git push origin develop
git checkout main
git merge develop
git commit -m "Merge develop "
git push origin main

3)

4)

Forked below repository : https://github.com/nithindante/first-contributions
git clone https://github.com/nithindante/first-contributions.git
cd first-contributions
git switch -c new_branch
git add Contributors.md
git commit -m "Add your-name to Contributors list"
git push -u origin your-branch-name

Went to my repository and clicked on compare and pull request
submit the pull request.
