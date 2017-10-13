## collection of git tips ##

**rebase: apply commits from other branches on current branch**
>git rebase <branch>

**force push**
>git push origin +master

<sup>source: https://stackoverflow.com/questions/5667884/how-to-squash-commits-in-git-after-they-have-been-pushed
</sup>

**overwrite local changes with origin**
>git reset --hard origin/<branch_name>

<sup>source: https://stackoverflow.com/questions/1125968/how-do-i-force-git-pull-to-overwrite-local-files
</sup>

**changing a commit message**
>git commit --amend

<sup>source: https://help.github.com/articles/changing-a-commit-message/
</sup>

**checkout a specific version of a file**
>git checkout <commit_id> <file>

<sup>source: https://stackoverflow.com/questions/1173676/how-can-i-check-out-a-particular-version-of-one-file-in-git
</sup>

**Squash latest commits**
>git rebase -i HEAD~4

<sup>source: https://www.devroom.io/2011/07/05/git-squash-your-latests-commits-into-one/
	https://stackoverflow.com/questions/5667884/how-to-squash-commits-in-git-after-they-have-been-pushed
</sup>

**pick a specific commit and apply it on current branch**
>git cherry-pick <commit_id>

<sup>source: https://git-scm.com/docs/git-cherry-pick
</sup>
