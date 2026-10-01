1. What did `pwd` print?
Ans - It prints the path of the present working directory. It prints 'Users/arihantmaity'.

2. What did `ls -a` show that plain `ls` did not?
Ans - It shows additional hidden folders along with the current folders and files in the current directory.

3. Pick one line from `ls -l`. What do you think the first column means?
Ans - The first column represents the type of file and the access permissions for the users.

4. Why does that work from where you are standing? Which kind of path is `coding-cafe/week02`? Absolute or Relative?
Ans - This path is relative and it lists all the files and folders in the given path. This works because we provide the path to which we want to make our modifications based on our current path to the terminal.

5. `mv` did two different jobs above. What were they?
Ans - 'mv' moved the file into the specified folder. It also is used to rename a file.

6. How many folders are on your `PATH`? (They are separated by `:`)
Ans - 10

7. **Write down exactly where your `python3` lives.** You will need this again in a minute.
Ans - '/bin/ls'

8. Compare your answer to 7 with the person next to you. Are they the same? If not, why might that be?
Ans - No the answer is not same, as they have a different opearating system and file path to where the tool 'ls' is stored.

9. What exactly did the shell say? Explain the error in your own words, using the word **PATH**.
Ans - "zsh: command not found: pyton3". The shell searched for every file in our PATH and couldnt find it thus giving us an error.

10. `.venv` did not appear with plain `ls`. Why not? (Refer back to section 1.)
Ans - This is because plain 'ls' lists the files and folders in the current directory. However 'ls -a' also lists the hidden files and folders in the directory. Thus '.venv' did not appear with plain 'ls'.

11. What changed about your prompt?
Ans - We see a (.venv) in front of the path name, indicating that the folder is linked with that particular version of python.

12. Compare this with what you wrote down for question 7. Is it the same path? If not, what does that tell
    you about what `activate` actually did to your `PATH`?
Ans- '/Users/arihantmaity/Documents/Arihant Maity/Plaksha/Year 1/Sem1/coding-cafe/.venv/bin/python3' this is the result which is different from that in Q7, this tells us that the version of python is activated and linked with that particular path.

13. What is in the second list that was not in the first?
Ans - In the first list the only package installed was pip, however in the second list there were additional packages installed such as certifi, charset-normalizer, idna, requests and urllib3.

14. Where does `python3` point now?
Ans - 'python3' points now to its original place which is '/Library/Frameworks/Python.framework/Versions/3.13/bin/python3' rather than the path we had linked it with earlier (i.e. coding-cafe).

15. Find what `ls -h` does. Write it in your own words.
Ans - It tells us the file size in an easy to read form. Suffixed with B,K,M etc.

16. What is the difference between what Ctrl + C and Ctrl + D did?
Ans - 'Ctrl + C' - it interrupts whatever python is currently doing, example it exits out of an infinite loop and gives output as KeyboardInterrupt.
'Ctrl + D' - it stops the python program and exits back into the terminal.




