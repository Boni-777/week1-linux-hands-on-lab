# Week 1 Linux Hands-on Lab: Your First Project Workspace

## Overview

This project demonstrates basic Linux command-line skills as part of the Week 1 Cloud and DevOps hands-on lab.

The tasks include creating directories and files, writing text to a file, moving files, searching for files, and identifying running processes and their Process IDs (PIDs).

## Project Structure

```text
week1/
├── README.md
├── screenshots/
│   ├── 01-create-directory.png
│   ├── 02-create-file.png
│   ├── 03-add-text.png
│   ├── 04-create-scripts-directory.png
│   ├── 05-move-file.png
│   ├── 06-search-file.png
│   └── 07-process-pid.png
└── scripts/
    └── notes.txt
```

## Tasks and Commands

### Task 1: Create the Project Directory

Command:

```bash
mkdir -p ~/cloud-devops/week1
```

Purpose: Creates the project directory and any missing parent directories.

### Task 2: Create notes.txt

Command:

```bash
touch notes.txt
```

Purpose: Creates an empty file named `notes.txt`.

### Task 3: Add Text to notes.txt

Command:

```bash
echo "This is my Week 1 Linux hands-on lab for Cloud and DevOps." > notes.txt
```

Purpose: Writes text into the file.

### Task 4: Create the scripts Directory

Command:

```bash
mkdir scripts
```

Purpose: Creates a directory named `scripts`.

### Task 5: Move notes.txt into scripts

Command:

```bash
mv notes.txt scripts/
```

Purpose: Moves `notes.txt` into the `scripts` directory.

### Task 6: Search for notes.txt

Command:

```bash
find ~/cloud-devops/week1 -name "notes.txt"
```

Purpose: Searches the project directory for the file.

Expected location:

```text
~/cloud-devops/week1/scripts/notes.txt
```

### Task 7: Identify a Running Process and Its PID

Command:

```bash
ps
```

Purpose: Displays processes associated with the current terminal, including their Process IDs (PIDs).

The actual process names and PIDs depend on the running system.

## Verification Commands

Display the project structure:

```bash
find . -maxdepth 2 -print
```

Display the file contents:

```bash
cat scripts/notes.txt
```

Display running processes:

```bash
ps -e
```

## Evidence

The `screenshots/` directory contains screenshots demonstrating the completion of the seven lab tasks.

## Conclusion

This lab provided practical experience with Linux directory and file management, file searching, and process identification. The completed project and supporting evidence are maintained in this GitHub repository.

