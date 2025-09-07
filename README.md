echo "# test-pr-repo" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/AlzhanWiz/test-pr-repo.git
git push -u origin mainTest change for PR
