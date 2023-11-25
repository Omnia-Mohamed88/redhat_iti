# lab2

## Create a user account with the following attribute:
![image 1](q1.1.jfif)


## Create a user account with the following attribute
![image 1](q1.2.jfif)

## Create a supplementary (Secondary) group called pgroup with group ID of 30000

![image 1](q3.jfif)

## Create a supplementary group called badgroup

![image 1](q4.jfif)

## Add islam user to the pgroup group as a supplementary group
 
 ![image 1](q5.jfif)

 ## Modify the password of islam's account to password

 ![image 1](q6.jfif)

 ## Modify islam's account so the password expires after 30 days

  ![image 1](q7.jfif)

  ## Lock bad user account so he can't log in

![image 1](q8.jfif)

## Delete bad user account

![image 1](q9.jfif)

## Delete the supplementary group called badgroup.

![image 1](q10.jfif)

## Create a folder called myteam in your home directory and change its permissions to read only for the owner.

![image 1](q13.jfif)

## Log out and log in by another user

![image 1](q14.jfif)

## Try to access (by cd command) the folder (myteam)

![image 1](q15.1.jfif)

![image 1](q15.2.jfif)



## Using the command Line

Change the permissions of oldpasswd file to give owner read and write
permissions and for group write and execute and execute only for the others
(using chmod in 2 different ways)

![image 1](q16.1.jfif)

Change your default permissions to be as above.

![image 1](q16.2.jfif)

### What is the maximum permission a file can have, by default when it is just created? And what is that for directory.

-By default, when a file is created, it has a maximum permission of rw-rw-rw- (666), and for a directory, it is rwxrwxrwx (777).

Change your default permissions to be no permission to everyone then create a
directory and a file to verify.

![image 1](q16.4.jfif)


## What are the minimum permission needed for:

### Copy a directory (permission for source directory and permissions for target
parent directory)

-To copy a directory, the minimum permissions needed are:

Source Directory: Read permission (r) is required for the source directory to list its contents.

Target Parent Directory: Write permission (w) is required for the target parent directory to create a new directory entry (copy).


### Copy a file (permission for source file and and permission for target parent directory)

To copy a file, the minimum permissions needed are:

Source File: Read permission (r) is required for the source file to read its contents.

Target Parent Directory: Write permission (w) is required for the target parent directory to create a new file entry (copy).

### Delete a file
To delete a file, the minimum permission needed is Write (w) permission on the directory containing the file.

### Change to a directory

To change (or navigate) to a directory, the minimum permissions needed are Execute (x) permission on the directory.

### List a directory content (ls command)

To list the contents of a directory using the ls command, you need Read (r) and Execute (x) permissions on the directory

### View a file content (more/cat command)

To view the contents of a file using the more or cat command, you need Read (r) permission on the file

### Modify a file content

To modify the content of a file, you need Write (w) permission on the file.


## Create a file with permission 444. Try to edit in it and to remove it? Note what happened.

![image 1](q18.jfif)


![image 1](q18.2.jfif)

![image 1](q18.3.jfif)

## What is the difference between the “x” permission for a file and for a directory?

for files, execute permission enables the execution of the file, while for directories, execute permission enables access to the contents of the directory.















