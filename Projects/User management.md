Before get into this project, we are going to learn few basic commands
regarding user management in Linux Operating system.  Here I am logged into root and creating all these.

- Whatever the user account created by admin/root, by default it will goes into home directory.  
- Home directory is the default directory to all the users.
- We can give userid while creating or after creating, by default userid starts from 1001.
- System users like root, bin etc. are starts from 0 upto 999 or 1000.
- When we try to create an account userid starts from 1000 or 1001.
- userid plays a vital role in user management, it is unique.
- Userid used to to give permissions to the file they created in simple, file ownership.
- Passwords can be set, manage, userid and password locking, adding to different groups.

Lets dive into the user creation.

In linux before creating an user makesure that user account  
make sure that user account name without space execpt underscore( _ ), dot(.) and hyphens(-).
- The following is the syntax to create user `useradd [Options] username`  
- Now create `user1` in linux with home direcory.  

```
useradd -m user1
```
![image](https://github.com/user-attachments/assets/8757d0fa-cabd-40a1-885a-7c6a64b7fadf)  

`drwxr-x---  2  user1  user1 4096  may 12 21:55  user1`  
-  `drwxr-x---` represents file permissions. In which "d" states it is a directory, remaining are file permissions.

| Character   | Numerical   |
|-------------|-------------|
| r - read    | 4 - read    |
| w - write   | 2 - write   |
| x - execute | 1 - execute |  

-  file permissions are given to 3 members, those are users, groups and others.
-  First `rwx` represents permissions to the `user`, second `r-x` represents permissions to the `group` and third `---` represents permissions to the others.

Now we create an empty file in the `user1` directory.  

- create `file.txt` using `touch` command  

`touch file.txt`

![image](https://github.com/user-attachments/assets/f55433e3-ce73-4fbe-91a6-49feeab93950)  

-rw-r--r-- 
