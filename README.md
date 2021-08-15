<h1 align-"center">Simple Shell </h1>

## Repository Description
<p> This repository contains files to simulate basic Unix Shell with its normal commands.
0x16. C- Simple Shell project at ALX Holberton </p>

<h2>Learning Objectives</h2>
<p>At the end of the project, we should be able to explain the project without the help of Google</p>

<h3>General</h3>
<ul>
    <li>Who designed and implemented the original Unix operating system</li>
    <li>Who wrote the first version of the UNIX shell</li>
    <li>Who invented the B programming language (the direct predecessor to the C programming language)</li>
    <li>Who is Ken Thompson</li>
    <li>How does a shell work</li>
    <li>What is a pid and a ppid</li>
    <li>How to manipulate the environment of the current process</li>
    <li>What is the difference between a function and a system call</li>
    <li>How to create processes</li>
    <li>What are the three prototypes of main</li>
    <li>How does the shell use the PATH to find the programs</li>
    <li>How to execute another program with the execve system call</li>
    <li>How to suspend the execution of a process until one of its children terminates</li>
    <li>What is EOF / “end-of-file”?</li>
</ul>

<h3>Environment</h3>
<ul>
    <li>Language: C</li>
    <li>Style Guideline<a href="https://github.com/holbertonschool/Betty/wiki">Betty style</a></li>
    <li>OS: Ubuntu 14.04 LTS</li>
</ul>

<h2>How To install and Use</h2>
<br>
<h4>Install and Compile</h4>
<br>
<hr>
(your_terminal)$ git clone https://github.com/layan2k/simple_shell.git
(your_terminal)$ cd simple_shell
(your_terminal)$ gcc -Wall -Werror -Wextra -pedantic -Wno-format *.c -o simple_shell

```
**Non-Interactive Mode**
```
echo "ls -l" | ./simple_shell
```
**Interactive Mode***
Activate the shell
```
(your_terminal)$ ./simple_shell
$
```
Sample Usage
```
$ ls -al
total 4
-rw-rw-r-- 1 vagrant vagrant   234 Aug 14 19:32 file1.c
-rw-rw-r-- 1 vagrant vagrant    69 Aug 14 19:32 file2.c
$ echo "This is a pretty cool!"
This is pretty cool!
$ man ./man_1_simple_shell (opens our manpage for more information)
```
Stop and return to your original shell
```
$ exit
(your_terminal)$
```
```
### Authors
[Leslie D Shumba][https://github.com/layan2k]
[John Merga'][https://github.com/johnmerga]