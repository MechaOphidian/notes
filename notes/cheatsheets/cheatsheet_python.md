___
# Console use
```Markdown

The console supports native Python use

form1
`>>> print('...Log # 001...')''`

entered into the console the above will print out just like an IDE terminal

```
___
# Indentation
```Markdown
Python uses indentation to denote it's wrapped containers

form1

if x > y
	print('x is greater than y') 

The indentation denotes that everything on that line is inside of the above line

form2

if x > y
	           print('x is greater than y') 

The number of spaces is irrelevant, pick a standard and stick to it most people use 4

form3

if x > y
      print('x is greater than y') 
	                print('x is greater than y') 

The number of spaces matters when using multiple lines the above will throw an error
The error would be because the indentation on the sub elements doesn't match
```
___
# Variables
```Markdown
Python doesn't need a command to declare a variable simply declare one

form1

x = 1
```
___
# Comments
```Markdown
Python comments are like notes that aren't read by the console; declared as followed

form1

#Everything on this line is not run by the code
print('Meanwhile everything on this line is')
```
___

















































# Python Package Management

## Interacting with `pip` as a **python module**

### NOTE: **_Required_** for updating `pip` on Windows

`python -m pip`

## Checking for updates to `pip` and installed packages
`pip list -o`

## Updating `pip` with `pip` (Windows Only!)

#### NOTE: `pip` gets updated before anything else!

`python -m pip install -U pip`

## Updating packages

### `wheel` and `setuptools` ***ALWAYS*** get installed and updated before other packages!

`python -m pip install -U wheel setuptools`

## Updating & Installing package lists with `pip`

### NOTE: Version controlled lists are accepted, otherwise tries newest versions. 

`python -m pip install -r requirements.txt`

## Using `pip` to freeze relevant packages for `requirements.txt`, overwriting existing file in pwd.

`pip freeze > requirements.txt`