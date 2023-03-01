___
# 1. Console use
___
## Example 1. (execute python in console)

* The console supports native Python use
* entered into the console the below will print out just like an IDE terminal

```python
>>> print('...Log # 001...')''
```

___



___
# 2. Indentation
___
## Example 1. (indentation syntax)

* Python uses indentation to denote it's wrapped containers
* The indentation denotes that everything on that line is inside of the above line

```python
if x > y
	print('x is greater than y') 
```
___

## Example 2. (spacing rule)

* The number of spaces is irrelevant, pick a standard and stick to it most people use 4

```python
if x > y
	           print('x is greater than y') 
```
___

## Example 3. (multi-line spacing rule)

* The number of spaces matters when using multiple lines the above will throw an error
* The error would be because the indentation on the sub elements doesn't match

```python
if x > y
      print('x is greater than y') 
	                print('x is greater than y')
```
___



___
# 3. Variables
___
## Example 1. (variable declaration)

* Python doesn't need a command to declare a variable simply declare one

```python
x = "Mecha"  
y = "Ophidian"  
print(x)  
print(y)
```
___

## Example 2. (variable declaration)

* You don't need to declare a variable type
* You can also change a type after declaration later in the code

```python
x = 26       # x is of type int  
x = "String" # x is now of type str  
print(x)
```
___



___
# 4. Comments
___
## Example 1. (comment)

* Python comments are like notes that aren't read by the console; declared as followed

```python
#Everything on this line is not run by the code
print('Meanwhile everything on this line is')
```
___

## Example 2. (in-line comment)

* You can add comments at the end of code lines with the same result

```python
print('I will be printed') #I will not be printed
```
___

## Example 3. (multi-line comment)

* The number of spaces matters when using multiple lines the above will throw an error
* The error would be because the indentation on the sub elements doesn't match

```python
"""
Multi
	----TRACK
			----DRIFTING
"""
print('Was that a train drifting bruh?')
```
___



# 4. Section 5
___
## Example 1. (comment)

* Python comments are like notes that aren't read by the console; declared as followed

```python
#Everything on this line is not run by the code
print('Meanwhile everything on this line is')
```
___

## Example 2. (in-line comment)

* You can add comments at the end of code lines with the same result

```python
print('I will be printed') #I will not be printed
```
___

## Example 3. (multi-line comment)

* The number of spaces matters when using multiple lines the above will throw an error
* The error would be because the indentation on the sub elements doesn't match

```python
"""
Multi
	----TRACK
			----DRIFTING
"""
print('Was that a train drifting bruh?')
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