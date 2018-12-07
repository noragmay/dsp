# Learn command line

Please follow and complete the free online [Bash Scripting Tutorial](https://ryanstutorials.net/bash-scripting-tutorial/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. You should be able to go through these in a couple of hours.

**Note:** Bash is not installed on a PC. Rather, PC users must install Cygwin. Once Cygwin has been installed, the command line interface witll _emulate_ bash. You can find all information regarding Cygwin [here](https://www.cygwin.com/).

---

### Q1.  Cheat Sheet of Commands  

Here's a list of items with which you should be familiar:  
* show current working directory path
* creating a directory
* deleting a directory
* creating a file using `touch` command
* deleting a file
* renaming a file
* listing hidden files
* copying a file from one directory to another

Make a cheat sheet for yourself: a list of at least **ten** commands and what they do.  (Use the 8 items above and add a couple of your own.)  

> > * `pwd` : show current working directory path
> > * `ls` : list contents of the directory
> > * `cd` : change directory
> > * `mkdir` : create a directory
> > * `touch` : create a file in working
> > * `rm` : remove a file
> > * `rmdir` : remove an empty directory
> > * `rm -R` : remove a directory and all files inside
> > * `..` : go up one directory
> > * `ren` : rename a file or directory
> > * `cp` : copy a file from source to destination
> > * `ls -a` : list all contents including hidden files

---

### Q2.  List Files in Unix   

What do the following commands do:  
`ls`  
`ls -a`  
`ls -l`  
`ls -lh`  
`ls -lah`  
`ls -t`  
`ls -Glp`  

> > * `ls` : list contents of the directory
> > * `ls -a` : list including hidden files beginning with .
> > * `ls -l` : 	list with long format - show permissions
> > * `ls -lh` : list long format with readable file size 
> > * `ls -lah` : list long format including hidden files beginning with .
> > * `ls -t` : list sort by time & date
> > * `ls -Glp` : don't print group names, show append / indicator to directories

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> > * `ls -U` : do not sort; list entries in directory order
> > * `ls -p` : shows directories with / 
> > * `ls -d` : shows only directories
> > * `ls -X` : sort alphabetically by entry extension
> > * `ls -m` : fill width with a comma separated list of entries

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > xargs will essentially execute a command multiple times for an standard input of multiple items
> > `file1.doc file2.doc file3 | xargs rm` will remove all three files


