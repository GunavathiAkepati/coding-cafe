1. What did `pwd` print?  
- pwd printed `/Users/gunavathiakepati` ,which is my present working directory.  

2. What did `ls -a` show that plain `ls` did not?  
- It `showed the hidden files and folders` which is not shown by plain ls.

3. Pick one line from `ls -l`. What do you think the first column means?  
- The first column (Example: `drwxr-xr-x`) shows `the file or folder type and its permissions`.It tells us who can read, write or access the fileor folder. 

4. Why does that work from where you are standing? Which kind of path is `coding-cafe/week02`? Absolute or Relative?
- It works because I am standing in the `parent directory` that contains the coding-cafe folder. is a `relative path` because it starts from my current loction, not from root directory.

5. `mv` did two different jobs above. What were they?
- `mv` was used `to move a file from one folder to another`, and then it was used to `rename the file`.

6. How many folders are on your `PATH`? (They are separated by :)
- 10 folders

7. Write down exactly where your `python3` lives.
- My python3 lives at `/usr/local/bin/python3`.

8. Compare your answer to 7 with the person next to you. Are they the same? If not, why might that be?
- `No, they are not the same`.`Python can be inastalled in different locations on different computrs`,so the location of `python3` can be different.Their `PATH` settings may also be different.

9. What exactly did the shell say? Explain the error in your own words, using the word `PATH`.
- The shell said: `zsh: command not found: pyton3` .
This means `the shell could not find a command called pyton3 in any of the folders listed in my PATH`. 


10. `.venv` did not appear with plain `ls`. Why not?
- .venv did not appear with plain ls because it is a hidden folder. Plain ls does not show hidden files or folders. ls -a shows them.

11. What changed about your prompt?
- My prompt changed by showing `(.venv)` at the beginning. This indicates that the virtual environment is activated.

12. Run which python3,
Compare this with what you wrote down for question 7. Is it the same path? If not, what does that tell you about what `activate` actually did to your `PATH`?
- `No, the paths are different`. This tells me that `activate changed my PATH` so that the virtual environment's Python is found first.

13. What is in the second list that was not in the first?
- The second list contains `requests` and its dependencies: `certifi, charset-normalizer, idna, and urllib3`. These were not in the first list.

14. Where does `python3` point now?
- After deactivating the virtual environment, python3 points back to `/usr/local/bin/python3`.

15. Find what ls -h does. Write it in your own words.
- ls -h displays file sizes in a human-readable format, such as KB, MB, or GB, instead of showing the sizes only in bytes.

16. What is the difference between what Ctrl + C and Ctrl + D did?
- Ctrl + C: interrupt/stop and
Ctrl + D: end input / exit the current interactive session







