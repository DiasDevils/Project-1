Learning to use GitPod and GitHub typing in TERMINAL.

1- Typing "ls"  displays files in terminal

2- Typing "echo "once upon a time">> story.txt" in TERMINAL created a story.txt file with once upon a time inside as text 

3- Typing "ls -a" displays all including .git hidden directories

4- Typing "git status" in TERMINAL displays the status tracked or untracked of the files being used

5- Typing  "git init"   in TERMINAL shows the respositry open

6- Typing "git add README.MD" tracking README 
6- Typing  "git commit -m "Initial Commit" to save in README file in TERMINAL with message

7- Typing  "git add story.txt" to track file story in TERMINAL
7- Typing  "git commit -m "Second Commit" to save in the story file in termninal with message

8 - Typing "git status" and getting working tree clean means eveything is saved

"touch" command creates a new file - not used
"mkdir" One Two Three makes three files - not used 

9- git add <file name>-- adds a specific file with saved chages
9- git add . -- adds all files with saved changes

10- git commit -m "your commit message" -- commit's the added changes to the local repo

11- git push -- pushes the commited changes from your local repo to github

12- git rm --cached <file_name> -- removed the file you dont want to commit

13- git dif story.txt --  shows what is different from a previous to the new file

14- git log -- shows the history of the changes and when

15- "git reset -- hard SHA first 6 digits -> this will revert back to the version indicated
 

16- The .gitignore file
echo "password.txt">> .gitignore
 -> git status
 -> git add .gitignore
 -> git commit -m "added password text file to gitinogre"
 
EXAMPLE
echo "password" >> password.txt
echo "This is an extra line" >> story.txt
git status 
-- will show untracked in red -- 
ls - a 
-- will show all files -- 
git add . 
-- will track both files now -- 
git status 
-- will show the files that are ready to be committed in green --
git rm --cached password.txt 
-- this will remove password.txt file --
git status
-- will only now show the story.txt file to be committed--
git commit -m "added more text to the story"
-- now its tracked--
