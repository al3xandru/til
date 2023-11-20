# Sync GitHub Fork

The different mechanisms are documented in detail on [Syncing a fork - GitHub Docs](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/syncing-a-fork).

## Synching a fork branch from the web UI

This is the easiest way. On the forked repo, if the fork is behind it will show
a button "Sync fork".

## Synching a fork branch from the command line

1.  Add a new remote _parentrepo_ repository
2.  Fetch the _parentrepo_: `git fetch parentrepo`
3.  Check out your fork's local default branch: `git checkout main`
4.  Merge the changes from the _parentrepo_: `git merge parentrepo/main`

