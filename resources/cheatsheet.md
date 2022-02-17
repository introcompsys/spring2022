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

Shows the differences between the index file and the current file. Git status displays the current state of the working directory.
```
git status
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

