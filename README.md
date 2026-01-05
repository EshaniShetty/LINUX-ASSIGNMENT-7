# LINUX-ASSIGNMENT-7
Linux Programming Assignment 7: Introduction to Bash Shell Scripting, variable handling, automation logic, debugging techniques, and environment management using the source command.

Overview
This repository transitions from manual command execution to Automation through Bash Shell Scripting. It covers script structure, variable declaration, mathematical operations, and debugging workflows.

Topics & Scripts Covered

1. Bash Scripting Fundamentals
Shebang (#!/bin/bash): The essential first line that tells the system which interpreter to use to execute the script.

Comments (#): Documentation within scripts to explain logic; these lines are ignored by the shell during execution.

2. Variables & Data Handling
In Bash, variables are treated as strings by default, but can be used for various data types:

Strings: name="Alice"

Integers: age=25

Arithmetic: Using the $((...)) syntax for operations like sum=$((num1 + num2)).

Input: Using read -p to capture user data during script execution.

3. Environment & Execution
The source Command: Executing a script in the current shell environment rather than a subshell. This is critical for loading environment variables or functions from one script into another (e.g., source vars.sh).

4. Debugging Techniques
Two primary methods for troubleshooting script errors:

Execution Trace (-x): Running a script with bash -x script.sh to see every command as it executes.

Selective Debugging: Using set -x to start and set +x to stop debugging for specific blocks of code.

5. Automation Examples
This assignment includes scripts for:

Printing "Hello World" and user greetings.

Performing basic addition of two user-provided numbers.

Automated file management (creating and deleting files via script logic).
