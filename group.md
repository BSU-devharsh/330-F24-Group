**Bowie State University**  
**Department of Computer Science**  
**COSC 330, Section 102**  
**Systems Programming, Fall 2024**  
**Group Project, 23 October 2024**  
**Dr. Devharsh Trivedi**

**Instructions:**

* This group programming assignment is worth 100 points.  
* This project is due in 5 weeks, on 27 November 2024\.  
* Grace days policies do not apply to this project.  
* You must work in groups of 2-4 and follow university policies for academic integrity.  
* You must demonstrate using c, vi, make, git, and Unix environment.  
* You can work on any of the following projects as listed.  
* Your GitHub repository submission must contain source code, make file, test cases, presentation slides, and a README file containing build instructions, usage examples, design decisions, known limitations, and references used.

**1\. Command Shell:** Build a bare Unix shell that executes commands and manages processes.

**Requirements:**

* Basic command execution (e.g., ls, pwd, cp)  
* Support for pipes (cmd1 | cmd2)  
* I/O redirection (\>, \<, \>\>)  
* Background processes (&)  
* Basic job control (fg, bg)  
* Signal handling (Ctrl-C, Ctrl-Z)  
* Built-in commands (cd, exit, help)

**Required System Calls:** fork(), execvp(), wait(), waitpid(), pipe(), dup2(), signal()

**2\. File System Explorer:** Implement a file system navigation and manipulation tool.

**Requirements:**

* Directory traversal and listing  
* File creation and deletion  
* File/directory permissions management  
* File copying and moving  
* File information display (size, permissions, timestamps)  
* Search functionality (by name/size/date)

**Required System Calls:** open(), close(), read(), write(), stat(), mkdir(), rmdir(), chmod()  
**3\. Process Manager:** Create a system monitor that tracks and manages processes.

**Requirements:**

* Process creation and termination  
* Process status monitoring  
* Resource usage tracking  
* Priority management  
* Signal sending interface  
* Process tree visualization

**Required System Calls:** fork(), exec(), wait(), kill(), getpriority(), setpriority(), getrusage()

**4\. Network Chat System:** Develop a multi-user chat application.

**Requirements:**

* Client-server architecture  
* Multiple concurrent clients (at least 10\)  
* Public and private messaging  
* User authentication  
* Active user list  
* Message history  
* Error recovery

**Required System Calls:** socket(), bind(), listen(), accept(), send(), recv(), select()

**5\. Virtual Device Driver:** Create a character device driver for a virtual device.

**Requirements:**

* Device registration  
* Read/write operations  
* Device control interface  
* Error handling  
* Support for multiple devices  
* Basic data buffering

**Required System Calls:** open(), read(), write(), ioctl(), mmap(), close()

**6\. Memory Management System:** Implement a custom memory allocator.

**Requirements:**

* Custom malloc() and free()  
* Multiple allocation strategies  
* Memory coalescing  
* Memory tracking  
* Memory leak detection  
* Performance metrics

**Required System Calls:** sbrk(), mmap(), munmap(), getpagesize()

**7\. File Compression Tool:** Build a file compression/decompression utility.

**Requirements:**

* Basic compression algorithm implementation  
* Multiple file handling  
* Progress reporting  
* Compression ratio display  
* File integrity verification  
* Error recovery

**Required System Calls:** open(), read(), write(), lseek(), stat()

**8\. HTTP Web Server:** Implement a basic HTTP server.

**Requirements:**

* HTTP/1.1 protocol support  
* Static file serving  
* Multiple client handling  
* Basic request routing  
* Error pages (404, 500, etc.)  
* Access logging  
* Basic security headers

**Required System Calls:** socket(), bind(), listen(), accept(), send(), sendfile()
