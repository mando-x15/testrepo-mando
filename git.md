## Git Commands

### fetch/overwrite
`git fetch --all`
git reset --hard origin/master


# add single file
git add CHC.tex include

or 

# Add/push/commit
git add . 

git commit -m 'text'

git push -u origin master


# pull, merge changes
???

# Branches
git branch -a      # see all

git checkout -b name  # create new branch


# see files being tracked
git ls-tree -r master --name-only


# to revert back to a previous commit
git log
git reset --hard 914e8b57366b4e35dd694c8f3976da765be7f432


# for versioning add tags:
git tag -a 1.0 -m 'the initial release'
git push origin --tags

# MERGE/fast forward issue:
git pull origin branch_name

git mergetool
git commit
git push

# to remove a file from the cache
git rm --cached -r <file>


#config
 git config --global core.editor "gedit"

# overwrite repo
git fetch --all
git reset --hard origin/master




**OTHER**
#create link to directory
ln -s /media/ext4/CHC/tLong/2D/t1e-6 data


#get hardware info
sudo lshw -html > hardware.html



**VIM**

