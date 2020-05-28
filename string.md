## string

Python everything is object

string 双引号 "i'm string"

substring 用 square brackets var1[0], var2[2:5]

string操作

| []     |      |      |
| ------ | ---- | ---- |
| [:]    |      |      |
| in     |      |      |
| not in |      |      |
| r/R    |      |      |
| %      |      |      |
| +      |      |      |
| *      |      |      |

## Summary:

Since Python is an object-oriented programming language, many functions can be applied to Python objects. A notable feature of Python is its indenting source statements to make the code easier to read.

- Accessing values through slicing - square brackets are used for slicing along with the index or indices to obtain a substring.
  - In slicing, if range is declared [1:5], it can actually fetch the value from range [1:4]
- You can update Python String by re-assigning a variable to another string
- Method replace() returns a copy of the string in which the occurrence of old is replaced with new.
  - Syntax for method replace: oldstring.replace("value to change","value to be replaced")
- String operators like [], [ : ], in, Not in, etc. can be applied to concatenate the string, fetching or inserting specific characters into the string, or to check whether certain character exist in the string
- Other string operations include
  - Changing upper and lower case
  - Join function to glue any character into the string
  - Reversing string
  - Split string