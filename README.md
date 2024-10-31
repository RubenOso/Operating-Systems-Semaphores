# Operating-Systems-Semaphores

<img width="464" alt="Screenshot 2024-10-29 at 10 17 48 PM" src="https://github.com/user-attachments/assets/41337700-40d8-4b5d-9936-cba4873f764d">

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
-o OShw2 specifies the output executable name
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
