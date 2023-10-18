### Robotics lab - Assignment completion & submission instructions
### --------------------------------------------------------------

1. Install git commandline on your Ubuntu OS (follow the steps in the link shared earlier)

2. Accept the assigment using the GitHub classroom assignment link (share in the class whatsapp group)

3. Clone the assignment from the remote git repo (ie, the one in the GitHub classroom) to your PC \
Use ```gitclone``` command for this

4. Do the assignment on your PC / lab PC

5. You can push the partially completed assignment to the remote git

(please note that i have renamed the folder as JIM-CET; your assignment folder would have your name)

6. Once the assignment is completed push it to the remote repo on or before the due time.

#### Steps to push local repo (ie the files on your PC) to remote repo (ie the one on the GitHub)

use git add .          

#note the space and . after add ; this caches (or adds) all the files in the local repo.

this process is known as staging 

Staged files are files that are ready to be committed to the repository you are working on

if you want to clear current git cache 
for example you didn't want to include some/all files in the current commit

git rm -r --cached .       # don't forget the dot (.)

if want to remove any particular folder or file then

git rm  --cached filepath/foldername

with git commit command you commit to the remote repo
you can include a message in double quotes 

git commit -m "commit-message"

Git Push
The push term refers to upload local repository content to a remote repository. 
Pushing is an act of transfer commits from your local repository to a remote repository. Pushing is capable of overwriting changes; caution should be taken when pushing.

Adding remote repo
- Open your assignment remote folder (ie github folder) in a browser and copy the address from the address bar 

git branch -M main
git remote add origin <remote git repo address>
git push -u origin main




