# Virtual File System 
## Date: December 9, 2024

## Group Contributors
- Sangam Lamichhane
- Serwes Bhatta

## Project Summary
This Virtual File System (VFS) is integrated within a custom shell environment, designed to simulate file management and operations akin to an operating system's file handling capabilities, but within a self-contained database environment. The VFS interacts with the shell to provide file and directory management via command-line interfaces. 

### Core Functionalities
- Allows creating, reading, updating, and deleting file and directory entries within a virtualized environment.
- Supports executing commands that interact with the virtual filesystem, such as listing contents, changing directories, and modifying file permissions.
- Maintains a history of commands executed within the shell, saving them within the virtual filesystem for persistence and review.
- Facilitates redirecting the output of commands to files within the virtual filesystem, enhancing scriptability and data logging.

## Setup Instructions
1. Install necessary dependencies from the `requirements.txt`.
    ```bash
    pip install -r requirements.txt
    ```
2. Run the main shell script to start interacting with the virtual file system.
    ```bash
    python3 shell.py
    ```
3. Enter commands as per your needs to interact with the virtual file system (e.g., `ls`, `cd`, `mkdir`, `touch`).

## Known Issues
- **Limited Arrow Key Functionality**: Navigation within the command line input via arrow keys may not function as expected.

## Project Files

| #  | File                    | Description                                                    |
|----|-------------------------|----------------------------------------------------------------|
| 1  | `shell.py`              | Main script facilitating user interaction through the shell interface. |
| 2  | `requirements.txt`      | Contains all dependencies required for the project.            |
| 3  | `database/`             | Houses the SQLite database and scripts managing database operations. |
| 4  | `api/`                  | API layer that provides an interface between the shell and the database. |
| 5  | `shell/cmd_pkg/`           | Includes all the shell commands that are required for the project.  |



