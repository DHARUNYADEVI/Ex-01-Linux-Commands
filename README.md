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

<img width="922" height="86" alt="Screenshot 2025-08-25 223721" src="https://github.com/user-attachments/assets/89c6b4ee-c3bd-46f2-8eef-bc823d25d2e8" />


### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd

<img width="228" height="62" alt="Screenshot 2025-08-25 223740" src="https://github.com/user-attachments/assets/d09d612d-5610-450f-a885-8fa66a24866a" />

 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>

<img width="268" height="47" alt="Screenshot 2025-08-25 223814" src="https://github.com/user-attachments/assets/92ce1364-c2c3-46f1-ae3f-0775967bc305" />


### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>


<img width="265" height="44" alt="Screenshot 2025-08-25 223842" src="https://github.com/user-attachments/assets/854c743e-bd4f-4da1-a86b-b64cd753bec3" />


### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>

<img width="401" height="111" alt="Screenshot 2025-08-25 223907" src="https://github.com/user-attachments/assets/360e1667-9550-4a5f-a643-46cfcf4ffc62" />


### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

<img width="300" height="50" alt="Screenshot 2025-08-25 224105" src="https://github.com/user-attachments/assets/91417f0f-0671-4f5d-be67-95f8d982fa05" />
<img width="306" height="57" alt="Screenshot 2025-08-25 224114" src="https://github.com/user-attachments/assets/ebe089b6-6050-4e87-9847-e2509c3414e5" />

 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>


<img width="318" height="92" alt="Screenshot 2025-08-25 224208" src="https://github.com/user-attachments/assets/f1477b91-241f-499f-abbe-b8bef1541a44" />

### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name


<img width="348" height="49" alt="Screenshot 2025-08-25 224414" src="https://github.com/user-attachments/assets/168f2842-3f78-4bf4-a5ed-8da2a49a5ea0" />

### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>

<img width="389" height="56" alt="Screenshot 2025-08-25 224506" src="https://github.com/user-attachments/assets/e31f6be0-5d2e-4906-bf0f-35ba501d8377" />


### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>


 <img width="363" height="48" alt="Screenshot 2025-08-25 224539" src="https://github.com/user-attachments/assets/0bd15a64-1a33-4309-ab3a-be19a083028f" />

## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

<img width="859" height="182" alt="image" src="https://github.com/user-attachments/assets/5ccbc288-7919-4c95-9ae0-415d565c2648" />


### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>

<img width="260" height="199" alt="Screenshot 2025-08-28 102507" src="https://github.com/user-attachments/assets/3231ca1a-a9a2-4655-8cff-70b0ababfa7d" />


### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>

<img width="360" height="197" alt="Screenshot 2025-08-28 102551" src="https://github.com/user-attachments/assets/3ecba70f-9d6c-4d25-9bfb-01150f482986" />

 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

<img width="936" height="116" alt="Screenshot 2025-08-28 102605" src="https://github.com/user-attachments/assets/34dd0b51-4086-4e8d-9abb-af55e9edb726" />


### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>

<img width="267" height="69" alt="Screenshot 2025-08-28 102651" src="https://github.com/user-attachments/assets/6e205fe0-5328-4cf7-a154-ac24bb2ed45a" />


### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

<img width="313" height="214" alt="Screenshot 2025-08-28 102728" src="https://github.com/user-attachments/assets/a3c9f542-25dd-4703-b1a4-9e0376b0ec58" />


### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>

<img width="421" height="118" alt="Screenshot 2025-08-28 102812" src="https://github.com/user-attachments/assets/97c8ac9a-30dd-4068-a497-f76784d6aca0" />


### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]
$ tar xvzf file.tar *.c

<img width="314" height="147" alt="Screenshot 2025-08-28 102850" src="https://github.com/user-attachments/assets/2bc51b9e-65af-45ea-809a-a2043718807c" />

 
### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name


<img width="320" height="47" alt="Screenshot 2025-08-28 103005" src="https://github.com/user-attachments/assets/225c0539-319c-43ef-bd9a-ee9942a26e54" />

### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….

<img width="805" height="87" alt="image" src="https://github.com/user-attachments/assets/310a46a0-2f52-47c0-ae9e-ebae0027dc36" />


### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]


<img width="722" height="105" alt="Screenshot 2025-08-28 103044" src="https://github.com/user-attachments/assets/7fedc200-77d5-4261-a651-d4e11bc9fe34" />

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder
 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>

<img width="834" height="72" alt="image" src="https://github.com/user-attachments/assets/958013f7-8e4d-4c34-bb5f-88a4473ef2ee" />


### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..

<img width="827" height="159" alt="Screenshot 2025-08-28 103627" src="https://github.com/user-attachments/assets/aa371a3e-e873-4783-a33c-749c768343f7" />


### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>

<img width="344" height="127" alt="Screenshot 2025-08-28 103846" src="https://github.com/user-attachments/assets/d918d03d-7ee3-4ff8-9dbf-f8a0a6bda067" />

 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal
<img width="802" height="144" alt="image" src="https://github.com/user-attachments/assets/f3074491-0ec0-4c36-be20-3a585666da01" />


### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear

<img width="385" height="110" alt="Screenshot 2025-08-28 104534" src="https://github.com/user-attachments/assets/c61b6e2e-bf4e-4844-a00e-e78cb64b7f03" />

### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>

<img width="438" height="97" alt="Screenshot 2025-08-28 104648" src="https://github.com/user-attachments/assets/cd2d5dc3-0402-4fd6-a7c0-76ae37ca2f53" />

### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df

<img width="796" height="217" alt="Screenshot 2025-08-28 104703" src="https://github.com/user-attachments/assets/b3ba3e6f-3d0c-4940-813f-767a0c66dd45" />


### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”


<img width="468" height="522" alt="Screenshot 2025-08-28 104954" src="https://github.com/user-attachments/assets/2f512871-229f-41b1-8374-015df4e21e2e" />

## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.
