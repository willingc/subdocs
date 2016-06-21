# subdocs
A test repo for submodules in git 2.9


A follow up to a prior test in Fall 2015 https://github.com/willingc/docshelf

## Cloning the repo

    git clone --recurse-submodules {--jobs=<N>} https://github.com/willingc/subdocs.git

## Update the submodules

    git fetch --recurse-submodules {--jobs=<N>}

## Notes

git submodules are found in .gitsubmodules

This directory should be checked into version control as we do with .gitignore


