<!--
NOTES:
This README provides instructions for compiling and running the "readdir.c", "readdir_v2.c", and "printstat.c" programs. It aims to be clear and concise, following basic documentation conventions.
-->

# Compilation and Execution Instructions

## Compilation Instructions

1. **Download the source code files:**

   Ensure you have the source code files downloaded to your local machine.

2. **Install a C compiler (gcc):**

   If not already installed, ensure you have a C compiler such as gcc installed on your system. You can download and install gcc from the official GNU website [gcc.gnu.org](https://gcc.gnu.org/) or via a package manager on Unix-like systems (e.g., apt, yum, brew).

3. **Open a Terminal/Command Prompt:**

   Navigate to the directory where the source code files are located using the terminal/command prompt.

4. **Compile the programs:**

   Use the following commands to compile each program:

   ```bash
   gcc readdir.c -o readdir
   gcc readdir_v2.c -o readdir_v2
   gcc printstat.c -o printstat
