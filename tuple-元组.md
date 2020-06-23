## tuple

tuple 使用() **parentheses** ，不能改变

```
Tup = ('Jan','feb','march')
```

```
tup1 = ();
```

```
Tup1 = (50,);  #只有一个值，后面需要跟, comma
```

## Packing and Unpacking

```
x = ("Guru99", 20, "Education")    # tuple packing
(company, emp, profile) = x    # tuple unpacking
print(company)
print(emp)
print(profile)
```

## 比较

```
a=(5,6)
b=(5,4)
if (a>b):print("a is bigger")
else: print ("b is bigger")
```

output

```
a is bigger
```

5>5 which is inconclusive 5>5不确定，所以比较下一个

## tuple用作词典的key

 tuples are hashable



**Summary**:

Python has tuple assignment feature which enables you to assign more than one variable at a time.

- Packing and Unpacking of Tuples
  - In packing, we place value into a new tuple while in unpacking we extract those values back into variables.
- A comparison operator in Python can work with tuples.
- Using tuples as keys in dictionaries
  - Tuples are hashable, and list are not
  - We must use tuple as the key if we need to create a composite key to use in a dictionary
  - Dictionary can return the list of tuples by calling items, where each tuple is a key value pair
- Tuples are immutable and cannot be deleted. You cannot delete or remove items from a tuple. But deleting tuple entirely is possible by using the keyword "del"
- To fetch specific sets of sub-elements from tuple or list, we use this unique function called slicing