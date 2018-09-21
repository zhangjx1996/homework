# Homework \# 3
*git and git servers*

## Problem 1
1. Create a directory and name it `whereintheworldishash`.
2. Move into this directory and initialize a git repo.
3. Create a bash shell script and name it printcap3.sh that:  
- Takes 1 argument
- Checks if the argument is a directory
    - If the argument is a directory, store the names of all files in that directory in a variable.
    - Print out the contents of this variable replacing all captial letters with 3 of the same capital letters.
- If the argument is not a directory print out 'Not a directory' send this result to standard error.
4. Save this file in our project folder.
5. Do the `local git workflow` to get this first file in a commit.
6. Modify printcap3.sh so that if the argument is not a directory it will create a file called printcap3_error.log and
redirect the message to this file instead of standard error.
7. Do the `local git workflow` to get these changes into a commit.
8. Add a new file in our project called `README.md`.
9. Add some information in here and be sure to use three different types of headings.
10. Add this new file to the commit.
11. Let's pretend we didn't want to do steps 6-10. Issue a git command that resets the HEAD commit to this place in history.


## Problem 2
1. Archive and compress all material in the directory `whereintheworldishash`.

## Problem 3
1. Go to the repository https://github.com/bios821-2018/homework and submit an issue under this repo where you assert
"My name is <fill in your real name here>."
2. Fork this repo and clone your fork using ssh.
3. Within this new project (i.e. `homework` folder), create a new branch and name it after your github username.
4. Within the project folder `homework/homework3` modify the README.md file so that you tell me the command you used in Problem 3 step 1
to clone your fork of the repo.
5. Commit this change of README.md to your specific branch.
6. Within your branch (i.e. your user name) add the archived compressed file that you created in Problem 1 and save it
in `homework/homework3`.
7. Commit this change.
8. Push these changes to your fork.
9. Submit a pull request that asks to incorporate your branch into bios821/homework repo with a branch of the same name (i.e.
your githubuser name).
