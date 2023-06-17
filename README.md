# Basic Bash Scripts

# Automate tasks with bash scripts

# Introduction
Bash (Bourne Again SHell) is a command language interpreter that is widely used in Linux and Unix systems. It provides a powerful scripting environment for automating tasks, managing files, and executing commands.

This repository serves as a beginner-friendly guide to Bash scripting, covering the essential concepts and techniques required to write functional scripts.


Let's get straight into it and create our first shell script.

```touch 90DaysOfDevOps.sh```

Followed by ```nano 90DaysOfDevOps.sh``` this will open our new blank shell script in nano. Again you can choose your text editor of choice here.

The first line of all bash scripts will need to look something like this ```#!/usr/bin/bash``` this is the path to your bash binary.

You should however check this in the terminal by running which bash if you are not using Ubuntu then you might also try whereis bash from the terminal.

However, you may see other paths listed in already created shell scripts which could include:

```!/bin/bash```
```!/usr/bin/env bash```

Here we have to give permission to execute so just type ``` chmod +x filename.sh ```

# Variables

Variables in Bash are used to store values and can be accessed and modified throughout the script. Bash variables are untyped, meaning they can hold any type of value, such as numbers, strings, or even arrays.

In this repository, you'll find examples and best practices for declaring and working with variables in Bash scripts.

# Input and Output

Bash provides various ways to interact with the user and handle input and output. You can read input from the user, display output on the screen, redirect output to files, and more.

The examples in this repository will demonstrate different methods of obtaining input, printing output, and using standard input/output redirection.

# Conditional Statements

Conditional statements allow you to make decisions based on certain conditions. In Bash, you can use if statements to perform conditional branching and execute different blocks of code based on the evaluation of conditions.
