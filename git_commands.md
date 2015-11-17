Git workflow commands
=

- `git add -A`
  - stages changed files for commit
  - allows you to choose which files you would like to commit
  - `git add .` only stages constructive changes (added/modified files), it does not stage deleted files
- `git commit -m 'commit message'`
  - `git commit --amend`
- `git push <remote> <local branch>:<remote branch>`
- `git pull`

#### Resolving merge conflicts
```
the number of planets are
<<<<<<< HEAD
nine
=======
eight
>>>>>>> master
```


#### Try it
- set up a repo with a `README.md`
- add your name to the readme
- push it to master
