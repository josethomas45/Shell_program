# Shell Program

## Overview

This repository contains **my implementations of various shell programs**. These programs mimic the functionality of a Unix shell, allowing users to execute commands, manage processes, and navigate the filesystem. The projects included here serve as practical examples of how shells work and the underlying mechanisms involved.

### Key Topics:
- **Command Execution**: Handling user inputs to execute commands.
- **Process Management**: Managing foreground and background processes.
- **I/O Redirection**: Redirecting input and output for commands.
- **Piping**: Connecting the output of one command to the input of another.
- **Built-in Commands**: Implementing essential shell commands like `cd`, `exit`, and `help`.

---

## Folder Structure

```
Shell_program/
│
├── simple_shell.c              # Basic shell implementation with command execution
├── process_management.c         # Managing foreground and background processes
├── io_redirection.c             # Implementing I/O redirection in the shell
├── piping.c                     # Implementing piping between commands
└── built_in_commands.c          # Implementation of built-in shell commands
```

---

## Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/josethomas45/Shell_program.git
   ```

2. **Compile the C programs**:
   You can compile the shell programs using GCC:
   ```bash
   gcc -o shell_program simple_shell.c
   ```

3. **Run the Shell**:
   Execute the compiled shell program:
   ```bash
   ./shell_program
   ```

---

## Key Features

1. **Command Execution**:
   - The shell reads user input, parses commands, and executes them using `exec()` system calls.

2. **Process Management**:
   - Allows execution of processes in the foreground and background using `fork()` and `wait()`.

3. **I/O Redirection**:
   - Supports input (`<`) and output (`>`) redirection for executing commands with file input and output.

4. **Piping**:
   - Implemented the ability to pipe commands together using `|`, allowing for complex command execution sequences.

5. **Built-in Commands**:
   - Implemented essential built-in commands such as `cd` for changing directories and `exit` for terminating the shell.

---

## Requirements

- **C Compiler**: Ensure you have a C compiler like GCC installed.
- **Linux/Unix Environment**: Recommended for running and testing the shell programs.

---

## How to Contribute

Contributions are welcome! To contribute to this repository:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add new feature'`).
4. Push the changes to your branch (`git push origin feature-branch`).
5. Create a pull request.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

## Contact

For any questions, feedback, or suggestions, feel free to reach out:

**Jose Thomas**  
[GitHub Profile](https://github.com/josethomas45)
