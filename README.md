# Project: 0x16 - C Simple Shell

## Overview

This project involves the creation of a simple UNIX command interpreter, also known as a shell. The shell is designed to execute commands entered by the user and provide a command-line interface. This project is a group effort by Zakaria Bakour, and Ifeanyi Ekezie.

## Project Timeline

- **Start Date:** November 1, 2023, 6:00 AM
- **End Date:** November 18, 2023, 6:00 AM

## Project Description

The goal of this project is to create a UNIX shell capable of interpreting and executing commands. The shell should be able to handle basic commands, display a prompt, and execute commands with or without arguments. The project also includes handling the PATH, implementing built-in commands like `exit` and `env`, and incorporating advanced features such as logical operators (`&&`, `||`), variables, and file input.

## Learning Objectives

By the end of this project, participants are expected to:

- Understand the basics of programming in C
- Grasp the fundamentals of C programming language
- Think like an engineer when approaching a project
- Gain experience in group work
- Develop skills in learning how to learn

## Important Guidelines

- **Code Style:** Ensure your code adheres to the Betty style. Use `betty-style.pl` and `betty-doc.pl` for checks.
- **Memory Leaks:** Your shell should not have any memory leaks.
- **Functions Per File:** Limit the number of functions in each file to no more than 5.
- **Header Files:** All header files should be include guarded.
- **System Calls:** Use system calls only when necessary.
- **Readme:** Include a `README.md` file at the root of the project folder.

## Project Tasks

The project is divided into multiple tasks, each building upon the previous one. Ensure that each task is completed successfully before moving on to the next. Refer to the project repository for detailed information on each task.

1. **Task 0 - Betty would be proud:** Write code that passes the Betty checks.

2. **Task 1 - Simple shell 0.1:** Write a UNIX command line interpreter.

3. **Task 2 - Simple shell 0.2:** Handle command lines with arguments.

4. **Task 3 - Simple shell 0.3:** Handle the PATH and avoid calling `fork` if the command doesn’t exist.

5. **Task 4 - Simple shell 0.4:** Implement the `exit` built-in command.

6. **Task 5 - Simple shell 1.0:** Implement the `env` built-in command.

7. **Task 6 - Simple shell 0.1.1 (Advanced):** Write your own `getline` function.

8. **Task 7 - Simple shell 0.2.1 (Advanced):** Avoid using `strtok`.

9. **Task 8 - Simple shell 0.4.1 (Advanced):** Handle arguments for the built-in `exit` command.

10. **Task 9 - setenv, unsetenv (Advanced):** Implement the `setenv` and `unsetenv` builtin commands.

11. **Task 10 - cd (Advanced):** Implement the `cd` builtin command.

12. **Task 11 - ; (Advanced):** Handle commands separated by `;`.

13. **Task 12 - && and || (Advanced):** Handle the `&&` and `||` shell logical operators.

14. **Task 13 - alias (Advanced):** Implement the `alias` builtin command.

15. **Task 14 - Variables (Advanced):** Handle variables replacement, including `$?` and `$$`.

16. **Task 15 - Comments (Advanced):** Handle comments marked with `#`.

17. **Task 16 - File as input (Advanced):** Allow the shell to take a file as a command line argument.

## Compilation and Testing

- **Compilation:** Compile your shell using the command: `gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o hsh`

- **Testing:** Test your shell in both interactive and non-interactive modes. Ensure it provides the same output and error messages as `/bin/sh`.


## Repository Guidelines

- Each group should have one project repository. Collaborate with your partner and avoid duplicate repositories with the same name.
- If collaborating, add your partner as a collaborator on GitHub.

### Authors
	 Ifeanyi Ekezie
	 email: iiekezie@gmail.com

## Conclusion

This project provides a hands-on opportunity to understand and implement a simple shell, covering various aspects of system calls, process execution, and command interpretation. It is a significant milestone in the ALX Software Engineering program, contributing to the overall learning experience and skill development. Good luck and have fun!
