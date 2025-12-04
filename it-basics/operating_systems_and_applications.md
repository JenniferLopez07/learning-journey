# Operating Systems and Applications – Codecademy

## Overview
This lesson provides a high‑level overview of the responsibilities of an operating system (OS), including how it manages hardware, software, processes, memory, files, and user interactions. Understanding OS fundamentals is essential for IT support and cybersecurity, since misconfigurations, outdated systems, and insecure applications are common sources of vulnerabilities.

## Key Concepts
 **Hardware Components**
 - Hard Drive – A spinning platter with a thin magnetic coating used for long‑term storage.
 - Sectors – The smallest physical storage units on a drive.
 - Smaller sectors require more indexing information to map the entire drive.

--- 
   
 **Operating Systems**
 - Common OS types:
   - Windows
   - Linux
   - macOS
   - Android
   - iOS
 - Core OS components:
   - Kernel – Manages interactions between hardware and software, including memory, processes, and device drivers.
   - File Systems – Data structures used by the OS to store, organize, and retrieve data.

---

  **Functions of an OS**
 -  Process Management – Handles running programs and multitasking.
 -  Memory Management – Allocates RAM to processes and prevents conflicts.
 -  File Management – Creates, deletes, renames, and organizes files and directories.
 -  I/O Management – Manages communication between hardware devices and applications.
 -  Multitasking – Allows multiple programs to run simultaneously.
 -  Networking – Manages network connections and data transfer.
 -  Security – Enforces permissions, authentication, and access control.
 -  User Interface – Provides GUI or CLI for user interaction.

---
  
  **Filesystem**
  
  ---- *A file system is a data structure used by the OS to store and retrieve data.*
      
  Key points:
  - Files support three main actions: read, write, and execute.
  - File system layers include:
    - Application Programs
    - Logical File System
    - File-Organization Module
    - Basic File System
    - I/O Control
    - Devices
   
  **Directories**
  - Provide a hierarchical structure for organizing files.
  - Common directory commands:
    - mkdir – Create new directories (including subdirectories).
    - ls – List directory contents.
    - rm -r – Remove directories and their contents.

---

  **Unix Commands**
  - touch – Create an empty file.
  - ls – List directory contents (lowercase “L”).
  - echo – Output text to the terminal; can redirect output using > to write to a file.
  - cat – Display the contents of a file.
  - rm – Delete a file.
    
---

  **Software Installation**
  - Software is installed when all required files are placed in a folder and an executable file (entry point) is created.
  - Installation steps:
    1. Download the software (retrieve files from a server and store them locally).
    2. Run the installer appropriate for the OS (e.g., .exe on Windows).
    3. The installer places files in the correct directories and configures the application.
       
---

**Topics Covered in This Course**
- Processes and Threads
- Process Scheduling
- Synchronization
- Memory Management
- Filesystems
- I/O Systems

---

## Examples
--- Unix File Permissions:
- *Permissions are represented by a 10-character string:*
- -rwxr-xr--
- First Character:
  - *-* = file
  - d = directory
- Next three characters: owner permissions
- Next three: group permissions
- Final three: other users
- r = read, w = write, x = execute
  
--- Software Installation Example
  - Downloading and installing Python 3.10.2 on a computer
 
## Takeaways
- A process represents a running instance of a program; the OS manages all active processes.
- The OS maintains file systems and handles creating, deleting, renaming, and copying files and directories.
- Every computer has at least one OS, which begins running as soon as the machine powers on.
- Core OS responsibilities include process management, memory management, file system management, and I/O management.
- File extensions such as .txt, .doc, and .jpg indicate file types and associated applications.
- A directory is a data structure containing references to files and other directories.
- Some applications are single‑platform, while others are cross‑platform and can run on multiple operating systems.
- Common app categories include productivity, collaboration, and business tools.
- System tools allow users to view running applications and close them when needed.
  
## Resources
- [Codecademy: Operating Systems and Applications](https://www.codecademy.com/courses/introduction-to-it/articles/basics-of-operating-systems-article)
- [Codeacademy: Fundamentals of Operating Systems](https://www.codecademy.com/courses/introduction-to-it/informationals/going-further-with-operating-systems)


