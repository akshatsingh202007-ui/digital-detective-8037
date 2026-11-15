# Mission 2 – Terminal and File Management

## 1. Objective

The aim of this mission was to learn how to use Terminal for basic file and folder operations and understand a few useful commands.

## 2. Work Completed

### Task 2.1 – Basic Commands

I practised the following commands:

| Command | Use |
|---|---|
| `pwd` | Shows the current directory. |
| `ls` | Lists files and folders. |
| `ls -l` | Shows detailed file information. |
| `cd ..` | Moves to the parent directory. |
| `mkdir` | Creates a folder. |
| `touch` | Creates an empty file. |
| `cp` | Copies a file. |
| `mv` | Moves or renames a file. |
| `cat` | Displays file contents. |

### Task 2.2 – File Management

I created a folder named `terminal-practice` and a text file inside it. I added two lines to the file, making sure the second line did not replace the first one.

- `>` replaces the existing content of a file.
- `>>` adds new content without removing the existing content.
- `cp` creates a copy, while `mv` moves or renames a file.
- `pwd` tells me where I am working, and `ls` helps me see the files and folders in a directory.

### Task 2.3 – Flags and Pipes

I tried these commands:

| Command | Use |
|---|---|
| `ls` | Shows the normal directory listing. |
| `ls -lah` | Shows detailed information, including hidden files and readable file sizes. |
| `ls -lah \| head` | Displays only the first few lines of the listing. |

A pipe (`|`) passes the output of one command to another. Here, `ls -lah` provides the listing and `head` displays its first few lines.

### Task 2.4 – Homebrew

I checked Homebrew using `brew --version` and `brew list`.

- Homebrew version: **7.0.9**

Homebrew is a package manager for macOS. It helps install and manage software directly from the Terminal.

## 3. What I Learned

I learned how to navigate directories, create and manage files, use command flags and connect commands using pipes. I also got familiar with Homebrew and how it manages installed packages.

## 4. Difficulties Faced

At first, I was a little confused about file paths and the difference between `>` and `>>`. After trying the commands and checking the file using `cat`, I understood how they work.

## 5. Files Created

The `terminal-practice` folder contains the files created during this mission.