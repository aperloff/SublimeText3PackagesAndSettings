# SublimeText3PackagesAndSettings
Maintains a master copy of the packages and settings I use for Sublime Text 3.

In order to clone this repository and not overwrite any necessary files, use the command:
```bash
git init
git remote add origin git@github.com:aperloff/SublimeText3PackagesAndSettings.git
git fetch
git reset origin/master # Required when the versioned files existed in path before "git init" of this repo.
git checkout -t origin/master # Only necessary if not on the master branch
git restore --progress . # Recreates all of the files from the repository
```
