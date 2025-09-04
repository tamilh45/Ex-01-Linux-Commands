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
<img width="904" height="66" alt="Screenshot 2025-08-28 102832" src="https://github.com/user-attachments/assets/74605c0d-055d-4600-baeb-f75a836ea694" />


### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd

 <img width="203" height="60" alt="Screenshot 2025-08-28 102842" src="https://github.com/user-attachments/assets/84e59a2c-1029-43d9-9047-6424ff820500" />

### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>
<img width="324" height="65" alt="Screenshot 2025-08-28 102900" src="https://github.com/user-attachments/assets/fab83328-aa10-456a-b00b-9270a5f1e497" />


### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>

<img width="294" height="70" alt="Screenshot 2025-08-28 102912" src="https://github.com/user-attachments/assets/d21427c8-e353-4e68-bfb3-f276d7244c86" />

### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>

<img width="359" height="97" alt="Screenshot 2025-08-28 102931" src="https://github.com/user-attachments/assets/3cca5759-3fe0-4815-9510-a3e609797598" />

### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..
<img width="773" height="214" alt="Screenshot 2025-08-28 103044" src="https://github.com/user-attachments/assets/5b2e96b8-e4e7-4f6b-8008-6849a8c6c017" />

 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>



### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name


### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>


### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>

 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

<img width="513" height="277" alt="image" src="https://github.com/user-attachments/assets/02b93b88-bf37-487e-9ea8-028741c7b0e3" />

### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>

<img width="866" height="204" alt="Screenshot 2025-08-28 103307" src="https://github.com/user-attachments/assets/5ab2a246-ebc6-4a96-b0fd-56a76e3ac4c4" />

### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>
<img width="528" height="140" alt="Screenshot 2025-08-28 103202" src="https://github.com/user-attachments/assets/5ac07f94-1e1d-4c3b-a3bf-3741b8c7867c" />

 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id
<img width="615" height="97" alt="Screenshot 2025-08-28 103836" src="https://github.com/user-attachments/assets/a184bd03-72fa-47b1-9362-6f6c11e3d297" />


### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>


### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

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

### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….


### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder
 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>

<img width="905" height="440" alt="image" src="https://github.com/user-attachments/assets/88b19a21-6f10-4e05-a2fb-e1953c2693b1" />

### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..


### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>

 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal
<img width="362" height="162" alt="Screenshot 2025-08-28 103649" src="https://github.com/user-attachments/assets/e5161df3-9534-4c86-a01e-aee1c06d5c11" />


### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear


### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>

### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df
<img width="743" height="199" alt="image" src="https://github.com/user-attachments/assets/86c5903c-df3a-4a30-98df-8fde35b5344d" />


### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”

<img width="597" height="117" alt="image" src="https://github.com/user-attachments/assets/a62c60fd-5920-4ba0-a9f3-da86c76c8b06" />


## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
