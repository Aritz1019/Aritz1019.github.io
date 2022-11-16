# aritz1019.github.io
# Aritz Domaika

# 1. Select branching strategy
	The selected branching strategy has been to have a master and a develop branches.
	In this way, the develop branch is were all the code is develep, whereas the changes and the commits are only posted to the master branch when
	a funcionality has been ended and tested.
# 2. 10 new git commands
##	2.1 echo "Hello World" > index.html
		Create a index.html file with the "Hello world" text
##	2.2 git rebase --onto develop~1 develop
		Delete the first commit in the develop branch
##	2.3 git push --set-upstream origin develop
		To create the develop branch in the repository and push the commits in it
##	2.4 git stage --all
		To add all the changed files to be prepared to do a commit
##	2.5 git cherry-pick 4cce7fcd98c029bfa38fdb3b2c435627879018be
		To add the next commit of the commit that we want to delete
##	2.6 git reset --hard 5256612ddc109492bdd2e64ead875cf8cbac722f
		To move the HEAD to the commit which is before to the one that we want to delete
##	2.7 git push --force origin develop
		To force push the currently checked-out branch to the remote-current part
##	2.8 git branch -d cherry
		To delete the cherry branch used to delete not consecutive commits
##	2.9 git rebase develop
		To push the changes of develop-aritz commits to the develop branch
##	2.10 git revert 1948a91e9b4224ddc72ddaffb2aeef5874712ac9
		To revert a commit and return to an older commit
