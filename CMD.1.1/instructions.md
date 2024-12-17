# Command Line Day 1 Part 1
Introduction to Terminal Commands (Mac and Windows)
Welcome to the assignments! For each task, you’ll find detailed instructions in a file called instructions.md, which you can follow directly from your computer’s terminal or command line interface (CLI).

## Accessing the Terminal:
On a Mac, open the Terminal app by going to Applications > Utilities > Terminal or using Spotlight (cmd + space and type "Terminal").
On Windows, open Command Prompt or PowerShell by typing cmd or powershell in the Start menu search bar. Alternatively, you can use Windows Subsystem for Linux (WSL) if you have it installed.

## Print Working Directory - pwd
The first thing you’ll learn is how to check which directory you are currently in. This is important because many commands rely on the context of your current directory.

Open your terminal (Mac: cmd + space > "Terminal"; Windows: Search for "cmd" or "PowerShell").

Type the following command and press Enter:
```
  pwd
```
The output will show the current directory you're in, which might look something like this

```
/Users/YourName
```
This means you're inside the `YourName` folder, located within the Projects folder in your user directory.

Now that you've learned how to find your current directory using pwd, you can continue to the next tasks where you'll learn how to navigate directories, create files, and more. Always remember to use the terminal on your Mac or Windows system for these exercises.

## List - ls
What `ls` does is lists what files and directories are in your current scope. Which right now you are in the runner directory. Go ahead and type `ls` press enter.

Your output should show a batch of folders or directory. For Mac, it'll show:

```
Applications | Documents | Library | Music | Public
Desktop | Downloads | Movies | Pictures 
```

## Change Directory - cd
It is super important to know how to change the directory that you are currently in. This allows you to traverse through the file system.

The syntax for `cd` is to first type the cd command and then type a space and then the directory name you want to move into. Example for Mac Users:

```
cd Desktop
```

This will move you into Desktop. Go ahead and try it yourself. Input the following into the terminal:

```
cd Desktop
```

Then

```
ls
```

This time when the ls command runs it is going to show you what is inside the `Desktop` directory.



Type: `cd ..` then press enter.
Then type `ls` to see the files in your current view(or scope).

## Submission

Make sure you feel comfortable with these commands before moving on. If you have any questions make sure you ask your instructor.

Once you feel comfortable with these commands click the submit button in the top right and move onto the next assignment.
