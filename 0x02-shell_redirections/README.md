# Shell, I/O Redirections and filters
---

1. Hello World 
 **0-hello_world**
Script that prints “Hello, World”, followed by a new line to the standard output

2. Confused smiley
**1-confused_smiley**
Script that displays a confused smiley "(Ôo)'

3. Let's display a file
**2-hellofile**
Display the content of the /etc/passwd file.

4. What about 2?
**3-twofiles**
Display the content of /etc/passwd and /etc/hosts

5. Last lines of a file
**4-lastlines**
Display the last 10 lines of /etc/passwd

6. I'd prefer the first ones actually
**5-firstlines**
 Display the first 10 lines of /etc/passwd

7. Line #2
**6-third_line**
script that displays the third line of the file iacta

8. It is a good file that cuts iron without making a noise. 
**7-file**
shell script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.

9. Save current state of directory
**8-cwd_state**
script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.

10. Duplicate last line
**Duplicate last line**
script that duplicates the last line of the file iacta

11.  No more javascript
**10-no_more_js**
script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.

12. Don't just count your directories, make your directories count
**11-directories**
script that counts the number of directories and sub-directories in the current directory.
-The current and parent directories should not be taken into account
-Hidden directories should be counted

13. What’s new
**12-newest_files**
script that displays the 10 newest files in the current directory.

14. Being unique is better than being perfect
**13-unique**
script that takes a list of words as input and prints only words that appear exactly once.
-Input format: One line, one word
-Output format: One line, one word
-Words should be sorted

15. It must be in that file
**14-findthatword**
Display lines containing the pattern “root” from the file /etc/passwd

16. Count that word
**15-countthatword**
Display the number of lines that contain the pattern “bin” in the file /etc/passwd

17. What's next?
**16-whatsnext**
Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.

18.  I hate bins
**17-hidethisword**
Display all the lines in the file /etc/passwd that do not contain the pattern “bin”.

19. Letters only please
**18-letteronly**
Display all lines of the file /etc/ssh/sshd_config starting with a letter.
-include capital letters as well

20.  A to Z
**19-AZ**
Replace all characters A and c from input to Z and e respectively.

21. Without C, you would live in hiago
**20-hiago**
Create a script that removes all letters c and C from input.

22. esreveR
**21-reverse**
script that reverse its input.

23.  DJ Cut Killer
**22-users_and_homes**
script that displays all users and their home directories, sorted by users.
-Based on the the /etc/passwd file

24. Empty casks make the most noise
**100-empty_casks**
 a command that finds all empty files and directories in the current directory and all sub-directories.
-Only the names of the files and directories should be displayed (not the entire path)
-Hidden files should be listed
-One file name per line
-The listing should end with a new line

25. A gif is worth ten thousand words
**101-gifs**
script that lists all the files with a .gif extension in the current directory and all its sub-directories.
-Hidden files should be listed
-Only regular files (not directories) should be listed
-The names of the files should be displayed without their extensions
-The files should be sorted by byte values, but case-insensitive (file aaa should be listed before file bbb, file .b should be listed before file a, and file Rona should be listed after file jay)
-One file name per line
-The listing should end with a new line

26. Acrostic
**102-acrostic**
script that decodes acrostics that use the first letter of each line
-The ‘decoded’ message has to end with a new line

27. The biggest fan
**103-the_biggest_fan**
script that parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests.
-Order by number of requests, most active host or IP at the top
