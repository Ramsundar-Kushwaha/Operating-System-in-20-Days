### Time-Sharign Operating System

A Time-Sharing Operating System is an operating system that allows multiple users or processes to share CPU time simultaneously by allocating a small amount of CPU time to each processes.

In simple words, the CPU switches rapidly between multiple processes, giving each process a chance to execute. This makes it appear that all processes are running at the same time.

### How does Time-Sharing OS work?

Let's understand with an example.<br>
Suppose three users are working on the same computer system:<br>
*User A is editing a document.*<br>
*User B is running a program.*<br>
*User C is browsing files.*

The CPU gives each process a small amount of time called a Time Slice (Time Quantum).

### Important terminology

**1. Time Slice (Time Quantum)**<br>
*I. A fixed amount of CPU time allocated to a process.*<br>
*For example, 10 miliseconds.*

**2. Context Switching**<br>
*The process of saving the state of the currently running process and loading the state of another process.*<br>
*Allows the CPU to switch between processes.*

**3. CPU Scheduling**<br>
*I. Decides which process gets CPU time next.*<br>
*II. Round Robin scheduling is commonly associated with time-sharing systems.*

<hr>

### Charaterstics of Time-Sharing OS**

***I. Multiple Users:*** *Supports multiple users accessing the system.*<br>
***II. Time Silicing:*** *CPU time is divided into small intervals.*<br>
***III. Quick Response:*** *Provides quick responses to user requests.*<br>
***IV. Context Switching:*** *Switches between processes frequently.*<br>
***V. Resource Sharing:*** *Multiple users share CPU, memory, and other resources.*<br>
***VI. Interactive Environment:*** *Users can interact with the system while program are executing.*

<hr>

### Advantages

*I. Supports multiple users simultaneously.*<br>
*II. Provides quick response times.*<br>
*III. Improve CPU utilization.*<br>
*IV. Allows interactive computing.*<br>
*v. Shares sytem resources efficiently.*

<hr>

### Disadvantages

*I. Context switching introduces overhead.*<br>
*II. Requiring proper CPU scheduling.*<br>
*III. Security and privacy become more challenging with multiple users.*<br>
*IV. System performance may decrease when too many users are active.*<br>
*V. Requires memory and resource management.*

<hr>

### Why Time-Sharing OS developed, if we already had Bacth OS?

The main problem with Batch OS was that users had to wait for their jobs to finish without interacting with the computer during execution. Time-Sharing OS was developed to overcome this limitation and provide interactive computing.

Let's understand the evolution.

#### 1. Problem with Batch Operating System

Imagine you are a programmer working on a university computer.<br>
You wite a program and submit it to the computer for execution.<br>
Suppose your program contains an errro.<br>

In a Batch OS:

*I. You submit your program.*<br>
*II. Your program waits in a job queue.*<br>
*III. The computer executes your program.*<br>
*IV. It discovers an error.*<br>
*V. You receive the output showing the error.*<br>
*VI. You correct the program and submit it again.*

The Problem: *You cannot interact with the program while it is executing. You may have to wait a long time just to discover a small error.*

![Batch OS](/images/batch_os.jpg)


#### 2. Why was Time-Sharing OS introduced?

To solve these problems:

*I. Users wanted immediate response.*<br>
*II. Users wanted to interact with program during execution.*<br>
*III. Multiple users wanted to use the same computer system.*<br>
*IV. Waiting for an entire batch to finish was inefficient for interactive tasks.*

Time-Sharing OS addressed these requirements by dividing CPU time into small time slices and sharing it among multiple users or processes.

![Time-Sharing OS](/images/time_sharing_os.jpg)