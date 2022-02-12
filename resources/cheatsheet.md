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
