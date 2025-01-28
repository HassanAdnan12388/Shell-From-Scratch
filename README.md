# Shell-From-Scratch
Command-line shell implemented in C with support for basic built-in commands, external command execution, I/O redirection, and alias management.


## Features

- **Built-in commands:** `cd`, `pwd`, `exit`, `echo`
- **Execution of external commands** using `execvp`
- **I/O Redirection:** Supports `>`, `>>`, `<`
- **Alias support:** Define and use custom aliases
- **Command history management**


### Prerequisites
- A C compiler (e.g., `gcc`)
- Linux or macOS environment


## Commands

### Built-in Commands
| Command         | Description                         |
|----------------|-------------------------------------|
| `cd <dir>`     | Change directory                   |
| `pwd`          | Print working directory            |
| `exit`         | Exit the shell                     |
| `echo <text>`  | Print text to stdout               |

### I/O Redirection
| Operator | Function |
|----------|----------|
| `>`      | Redirect output to a file (overwrite) |
| `>>`     | Redirect output to a file (append) |
| `<`      | Read input from a file |

### Alias Commands
Define aliases for custom commands:
```sh
alias ll='ls -al'
```
Remove an alias:
```sh
unalias ll
```

## Future Improvements
- Implement piping (`|`)
- Improve alias expansion
- Add command history navigation



