## collection of git tips ##

**rebase: apply commits from other branches on current branch**
>git rebase <branch>

**force push**
>git push origin +master

source: https://stackoverflow.com/questions/5667884/how-to-squash-commits-in-git-after-they-have-been-pushed

**overwrite local changes with origin**
>git reset --hard origin/<branch_name>

source: https://stackoverflow.com/questions/1125968/how-do-i-force-git-pull-to-overwrite-local-files

**changing a commit message**
>git commit --amend

source: https://help.github.com/articles/changing-a-commit-message/

**checkout a specific version of a file**
>git checkout <commit_id> <file>

source: https://stackoverflow.com/questions/1173676/how-can-i-check-out-a-particular-version-of-one-file-in-git

**Squash latest commits**
>git rebase -i HEAD~4

source: https://www.devroom.io/2011/07/05/git-squash-your-latests-commits-into-one/
	https://stackoverflow.com/questions/5667884/how-to-squash-commits-in-git-after-they-have-been-pushed

**pick a specific commit and apply it on current branch**
>git cherry-pick <commit_id>

source: https://git-scm.com/docs/git-cherry-pick
