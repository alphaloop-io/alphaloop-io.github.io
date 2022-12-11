---
layout: post
title: 20 Linux Commands For Better Programming
author: sajith
date: '2020-11-16 18:40:23 +0530'
categories: [ Linux ]
tags: [Linux]
hidden: true
---

As a linux user over a decade, I can say that experienced linux users have an everlasting intimate bond with linux shell commands even though they were struggling to become familiar at the beginning. Things that can be done with shell commands are more powerful and efficient than GUIs that might take more and more steps. Because it’s just a single line command. Thus learning shell commands in linux improves your productivity as well as self-confidence on using linux distros.

When it comes to software development, linux commands are a critical factor because in the process of software deployment in linux server machines, shell commands are a must. In many instances developers log in to servers through ssh and execute commands remotely without GUI. Hence better knowledge of linux commands helps software developers to do their job smoothly.

Though there are numerous linux [distros](https://en.wikipedia.org/wiki/Linuxdistribution) such as Pop!OS (My Favorite), Ubuntu, Arch linux, Fedora, Kubuntu, Mint etc you can use the same shell command in any of these since they are built with linux kernel. Open your terminal and I hope you’ll learn useful shell commands whether you’re a beginner or daily Linux user.


### **1. man**
You can use the `man` command to read the manual and understand the usage of any other command.

```shell
$ man pwd
PWD(1)		User Commands		PWD(1)

NAME
	pwd - print name of current/working directory

SYNOPSIS
pwd [OPTION]...
```

### **2. pwd**

Used to print the absolute path(path from the root) of the current working directory/folder.

```
$ pwd
/home/username/
```

### **3. ls**

If you want to list contents of a directory, use `ls` command. The command without arguments lists files of the current working directory.

```
$ ls
Documents
Downloads
text_file.txt
demo.mp4
Videos
```
Results of the default command are sorted alphabetically by ascending order and excluded hidden files. If you want to show hidden files as well use,

```
$ ls -a
Documents
Downloads
text_file.txt
hidden_file.txt
```
Following command line arguments can be used to get expected results.

`ls -R` - List subdirectories recursively<br/>
`ls -s` - Print the allocated size of each file, in blocks<br/>
`ls -l` - Print detailed information of files and folders such as permissions, owner, file size, created date etc<br/>

