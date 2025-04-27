# File permission
In this, you will learn about file creation and various file operations such as deleting, renaming, moving, and different ways to create, edit, and append a file.  

But, before you get into this you ahsould have a basic knowledge on definitions.

### Definitions
- **File**: A file in Linux is a container where data is stored. It can be text, images, programs, or anything else. Everything in Linux, including programs and devices, is treated as a file.
- **Directory**: A directory in Linux is like a folder. It is used to organize and store files. A directory can also contain other directories, called subdirectories.

### Basic Commands used in file management:
- **File creation**:
  For file creation we use follow command `touch filename.txt`  
  **Output:**  
  ![image](https://github.com/user-attachments/assets/748af1b4-e8d6-4d28-98cc-9831191b3fe1)  
  Here, you can see that a file has been created using the `touch` command, along with its timestamp and other details, which you will understand later.


  **Method 2**:  
  Using directly by creating `echo` command.
  Before this, we need to understand how the `echo` command works. In Python, we use the `print` command, and the `echo` command in Linux works on a similar principle.
  **Output:**
  ![image](https://github.com/user-attachments/assets/042d2c71-daa3-4276-a6af-522961efa476)  

  
  **Output:**  
  ![image](https://github.com/user-attachments/assets/8d9f3bec-ddce-490a-8bb4-03835851b252)
  
  In this example, we are directly appending the string `"Hello world"` to `file2.txt`, even if it hasn't been created yet. The system first checks for the file, and if it doesn't exist, it creates a new file with the same name and appends the output to it.


  **Method 3**:  
  Using directly by creating path.  
  ![image](https://github.com/user-attachments/assets/f9ee490f-256b-4d71-b58b-d3e30cb882fb)

  Here, I provided a direct path to create a file, even though I am in a different directory. It allowed me to create the file directly using the touch command with a path as an argument.


- **File deletion**: For file creation we use follow command `rm filename.txt`  
  ![image](https://github.com/user-attachments/assets/c9960d12-00b2-4c7b-8297-6f382a0d753b)  

  **Output:**  
  ![image](https://github.com/user-attachments/assets/d1b938f1-8679-4af1-93c7-b3cfb3328ce6)  

- **Copying a file into a directory:**  
  To copy a file, we will use `cp filename.txt /destinantion` command to copy to the desired destination.  
  But befor this we are goingb to create another directory called "test2.0" to where we are using this copy method to copy files from source "test" directory to "test2.0"  
  ![image](https://github.com/user-attachments/assets/3f2caebe-1eb0-41b7-803f-008e9df67c4f)  
  we copied the file `file2.txt` to directory "test2.0".
  
  **Output:**  
  ![image](https://github.com/user-attachments/assets/e7bd0fde-46dc-4130-afea-01f0696b1215)
- **Moving a file into a directory:**
  To move and rename a file we use `mv` command `mv file3.txt /test2.0`

