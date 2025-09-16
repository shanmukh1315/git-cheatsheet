
> Maintained by shanmukh1315

---

## Linux Commands 

1. `ls` — list files  - notes: ls -l (long), ls -a (hidden), ls -h (human sizes)

2. `cd` — change directory     - notes: cd .. (up one level), cd ~ (home)

3. `pwd` — print working directory     - notes: prints the absolute path of the current directory

4. `mkdir` — create directory  - notes: mkdir -p (make parent dirs), mkdir new_folder

5. `rm` — remove files/directories  - notes: rm file.txt, rm -r dir (remove directory), rm -f (force)

6. `cp` — copy files  - notes: cp file1 file2, cp -r dir1 dir2 (copy folder)

7. `mv` — move/rename files  - notes: mv old.txt new.txt (rename), mv file.txt /path/ (move)

8. `cat` — print file contents  - notes: cat file.txt, cat file1 file2 > combined.txt

9. `less` — view file paged  - notes: less bigfile.txt (scroll with arrows, q to quit)

10. `grep` — search text  - notes: grep "word" file.txt, grep -i (ignore case), grep -R (recursive)

11. `find` — search files - notes: find . -name "*.txt", find /path -type f -mtime -1
 
12. `chmod` — change permissions  - notes: chmod +x script.sh, chmod 644 file.txt

13. `chown` — change owner  - notes: sudo chown user:user file.txt

14. `tar` — archive/compress  - notes: tar -czvf archive.tar.gz folder/, tar -xvzf archive.tar.gz

15. `ssh` — secure shell   - notes: ssh user@host, ssh -i keyfile.pem user@host

16. `echo` — print text to terminal or file  - notes: echo "hello", echo $PATH
17. `head` — show first lines of a file  - notes: head -n 5 file.txt (first 5 lines)
18. `tail` — show last lines of a file  - notes: tail -n 5 file.txt (last 5 lines), tail -f logfile (follow)

---

## Git Commands 

1. `git init` — create repo    - notes: init new repo in current folder
 
2. `git status` — what changed  - notes: show staged, unstaged, and untracked files

3. `git add` — stage changes  - notes: stage changes for the next commit (use . to add all)

4. `git commit` — save snapshot  - notes: record staged changes (with -m "msg" for inline message)

5. `git log` — history  - notes: view commit history, use --oneline for concise view

6. `git branch` — list/create branches  - notes: list branches, git branch new-branch creates one
7. `git checkout -b <name>` — new branch + switch  - notes: create and switch to a new branch in one command

8. `git merge <name>` - notes: merge changes from another branch into the current branch

9. `git remote add origin <url>` — set remote  - notes: link local repo to a remote server (usually GitHub)

10. `git push -u origin main` — push main upstream  - notes: upload local commits to remote, -u sets tracking

11. `git clone <url>` — copy a repo from GitHub  - notes: download a full copy of a remote repository

12. `git pull` — get latest changes from remote  - notes: fetch and merge changes from the remote branch

13. `git diff` — show changes between commits or working tree  - notes: show line-by-line differences since last commit

14. `git reset <file>` — unstage a file  - notes: unstage a file but keep changes in working directory

15. `git stash` — save work in progress temporarily  - notes: save uncommitted changes for later, restore with stash pop


