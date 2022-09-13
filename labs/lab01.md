# lab-01 - 9/13/2022
## intro to terminal

#### [git link for prof notes](https://github.com/MRU-MACO-1501-202204-002/laborials/blob/main/laborial-01-intro-to-terminal.md)

- use terminal for git, assignment submission
- will need it in cs stream, not so much bcis
- use git bash, since we're totally not using a microsoft editor that can push to git natively -_-

### basic cli commands (bash):
| Command | Arguments       | Description                                                                   |
| ------- | --------------- | ----------------------------------------------------------------------------- |
| `ls`    | `<dir>` or None | List directory contents. If no argument is provided, lists current directory. |
| `cd`    | `<dir>`         | Change into specified directory                                               |
| `pwd`   | None            | Print the working directory                                                   |
| `cat`   | `<filename>`    | Prints the entire contents of the file to the terminal                        |
| `head`  | `<filename>`    | Prints the first 10 lines of `<filename>` to the terminal                     |
| `tail`  | `<filename>`    | Prints the last 10 lines of `<filename>` to the terminal                      |
| `cp`    | `<src> <dest>`  | Copies the file `<src>` to a file named `<dest>`                              |
| `mkdir` | `<dir>`         | Make a new directory with the specified name                                  |
| `touch` | `<filename>`    | Make a new empty file with the specified name. If `<filename>`                |
|         |                 | exists, updates the "last modified" time with current time.                   |

### flags:
| Special Arguments | Description                               |
| ----------------- | ----------------------------------------- |
| `.`               | Refers to the current directory           |
| `..`              | Refers to the parent directory            |
| `~`               | Refers to your home directory             |
| `/`               | Refers to your file system root directory |