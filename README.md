# monty
![banner](img/banner.png)

![GitHub repo size](https://img.shields.io/github/repo-size/MelakuDemeke/monty)
![GitHub issues](https://img.shields.io/github/issues/MelakuDemeke/monty)
![GitHub Repo stars](https://img.shields.io/github/stars/MelakuDemeke/monty?logo=github&style=flat)
![GitHub forks](https://img.shields.io/github/forks/MelakuDemeke/monty?logo=github&style=falt)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/MelakuDemeke/monty?logo=github)

- [monty](#monty)
  - [Description](#description)
    - [Monty ByteCodes](#monty-bytecodes)
  - [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
  - [Installing](#installing)
  - [Usage](#usage)
  - [contributors](#contributors)


## Description
In this project, I created a simple interpreter for Monty ByteCodes. The interpreter reads a bytecode file and executes the bytecode commands.

### Monty ByteCodes
Monty ByteCodes is a programming language inspired by Python and designed to be simple and easy to learn. It was created by Zed A. Shaw as a teaching tool for beginner programmers. Monty ByteCodes uses a minimalist syntax and provides a small set of powerful features, making it a great choice for learning the basics of programming. It is also used as an example language in Zed Shaw's book "Learn More Python the Hard Way."

## Getting Started
### Prerequisites
In order to build and run this project, you need to have the following software installed on your system:

- Git
- GCC

## Installing
You can download the source code of this project by running the following command:
```bash
git clone https://github.com/MelakuDemeke/monty.git
```
Once you have downloaded the source code, you can build the executable by running the following command:

```bash
gcc -Wall -Werror -Wextra -pedantic -std=c89 *.c -o monty
```
This will create an executable file named `monty` in the same directory.
- Any output must be printed on `stdout`
- Any error message must be printed on `stderr`

## Usage
any execution of the code can be done using the byte codes
```
julien@ubuntu:~/monty$ cat -e bytecodes/000.m
push 0$
push 1$
push 2$
  push 3$
                   pall    $
push 4$
    push 5    $
      push    6        $
pall$
julien@ubuntu:~/monty$
```

## contributors
<a href="https://github.com/MelakuDemeke/monty/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=MelakuDemeke/monty" />
</a>