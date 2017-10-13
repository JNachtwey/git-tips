// GIT
tiP: rebase: apply commits from other branches on current branch
command: git rebase <branch>

tiP: force push
command: push origin +master
source: https://stackoverflow.com/questions/5667884/how-to-squash-commits-in-git-after-they-have-been-pushed

tip: overright local changes with origin
command: git reset --hard origin/<branch_name>
source: https://stackoverflow.com/questions/1125968/how-do-i-force-git-pull-to-overwrite-local-files

tip: changing a commit message
command: git commit --amend 
source: https://help.github.com/articles/changing-a-commit-message/

tip: checkout a specific version of a file
command: git checkout <commit_id> <file>
source: https://stackoverflow.com/questions/1173676/how-can-i-check-out-a-particular-version-of-one-file-in-git

tip: Squash latest commits
command: git rebase -i HEAD~4 
source: https://www.devroom.io/2011/07/05/git-squash-your-latests-commits-into-one/
	https://stackoverflow.com/questions/5667884/how-to-squash-commits-in-git-after-they-have-been-pushed

tip: pick a specific commit and apply it on current branch
command: git cherry-pick <commit_id>
source: https://git-scm.com/docs/git-cherry-pick
