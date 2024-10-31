# Operating-Systems-Semaphores


<img width="404" alt="Screenshot 2024-10-31 at 1 10 01 PM" src="https://github.com/user-attachments/assets/5abcdd64-156f-4886-8503-6121c1ad0c6a">

README: Compilation and Execution Instructions

1. Prerequisites

Ensure the following tools are installed on your system:

C Compiler: GCC (GNU Compiler Collection)
POSIX Shared Memory Support: Typically available on Unix-like systems
POSIX Semaphores Support: Ensure your system supports POSIX semaphores

2. Compilation

Open a terminal and navigate to the directory containing your source code files. Compile the code using GCC with the following command:

bash
Copy code
gcc -o OShw2 OShw2.c 

3. Execution

After successful compilation, execute the program with:

bash
Copy code
./OShw2

4. Expected Output

The program will display messages indicating the progress of each child process and the final counter value upon completion.

5. Troubleshooting

Compilation Errors: Ensure all required libraries are installed and that the code is free of syntax errors.
Runtime Errors: Verify that your system supports POSIX shared memory and semaphores. Consult your system's documentation for enabling these features.
