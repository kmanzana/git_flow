- reset
- checkout
- merge/rebase
- setup auto rebase:
```
$ git config --global branch.autosetuprebase always # Force all new branches to automatically use rebase
$ git config branch.*branch-name*.rebase true # Force existing branches to use rebase.
```
