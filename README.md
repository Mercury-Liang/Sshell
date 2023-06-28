# Sshell

Sshell is a simple shell created as an end of term project for Computer Systems 2023 Class @SEM.

## Table of Contents

- [Sshell](#sshell)
  - [Table of Contents](#table-of-contents)
  - [Project Details](#project-details)
    - [Description](#description)
    - [Project Requirements](#project-requirements)
  - [Project Breakdown](#project-breakdown)
  - [Getting Started](#getting-started)
    - [Installation](#installation)
  - [Contact](#contact)

---

## Project Details

### Description

Sshell is a simple UNIX command line shell and was built as an end of final project for SEM. It includes many basic features present in the bash shell.

File Name | Description
 --- | ---
`main.c` | Main function for the shell.



### Project Requirements

- All your files will be compiled on Ubuntu 14.04 LTS
- Your programs and functions will be compiled with `gcc 4.8.4` (`C90`) using the flags `-Wall -Werror -Wextra and -pedantic`
- All your files should end with a new line
- A `README.md` file, at the root of the folder of the project is mandatory
- Your code should use the same style as example.
- All your header files should be include guarded
- Unless specified otherwise, your program must have the exact same output as `sh` as long as the exact same error output.

## Project Breakdown

Task # | Type | Short description
 ---: | --- | --- | 
0 | **Mandatory** | See the README [link](/README.md)
1 | **Mandatory** | Display prompt information and accept command that user types in.
2 | **Mandatory** | Execute the command.
3 | **Mandatory** | When the execution of the command is finished, display the prompt again and wait for next command.
4 | **Mandatory** | Terminate when the user types "exit".
5 | ***Advanced*** | Allow multiple commands to be executed in one line.
6 | ***Advanced*** | Execute the command in background when a “&” is appended to the command
7 | ***Advanced*** | Prevent the SHELL program from being interrupted by "CTRL-C"
8 | ***Advanced*** | BASH related features. such as: Use the **"tab" key** to autocomplete a command and keep a history of commands and use **up/down arrow keys** to re-use them.

## Getting Started

Using Sshell is as easy as 1-2-3! Simply clone this repository onto your local machine, compile with the flags listed below and run!

### Installation

1. Clone

Download this file at web learning, open and run file `compile.sh` to compile and run shell.

2. Compile

On your machine, navigate (`cd`) to the newly created directory then compile with the following tags.

```sh
cd PROJECT
gcc -Wall -Werror -Wextra -pedantic *.c -o hsh
```

3. Run shell

```sh
./hsh
```

4. Run commands and enjoy!

5. To exit

```sh
exit
```

## Contact

Thank you for your time. If you have any questions, please feel free to contact me via `liangzc21@mails.tsinghua.edu.cn`. I might update this repository in the future, so star this repository to keep track of it.

Please enjoy!
