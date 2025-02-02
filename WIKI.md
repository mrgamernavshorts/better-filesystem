# **Welcome to the betterfilesystem WIKI!**
<img src="https://i.imgur.com/lEHFOv7.png" width="500px" style="border-radius: 20px;">

Here, you will learn to use the `betterfilesysytem` lib!

## Installation
open the terminal, and paste the following command:
```terminal
pip install betterfilesystem
```
<span style="color: green;">Congrats!</span> you have installed the `betterfilesystem` lib!

## Useage
Create the `main.py` file and paste this code to access it:
```python
from betterfilesystem import *
```
This will import the Library.

## Functions
There are various Functions in the `better filesystem` lib like `createfile`,  `deletefile`, `readfile`, `editfile`, `move`, `create_dir` and `delete_dir`.

The `createfile` function uses 2 parameters:
```python
createfile(filename, filecontent)
```
This will create a file.

The `deletefile` function takes only 1 parameter:
```python
deletefile(filepath)
```
this will delete the file.

The `readfile` function takes 1 parameter also:
```python
variable_name = readfile(filepath)
```
This will return the contents of the file.so, you need to store it in an variable Like mentioned above.

The `editfile` function takes 2 parameters:
```python
editfile(filename, filecontent)
```
It just calls the `createfile()` function inside it. this function is created for better Grammatical Understanding <span style="color: grey;">*or whateaver you call It.*</span>

The `move` function takes 2 parameters:
```python
move(currentpath, movedpath)
```
This will move a file.

The `create_dir` function takes 1 parameter:
```python
create_dir(directory)
```
This will create a directory and also support the creation of **Nested Directories**.

The `delete_dir` function takes 2 parameters:
```python
delete_dir(directory)
```
This will Delete a Directory or or Nested Directories.