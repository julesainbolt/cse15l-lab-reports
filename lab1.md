# Filesystem commands: cd, ls, and cat

## cd - Change Directory

1. Example of command with no arguments: 

![Image](cd%20-%20no%20arguments.png)

- Working Directory: ~/lecture1/messages

- The cd command changed the working directory to the root directory with no arguments specified.
  When I entered in the pwd command, it displayed the new current working directory /home.
  If you don't specify any arguments to the cd command, it must default to the root directory. 

- There's no error indicated. 

2. Example of command with a path to a directory as an argument:

![Image](cd%20-%20path%20to%20directory.png)

- Working Directory: /home

- The cd command changed the working directory to lecture1/messages that I specified as an argument.
  When I entered in the pwd command, it displayed the new current working directory /home/lecture1/messages. 

- There's no error indicated. 


3. Example of command with a path to a file as an argument:

![Image](cd%20-%20path%20to%20file.png)

- Working Directory: ~/lecture1/messages

- The cd command I ran gave me an error on the next line saying, "cd: fr.txt: Not a directory".
  Because I passed in a file as an argument to the cd command, it caused that error to occur. 

- There's an error in the cd command I ran. Because I passed in a file as an argument to the cd command,
  the next line says, "cd: fr.txt: Not a directory", since the argument that's specified should be a directory, not 
  a file.  


## ls - List 

1. Example of command with no arguments:

![Image](ls%20-%20no%20arguments.png)

- Working Directory: ~/lecture1

- The ls command I ran displayed all three files and the messages folder in the current working
  directory with no arguments specified. If you don't specify any arguments,
  it displays all the files and folders in the current working directory. 

- There's no error indicated. 


2. Example of command with a path to a directory as an argument:

![Image](ls%20-%20path%20to%20directory.png)

- Working Directory: /home

- The ls command I ran displayed all the text files in the directory lecture1/messages with 
  the path to that directory passed in as an argument. If you specify a path to a directory as an argument,
  it displays all the files and folders in that directory. 

- There's no error indicated. 


3. Example of command with a path to a file as an argument:

![Image](ls%20-%20path%20to%20file.png)

- Working Directory: ~/lecture1

- When I ran the ls command with the path messages/es-mx.txt as an argument, the output
  displayed the same result as what I entered, messages/es-mx.txt. If you specify a path to a file as an argument,
  it displays the same file path as what you passed in. Because you are only specifying one file,
  it displays only that file or path to that file. 

- There's no error indicated. 


## cat - Concatenate 

1. Example of command with no arguments:

![Image](cat%20-%20no%20arguments.png)

- Working Directory: ~/lecture1/messages

- When I ran the cat command with no arguments specified, the cursor moved to the next line and stopped.
  If you don't specify any arguments, the cat command waits for user input from
  the keyboard until the user presses CTRL + D. 
  

- There's no error indicated. 


2. Example of command with a path to a directory as an argument:

![Image](cat%20-%20path%20to%20directory.png)

- Working Directory: /home

- When I ran the cat command with the path lecture1/messages as an argument, the next line
  displayed a message, "cat: lecture1/messages: Is a directory". If you specify a path to a directory as an   
  argument, you get that message. Because the cat command is used to display the contents of
  one or more files, it only works with files.  

- There's no error indicated, but it shows a message saying, "cat: lecture1/messages: Is a directory".
  This is giving a warning to the user that they are trying to access a directory.


3. Example of command with a path to a file as an argument:

![Image](cat%20-%20path%20to%20file.png)

- Working Directory: ~/lecture1/messages

- When I ran the cat command with the file fr.txt as an argument, the next line
  displayed the contents of that file. If you specify a path to a file as an argument, the
  contents of that file are displayed.   

- There's no error indicated.
