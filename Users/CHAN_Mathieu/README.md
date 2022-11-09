# 1.1 First commit

1. commited to "master" branch
2. commit hash = a28b21a5f90b64dbe65fd8a91317547c7d535b72
3. One file modified 

# Command used

git add
git commit
git diff
git status
git commit --amend
git restore
git checkout
git checkout -b
git reset
git restore --staged
git rebase
git

# Commit creation

touch file_1.txt
echo "hello" >> file_1.txt
git add file_1.txt
git commit -m "[chan-mathieu]: Create file_1.txt"

# Fetching and pushing

git fetch // Data searching from remote (origin by default)
git rebase // Update main / master branch (assuming you are in the main / master branch)
git push origin HEAD // Update remote main / master branch

# Restoring file and branch switching

## Restoring unstaged files

git restore file_1.txt
git reset --hard

## Restoring staged files

git restore --staged file_1.txt
git checkout --

## Branch switching

git switch <branch>
git checkout <branch>
