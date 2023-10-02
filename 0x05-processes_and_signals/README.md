README file
0x05-processes_and_signals
...What is a PID (Process ID)?
A PID, or Process ID, is a unique numerical identifier assigned to each running process in an operating system. It is used by the operating system's kernel to track and manage processes. PIDs are essential for various system tasks, such as process management, monitoring, and termination.

...What is a Process?
A process is a fundamental concept in computer science and operating systems. It refers to an independent, executing program in a computer's memory. A process can contain one or more threads of execution and includes its own memory space, resources, and system state. Each process runs separately from others, allowing multiple programs to run concurrently on a computer.

...How to Find a Process's PID:
To find a process's PID, you can use various system commands depending on your operating system. Commonly used commands include:
ps (Unix-like systems): You can use the ps command to list running processes along with their PIDs.
Task Manager (Windows): In Windows, you can open the Task Manager to view and identify running processes and their PIDs.

...How to Kill a Process:
To terminate or "kill" a process, you typically use a command or utility provided by your operating system. Common commands include:
kill (Unix-like systems): You can use the kill command followed by the process's PID to terminate it.
Task Manager (Windows): In Windows, you can use the Task Manager to end a process by selecting it and clicking the "End Task" button.

...What is a Signal?
In the context of process management, a signal is a software interrupt delivered to a process to notify it of a specific event or request. Signals are used for various purposes, such as terminating a process, pausing it, or asking it to reload configuration settings.

...What Are the 2 Signals That Cannot Be Ignored?
In Unix-like operating systems, two signals cannot be ignored by a process:
SIGKILL (signal number 9): This signal forcefully terminates a process. It cannot be caught or ignored by the process, making it a last resort for stopping unresponsive or rogue processes.
SIGSTOP (signal number 19): This signal suspends a process temporarily, effectively pausing its execution. Like SIGKILL, it cannot be ignored.
These objectives provide a basic understanding of processes, PIDs, signals, and how to manage processes in a computer's operating system. The specifics may vary depending on the operating system and the tools available.
Happy coding !!
