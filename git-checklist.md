Here's a checklist of some generic steps and git commands that I use:

- [ ] Fork the project
- [ ] Clone it to your local development system `git clone`
- [ ] Set up your git remotes (*origin* and *upstream*) `git remote -v` `git remote add <remote name> <url of remote repo>` Note: you will only need to do this step once.
- [ ] Create a local branch for any new development `git branch <feature branch name>` and checkout the branch `git checkout <feature branch name>`
- [ ] Develop and commit changes to the local branch `git add`, `git commit`, `git log`, `git status`
- [ ] Get the most up to date version of the upstream code `git fetch upstream`
- [ ] Rebase your changes onto upstream `git rebase upstream/master` Use `git log` to check that your commit is the most recent.
- [ ] Push the changes to your GitHub repo `git push origin <feature branch name>`
- [ ] Go to your account in GitHub and submit the pull request :smile:

As an aside, `git status` is your friend. Use it often :wink:

While this might seem like a lot now, it's very helpful to have a consistent workflow since it keeps you organized and saves time and reduces errors in the long run.