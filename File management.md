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
  

  
