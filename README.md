touch README.md 
git add . 
git commit -m 'add README.md'
mkdir git_test 
git init git_test
git checkout -b first_branch 
git add . 
git commit -m 'Edit README.md in branch first_branch'

git checkout - 
git add . 
git commit -m 'Edit README.md in branch master' 
git log