# create a new repository on the command line
echo "# git_test" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/algorithmlover2016/git_test.git
git push -u origin master

# push an existing repository from the command line
git remote add origin https://github.com/algorithmlover2016/git_test.git
git push -u origin master

#
