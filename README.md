## The order of commands

```

git clone <repo url>
touch hello_world.txt
touch README.md
git status
git add hello_world.txt
git status
git commit -m "first commit"
git log
git remote set-url origin "https://username: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@github.com/vivek-zemoso/first_git_repo.git"
git push -u origin master
git diff
git add hello_world.txt
git status
git commit -m "modified all \"to\" to \"vivek\" "
git log
git push
git revert HEAD
git status
git add hello_world.txt
git status
git commit
git push
git revert HEAD --no-edit
git log
git checkout -b new_branch
git add hello_world.txt
git log
git push -u origin new_branch
git checkout master
git pull
git status
git add .
git commit -m "add README to master branch"
git push

```