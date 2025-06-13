# Operating Systems Project  

This project focuses on implementing and exploring various aspects of operating systems, including Linux Kernel programming, scripting, and the XV6 operating system. The project is divided into three main parts:  

## Overview  
1. **Linux Kernel Programming**:  
   - Learn to compile and install the Linux Kernel.  
   - Create and execute simple kernel modules.  
   - Develop a kernel module to retrieve process information, including `pid`, `name`, `state`, and parent process details.  

2. **Linux Scripting**:  
   - Explore basic Linux scripting tasks, including directory creation, file manipulation, and command execution.  
   - Implement commands for managing files, directories, variables, and sorted user lists.  

3. **XV6 Operating System**:  
   - Implement a **ticket lock** mechanism to handle critical sections with FIFO guarantees and prevent starvation.  
   - Develop a **reader-writer lock** with priority for readers using the ticket lock.  

## Key Features  
### Linux Kernel Programming  
- Learn kernel compilation and module programming.  
- Implement a custom kernel module for process information retrieval.  

### Linux Scripting  
- Perform scripting tasks such as directory creation, file manipulation, and user list management.  
- Use shell commands effectively for automation.  

### XV6 Operating System  
- Implement ticket locks in **spinlock.c** and **spinlock.h**.  
- Add system calls:  
  - `ticketlockInit` to initialize the ticket lock.  
  - `ticketlockTest` to test the ticket lock mechanism.  
- Develop a reader-writer lock with priority for readers and implement the associated system calls (`rwinit` and `rwtest`).  

## Purpose  
This project aims to provide hands-on experience with essential operating system concepts, including kernel programming, process management, concurrency, and synchronization.

## Acknowledgements  
This project was developed as part of the **Operating Systems course** at **Amirkabir University of Technology (AUT)**.

## License  

This project is based on the XV6 operating system, which is licensed under the MIT License. The original authors are **Frans Kaashoek**, **Robert Morris**, and **Russ Cox** from the **Massachusetts Institute of Technology (MIT)**.  

See the [LICENSE](LICENSE) file for full details.  
