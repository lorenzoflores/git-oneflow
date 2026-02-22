#git-oneflow

A GNU/Linux script tool to help make the git onelflow workflow simpler.

Download the script and place it in a folder like /usr/local/sbin so your GNU/Linux system can find and run it.

Make sure it has the necessary permissions: `chmod +x git-oneflow`.

Run `git-oneflow` to see the command help.

Usage: `git one <command> [name]`

Available commands:

`start <name>` Creates a feature branch from `main`

`finish` Merges the current branch into `main` and deletes it

`hotfix <name>` Creates an urgent hotfix branch from `main`

`release <version>` Creates a release branch to prepare for deployment

`sync` Updates `main` and cleans up local branches
