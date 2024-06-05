PS D:\STUDY\DEVOPS_STUDY\PROJECT_2\HelloWorldApp> 

PS D:\STUDY\DEVOPS_STUDY\PROJECT_2\HelloWorldApp> git init

### Now add gitignore file here >> 
go to vs code studio > view > extension > search the extension named gitignore ( i installed code zombie and install that )
then go to project page in vs code studio and then press F1 and then type gitignore and select add gitignore and then again type visualstudio.gitignore and then 
see gitignore file is added 

PS D:\STUDY\DEVOPS_STUDY\PROJECT_2\HelloWorldApp> ls


    Directory: D:\STUDY\DEVOPS_STUDY\PROJECT_2\HelloWorldApp


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----          6/5/2024   2:47 PM                HelloWorldApp.web
-a----          6/5/2024   3:44 PM           6860 .gitignore
-a----          6/5/2024   2:46 PM           1027 HelloWorldApp.sln


PS D:\STUDY\DEVOPS_STUDY\PROJECT_2\HelloWorldApp>

PS D:\STUDY\DEVOPS_STUDY\PROJECT_2\HelloWorldApp>

PS D:\STUDY\DEVOPS_STUDY\PROJECT_2\HelloWorldApp> git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .gitignore
        HelloWorldApp.sln
        HelloWorldApp.web/

nothing added to commit but untracked files present (use "git add" to track)
PS D:\STUDY\DEVOPS_STUDY\PROJECT_2\HelloWorldApp> 

PS D:\STUDY\DEVOPS_STUDY\PROJECT_2\HelloWorldApp> git add .

PS D:\STUDY\DEVOPS_STUDY\PROJECT_2\HelloWorldApp> git status

( you can see that bin and obj was excluded from the commit as we mention in gitignore file as we donot need bin and obj folder as 
these folders  are irrelivent to the code respositry and because these folders are created everytime on the fly when we build the project with the code.
when 


PS D:\STUDY\DEVOPS_STUDY\PROJECT_2\HelloWorldApp> git commit -m "project2 First Commit"

PS D:\STUDY\DEVOPS_STUDY\PROJECT_2\HelloWorldApp> git status
On branch master
nothing to commit, working tree clean
PS D:\STUDY\DEVOPS_STUDY\PROJECT_2\HelloWorldApp>

git branch -M main

git remote add origin https://github.com/harishdhawan2022/project2.git
                      
