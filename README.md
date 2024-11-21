# Linux-Custom_shell
Welcome to our Custom Shell ! 
This is a simple shell implementation written in C that mimics the behavior of a command-line interface (CLI) with several built-in commands for file management, system information, and more.

# Features
Directory Management: Change directories (cd), list files (list), and create new files/folders (create).

File Operations: Copy (copy), move (move), rename (rename), and delete (delete) files.

System Information: Check CPU usage (cpu), disk usage (diskusage), and find file size (findsize).

File Search: Search for a file by name within the current directory.

Text File Creation: Create files directly from user input (create_from_text).

File Merging: Merge the contents of two files into one (merge).

User-Friendly Interface: Displays a welcoming message with available commands.

# Commands
Below is the list of available commands you can use in this custom shell:

cd <directory>: Change the working directory.


exit: Exit the shell.

copy <src> <dest>: Copy a file from source to destination.

move <src> <dest>: Move a file from source to destination.

rename <old> <new>: Rename a file or folder.

cpu: Display CPU usage.

delete <file>: Delete a specified file with a confirmation prompt.

create <file/folder>: Create a new file or folder.

list: List all files and folders in the current directory.

findsize <file>: Find the size of a specified file.

search <file>: Search for a file by name within the current directory.

diskusage: Display disk usage of the system.

merge <file1> <file2>: Merge two files into one.

create_from_text: Create a file from user input text.

# Installation
Clone this repository to your local machine:

git clone https://github.com/yourusername/custom-shell.git

cd custom-shell

Compile the project:

gcc -o myshell myshell.c

Run the shell:

./myshell

# Usage
Once the shell is running, you can use the various commands as listed above. To exit the shell, type exit.

# Contributions
Feel free to fork the repository and contribute to the project by opening pull requests or reporting issues.

