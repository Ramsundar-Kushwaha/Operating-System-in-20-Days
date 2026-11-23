## Types of Operating System
Operating Systems (OS) are classified into different types based on how they manage processes, users, tasks and computer resources.

<hr>

### 1. Batch Operating System
*I. Executes a group (batch) of similar jobs without requiring direct user interaction during execution.*<br>
*II. Jobs are collected and processed one after another.*<br>
*III. Example: IBM OS/360.*

<hr>

### 2. Multiprogramming Operating System
*I. Keeps multiple programs in memory simultaneously.*<br>
*II. When one program waits for I/O, the CPU executes another program.*<br>
*III. Improves CPU utilization.*<br>
*IV. Example: OS/360*

<hr>

### 3. Multitasking Operating System
*I. Allow a user to run multiple application seemingly at the same time.*<br>
*II. CPU switches between tasks rapidly.*<br>
*III. Examples: Window, Linux, macOS.*

<hr>

### 4. Multiuser Operating System
*I. Allows multiple users to access the same computer system simultaneously.*<br>
*II. Each user gets access to system resources.*<br>
*III. Examples: UNIX, Linux.*

<hr>

### 5. Multiprocessing Operating System
*I. Uses two or more CPUs or processor cores to execute processes simultaneously.*<br>
*II. Improves performance and processing capacity.*<br>
*III. Examples: Linux, Windows, macOS.*

<hr>

### 6. Multithreading Operating System
*I. Supports multiple threads within a single process.*<br>
*II. Threads share the same process resources but can execute independently.*<br>
*III. Example: Windows, Linux, macOS.*

<hr>

### 7. Real-Time Operating System (RTOS)
*I. Processes data and responds to events within a specified time limit.*<br>
*II. Used where timely responses are critical.*<br>

Types:<br>
    *1. Hard Real-Time OS: Missing a deadline is unnacceptable.*<br>
    *2. Soft Real-Time OS: Occasional deadline misses are acceptable.*<br>

*III. Example: VxWorks, QNX, FreeRTOS.*

<hr>

### 8. Distributed Operating System
*I. Manages multiple connected computers and makes them work together as a unified system.*<br>
*II. Resoureces and workloads can be shared across machines.*<br>
*III. Examples: Amoeba, Plan 9.*

<hr>

### 9. Network Operating System
*I. Provides services to computers connected through a network.*<br>
*II. Supports file sharing, printer sharing, user management, and network security.*<br>
*III. Examples: Windows Server, Novell NetWare.*

<hr>

### 10. Embedded Operating System
*I. Designed for dedicated devices that perform specific functions.*<br>
*II. Usually optimized for limited hardware resources.*<br>
*III. Examples: Embedded Linux, FreeRTOS, Zephyr.*

<hr>

### 11. Mobile Operating System
*I. Designed specifically for smartphones and tablets.*<br>
*II. Manages touch interfaces, mobile applications, sensors, and wireless connectivity.*<br>
*III. Examples: Android, iOS.*

<hr>

### Important concepts to understand
Some types are closely related, but they are not the same:<br>

**Multiprogramming vs Multitasking:**<br>
*I. Multiprogramming focuses on keeping the CPU busy*<br>
*II. Multitasking focuses on switching between tasks to provide responsive execution.*

**Multiprocessing vs Multithreading:**<br>
*I. Multiprocessing uses multiple processing units.*<br>
*II. Multithreading allows multiple execution threads within a process.*<br>

**Distributed OS vs Network OS:**<br>
*I. A distributed OS aims to make multiple computers works as one system.*<br>
*II. A network OS provides services and resources sharing between independent computers.*