THIS PROJECT IS ON SHELL(AN INTERFACE BETWEEN A USER AND THE OPERATING
SYSTEM)

BY: UBI, JOSEPH && FRANKELLY OZONWU.
----------------------------------------------------------------------------------------------------------------

A shell in Unix and Unix-like systems is a command-line interface (CLI)
that provides users with an interface to the underlying operating system's services.
It allows users to execute commands, run scripts, and automate tasks,
either by typing commands directly into the shell or by executing scripts that contain sequences of commands.
The shell acts as a bridge between the user and the operating system,
interpreting commands from the user and executing them on behalf of the user.
Some popular shells in Unix and Unix-like systems include the Bourne shell (sh),
the C shell (csh), the Korn shell (ksh), and the Bourne Again shell (bash).
Each shell has its own syntax and features, but all provide a way for users to interact with
the underlying operating system and run commands and scripts.
The choice of shell can have a significant impact on a user's experience with the operating system,
as different shells offer different levels of customization, scripting capabilities, and user-friendly features.

-----------------------------------------------------------------------------------------------------------------

In C programming, it is possible to use the shell within C-programs to execute shell commands and scripts.
This can be done by using the 'system()' function, which is part of the C standard library.
The 'system()' function takes a string argument, which represents the command to be executed by the shell,
and runs the command in a separate process.
The return value of the 'system()' function indicates the status of the executed command.
It is important to note that the use of the 'system()' function to execute shell commands within a C program
can have security implications, as malicious commands could be passed to the shell and executed on the system.
To mitigate these risks, it is recommended to validate and sanitize the input passed to the
'system()' function before executing it.
