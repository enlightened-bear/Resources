# Coding

## Git

### Cheat Sheet

| Command | Example | Description |
| ----------- | ----------- | ----------- |
| `git help` |`git help log` | Shows documentation for a `log` command.|----------
| `git config` |`git config --global core.editor vim` | Sets default editor to `vim`. |
| | `git config user.name` | Shows the value set for the key `user.name`. |
| | `git config --global alias.co checkout` | You can now type in `git co` instead of `git checkout`.|
| `git init` | `git init` | Start version controlling the current directory. |
| `git clone` | `git clone git@github.com:enlightened-bear/Resources.git` | Clone the repository into the current directory. |
| | `git clone git@github.com:enlightened-bear/Resources.git ~/res` | Clone the repo as `res` in the home directory. |
| | `git clone --recurse-submodules https://github.com/chaconinc/MainProject` |  Initialize and update the submodules while cloning the repository. |
| `git add` | `git add README` | Adds the content of `README` into the staging area. Also, used to start tracking the new files. |
| `git status` | `git status` | Shows the state of files. |
| | `git status -s`| Simplied output.|
| `git diff` | `git diff` | Shows diff between working directory and staging area. |
| | `git diff --staged` | Shows diff between staging area and last commit. |
| | `git diff master branchB` | Shows diff between the commits. |
| | `git diff --check` | Identifies possible white space errors. |
| `git commit` | `git commit` | Records a new permanent snapshot with the files that have been staged. |
| | `git commit -a -m 'Commit Message'` | Automatically stages all modified and deleted files and commits with provided message. |
| | `git commit --ammend` | Allows for ammending the most recent commit. |
| `git reset` | `git reset HEAD README.md` | Unstages the file `README.md`. |
| | `git reset --hard HEAD` | Repository is rolled back to the last committed state. |
| `git rm` | `git rm PROJECTS.md` | Removes the file from working directory and also the staging area. |
| | `git rm --cached README` | Removes the file from the staging area but not from working directory. |
| `git clean` | `git clean -f -d` | Removes any file/subdirectories that are not tracked. |
| | `git clean -d -n`| Dry run - shows what files/subdirectories would be removed. |
| | `git clean -x -i`| `-x` options even removes the files that match `.gitignore` patterns. `-i` is interactive flag. |

### Resources

1. [Pro Git book.](https://git-scm.com/book/en/v2)
2. [Github collection of .gitignore templates.](https://github.com/github/gitignore)

## Others

1. [Markdown(.md) cheat sheet.](https://www.markdownguide.org/cheat-sheet/)
