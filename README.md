# git
git intro and cheatsheet
Git – Intro and Cheat sheet 
https://git-intro.readthedocs.io/en/latest/cheat_sheet.html
https://media.readthedocs.org/pdf/git-intro/latest/git-intro.pdf



#git global#
git config --global user.name "bhoobal"
git config --global user.email 'bhoobal@gmail.com'

#*above will setup a global config under local user in windows C:\user\username\.gitconfig on ubuntu ~/.gitconfig*#

#list global config#
git config --global -l

#git commit - below command commit the change#
git commit filename

# view last history #
git log -1

#stash /stage changes#
git add .
git reset HEAD README.md  //unstage changes

#push new branch to origin#
git push -u origin newbranch


