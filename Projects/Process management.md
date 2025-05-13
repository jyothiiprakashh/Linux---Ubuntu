Process management in linux is used to display the current process running by the system.
Let's get into detail.  

In Linux right after when we enter command `ps` we will get the following image.  

![Alt text](https://github.com/jyothiiprakashh/Linux-Ubuntu/blob/main/Projects/SmartSelect_20250513-143524_UserLAnd.jpg)  

### Process Management:
- In process management we can identify the process running in backgin the system.
- We can turn off the process which is running in background by using `kill` command.
- Killing a process called as termination.
- `top` is a command which is used ft monitor the real time system information.
- It gives CPU, storage, memory etc. details.


Now lets make a scenario of process management.

- To understand how the process management is works, lets make an example.
- Here, I created a user called `TestUser` using `useradd` command with directory in `/home`.  
![Alt text](https://github.com/jyothiiprakashh/Linux-Ubuntu/blob/main/Projects/SmartSelect_20250513-150212_UserLAnd.jpg)


- Now let us create an empty file using `touch` command having file name `TestFile`.  
![Alt text](https://github.com/jyothiiprakashh/Linux-Ubuntu/blob/main/Projects/SmartSelect_20250513-151228_UserLAnd.jpg)  

- After that, open vi editor and write some text in that.
- And create a new file using `echo` command.
![Alt](https://github.com/jyothiiprakashh/Linux-Ubuntu/blob/main/Projects/SmartSelect_20250513-151249_UserLAnd.jpg)  

 ```
   echo "Hello World !" >> TestFile2.txt

 ```
- 
