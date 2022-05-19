# assignments
vredd218@LIN33003674 MINGW64 ~ (master)
$ mkdir assignments

vredd218@LIN33003674 MINGW64 ~ (master)
$ cd assignments

vredd218@LIN33003674 MINGW64 ~/assignments (master)
$ git add Readme.txt

vredd218@LIN33003674 MINGW64 ~/assignments (master)
$ touch Readme.txt

vredd218@LIN33003674 MINGW64 ~/assignments (master)
$ git add Readme.txt

vredd218@LIN33003674 MINGW64 ~/assignments (master)
$ git commit -m 'Readme.txt file commited'
[master (root-commit) 00fdd57] Readme.txt file commited
 Committer: Reddy Muppana <venkata-sataya-sai-ram.reddy@capgemini.com>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 2 files changed, 7 insertions(+)
 create mode 100644 .bash_history
 create mode 100644 assignments/Readme.txt

vredd218@LIN33003674 MINGW64 ~/assignments (master)
$ git status
warning: could not open directory 'Application Data/': Permission denied
warning: could not open directory 'Cookies/': Permission denied
warning: could not open directory 'Local Settings/': Permission denied
warning: could not open directory 'My Documents/': Permission denied
warning: could not open directory 'NetHood/': Permission denied
warning: could not open directory 'PrintHood/': Permission denied
warning: could not open directory 'Recent/': Permission denied
warning: could not open directory 'SendTo/': Permission denied
warning: could not open directory 'Start Menu/': Permission denied
warning: could not open directory 'Templates/': Permission denied
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   ../.bash_history

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ../.cache/
        ../.cisco/
        ../.dbshell
        ../.eclipse/
        ../.junique/
        ../.lesshst
        ../.mongorc.js
        ../.p2/
        ../.viminfo
        ../3D Objects/
        ../AppData/
        ../Contacts/
        ../Desktop/
        ../Documents/
        ../Downloads/
        ../Favorites/
        ../IntelGraphicsProfiles/
        ../Links/
        ../Music/
        ../NTUSER.DAT
        ../NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TM.blf
        ../NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer00000000000000000001.regtrans-ms
        ../NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer00000000000000000002.regtrans-ms
        ../OneDrive - Capgemini/
        ../Pictures/
        ../Saved Games/
        ../Searches/
        ../Videos/
        ../eclipse-workspace/
        ../eclipse/
        ../ntuser.dat.LOG1
        ../ntuser.dat.LOG2
        ../ntuser.ini
        ../project_dir/
        ../test/

no changes added to commit (use "git add" and/or "git commit -a")

vredd218@LIN33003674 MINGW64 ~/assignments (master)
$ vi Readme.txt

vredd218@LIN33003674 MINGW64 ~/assignments (master)
$ git init
Initialized empty Git repository in C:/Users/VREDD218/assignments/.git/

vredd218@LIN33003674 MINGW64 ~/assignments (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Readme.txt

nothing added to commit but untracked files present (use "git add" to track)

vredd218@LIN33003674 MINGW64 ~/assignments (master)
$ git add Readme.txt

vredd218@LIN33003674 MINGW64 ~/assignments (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   Readme.txt


vredd218@LIN33003674 MINGW64 ~/assignments (master)
$ git commit -m 'Readme.txt file commited'
[master (root-commit) 67cbac6] Readme.txt file commited
 Committer: Reddy Muppana <venkata-sataya-sai-ram.reddy@capgemini.com>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 1 insertion(+)
 create mode 100644 Readme.txt

vredd218@LIN33003674 MINGW64 ~/assignments (master)
$ git status
On branch master
nothing to commit, working tree clean

vredd218@LIN33003674 MINGW64 ~/assignments (master)
$ git add Readme.txt

vredd218@LIN33003674 MINGW64 ~/assignments (master)
$ git status
On branch master
nothing to commit, working tree clean

vredd218@LIN33003674 MINGW64 ~/assignments (master)
$ touch html-assignments

vredd218@LIN33003674 MINGW64 ~/assignments (master)
$ git checkout -b <new branch>
bash: syntax error near unexpected token `newline'

vredd218@LIN33003674 MINGW64 ~/assignments (master)
$ git pull
There is no tracking information for the current branch.
Please specify which branch you want to merge with.
See git-pull(1) for details.

    git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=<remote>/<branch> master


vredd218@LIN33003674 MINGW64 ~/assignments (master)
$ git pull html-assignments
fatal: invalid gitfile format: html-assignments
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

vredd218@LIN33003674 MINGW64 ~/assignments (master)
$ git branch
* master

vredd218@LIN33003674 MINGW64 ~/assignments (master)
$ git pull html-assignments
fatal: invalid gitfile format: html-assignments
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

vredd218@LIN33003674 MINGW64 ~/assignments (master)
$ git pull
There is no tracking information for the current branch.
Please specify which branch you want to merge with.
See git-pull(1) for details.

    git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=<remote>/<branch> master


vredd218@LIN33003674 MINGW64 ~/assignments (master)
$ git branch html-assignments

vredd218@LIN33003674 MINGW64 ~/assignments (master)
$ git switch html-assignments
Switched to branch 'html-assignments'

vredd218@LIN33003674 MINGW64 ~/assignments (html-assignments)
$ git checkout master Readme.txt
Updated 0 paths from 0f0cb0d

vredd218@LIN33003674 MINGW64 ~/assignments (html-assignments)
$ git status
On branch html-assignments
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        html-assignments

nothing added to commit but untracked files present (use "git add" to track)

vredd218@LIN33003674 MINGW64 ~/assignments (html-assignments)
$ touch file.txt

vredd218@LIN33003674 MINGW64 ~/assignments (html-assignments)
$ git add-A
git: 'add-A' is not a git command. See 'git --help'.

vredd218@LIN33003674 MINGW64 ~/assignments (html-assignments)
$ git status
On branch html-assignments
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        file.txt
        html-assignments

nothing added to commit but untracked files present (use "git add" to track)

vredd218@LIN33003674 MINGW64 ~/assignments (html-assignments)
$ git switch master
Switched to branch 'master'

vredd218@LIN33003674 MINGW64 ~/assignments (master)
$ touch file.html

vredd218@LIN33003674 MINGW64 ~/assignments (master)
$ git add -A

vredd218@LIN33003674 MINGW64 ~/assignments (master)
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   file.html
        new file:   file.txt
        new file:   html-assignments


vredd218@LIN33003674 MINGW64 ~/assignments (master)
$ git commit
Aborting commit due to empty commit message.

vredd218@LIN33003674 MINGW64 ~/assignments (master)
$ git switch html-assignments
Switched to branch 'html-assignments'
A       file.html
A       file.txt
A       html-assignments

vredd218@LIN33003674 MINGW64 ~/assignments (html-assignments)
$ git stash
Saved working directory and index state WIP on html-assignments: 67cbac6 Readme.txt file commited

vredd218@LIN33003674 MINGW64 ~/assignments (html-assignments)
$ git switch master
Switched to branch 'master'

vredd218@LIN33003674 MINGW64 ~/assignments (master)
$ git add -A

vredd218@LIN33003674 MINGW64 ~/assignments (master)
$ git status
On branch master
nothing to commit, working tree clean

vredd218@LIN33003674 MINGW64 ~/assignments (master)
$ git commit -a
On branch master
nothing to commit, working tree clean

vredd218@LIN33003674 MINGW64 ~/assignments (master)
$ git switch master
Already on 'master'

vredd218@LIN33003674 MINGW64 ~/assignments (master)
$ git merge html-assignments
Already up to date.

vredd218@LIN33003674 MINGW64 ~/assignments (master)
$ git branch -d html-assignments
Deleted branch html-assignments (was 67cbac6).

vredd218@LIN33003674 MINGW64 ~/assignments (master)
$
