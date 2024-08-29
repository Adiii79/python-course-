# Strings 
- Strings is surrounded by either single quotation marks , or double quotation marks.

    Ex: "Aditya" is same as 'Aditya'

###  - Slicing in python 
- in slicing you can return a range of character. Slicing , written as, the start index and the end index, seprated by colon.

  ``` 
   Ex:  b = "Hello, World!" 
        print(b[2:5]) // ity 
   ```
### - Slicing from the start 
- If you leaving the start index , the range will start from the first character.
```
    b="Aditya sharma"
    print(b[:5])  // Aditya
```
### - Slicing from the end 
- If you leaving the end index , the range will end index.
```
    b="Aditya sharma"
    print(b[2:]) // ity sharma
```
# Modify Strings
### - Upper case
- return value in upper case.
```
   a="Hello world!"
   print(a.upper()) // HELLO WORLD!
```
### - Lower case
- return value in lower case.
```
  a="Hello world!"
  print(a.upper()) // hello world!
```
### - Remove Whitespace
-  The strip() method removes any whitespaces from beging or the end .
```
  a = " Hello, World! "
  print(a.strip()) // "Hello, World!"
```
### - Replace String
- Replace a string with another string.
```
  a = "Hello, World!"
  print(a.replace("H", "J")) // Jello, World!
```
### - Split String
- split the string into two diffrent parts. 
```
  a = "Hello, World!"
  print(a.split(",")) // ['Hello', ' World!']
```
### - String Concatenation
- combine, two strings you can use the + operator.
```
  a = "Aditya"
  b = "Sharma"
  c = a + b
  print(c)  // AdityaSharma
```
# String Format
- We canot combine and number together, like this,
```
  age = 36
  txt = "My name is John, I am " + age
  print(txt)  
  
  // Traceback (most recent call last):
  File "demo_string_format_error.py", line 2, in <module>
    txt = "My name is John, I am " + age
TypeError: must be str, not int
```
### - F string
- in python, Simply put an F in front of the string and add early bracket {} as placeholders for variable amd other operations. 
```
  age = 36
  txt = f"I am a student, I am {age} year old"
  print(txt)  
  
  // I am a student, I am 36 year old
```
- for decimal value, A modifier is included by adding a colon : followed by a legal formatting type, like .2f which means fixed point number with 2 decimals:
```
  price = 36
  txt = f"In market price of a onion is {price.2F} rupees.
  print(txt)  
  
  //In market price of a onion is 36.00 rupees.
```
## Escape Character
```
\'	      Single Quote
\\	      Backslash	
\n	      New Line	
\r	      Carriage Return	
\t	      Tab	
\b	      Backspace	
\f	      Form Feed	
\ooo	  Octal value	
\xhh	  Hex value	
```
## Some Strings Method
```
Method	                                   Description

capitalize()	           Converts the first character to upper case
casefold()	               Converts string into lower case
center()	               Returns a centered string
count()	                   Returns the number of times a specified value occurs in a string
encode()	               Returns an encoded version of the string
endswith()	               Returns true if the string ends with the specified value
expandtabs()	           Sets the tab size of the string
find()	                   Searches the string for a specified value and returns the position of where it was found

format()	               Formats specified values in a string
format_map()	           Formats specified values in a string
index()	                   Searches the string for a specified value and returns the position of where it was found

isalnum()	               Returns True if all characters in the string are alphanumeric
isalpha()	               Returns True if all characters in the string are in the alphabet
isascii()              	   Returns True if all characters in the string are ascii characters
isdecimal()	               Returns True if all characters in the string are decimals
isdigit()	               Returns True if all characters in the string are digits
isidentifier()	           Returns True if the string is an identifier
islower()	               Returns True if all characters in the string are lower case
isnumeric()	               Returns True if all characters in the string are numeric
isprintable()	           Returns True if all characters in the string are printable
isspace()	               Returns True if all characters in the string are whitespaces
istitle()	               Returns True if the string follows the rules of a title
isupper()	               Returns True if all characters in the string are upper case
join()	                   Joins the elements of an iterable to the end of the string
ljust()	                   Returns a left justified version of the string
lower()	                   Converts a string into lower case
lstrip()	               Returns a left trim version of the string
maketrans()	               Returns a translation table to be used in translations
partition()	               Returns a tuple where the string is parted into three parts
replace()	               Returns a string where a specified value is replaced with a    specified value

rfind()	                   Searches the string for a specified value and returns the last position of where it was found

rindex()	               Searches the string for a specified value and returns the last position of where it was found

rjust()	                   Returns a right justified version of the string
rpartition()           	   Returns a tuple where the string is parted into three parts
rsplit()	               Splits the string at the specified separator, and returns a list
rstrip()	               Returns a right trim version of the string
split()	                   Splits the string at the specified separator, and returns a list
splitlines()	           Splits the string at line breaks and returns a list
startswith()	           Returns true if the string starts with the specified value
strip()	                   Returns a trimmed version of the string
swapcase()	               Swaps cases, lower case becomes upper case and vice versa
title()	                   Converts the first character of each word to upper case
translate()	               Returns a translated string
upper()	                   Converts a string into upper case
zfill()	                   Fills the string with a specified number of 0 values at the beginning
```

updated strings.md





 
    


      





    