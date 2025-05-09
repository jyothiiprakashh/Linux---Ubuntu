Before get into this project, we are going to learn few basic commands
regarding user management in Linux Operating system.  

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
make sure that user account name without space execpt underscore(_), dot(.) and hyphens(-).
- The following is the syntax to create user
`useradd username
