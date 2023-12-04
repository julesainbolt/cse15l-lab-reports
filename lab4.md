# Lab Report 4 - Vim 


## Timing Tasks

Log into ieng6

   ![ieng6 Login](ieng6%20login.png)

Keys pressed: `<up>`, `<enter>` The `ssh cs15lfa23si@ieng6.ucsd.edu` command was 1 up 
in the search history, so I used the up arrow key to access and run it.

The `ssh` command connects to a remote computer or server over the internet. 
After I pressed `<enter>`, it prompted me for a password, and so I copied 
and pasted my password after the prompt. I pressed `<enter>` and I was able to 
login to ieng6, the school server, using the `ssh` command. 


Clone your fork of the repository from your Github account (using the SSH URL)

   ![ssh clone](ssh%20clone.png)

Keys pressed: `git clone`, `<command V>`, `<enter>` 
 
I typed in the command `git clone` and copied the `git@github.com:julesainbolt/lab7.git` 
`ssh` url from GitHub and pasted it onto the terminal after the `git clone` command using `<command V>`. 
Then I pressed `<enter>` and it cloned or downloaded the repository on the ieng6 server. 

Run the tests, demonstrating that they fail

   ![run tests - fail](run%20tests%20-%20fail.png)

Keys pressed: `cd lab7` , `<enter>`, `bash test.sh`, `<enter>`

I typed in the `cd` command to change the working directory to 
the *lab7* repository and pressed `<enter>`. Then I typed in the `bash` 
command and the name of the shell script file *test.sh* and pressed `<enter>`.
After I pressed `<enter>`, it ran the commands in the shell script file, which 
compiled all the Java files and ran the JUnit tests. This was the output of 
running the JUnit tests where one of the tests failed. 

Edit the code file to fix the failing test

   ![failing test fix](failing%20test%20fix.png)

Keys pressed: `vim ListExamples.java`, `j`, `j`, `j`, `j`, `j`, `j`, `j`, `j`, 
`j`, `j`, `j`, `j`, `j`, `j`, `j`, `j`, `j`, `j`, `j`, `j`, `j`, `j`, `j`,
`j`, `j`, `j`, `j`, `j`, `j`, `j`, `j`, `j`, `j`, `j`, `j`, `j`, `j`, `j`, 
`j`, `j`, `j`, `j`, `j`, `l`, `l`, `l`, `l`, `l`, `l`, `l`, `l`, `l`, `l`, 
`l`, `l`, `i`, `<backspace>`,
`2`, `<Esc>`, `:wq`, `<enter>`

I typed in the `vim` command and the ListExamples.java file and pressed `<enter>`. 
After I pressed `<enter>`, the screen on the terminal changed and went into the Java file. 
I pressed on the `j` key 43 times to move the cursor down to the line of code that I want to edit, 
which was `index1 += 1;`. Then I pressed on the `l` key 12 times to move the cursor to the right 
on the line of code. Then I pressed on the `i` key to enter Insert Mode in vim, so I can edit 
and change the text. I lined up the cursor after the 1 on the space and pressed `<backspace>` 
to delete it and changed it with the number 2. Then I typed `:wq` to save my changes that I made 
to the file and closed the editor. When I typed the colon, I noticed that the cursor moved down 
to the bottom of the terminal. After I pressed `<enter>`, the screen on the terminal reverted back to 
its original state on the command line. 


Run the tests, demonstrating that they now succeed

   ![run tests - pass](run%20tests%20-%20pass.png)

Keys pressed: `<up>`, `<up>`, `<up>`, `<enter>`, The `bash test.sh` command was 3 up 
in the search history, so I used the up arrow key to access and run it.

After I pressed `<enter>`, it ran the commands in the shell script 
file, which compiled all the Java files and ran the JUnit tests. This was the output of 
running the JUnit tests, which was successful.


Commit and push the resulting change to your Github account

   ![commit and push](commit%20and%20push.png)

Keys pressed: `git status`, `<enter>`, `git add ListExamples.java`, `<enter>`, 
`git status`, `<enter>`, `git commit -m "Update ListExamples.java"`, `<enter>`, 
`git push`, `<enter>`


I typed in the `git status` command to check the status of the 
commit. Then I pressed `<enter>` and it displayed information 
about the file I modified and what commands I could run and 
a message about not staging the file yet. I then typed 
`git add` and ListExamples.java, which 
adds that file to the set of committed changes. Then I 
pressed `<enter>` and typed `git status` again to check the
status of the commit and pressed `<enter>`. After pressing 
`<enter>`, it displayed similar information as before, except that 
a new message about the set of changes is ready to be committed. 
I then typed `git commit -m` followed by the commit message, 
"Update ListExamples.java", which updates the local repository 
with the changes made to the files. After pressing `<enter>`, it 
displays the commit message, the name of the committer, so my name, the 
email address of the committer, some info, and a message saying that one file 
has been changed with one insertion and one deletion. I then typed 
`git push`, which uploads the changes made in the local repository 
to GitHub. After pressing `<enter>`, it displayed a bunch of messages 
and one final message indicating that it pushed the changes to GitHub.


