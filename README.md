**Custom UNIX shell completely written in C using prallelism by processes and threads**

## Constraints
- Max characters in a command is 100<br>
- Max words in a command is 10<br>

## Commands
- **cd**
    - for changing directories
- **pwd**
    - for fetching path of present working directory
- **exit**
    - for exiting from the shell
- **ls**
    - **-a**: for listing all the files along with the hidden files
    - **-m**: for listing the files seperated by commas
- **cat**
    - **-E**: for printing the content with highlighting the line endings
    - **-n**: for printing the content with line numbers
- **date**
    - for printing date
- **mkdir**
    - **-m**: for creating a directory with specific permissions
    - **-v**: for verbose(ly) making the directory
- **rm**
    - **-i**: for asking confirmation before removing the file
    - **-v**: for verbose(ly) removing the file
- **help**
    - for getting help; of course
- **echo**
    - for printing something on the shell
- **clear**
    - for clearing the shell
- **else**
    - **&t**: for executing command using threads

## Error handled
- Multiple &t error
- Wrong command error

## How to use

### Step 1
Download all the (.c) files and Makefile

### Step 2
**Run commands**
```
make install
make compile
```

### Step 3
To use the shell; run command `make launch`
