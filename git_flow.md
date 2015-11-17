![](http://nvie.com/img/git-model@2x.png)

![](https://www.atlassian.com/git/images/tutorials/collaborating/comparing-workflows/gitflow-workflow/01.svg)

#### Try it
- (close existing PR from `feature_1` to `master`, we aren't following that workflow anymore)
- create `develop` branch from `master`
- create PR from `feature_1` to `develop`
  - your feature is complete and ready to be merged
- merge PR
  - do a code review and test in isolation prior to merge
- create `release_1` from `develop`
  - we are getting ready to release your knew feature
- add commit to `release_1`
  - a bug was found in integration testing
- create `hotfix_1` from master and add a commit
  - a production high priority bug was found
- merge `hotfix_1` to `release_1` and merge `release_1` to `develop`
  - get the branches in sync with new change
- create PR for `hotfix_1` to `master` and merge
- merge `release_1` to `master` (using command line, no need for a PR)
