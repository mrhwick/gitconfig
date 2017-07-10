# Hardwick's Git Configuration

These are my dark magic aliases that I prefer when I am using git.


### Installation

```bash
git clone https://github.com/mrhwick/gitconfig.git
cd gitconfig
cat gitconfig >> ~/.gitconfig
```

Edit the user information to match your actual email and name.

Reload your terminal, and your Git client will have discovered the new aliased commands.

### Usage

Common commands are shortened:

```bash
# git commit
git ci

# git status -s (shortened)
git st

# git checkout
git co

# git add
git a

# git add -p (patch mode)
git ap
```

Some helper command scripts are included for common workflows:

```bash
# Checkout the 'dev' branch and pull the latest code from remote named 'upstream'
git rst

# Checkout a new branch that clones the current branch and prefix the given name with 'feature/'
git feat my-new-thing
Switched to a new branch 'feature/my-new-thing'

# Checkout a new branch that clones the current branch and prefix the given name with 'hotfix/'
git fix my-hot-repair
Switched to a new branch 'hotfix/my-hot-repair'

# Push the current branch commits to the same branch on the remote named origin
git up

# Pull the latest commits from the current branch down from the remote named origin
git down

# Pull the latest commits from the current branch down from the remote named upstream.
git reload

# Delete all branches that have been merged into the latest commit on the current branch, excluding 'master', 'dev', 'staging', and 'qa'.
git delete-merged-branches
```

Some useful git log viewer command aliases are included:

```bash
# Show compact log information with pretty-formatted commit messages, branch name pointers, and authors.
git ls
```
![image](https://cloud.githubusercontent.com/assets/865759/15545550/b6079498-226a-11e6-97f6-a1584f739681.png)

```bash
# Show cozy log information with file changes and number of lines added/removed.
git ll
```
![image](https://cloud.githubusercontent.com/assets/865759/15545571/cf662f6c-226a-11e6-84f8-1260a93e5cc3.png)

```bash
# Show expanded log information with most useful information included.
git ld
```
![image](https://cloud.githubusercontent.com/assets/865759/15545592/ea7add7a-226a-11e6-8569-2e3293cfb5a4.png)
