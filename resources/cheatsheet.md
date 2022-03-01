---
jupytext:
  text_representation:
    extension: .md
    format_name: myst
    format_version: 0.13
    jupytext_version: 1.10.0
kernelspec:
  display_name: Python 3
  language: python
  name: python3
---


# Cheatsheet

Patterns and examples of how to accomplish frequent tasks. We will build up
this section together over the course of the semester. 


## Basic Bash file operations

Move one folder up:  
```
cd ..
```  
Move at the top of your directory:  
```
cd 
```   
Move to the specified directory:
```
cd directory
```
Create a file:
```
touch file_name.ext
```
Text editor:
```
nano file_name.ext
```
Display content:
```
cat file_name.ext
```
Create a new folder:
```
mkdir new_folder_name
```
Move a file:
```
mv file_name.ext folder_name_file_is_going_moved_to
```
Move multiple files:
```
mv file_name1.ext file_name2.ext file_name3.ext folder_name_files_are_going_moved_to
```
List files in the current directory:
```
ls
ls -hl  //displays rw-r-r 
ls -G - //folders are colorized
ls -hlG //displays rw-r-r and folders are colorized
```
Show your currect directory:
```
pwd
```
Remove a file:
```
rm file_name.ext
```
Copy a file:
```
cp file_name.ext copied_file_name.ext
```

``` {note} 
1. In every command you can add your directory/ location (ex. docs/file_name.ext).
2. "." dot symbolizes our current location and ".." two dots, one level up in the directory tree.
3. "*" represents any number of unknown characters; creates a pattern (ex. rm pyt*.py removes all files that start on 'pyt' and end with extension py).
```

Delete an empty directory:
```
rmdir directory
```

Since you can't delete a directory with files in it you need to recursively delete the folder and its contents. The ```-R``` is a recursive declaration which tells the terminal to delete the folder, the files within the folder, subfolders, files in the subfolder etc. [Source](https://www.macworld.com/article/222596/command-line-deleting-files-folders-mac-terminal.html)

Delete everything in a directory without confirmation:
```
rm -R directory
```
The ```-i``` is a flag that prompts you if you want to remove each separate file in the directory.

Delete everything in a directory with confirmation:
```
rm -iR directory
```

List the contents of the directory:
```
ls
```

Redirect Output:
  to overwrite an existing file or a create a new file with the given file name:
``
echo "send output to file.txt" > file.txt
``
  to append the output to already existing file or create a new file with the given file name:
  ```
  echo "append output to file.txt >> file.txt
  ```

## Wildcard / Kleene star

The wildcard character in bash `*` works by expanding in place to separate arguments that match whatever pattern you're writing. 

Example, given a directory `stuff/`:
```
stuff/
  a.py
  b.py
  c.py
  other.txt
  another.md
  nested_folder/
```
If we were to run `ls *.py` while in the `stuff/` directory, the command actually run by the computer is `ls a.py b.py c.py`. This also works for commands like `mv`. I.e. `mv *.py nested_folder/` runs `mv a.py b.py c.py nested_folder/`


