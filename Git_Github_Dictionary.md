# Git &Github Dictionary
# My first github project
## This is a subtitle

IMPORTANT: don't do double git init
IMPORTANT: don't remove the .git folder whee your history is kept

4 conceptual areas:
1. Develop. Area : the working directory
2. Staging Area : it's a temporary space to store file before commiting (access via git add)
4. Local repository: the .git folder # where snapshots are saved in your timeline

# Commands
git init: initializes my git repo
git commit -m "meaning message"  # it sends "saves" to the local repository

	Things to consider when writing a message
	Why
	How
	Effects
	Limitations

# New additions starting here
Git status allow me to check what files ar:
1. unstaged
2. untracked
3 ..

<<<<<<< HEAD
git add: adds it to your staging area (organizes the library books)
git status: check the status of your working folder
git log: very useful as it gives you access to the whole history

git show: shows what happens in the commits
git diff: actually compares the two commits -- super-useful for versions comparison
=======

>>>>>>> parent of a9c4014 (TITLE FOR YOUR MSG)


# Parallel timelines - how to experiment risk free in Git
1. create a new timeline - branch and give it a name
'git branch <name>'
2. checkout to the timeline you want to work on...
'git checkout <name/id>'

P.S. You can travel branches and commits


Even more data
