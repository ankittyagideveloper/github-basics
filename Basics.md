Git-> VCS(VERSION CONTROL SYSTEM)-->  Git was built by Linus Torvalds( also created Linux)

  VCS-> Git, Subversion , Mercurial, Perforce


- Backup

  
- Tracking --> Maintain History
- rollback --> will be able to revert if any problem occours

# git init ---> to initialise git and start tracking the files 
- it creates a hidden folder and it starts the tracking --> to see do ls -a
- .git has the file system where our all changes get store

<img width="243" alt="image" src="https://github.com/user-attachments/assets/769fe913-8a75-4289-b882-55aa20650d8d" />

* the 'U' before file shows that this file is untracked (by default it doesn't track and have ask him to track by running below command
  
 `U` ---> Untracked

# git add <file name here>
or 
# git add . ---> To Track all files (. means all files)

![image](https://github.com/user-attachments/assets/328dc2ed-9470-4161-9c36-791c4a4c187f)

<img width="270" alt="image" src="https://github.com/user-attachments/assets/69e06a55-de79-4a97-aca1-056680e17614" />

 `A` --> Index Added

now it got added inside `.git > index` folder

`cd .git`

![image](https://github.com/user-attachments/assets/10cfff54-c0d5-47a4-b021-ebd3e9e8a7a5)

 
![image](https://github.com/user-attachments/assets/6fb4e848-b99d-4a33-843b-ff52f5a17aab)

`cat` --> cat command is used to see the content of a file
![image](https://github.com/user-attachments/assets/717c7878-c204-43d7-8297-31c98ef2b55c)

The content inside `index` file is zipped (compressed)

`git status` --> To check the current status of tracked and untracked files

All commands of git either Read/Write inside the git folder
whole tracking goes inside our local .git folder 

The current status of the file is uncommited and it is present in staging area, where we are actually tracking the files which got added
![image](https://github.com/user-attachments/assets/c8e1157c-3792-4a9c-8164-ec7240860bd7) ![image](https://github.com/user-attachments/assets/b5f8bdc2-a4a3-493c-90f7-266172d76edc)



# git commit -m "what this feature do"
![image](https://github.com/user-attachments/assets/90f7aa3d-c118-4618-b40c-f2f177cfcdeb)
- Now it created a basically a checkpoint or snapshot or commit
- every commit has an ID or a hash

# git log
to see the history

![image](https://github.com/user-attachments/assets/1efdd311-ae8c-4888-89ba-e43abd791f7e)

 








  



