# Linux Basic Commands

### echo:
- prints out statements on shell
- e.g echo 'Hello Linux!'


### list all directories:
   - ls
   - ls -a (hidden directories also)
   - ls -R (will show subdirectories as well)
   - ls -al (detailed info, permissions etc)

### current working directory
  - pwd

### Move files
  - mv <file_name> <destination>

### Rename files
  - mv <old_name> <new_name>

### create folder/directory
  - mkdir <folder_name>

### create new file
  - touch <file_path/name>
  - e.g "touch /home/username/test.py"

### “>” and “>>”:
  - represent **output redirection**. redirect the result of output
  - Inputs and outputs of a command can be redirected to another command or a file using redirection operators.
  - '>' creates a new file or overwrites an already existing file
    - e.g: echo "Welcome to Linux" > my_file.txt
  - “>>” operator appends an already present file or creates a new file if that file name doesn’t exist in the directory.
   - e.d: echo 'welcome to Linux!' >> my_file.txt

### system information:
  - sudo lshw -short
  - lscpu  (cpu information)
  
### OS version:
	- lsb_release -d

### close the console:
   - exit
