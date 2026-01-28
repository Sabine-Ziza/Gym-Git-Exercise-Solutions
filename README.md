# Gym-Git-Exercise-Solutions
## Bundle1
## Exercise 1
```bash



````

## Exercise2
```bash
USER@LAPTOP-L1U2P979 MINGW64 ~/Gym-Git-Exercise-Solutions (main)
$ git add home.html

USER@LAPTOP-L1U2P979 MINGW64 ~/Gym-Git-Exercise-Solutions (main)
$ git stash
Saved working directory and index state WIP on main: 55faab3 first files

USER@LAPTOP-L1U2P979 MINGW64 ~/Gym-Git-Exercise-Solutions (main)
$ git add about.html

USER@LAPTOP-L1U2P979 MINGW64 ~/Gym-Git-Exercise-Solutions (main)
$ git stash
Saved working directory and index state WIP on main: 55faab3 first files

USER@LAPTOP-L1U2P979 MINGW64 ~/Gym-Git-Exercise-Solutions (main)
$ git add team.html

USER@LAPTOP-L1U2P979 MINGW64 ~/Gym-Git-Exercise-Solutions (main)
$ git stash
Saved working directory and index state WIP on main: 55faab3 first files

USER@LAPTOP-L1U2P979 MINGW64 ~/Gym-Git-Exercise-Solutions (main)
$ git stash list
stash@{0}: WIP on main: 55faab3 first files
stash@{1}: WIP on main: 55faab3 first files
stash@{2}: WIP on main: 55faab3 first files
stash@{3}: WIP on main: 55faab3 first files
stash@{4}: WIP on main: 55faab3 first files

USER@LAPTOP-L1U2P979 MINGW64 ~/Gym-Git-Exercise-Solutions (main)
$ git commit -m "initial project"
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

USER@LAPTOP-L1U2P979 MINGW64 ~/Gym-Git-Exercise-Solutions (main)
$ git push origin main
Everything up-to-date

USER@LAPTOP-L1U2P979 MINGW64 ~/Gym-Git-Exercise-Solutions (main)
$ git stash pop
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   team.html

Dropped refs/stash@{0} (65e7d34c2aa52e1a6ac4a9eeef4a4ceaa4f18a00)

USER@LAPTOP-L1U2P979 MINGW64 ~/Gym-Git-Exercise-Solutions (main)
$ git stash pop
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html
        new file:   team.html

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    home.css
        deleted:    home.html

Dropped refs/stash@{0} (7c529eb4ccfca310f4cb2ae2fdc835378fecbdec)

USER@LAPTOP-L1U2P979 MINGW64 ~/Gym-Git-Exercise-Solutions (main)
$ git commit -m "initial project"
[main 7aa813d] initial project
 2 files changed, 25 insertions(+)
 create mode 100644 about.html
 create mode 100644 team.html

USER@LAPTOP-L1U2P979 MINGW64 ~/Gym-Git-Exercise-Solutions (main)
$ git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 565 bytes | 282.00 KiB/s, done.
Total 4 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/Sabine-Ziza/Gym-Git-Exercise-Solutions.git
   55faab3..7aa813d  main -> main
```