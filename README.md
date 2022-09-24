## Basic Python

**1. Data Type**
- Integer
* Integers are zero, positive or negative whole numbers without a fractional part and having unlimited precision
- Float
* Float value specified with a decimal point
- Boolean
* Two type of value in the boolean data type is True or False
- Complex
* Complex numbers is represented as A+Bj, where A is real part and B is imaginary part
- String
* Strings are sequences of character data, strings in python are surrounded by either single quotation marks (' '), or double quotation marks (" ")

**2. List**
- List define by using square brackets [ ], list items are ordered, changeable, allow duplicate values and indexed, the first item has index [0], the second item has index [1] etc

- Change item in the list
  * Append
    add new item in the list, by default the new item would add in the end of thr list
  * Delete
    delete item in the list
    syntax = del variabel[index]
  * Extend
    add new items more than one, by default the new item would add in the end of the list
    syntax = variabel.extend([item 1,item 2])
  * Pop
    The pop() use to remove the item at the given index from the list and returns the removed item
    syntax = variabel.pop(index)
  * Insert
    add new items in certain position
    syntax = variabel.insert(index,item)
- Slicing
* To access a range of elements in a list
* Syntax = Lst[ Initial : End : IndexJump ]
- Count
* Count he number of accurences of an element
* Syntax = Variabel.count(item)
- Sort
* Sorts the list, by default asc
* reverse = true --> desc
* Syntax = variabel.sort()

**3. Slicing in string**
- String is mutable objects, and mutable object can be changed after it is created, you can return a range of characters by using the slice syntax

**4. Tuple**
- Tuples are used to store multiple items in a single variable, a tuple is a collection which is ordered, unchangeable and define by parenthesis ( )

**5. Set**
- Sets are used to store multiple items in a single variable, must be uniqe, define by brackets { }, set is a collection which is unordered, unchangeable, and unindexed

- Union
* Returns a set that contains all items from the original set, and all items from the specified set(s)

- Intersection
* Returns set contains only items that exist in both sets or in all sets if the comparison is done with more than two sets

**6. Dictionary**
- Dictionaries are used to store data values in key:value pairs, define by brackets { }, a dictionary is a collection which is unordered, changeable and do not allow duplicates

**7. Number, Character and String Transformation**
- uppercase
* Return the string to upper case
- lowercase
* Return the string to lower case
- rstrip
* Remove the right whitespace
- lstrip
* Remove the left whitespace
- strip
* The strip() method removes any leading (spaces at the beginning) and trailing (spaces at the end) characters (space is the default leading character to remove)
- Startswith
* The startswith() method returns True if the string starts with the specified value, otherwise False
- Endswith
* The endswith() method returns True if the string end with the specified value, otherwise False

**8. Conversion between Data Type**
- Type conversion is the process of converting one data type to another

**9. Change Element in the String**
- Replace specified phrase with another specified phrase, syntax = variable.replace(old element, new elemen, count)

**10. Input Output**
- Input
* Input is any data, information, or value that is sent by the user
- Output
* Output is the value or data which is the result of the program

**11. String Check**
- isupper
* Returns “True” if all the characters in the string are uppercase; otherwise, It returns “False”
- islower
* Rethod returns “True” if all the characters in the string are lowercase; otherwise, it returns “False”
- isaplha
* Returns True if a string contains characters that are classified as a letter in the Unicode character database
- isalnum
* Returns True if all the characters are alphanumeric, meaning alphabet letter (a-z) and numbers (0-9)
- isdecimal
* Returns true if a character is an integer in the Base-10 number system
- isspace
* classification method returns true if the string represents a whitespace character (space, tab, or newline including \t, \r, \n)
- istitle
* Returns True if all words in a text start with a upper case letter and the rest of the word are lower case letters, otherwise False, symbols and numbers are ignored

**12. String Formatting**
- Zfill
* Adds zeros (0) at the beginning of the string, until it reaches the specified length, the chacaracter must be less or equal to the zfill value
- rjust and ljust
returns a new string of given length after substituting a given character in left or right side of original string
- Center
* Would center align the string, using a specified character (space is default) as the fill character
- String literal
* Specify the contents of a string in a program, string literals can use single or double quote
- Escape character
* To allow input the character such as ' and "in the string, use backlash \
- Raw string
* Created by prefixing a string literal with ‘r’ or ‘R’, python raw string treats backslash () as a literal character, this is useful when we want to have a string that contains backslash and don’t want it to be treated as an escape character

    
