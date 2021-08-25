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
<h2>Resources</h2>
<ul>
    <li><a href="https://medium.com/@MelissaNg__/how-a-shell-works-8a5a461c1910">Melissa Medium Blog How a Shell Works</a></li>
    <li><a href="https://en.wikipedia.org/wiki/Unix_shell">Unix Shell</a></li>
    <li><a href="https://en.wikipedia.org/wiki/Thompson_shell">Thompson Shell</a></li>
    <li><a href="https://en.wikipedia.org/wiki/Ken_Thompson">Ken Thompson shell</a></li>
</ul>
<h2>Description Of Files</h2>
<ol>
    <li>man_3_shell</li>
    <li>shell.h</li>
    <li>main.c</li>
</ol>
<h2>Shell Function Files</h2>
<ul>
    <li>prompt.c: <br>handles outline of shell's reprompting and executing</li>
    <li>print_error.c: <br>prints special error messages for certain fails</li>
    <li>__exit.c: <br>handles if user types exit or exit(value)</li>
    <li>get_env.c: <br>finds and returns copy of environmental variable</li>
    <li>env_linked_list.c: <br>prints and creates linked list of envrionmental variables</li>
    <li>set_unset_env.c: <br>finds environment variable index node, sets and unsets</li>
    <li>free_double_ptr.c: <br>frees double pointers (user's command, arrays)</li>
    <li>int_to_string.c: <br>converts int to string to write error messages</li>
    <li>_execve.c: <br>executes and frees command, then exits program</li>
    <li>which.c:  <br>appends command to PATHs, fleshes paths out, returns match</li>
    <li>_cd.c: <br>changes directories</li>
    <li>get_line.c: <br>reads user's typed input into buffer</li>
    <li>linked_lists.c <br>adds and deletes nodes; prints and frees linked list</li>
    <li>_strcat.c: <br>concatenates two strings</li>
    <li>_strcmp.c: <br>compares if two strings match</li>
    <li>_strdup.c: <br>duplicates a string</li>
    <li>_str_tok.c: <br>tokenizes user's command input and returns array</li>
    <li>_realloc.c: <br>helper function handles reallocation</li>
    <li>non_interactive.c: <br>handles output when shell is called outside of shell</li>
    <li>c_str_tok.c: <br>tokenizes PATH to include ":" as Null, checks current dir</li>
    <li>_strcpy.c: <br>copies a string</li>
</ul>
<hr>
<br>
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
(your_terminal)
```
```
<hr>
<h3>Authors</h3>
<ul>
<li><a href="https://github.com/layan2k">Leslie D Shumba</a></li>
<li><a href="https://github.com/johnmerga">John Merga'</a></li>
</ul>