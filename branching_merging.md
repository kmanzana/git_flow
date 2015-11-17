#### Branching & Merging

- checkout
  - `git checkout master`
  - `git checkout -b feature_1`
  - `git config.alias co=checkout`
- merge/rebase
- reset
- setup auto rebase:
```
$ git config --global branch.autosetuprebase always # Force all new branches to automatically use rebase
$ git config branch.*branch-name*.rebase true # Force existing branches to use rebase.
```


#### Try it
- checkout a new branch locally called `feature_1`
- make a change to `README.md` and commit it
- push it to a remote branch called `feature_1`
- do a soft reset: `git reset --soft HEAD~`
- recommit and do a hard reset: `git reset --hard HEAD~`
