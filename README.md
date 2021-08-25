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

## Shell Function Files</h2>

|           |FILE            |description                         |
|-----------|-----------------|-----------------------------|
|1			|`'prompt.c'`     |handles outline of shell's reprompting and executing |
|2          |`print_error.c`  |prints special error messages for certain fails |
|3          |`__exit.c`  |handles if user types exit or exit(value)            |
|4          |`get_env.c`  |finds and returns copy of environmental variable    |
|5          |`env_linked_list.c`  |prints and creates linked list of envrionmental variables |
|6          |`set_unset_env.c`  |finds environment variable index node, sets and unsets      |
|7          |`free_double_ptr.c`|frees double pointers (user's command, arrays)|
|8          |`int_to_string.c`  |converts int to string to write error messages |
|9          |`_execve.c`  |executes and frees command, then exits program|
|10          |`which.c`  |changes directories|
|11          |`_cd.c`  |finds environment variable index node, sets and unsets     |
|12         |`get_line.c`  |reads user's typed input into buffer|
|13         |`linked_lists.c`  |adds and deletes nodes; prints and frees linked list|
|14         |`_strcat.c`  |concatenates two strings|
|15         |`_strcmp.c`  |compares if two strings match|
|16         |`_strdup.c`  |duplicates a string|
|17         |`_str_tok.c`  |tokenizes user's command input and returns array|
|18         |`_realloc.c`  |helper function handles reallocation|
<!-- |19         |`c_str_tok.c`  |handles output when shell is called outside of shell|
|20         |`_strcpy.c`  |copies a string| -->


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
(your_terminal)$
```
```
<hr>
<h3>Authors</h3>
<ul>
<li><a href="https://github.com/layan2k">Leslie D Shumba</a></li>
<li><a href="https://github.com/johnmerga">John Merga'</a></li>
</ul>