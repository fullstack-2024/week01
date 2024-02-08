# Activity 2: Basic Linux Commands 

In this lab, you'll learn how to use fundamental commands in the Linux operating system. These commands are essential for navigating the file system, managing files, and obtaining system information.

**Prerequisites:**
- Access to a Linux terminal.

**Commands to be Covered:**
1. `ls`: List directory contents.
2. `cd`: Change directory.
3. `clear`: Clear the terminal screen.
4. `pwd`: Print working directory.
5. `rm`: Remove files or directories.
6. `whoami`: Display the current username.
7. `mkdir`: Create directories.
8. `cat`: Display file content.
9. `whereis`: Locate the binary, source, and manual page files for a command.

**Instructions:**

1. **Open Terminal:**
   - Open the terminal on your Linux system.

2. **Navigate to Your Home Directory:**
   - Use the `cd` command to navigate to your home directory:
     ```
     cd ~
     ```

3. **List Directory Contents:**
   - Use the `ls` command to list the contents of your home directory:
     ```
     ls
     ```

4. **Print Working Directory:**
   - Use the `pwd` command to print the current working directory:
     ```
     pwd
     ```

5. **Create a New Directory:**
   - Use the `mkdir` command to create a new directory named "lab":
     ```
     mkdir lab
     ```

6. **Change Directory:**
   - Use the `cd` command to change into the newly created "lab" directory:
     ```
     cd lab
     ```

7. **Verify Current Directory:**
   - Once again, use the `pwd` command to verify that you are in the correct directory:
     ```
     pwd
     ```

8. **Create Files:**
   - Create a few sample text files using the `echo` command:
     ```
     echo "This is file1 content." > file1.txt
     echo "This is file2 content." > file2.txt
     echo "This is file3 content." > file3.txt
     ```

9. **List Contents:**
   - Use the `ls` command to list the contents of the current directory and verify that the new files were created:
     ```
     ls
     ```

10. **Display File Contents:**
    - Use the `cat` command to display the contents of one of the newly created files (e.g., "file1.txt"):
      ```
      cat file1.txt
      ```

11. **Clear the Terminal Screen:**
    - Use the `clear` command to clear the terminal screen:
      ```
      clear
      ```

12. **Remove Files:**
    - Use the `rm` command to remove one of the files (e.g., "file2.txt"):
      ```
      rm file2.txt
      ```

13. **List Contents Again:**
    - Use the `ls` command to verify that the specified file has been removed:
      ```
      ls
      ```

14. **Display Current Username:**
    - Use the `whoami` command to display the current username:
      ```
      whoami
      ```

15. **Locate Command Binary:**
    - Use the `whereis` command to locate the binary file for the `ls` command:
      ```
      whereis ls
      ```

16. **Navigate Back to Home Directory:**
    - Finally, navigate back to your home directory using the `cd` command:
      ```
      cd ~
      ```

