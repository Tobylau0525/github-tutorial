# GitHub Tutorial

by Toby_lau 

---
## Git vs. GitHub
**Git** is like the place where you **input** your _**commands**_.  

**Github** is the cloud where all your **commits** would be saved,and used to 
store data/code.


---
## Initial Setup
1 go to [google chrome](https://www.google.com)<-press (press **on** the scroller on your mouse to open a new tap)  
2 go into incognito (press **command+shift+n** the <u>_**same**_</u> time)
![alt text](http://updatepedia.com/wp-content/uploads/2016/04/Google_Chrome_Incognito.png )
3 go to [github.com](https://www.github.com) (press **on** the scroller on your mouse to open a new tap)    
4 press <u>sign up</u>  
5 USERNAME: same as your hstat.org username  
ex: tomt0101  
6 PASSWORD: (<u>**Recommand**</u>)<u>**same**</u> as your HSTAT password so you don’t forget  
(Reminder)if you get a red bubble saying 
“something went wrong,” 
ignore it -- keep going!  
7 <u>**free account**</u>  
8 **finish sign up**  
9 When you are finished, check your email and verify with github  
10 go back to [google chrome](https://www.google.com)<-press  (press **on** the scroller on your mouse to open a new tap)  
11 go back into incognito (press **command+shift+n** the <u>_**same**_</u> time)  
12 go to your gmail  
13 check your email  
14 Look for an email from support called “Team hstatsep has invited you to join their team on cloud9"  
15 Click the link  
16 Create new account  
17 Your Name: First and Last name  
18 username: same as your hstat.org email (but without the @hstat.org)  
ex: Timt0101@hstat.org  you put Timt0101  
19 go to Student  
20 then click on Coursework  
21 finish the rest of the steps  
22 finish reading the message  
23 set your passsword  
24 go back to [www.c9.io](https://www.c9.io) (press **on** the scroller on your mouse to open a new tap)   
25 look at your top-right  
26 find the gear icon  
Right here ->![alt text](https://lh6.googleusercontent.com/30HBjz1rnXSNb4TxZQ5vBCU5i-BEXsJLpOftc5kBQAf8L0o1URo2sd6uWrGE9DYBe10LPCh25LqRPXEYiRRwjvAqKid-X--6coYVJkBxeAXREhyJNfdnPvsQEO25IsHQJZPoLFrzMxg)<- Right here  
27 Go to connected services  
![alt text](https://lh3.googleusercontent.com/OUIUvCy6_jXixNqv5A_N3NdQrOyddguVKpRLWGWgQxxqPukalIKQtsohxcCJlxSUIP6mYneW2jbjWrnRdZBOuoZ-kCJc9uYSM2qXBn-v8p-c89e8PoonZ3R7rPx54LSN7ujlNC2ZMrw)  
28 In the future, here is how you will log in
go to [c9.io](https://www.c9.io) ->![alt text](https://lh3.googleusercontent.com/p57o7f31-F5fCPYoWzAYwVv48WpdLOZXV8zxbRabuofCBU00nGpNWHsO0LDteIKtV1krpVRMN2CXzNC1QPaQlBlHHsMaGF9rmilvnK_mxIMvq4kwprvHSmBx9pCGliqiefmQuYuJNQ8)
click on the cat,you should see something that said" **Sign in to GitHub to continue to Cloud9**" 
![alt text](https://drive.google.com/a/hstat.org/file/d/0B0vpNprpg9i_ZHNzRG1BS0Z2Y0k/view?usp=sharing)  
SSH key:the key to access github(think of a door/gate in front of github,SSH is lik a key to open the door and access github)
## Repository Setup
**pwd **:print the current working directory  
**ls**list  
**mkdir**:make a directory(making a container)  
**rmdir**:delete a directory(destroying a container)  
**git init**: set up a repository    
**git add** :places chosen file in the staging area(just like adding people into the picture)  
git commit**: take a specific ‘snapshot’ of the files on the stage(taking a picture with people in it :)   
**mkdir**(thefilename):when you want to make a directory you type in `mkdir`,the term mkdir means make directory but in a shorter way. ![alt text](mkdir.png)

**rmdir**(thefilename)when you want to remove a directory you type in `rmdir`,the term mkdir means remove directory but in a shorter way.
<u>** *NOTE </u>:to delete a folder, you must be in its parent folder
if you type **ls**, you should see the folder you want to remove
you can only delete an **empty** directory,that means if you got something in the folder you **can't** delete the folder with this methon.  
**git status**:git status check the files status,if it's on the stage or edited/not commited  
**git init**:Then if you want to make your directory to a repository,you type in `git int`,what thsi does is that it initialize git into your directory, which makes it a repository.  
**git add**:add the file you want to the staging area,just like calling someone into the picture to get ready.  
**git commit**:take a "snapshot" of the file on the stage,just like taking a picture.  



---
## Workflow & Commands
Workflow:git status->git add->git commit->git push 

1 having a directory (folder) of files(**`mkdir`**)  
2 then initialize git(**`git init`**) like hiring a photographer.  
3 Once you have type in **`git init`** your file has become repository(or repo).  
4 if you have edit something in the file **and** you want to save it 
5 type in`git add` and the filename you want to add,what this does is that you are putting the file into the stage,just like putting people ino the frame.  
6 once you are done adding the files to the stage,you type in `git commit`
to basically take a "snapshot" of your code,like taking a picture.  
7when you are really to push your changes to github,you type in `git push` and all chanegs will be push to github.


---
## Rolling Back Changes
git checkout -- filename(you want to change back) :if you had edited a file and yo want the pervious file version.  
git reset HEAD filename :remove the file from stage   
git reset --soft HEAD~1:remove from the commit  
git reset HEAD~1:move file from commit to stage   
git reset --hard HEAD~1:remove file from commit to edit   
