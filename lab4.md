# Lab Report 4 - Vim 


## Timing Tasks

Log into ieng6

   ![ieng6 Login](ieng6%20login.png)

Keys pressed: `<up>`, `<enter>`

The `ssh` command connects to a remote computer or server over the internet. 
After I pressed `<enter>`, it prompted me for a password, and so I copied 
and pasted my password after the prompt. I pressed `<enter>` and I was able to 
login to ieng6, the school server, using the `ssh` command. 


Clone your fork of the repository from your Github account (using the SSH URL)

   ![ssh clone](ssh%20clone.png)

Keys pressed: `git clone`, command `v` to paste in the `ssh` url, and `<enter>` 
 
I typed in the command `git clone` and copied the `ssh` url from GitHub 
and pasted it onto the terminal after the `git clone` command. Then I pressed `<enter>` 
and it cloned or downloaded the repository on the ieng6 server. 

Run the tests, demonstrating that they fail

   ![run tests - fail](run%20tests%20-%20fail.png)

Keys pressed: `cd directory name` , `<enter>`, `bash file name`, `<enter>`

I typed in the `cd` command to change the working directory to 
the *lab7-final* repository and pressed `<enter>`. Then I typed in the `bash` 
command and the name of the shell script file *test.sh* and pressed `<enter>`.
After I pressed `<enter>`, it ran the commands in the shell script file, which 
compiled all the Java files and ran the JUnit tests. This was the output of 
running the JUnit tests where one of the tests failed. 

Edit the code file to fix the failing test

   ![failing test fix](failing%20test%20fix.png)

Keys pressed: `vim file name`, `j`, `l`, `i`, `<backspace>`,
`2`, `:wq`, `<enter>`

I typed in the `cd` command to change the working directory to 
the *lab7-final* repository and pressed `<enter>`. Then I typed in the `bash` 
command and the name of the shell script file *test.sh* and pressed `<enter>`.

Run the tests, demonstrating that they now succeed

   ![run tests - pass](run%20tests%20-%20pass.png)

Keys pressed: `<up>`, `<up>`, `<up>`, `<enter>`, The `bash test.sh` command was 3 up 
in the search history, so I used the up arrow key to access and run it.

After I pressed `<enter>`, it ran the commands in the shell script 
file, which compiled all the Java files and ran the JUnit tests. This was the output of 
running the JUnit tests, which was successful.


Commit and push the resulting change to your Github account

   ![commit and push](commit%20and%20push.png)

Keys pressed: `git status`, `<enter>`, `git add file name`, `<enter>`, 
`git status`, `git commit -m commit message`, `git push`





   
