# Ex-01-Linux-Commands


## Aim:

To study the execution of various Linux operating system commands.

## Linux:

Linux is an open-source operating system. The kernel is the heart of Linux OS which
 
helps the communication between hardware and software. The main advantage of Linux was that programmers can use Linux kernel to design their own custom OS.

Linux Commands:
All basic and advanced tasks can be done by executing commands. The commands are executed on Linux terminal. Linux commands are case sensitive.


## Commands:

### 1)	ls Command

The ls command is used to display a list of content of a directory.

 Syntax: ls

![image](https://github.com/chgeethika/Ex-01-Linux-Commands/assets/142209368/b02e05b1-7bf9-4544-997c-9a331f4bf3f8)


 


### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd

![image](https://github.com/chgeethika/Ex-01-Linux-Commands/assets/142209368/e6810f61-5784-41f3-8cdc-cd7a14170061)


 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>

![image](https://github.com/chgeethika/Ex-01-Linux-Commands/assets/142209368/5f5a547e-d864-4a84-ac50-05a811419bd1)


### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>

![image](https://github.com/chgeethika/Ex-01-Linux-Commands/assets/142209368/9d06854d-b3ac-4323-9a8b-0f482166c806)



### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>

![image](https://github.com/chgeethika/Ex-01-Linux-Commands/assets/142209368/74ad8d30-6a48-4f27-a70d-2f6a971458e8)



### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

![image](https://github.com/chgeethika/Ex-01-Linux-Commands/assets/142209368/e2a0a602-ff9d-4200-bf27-e0acce74ae6d)


 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>

![image](https://github.com/chgeethika/Ex-01-Linux-Commands/assets/142209368/d6fea08f-29fc-4687-9a7d-e5e37e559006)




### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

![image](https://github.com/chgeethika/Ex-01-Linux-Commands/assets/142209368/3079f7bc-c2f6-4e8f-83ca-2acf4b422ddb)



### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>

![image](https://github.com/chgeethika/Ex-01-Linux-Commands/assets/142209368/d068a549-c8b8-4b02-b740-4ca81851e906)



### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>

![image](https://github.com/chgeethika/Ex-01-Linux-Commands/assets/142209368/192b6bb6-be17-4a7b-849b-1f9894c745ba)


 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

![image](https://github.com/chgeethika/Ex-01-Linux-Commands/assets/142209368/f207f7cb-e8a4-4dcb-b6ed-f0f1a2ad0ad5)



### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>

![image](https://github.com/chgeethika/Ex-01-Linux-Commands/assets/142209368/c191a4f9-914b-40e5-951a-174897ec9a97)



### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>

![image](https://github.com/chgeethika/Ex-01-Linux-Commands/assets/142209368/2a32cf0b-fb8a-478b-a641-d2a66e282c91)


 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

![image](https://github.com/chgeethika/Ex-01-Linux-Commands/assets/142209368/253da810-9f3b-4604-a549-7f3aaf651d5b)



### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>

![image](https://github.com/chgeethika/Ex-01-Linux-Commands/assets/142209368/bb694ca5-e858-45ee-b867-846111b1eb21)



### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

![image](https://github.com/chgeethika/Ex-01-Linux-Commands/assets/142209368/217b8899-8c89-453a-9aea-4f91f0e72c9b)


### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>

### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c
 
### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name

![image](https://github.com/chgeethika/Ex-01-Linux-Commands/assets/142209368/636ce74c-7179-4fcc-9788-18353e63e93b)


### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….

![image](https://github.com/chgeethika/Ex-01-Linux-Commands/assets/142209368/ede4a8d7-55c6-4fc2-9b8a-c4e91a172983)



### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

![image](https://github.com/chgeethika/Ex-01-Linux-Commands/assets/142209368/23f51cce-de8c-4712-985e-8aed68513d53)


### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder
 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>


![image](https://github.com/chgeethika/Ex-01-Linux-Commands/assets/142209368/c5ed397e-a60b-4db6-884a-62327d44037c)



### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..


![image](https://github.com/chgeethika/Ex-01-Linux-Commands/assets/142209368/18cf7757-058a-4374-94c9-d6686212acf6)



### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>


![image](https://github.com/chgeethika/Ex-01-Linux-Commands/assets/142209368/c1271f3a-2b69-4230-83e4-e6d0a67e17c5)


 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal


![image](https://github.com/chgeethika/Ex-01-Linux-Commands/assets/142209368/11a91b13-f0fd-4a9d-ba63-fd4c7af709f5)



### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear


![image](https://github.com/chgeethika/Ex-01-Linux-Commands/assets/142209368/4dd1d8fd-439b-4b39-877b-05dd8ca69259)



### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>


![image](https://github.com/chgeethika/Ex-01-Linux-Commands/assets/142209368/77bd42a7-f537-4f15-ba66-1012c61996c8)


 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df


![image](https://github.com/chgeethika/Ex-01-Linux-Commands/assets/142209368/6ab1fb5b-2398-4502-a82b-82aeb5543070)







### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”





















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
