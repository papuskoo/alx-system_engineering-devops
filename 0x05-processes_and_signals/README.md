Project: Process and PID File Management

This project consists of several tasks related to process management, PID file creation, and handling signals in Bash scripting and C programming. Below are the details and implementation for each task.
Task 9: Process and PID File

Description:

    Bash script to create a PID file, display messages, and handle signals.

Implementation:

    Filename: 100-process_and_pid_file

Task 10: Manage My Process

Description:

    Bash script managing a background process that writes to a file.

Implementation:

    Filename: manage_my_process
    Init Script: 101-manage_my_process

Task 11: Zombie

Description:

    C program creating zombie processes.

Implementation:

    Filename: 102-zombie.c

Instructions for Running Each Task:
Task 9: Process and PID File

    Clone the repository:

    bash

git clone https://github.com/alx-system_engineering-devops.git

Navigate to directory 0x05-processes_and_signals.

Run the Bash script:

    sudo ./100-process_and_pid_file

Task 10: Manage My Process

    Follow steps 1 and 2 from Task 9.

    Run the init script with appropriate arguments:

    sql

sudo ./101-manage_my_process start

arduino

sudo ./101-manage_my_process stop

    sudo ./101-manage_my_process restart

Task 11: Zombie

    Follow steps 1 and 2 from Task 9.

    Compile the C program:

gcc 102-zombie.c -o zombie

Execute the compiled program:

bash

./zombie

In another terminal, check for zombie processes:

perl

    ps aux | grep -e 'Z+.*<defunct>'

Ensure to replace <defunct> with the actual output of your system.

For more details on each task, refer to the respective files in the repository.

Note: Make sure to run scripts and programs with appropriate permissions.

