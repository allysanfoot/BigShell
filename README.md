# BigShell

**BigShell** is a custom shell implementation designed to demonstrate core concepts of shell programming, including command parsing, job control, and signal handling. It serves as both a functional shell and a learning tool for developers interested in operating systems and low-level programming.

## Features

- Command parsing and execution
- Built-in commands (e.g., `exit`)
- Job control and background task management
- Signal handling for process control
- Expandable modular architecture

## Project Structure

- **`src/`**: Contains the source code files for the project.
  - `bigshell.c`: Entry point for the shell.
  - `builtins.c`: Implementation of built-in commands.
  - `parser.c`: Command-line parsing logic.
  - Other components include job management, signal handling, and utility functions.
- **`release/`**: Optimized compiled binaries for production.
- **`debug/`**: Debugging binaries with additional logging.
- **`reference/`**: A reference implementation of the shell.
- **`README.rst`**: Project documentation (this file).
- **`makefile`**: Build instructions for the project.

## Getting Started

### Prerequisites

- A Unix-like operating system (Linux, macOS, etc.)
- GCC or an equivalent C compiler
- Make utility

### Installation

Clone the repository:

```bash
git clone <repository_url>
cd BigShell-main
```
Build the project using `make`:
```
make
```
### Running the shell
After building the project, you can start the shell by running:
```
./bigshell
```
### Usage
- Run standard shell commands:
```
ls -l
```
- Use built-in commands like `exit` to terminate the shell
- Manage background tasks using job control features
