# git-tools
Scripts for git, enabling some of my commone workflows.

## Merge conflicts
### `git-conflicts`

Enables `git conflicts`; check the conflicts that will occur when merging two specified branches. 

Uses `git_conflict_parser.py` under the hood.

### `git-mergedit`

Enables `git mergedit`; does a merge and then opens all files with conflicts in $EDITOR. 

Uses `git_merge_parser.py` under the hood.

## Recent branches:
#### `git-recentch`

Enables `git recentch`; get recent branches by local checkout time.

#### `git-recentco`

Enables `git recent` and `git recentco`; get recent branches by last commit time.

#### `git-popb` / `git-switchb`

Tools for switching to recent branches. `popb` for last branch, `switchb` for an interactive menu.

## Misc
#### `git-jnb`

Enables `git jnb`; auto-format a new branch name based on a short text description and switch to it; base is current HEAD.

#### `git-diffago`

Enables `git diffago`; compare working tree with commit N commits ago (from `HEAD`). Eg `git diffago 3` = `git diff HEAD~3` and `git diffago 3 HEAD` = `git diffago HEAD~3 HEAD`.
