# Filesystem commands: cd, ls, and cat

## cd - Change Directory

1. Example of command with no arguments: 

![Image](https://github.com/julesainbolt/cse15l-lab-reports/blob/65ca78a6487797221cb83932670d78b9c4ec8a3c/cd%20-%20no%20arguments.png)

- Working Directory: ~/lecture1/messages

- The cd command changed the working directory to the root directory with no arguments specified.
  When I entered in the pwd command, it displayed the new current working directory /home.
  If you don't specify any arguments to the cd command, it must default to the root directory. 

- There's no error. 

2. Example of command with a path to a directory as an argument:

![Image](https://github.com/julesainbolt/cse15l-lab-reports/blob/65ca78a6487797221cb83932670d78b9c4ec8a3c/cd%20-%20path%20to%20directory.png)

- Working Directory: /home

- The cd command changed the working directory to lecture1/messages that I specified as an argument.
  When I entered in the pwd command, it displayed the new current working directory /home/lecture1/messages. 

- There's no error. 


3. Example of command with a path to a file as an argument:

![Image](https://github.com/julesainbolt/cse15l-lab-reports/blob/65ca78a6487797221cb83932670d78b9c4ec8a3c/cd%20-%20path%20to%20file.png)

- Working Directory: ~/lecture1/messages

- The cd command I ran gave me an error on the next line saying that cd: fr.txt: Not a directory.
  Because I passed in a file as an argument to the cd command, it caused that error to occur. 

- There's an error in the cd command I ran. Because I passed in a file as an argument to the cd command,
  the next line says cd: fr.txt: Not a directory, since the argument that's specified should be a directory, not a file.  


## ls - List 

1. Example of command with no arguments:

![Image](https://github.com/julesainbolt/cse15l-lab-reports/blob/65ca78a6487797221cb83932670d78b9c4ec8a3c/ls%20-%20no%20arguments.png)

- Working Directory: ~/lecture1/messages

- The cd command I ran gave me an error on the next line saying that cd: fr.txt: Not a directory.
  Because I passed in a file as an argument to the cd command, it caused that error to occur. 

- There's an error in the cd command I ran. Because I passed in a file as an argument to the cd command,
  the next line says cd: fr.txt: Not a directory, since the argument that's specified should be a directory, not a file. 



2. Example of command with a path to a directory as an argument:



3. Example of command with a path to a file as an argument:




## cat - Concatenate 

1. Example of command with no arguments:



2. Example of command with a path to a directory as an argument:



3. Example of command with a path to a file as an argument:


