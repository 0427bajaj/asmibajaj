# AryanNanda
# asmibajaj
learning git <br>
Git Repo>> clone >> changes >> add >> commot >> Push <br>
<P> <center> 
download git & visual studio <br> <br>
        <codevisualstudio.com>( visual studio) <br>
        <git-scm.com></git-scm.com> (download git) <br>
        select on desktop ( it will install git bash) <br>
        git --version to check set up 
        <br>
------------------------------------------<br></P><p><p></p>
       config change- set user name ans email <br>
       % git config --global user.name "0427bajaj" <br>
       (to set up user name) <br>
       % git config --global user.email "0427bajaj@gmail.com" <br>
      (to set up email as user name) <br>
       % git config --list ( to check what are the changes made to list them)
       <br>
------------------------------------------<br></P><p><p></p>
create repository, add code on line and commit <br>
https://github.com/new <br>
your profile <br>
       new <br>
        create name <br>
        public <br>
        readme <br>
        create repository <br>
        can see commit on right hand side <br>
        to check always go to your profile <br>
        edit under read me and commit change on right hand side <br>
        also can give commit message- <br>
        to understand what was change- it will let us know last change 
       <br>
------------------------------------------<br></P><p><p></p>
clone <br>
run git clone and folder link from copy cody/clone <br>
https://github.com/0427bajaj/asmibajaj.git <br>
and hit enter
<br>
------------------------------------------<br></P><p><p></p>
cd, cd .. mkdir, ls, ls -a, git status, clear <br>
cd and name of folder to go to the folder/directory <br>
cd .. to come out of the folder <br>
mkdir and name of folder to create new folder <br>
clear terminal clear <br>
ls is to list all the files under the folder <br>
ls -a can be used to see even hidden file,it will also show .git file <br>
git status can be used to see the status of project if anything to commit like there is gap in destop and remote repisiorygit status( VS code will show yellow and M on file)
<br>
------------------------------------------<br></P><p><p></p>
add- scrren shot, modified, staged,commit <br>
untract file/ new file- are git do not know what is in the file as screen shot /add was never taken <br>
modified- is changed <br>
stage- engagement- is screen shot taken- is file is ready to commit, after modification & adding 3rd stage is staged before commit <br>
commit- wedding phase- unchanged file, all screen shot has been taken by git, nothing is untracked <br>
>> stay in the folder that has file in it eg
PS C:\Users\P3056738\OneDrive - Charter Communications\Desktop\gitdesktopfolder\asmibajaj><br>
This folder have that file, I will saty in this folder and push the change 
<br>
------------------------------------------<br></P><p><p></p>
1. Add, it will be staged after we add- status will be Stage <br>
git add README.md (README.md is file name here that has changes )<br>
git add . ( to add many changes) 
<br>
------------------------------------------<br></P><p><p></p>
git status
<br>
------------------------------------------<br></P><p><p></p>
3. commit (legal record)- it add changes to local repo <br>
git commit -m "message" ( message is the message you want to keep to track change)<br>
git commit -m "commiting 1st change" 
       >> git add .
        git commit -m "Initial commit"

<br>
------------------------------------------<br></P><p><p></p>
4. Git Push- take code to remote repo- it publish to remote respository <br>
git push origin main <br>
it will ask to connect to remote ask permission and ask authorization
<br>
------------------------------------------<br></P><p><p></p>
git init <br>
to make it git repository a folder in visual code <br>
create new git repo <br>
mkdir 7 name of new folder <br>
go intols - this folder run git init to make it git repository for local system and have git folder that will be hidden can check with <br>
ls -a 
<br>
------------------------------------------<br></P><p><p></p>
README<br>
if select read me while creating repositary then we also have to bring to local respoitory
<br>
------------------------------------------<br></P><p><p></p>
to set repository link and origin<br>
git remote add origin <https://github.com/0427bajaj/asmirenuubajaj.git><br>
go to folder and run PS C:\Users\P3056738\OneDrive - Charter Communications\Desktop\gitdesktopfolder\LocalRepo> git remote add origin <https://github.com/0427bajaj/asmirenuubajaj.git> 
<br>
------------------------------------------<br></P><p><p></p>
git remote -v ( to verify remote) to see which is remote repositry
<br>
------------------------------------------<br></P><p><p></p>
git push as short cut for future to create use this one time,<br>
 next time we can use only git push to push to same repository <br>
git push -u origin main ( this is used to set push when we are using same repository/project for long time)
<br>
------------------------------------------<br></P><p><p></p>
git branch ( to check branch)<br>
to check which branch we are in<br>
eg: git branch -M main ( to rename branch)<br>
git branch -M (new name)<br>
git checkout <-branch name-> (to navigate)<br>
git checkout -b <- new branch name-> (to create new branch)<br>
git branch -d <-branch name-> to delete branch)
<br>
------------------------------------------<br></P><p><p></p>
Creating a repositiory without read me online and intiallising here
create repository in git hub
then run git remote add origin and link of repository
gitdesktopfolder> git remote add origin https://github.com/0427bajaj/RishitBajaj.git
>> then to check if it got connected here use git remote -v
origin  https://github.com/0427bajaj/RishitBajaj.git (fetch)
>> git branch
>> if no branch exist create a branch 
git checkout -b main ( it will switch to main branch)
<br>
------------------------------------------<br></P><p><p></p>

<br>
------------------------------------------<br></P><p><p></p>

<br>
------------------------------------------<br></P><p><p></p>