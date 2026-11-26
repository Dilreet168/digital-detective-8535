# Mission 3 - Understand The Operating System

## Task 3.1 — Explore your operating system

| Information explored | What it tells me | My privacy-safe observation |
|---|---|---|
| Operating system / system details | Identifies the operating system and its version. | My computer runs macOS version which is shown by `sw_vers` command . |
| Current account identity | Shows which account is currently signed in. | I checked the current account locally and hid my username for privacy. |
| Available and used storage | Shows how much storage is used and available. | The storage command displayed used and available space. |
| System activity snapshot | Shows some processes running at that moment. | I saw applications and background processes running. The list can change over time. |

I removed usernames, computer names, and other identifying details from my notes and screenshots.

## Task 3.2 - Understand Processes
- A process is just a program that is running on the computer. For example, when I open Chrome or VS Code, it starts running as a process and uses things like RAM and CPU.
- PID means Process ID. Every running process gets its own number so the operating system can identify it and keep track of it.
- Two examples : VScode and Google Chrome

## Task 3.3 — Understand Paths And Permissions

- An absolute path gives the full location of a file starting from the root of the computer’s file system. A relative path gives a location starting from the current directory.
- For this project, the relative path to this file is `mission-03-operating-system/tasks.md`. When I entered the mission folder, `pwd` displayed its full path; I kept private username details out of this README.md. It gives the file location based on the folder I am already working in, so I don't have to type the full path.

2. Owner permissions check (ls -l): I checked terminal-practice/notes.txt using ls -l and got -rw-r--r-- as the permission value. This means I can read and edit the file because I am its owner. Other users can only read it, and nobody has permission to execute it.

## Task 3.4 — Explain Operating-System Responsibilities

| OS responsibility | My explanation | Example |
|---|---|---|
| Process management | The operating system starts and coordinates programs that are running. | It lets a browser and text editor run at the same time. |
| Memory management | It allocates memory to programs and manages how that memory is used. | It gives an open application the memory it needs to work. |
| Device management | It helps programs communicate with the computer’s hardware. | It sends a document from an application to a printer. |
| File management | It organizes files and folders and helps programs save and open them. | It saves a document in a folder and opens it again later. |
| User interface / shell | It provides ways for people to interact with the computer. | Finder provides a graphical interface; Terminal accepts commands. |
| Security and permissions | It controls access to files and other computer resources. | File permissions determine who can read or change a file. |
