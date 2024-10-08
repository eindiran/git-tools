# git-tools

Scripts for git, enabling some of my common workflows.

## Merge conflicts

#### `git-conflicts`

Enables `git conflicts`; check the conflicts that will occur when merging two specified branches.

Uses `git_conflict_parser.py` under the hood.

#### `git-mergedit`

Enables `git mergedit`; does a merge and then opens all files with conflicts in `$EDITOR`.

Uses `git_merge_parser.py` under the hood.

## Recent branches:

#### `git-recent`

Enables `git recent` show recent branches with timestamps.

#### `git-recentch`

Enables `git recentch`; get recent branches sorted by local checkout time.

#### `git-recentco`

Enables `git recentco`; get recent branches by last commit time.

#### `git-popb` / `git-switchb`

Tools for switching to recent branches. `popb` for last branch, `switchb` for an interactive menu.

## Misc

#### `git-author`

Search the log on the current branch for commits by a specific author.

#### `git-cleanb`

Tool to interactively delete branches.

#### `git-jnb`

Enables `git jnb`; auto-format a new branch name based on a short text description and switch to it; base is current HEAD.

#### `git-diffago`

Enables `git diffago`; compare working tree with commit N commits ago (from `HEAD`). Eg `git diffago 3` = `git diff HEAD~3` and `git diffago 3 HEAD` = `git diffago HEAD~3 HEAD`.

#### `git-tree`

Enables showing files using the `tree` command; requires `tree` to be installed.

#### `git-ignored`

List all files ignored by the patterns in active `.gitignore` files.
