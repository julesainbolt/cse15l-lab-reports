# Servers and SSH Keys

## Part 1

![Image](Handler.png)

![Image](StringServer.png)

Example 1 of using `/add-message`: 

This is the first time I use `/add-message`.

![Image](add-message1.png)

- The `handleRequest` method from the `URLHandler` interface that
  the `Handler` class implements gets called. 

- The `handleRequest` method accepts a `URI` object as an argument,
  which is the URL that it processes. The fields of the class consist
  of an int variable named `num` initialized to 0, and a string variable
  named `message` initialized to an empty string.  

- The int variable `num` gets incremented whenever a valid string query
  parameter value gets added to the `/add-message` path at the end of the URL.
  The string variable `message` starts out as an empty string, then 
  whenever a valid string query parameter value gets added to
  the `/add-message` path at the end of the URL, that value
  gets added to the `message` string variable.

  In this example, the `message` variable is initialized to an empty string before
  the method is called. After the method is called, `message` is initialized to
  "1. Bonjour!\n\n". The `num` variable is initialized to 0 before the
  method is called. After the method is called, `num` is initialized to 1.  
  

Example 2 of using `/add-message`: 

This is the second time I use `/add-message`.

![Image](add-message2.png)

- The `handleRequest` method from the `URLHandler` interface that
  the `Handler` class implements gets called.

- The `handleRequest` method accepts a `URI` object as an argument,
  which is the URL that it processes. The fields of the class consist
  of an int variable named `num` initialized to 0, and a string variable
  named `message` initialized to an empty string.

- The int variable `num` gets incremented whenever a valid string query
  parameter value gets added to the `/add-message` path at the end of the URL.
  The string variable `message` starts out as an empty string, then 
  whenever a valid string query parameter value gets added to
  the `/add-message` path at the end of the URL, that value
  gets added to the `message` string variable.

  In this example, the `message` variable is initialized to "1. Bonjour!\n\n" before
  the method is called. After the method is called, `message` is initialized to
  "1. Bonjour!\n\n2. Comment ça va?\n\n". The `num` variable is initialized to 1
  before the method is called. After the method is called, `num` is initialized to 2.

## Part 2

## Using the `ls` command

Path to my private key for logging onto `ieng6`: 

![Image](path%20to%20private%20key.png)

Path to my public key for logging onto `ieng6`:

![Image](path%20to%20public%20key.png)

Logging onto `ieng6` without being asked for a password:

![Image](ieng6%20login.png)


## Part 3

In week 2, I learned how to connect to a remote computer or server over the internet
using the `ssh` command. I also learned how to make a simple search engine by 
implementing a web server that tracks a list of strings. 

In week 3, I learned how to securely transfer data over from the local host 
to the remote host by using the `scp` command. 
