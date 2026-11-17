### 1. What is Operating System?
An Operating System (OS) is system software that acts as an interface between the computer and the user or application programs. it manages computer hardware and software resources and provides an environment in which application can run.

In simple words, an Operating System helps users or applications communicate with computer hardware without needing to control the hardware directly.

#### **Examples of Operating Systems**
![exampel of OS](/images/examples_of_os.webp)


### 2. Why do we need an Operating System?
Imagine you have a computer with:<br>
**CPU**<br>
**RAM**<br>
**HARD disk/SSD**<br>
**Keyboard and Mouse**<br>
**Monitor**

without an Operating System, managing these components and running applications would be extremely difficult.

#### For example:
When you open Chrome, the OS allocates memory to it.<br>
When you play music, the OS manages audio output.<br>
When you save a file, the OS manages storage operations.<br>
When you run multiple applications, the OS manages CPU time.

*without an Operating System we have to manages these resources through our application programs, which makes our application program heavy/bulky and difficult to maintain.*

Therefor, an OS makes computer system easier to use and manages their resources efficiently.


**An Operating System sits between applications/users and hardware.**

![os interface](/images/os_interface.webp)

#### The communication happens in the following way:

**1. User:** interacts with the computer.<br>
**2. Application Software:** Programs such as Chrome, VS Code, Compiler, Assembler, Text editor, Databases and games etc.<br>
**3. Operating System:** Manages resources and provides services to applications.<br>
**Hardware:** CPU, RAM, storage devices, keyboard, etc.
<hr>
<br><br><br>



### 3. Main responsibility of an Operating System

**Process Management**<br>
*Manages running programs and processes.*

**Memory Management**<br>
*Allocates and deallocates RAM.*

**File Management*<br>*
*Organizes and manages files and directories.*

**Device Management**<br>
*Controls hardware devices through drivers.*

**CPU Scheduling**<br>
*Decides which process gets CPU time.*

**Security & Protection**<br>
*Protects system resources and user data.*

**I/O Management**<br>
*Manages input and output operations.*


![responsibilities of os](/images/functions_of_os.webp)
<hr>
<br><br><br>



### 4. Types of Operating System
***Batch OS***<br>
***Time sharing OS***<br>
***Distrubuted OS***<br>
***Network OS***<br>
***Real Time OS***<br>
***Multi Programming OS***<br>
***Multi Processing OS***<br>
***Multi Tasking OS***
<hr>
<br><br><br>



### 5. Goals of Operating System(OS)

**1. Convenience**<br>
*Make computers easier for users to operate.*<br>
*Provide a simple interface between users and hardware.*<br>
*Allow users to run applications without understanding hardware details.*

**2. Efficiency**<br>
*Utilize computer resource efficiently.*<br>
*Manage CPU, RAM, storage, and I/O devices.*<br>
*Minimize resource wastage and improve system performance.*

**Example:** CPU scheduling allows multiple processes to share CPU time efficiently.

**3. Resource Management**<br>
*Manage and distribute system resources among different programs.*<br>
*Allocate and deallocate memory when required.*<br>
*Coordinate access to hardware devices.*

**Example:** When multiple applications are running, the OS manages their CPU and memory requirements.

**4. Reliability and stability**<br>
*Ensure the system operates correctly and consistently.*<br>
*Handle errors and prevent application failures from affecting the entire system.*

**Example:** if one application crashes, the OS should prevent it from unnecessary crashing the entire computer.

**5. Security and Protection:**<br>
*Protect system resources and user data from unauthorized access.*<br>
*Provide authentication and access control.*<br>
*Isolate processes to prevent unwanted interference.*

**Example:** A user account password prevent unauthorized users from accessing your computer.

**6. Ability to Evolve**<br>
*Support new hardware and technologies.*<br>
*Allow new features and functionalities to be added.*<br>
*Adapt to changing user requirements.*

**Example:** An OS can support new processors, storage devices, and hardware drivers through updates.
<hr>
<br><br><br>



### 6. Components of an Operating System
An Operating System consists of several components that work together to manage computer hardware, software resources, and provide service to users and applications.

Each component has a specific responsibility.

**1. Kernal**<br>
The Kernal is the core component of an Operating System. it acts as a bridge between software and hardware.

**Responsibilities:**<br>
*Manages CPU and processes.*<br>
*Manages memory.*<br>
*Handles hardware communication.*<br>
*Managees system calls.*<br>
*Controls access to syistem resources.*

**Example:** When an application needs CPU time or memory, the kernal manages the requests.

**2. Process Management**<br>
Process Management handles the creation, execution, scheduling, and termination of processes.

**Responsibilities:**
*Create and terminate processes.*<br>
*Schedule process states.*<br>
*Manage process states.*<br>
*Handle process synchronization.*<br>
*Support inter-process communication (IPC).*

**Example:** Running chrome, VS Code, and a music player simultaneously.

**3. Memory Management**<br>
Memory Management manages the computer's main memory (RAM).

**Responsibilities:**<br>
*Allocate memory to processes.*<br>
*Dallocate memory when it is no longer needed.*<br>
*Track memory usage.*<br>
*Manage virtual memory.*<br>
*Protect the memory space of processes.*

**Example:** When you open VS Code, the OS allocates RAM for its execution.

**4. File System Management**<br>
File System Management organizes, stores, retrieves, and manages files and directories.

**Responsibilities:**<br>
*Create and delete files.*<br>
*Create and manage directories.*<br>
*Read and write files.*<br>
*Manage file permissions.*<br>
*Organize data on storage devices.*

**Example:** Creating a folder, saving a document, or deleting a file.

**5. I/O (Input/Output) Management**<br>
I/O Management controls and coordinates communication between the computer and input/output devices.

**Responsibilities:**<br>
*Manage input and output devices.*<br>
*Coordinate device communication.*<br>
*Handle I/O requests.*<br>
*Manage buffering, caching, and spooling.*<br>
*Work with device drivers.*

**Example:* Reading input from a keyboard or displaying output on a monitor.

**6. Secondary Storage Management**<br>
This component manages data stored on secondary storage devices such as HDDs and SSDs.

**Responsibilities:**<br>
*Manage free storage space.*<br>
*Allocate storage space.*<br>
*Manage disk scheduling.*<br>
*Organize data storage.*

**Example:** Saving a video or installing software on an SSD.

**7. Security and Protection**<br>
This component protects the computer system and its resources against unauthorized access.

**Responsibilities:**<br>
*User authentication.*<br>
*Access control.*<br>
*Process isolation.*<br>
*File permissions.*<br>
*Protection of system resources.*

**Example:** Requiring a password to log in to you computer.

**8. Networking Management**<br>
Networking management handles communication between computers and network devices.

**Responsibilities:**<br>
*Manage network connections.*<br>
*Support communication between systems.*<br>
*Manage network resources.*<br>
*Provide networking protocols and services.*

**Example:** Connecting your computer to the internet through Wi-Fi.

**9. Command Interpreter / User Interface**<br>
It provides a way for users to interact with the Operating System.

There are two common types:

***CLI (Command-Line Interface):*** Users interacting using text commands.<br>
***GUI (Graphical User Interface):*** Users interact using windows, icons, menus, and pointers.

**Example:**<br>
CLI: *Linux Terminal, Windows Command Prompt.*<br>
GUI: *Windows Desktop, Ubuntu Desktop.*


**Overall architecture of OS componets**<br>
![os componets](/images/os_components.jpg)
<hr>
<br><br><br>


### Important notes:

**Operating System (OS)**<br>
*An Operating System is system software that acts as an interface between the user, applications, and computer hardware.*

**Examples:** Windows, Linux, macOS, Android, IOs
<hr>

**System Software**<br>
*System Software is a collection of programs that manages computer hardware and provides a platform for running application software.*

*It helps the computer operate and allows other software to interact with hardware.*

**Examples:**

*Operating Systems:* Windows, Linux etc.<br>
*Device Drivers:* Printer driver, graphics driver<br>
*Language Translators:* compiler, intepreter, Assembler<br>
*Utility Programs:* Disk Cleanup, Antivirus
System Libraries: Standard C Library
<hr>

**Application Software**<br>
*Application Software is a program or collection of program designed to help users perform specific tasks.*

*it runs on top of system software and uses the services provided by the operating system.*

**Examples:**

*Text Editing:* MS Word, Notepad<br>
*Web Browsing:* Chrome, Firefor<br>
*Image Editing:* Photoshop, GIMP<br>
*Programming:* VS Code, PyCharm<br>
*Entertainment:* VLC, Games<br>
*Communication:* WhatsApp, Telegram

**Main responsibilities:**<br>
*1.* Performs specific user tasks.<br>
*2.* Provides a user-friendly interface.<br>
*3.* Uses OS service to access hardware and system resources.