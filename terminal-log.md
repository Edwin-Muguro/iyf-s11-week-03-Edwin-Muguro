
Administrator@DESKTOP-BUGKGO7 MINGW64 /c/IYF_ACADEMY/WEEK 3 ASSIGNMENT
$ echo "node_modules/
> .DS_Store
> .vscode/
> *.log'>.gitignore
> 
> echo "node_modules/
.DS_Store
.vscode/
*.log'>.gitignore
git init
node_modules/
.DS_Store
.vscode/
*.log'>.gitignore

echo node_modules/
bash: .DS_Store: command not found
bash: .vscode/: No such file or directory
> *.log'>.gitignore
git init git add.gitignore
bash: $'*.log>.gitignore\ngit init\n*.log': command not found
usage: git init [-q | --quiet] [--bare] [--template=<template-directory>]
         [--separate-git-dir <git-dir>] [--object-format=<format>]
         [--ref-format=<format>]
         [-b <branch-name> | --initial-branch=<branch-name>]
         [--shared[=<permissions>]] [<directory>]

Administrator@DESKTOP-BUGKGO7 MINGW64 /c/IYF_ACADEMY/WEEK 3 ASSIGNMENT
$ git init git add.gitignore git commit -m "chore: add.gitignore"
error: unknown switch `m'
usage: git init [-q | --quiet] [--bare] [--template=<template-directory>]
                [--separate-git-dir <git-dir>] [--object-format=<format>]
                [--ref-format=<format>]
                [-b <branch-name> | --initial-branch=<branch-name>]
                [--shared[=<permissions>]] [<directory>]

    --[no-]template <template-directory>
                          directory from which templates will be used
    --[no-]bare           create a bare repository
    --shared[=<permissions>]
                          specify that the git repository is to be shared amongst several users
    -q, --[no-]quiet      be quiet
    --[no-]separate-git-dir <gitdir>
                          separate git dir from working tree
    -b, --[no-]initial-branch <name>
                          override the name of the initial branch
    --[no-]object-format <hash>
                          specify the hash algorithm to use
    --[no-]ref-format <format>
                          specify the reference format to use


Administrator@DESKTOP-BUGKGO7 MINGW64 /c/IYF_ACADEMY/WEEK 3 ASSIGNMENT
$ create readme.md
bash: create: command not found

Administrator@DESKTOP-BUGKGO7 MINGW64 /c/IYF_ACADEMY/WEEK 3 ASSIGNMENT
$ git init
Initialized empty Git repository in C:/IYF_ACADEMY/WEEK 3 ASSIGNMENT/.git/

Administrator@DESKTOP-BUGKGO7 MINGW64 /c/IYF_ACADEMY/WEEK 3 ASSIGNMENT (main)
$ git add.readme.md
git: 'add.readme.md' is not a git command. See 'git --help'.

Administrator@DESKTOP-BUGKGO7 MINGW64 /c/IYF_ACADEMY/WEEK 3 ASSIGNMENT (main)
$ git add README.md

Administrator@DESKTOP-BUGKGO7 MINGW64 /c/IYF_ACADEMY/WEEK 3 ASSIGNMENT (main)
$ git commit -m "docs: add professional README"
[main (root-commit) 4f11f23] docs: add professional README
 1 file changed, 11 insertions(+)
 create mode 100644 README.md

Administrator@DESKTOP-BUGKGO7 MINGW64 /c/IYF_ACADEMY/WEEK 3 ASSIGNMENT (main)
$ git add about.html

Administrator@DESKTOP-BUGKGO7 MINGW64 /c/IYF_ACADEMY/WEEK 3 ASSIGNMENT (main)
$ git add index.html

Administrator@DESKTOP-BUGKGO7 MINGW64 /c/IYF_ACADEMY/WEEK 3 ASSIGNMENT (main)
$ git add terminal-log.md

Administrator@DESKTOP-BUGKGO7 MINGW64 /c/IYF_ACADEMY/WEEK 3 ASSIGNMENT (main)
$ git commit
Aborting commit due to empty commit message.

Administrator@DESKTOP-BUGKGO7 MINGW64 /c/IYF_ACADEMY/WEEK 3 ASSIGNMENT (main)
$ git commit --m "docs: add files"
[main 2bfaf9d] docs: add files
 3 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 about.html
 create mode 100644 index.html
 create mode 100644 terminal-log.md

Administrator@DESKTOP-BUGKGO7 MINGW64 /c/IYF_ACADEMY/WEEK 3 ASSIGNMENT (main)
$ git add style.css

Administrator@DESKTOP-BUGKGO7 MINGW64 /c/IYF_ACADEMY/WEEK 3 ASSIGNMENT (main)
$ git commit "add style.css"
error: pathspec 'add style.css' did not match any file(s) known to git

Administrator@DESKTOP-BUGKGO7 MINGW64 /c/IYF_ACADEMY/WEEK 3 ASSIGNMENT (main)
$ git commit -m "add style.css"
[main 6c5d3a4] add style.css
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 style.css

Administrator@DESKTOP-BUGKGO7 MINGW64 /c/IYF_ACADEMY/WEEK 3 ASSIGNMENT (main)
$ 
Administrator@DESKTOP-BUGKGO7 MINGW64 /c/IYF_ACADEMY/WEEK 3 ASSIGNMENT (main)
$ git checkout -b feature/navbar
Switched to a new branch 'feature/navbar'

Administrator@DESKTOP-BUGKGO7 MINGW64 /c/IYF_ACADEMY/WEEK 3 ASSIGNMENT (feature/navbar)
$ git add style.css

Administrator@DESKTOP-BUGKGO7 MINGW64 /c/IYF_ACADEMY/WEEK 3 ASSIGNMENT (feature/navbar)
$ git commit -m "feat: add flexbox navbar"
[feature/navbar b8175fc] feat: add flexbox navbar
 1 file changed, 12 insertions(+)

Administrator@DESKTOP-BUGKGO7 MINGW64 /c/IYF_ACADEMY/WEEK 3 ASSIGNMENT (feature/navbar)
$ git checkout main
M       index.html
M       terminal-log.md
Switched to branch 'main'

Administrator@DESKTOP-BUGKGO7 MINGW64 /c/IYF_ACADEMY/WEEK 3 ASSIGNMENT (main)
$ git merge feature/navbar
Updating 6c5d3a4..b8175fc
Fast-forward
 style.css | 12 ++++++++++++
 1 file changed, 12 insertions(+)

Administrator@DESKTOP-BUGKGO7 MINGW64 /c/IYF_ACADEMY/WEEK 3 ASSIGNMENT (main)
$ git add index.html

Administrator@DESKTOP-BUGKGO7 MINGW64 /c/IYF_ACADEMY/WEEK 3 ASSIGNMENT (main)
$ git checkout -b feature
fatal: cannot lock ref 'refs/heads/feature': 'refs/heads/feature/navbar' exists; cannot create 'refs/heads/feature'

Administrator@DESKTOP-BUGKGO7 MINGW64 /c/IYF_ACADEMY/WEEK 3 ASSIGNMENT (main)
$ git checkout main
M       index.html
M       terminal-log.md
Already on 'main'

Administrator@DESKTOP-BUGKGO7 MINGW64 /c/IYF_ACADEMY/WEEK 3 ASSIGNMENT (main)
$ git merge feature/navbar
Already up to date.

Administrator@DESKTOP-BUGKGO7 MINGW64 /c/IYF_ACADEMY/WEEK 3 ASSIGNMENT (main)
$ 