# Python Online Compiler

Write, Run & Share Python code online using OneCompiler's Python online compiler for free. It's one of the robust, feature-rich online compilers for python language. Getting started with the OneCompiler's Python editor is easy and fast. The editor shows sample boilerplate code when you choose language as Python or Python2. OneCompiler also has reference programs, where you can look for the sample code and start coding.

# Taking inputs (stdin)
OneCompiler's python online editor supports stdin and users can give inputs to programs using the STDIN textbox under the I/O tab. Following is a sample python program which takes name as input and print your name with hello.

```py
import sys
name = sys.stdin.readline()
print("Hello "+ name)
```

# About Python

Python is a very popular general-purpose programming language which was created by Guido van Rossum, and released in 1991. It is very popular for web development and you can build almost anything like mobile apps, web apps, tools, data analytics, machine learning etc. It is designed to be simple and easy like english language. It's is highly productive and efficient making it a very popular language. 

# Tutorial & Syntax help 

## Loops

### 1. If-Else:

When ever you want to perform a set of operations based on a condition IF-ELSE is used.

```py
if conditional-expression
    #code
elif conditional-expression
    #code
else:
    #code
```

### Note:
Indentation is very important in Python, make sure the indentation is followed correctly 

### 2. For:

For loop is used to iterate over arrays(list, tuple, set, dictionary) or strings.

### Example:
```py
mylist=("Iphone","Pixel","Samsung")
for i in mylist:
    print(i)
```

### 3. While:

While is also used to iterate a set of statements based on a condition. Usually while is preferred when number of iterations are not known in advance.

```py
while condition  
    #code 
```


## Collections

There are four types of collections in Python.

### 1. List:
List is a collection which is ordered and can be changed. Lists are specified in square brackets.

### Example:
```py
mylist=["iPhone","Pixel","Samsung"]
print(mylist)
```

### 2. Tuple:
Tuple is a collection which is ordered and can not be changed. Tuples are specified in round brackets.

### Example:
```py
myTuple=("iPhone","Pixel","Samsung")
print(myTuple)
```
Below throws an error if you assign another value to tuple again.
```py
myTuple=("iPhone","Pixel","Samsung")
print(myTuple)
myTuple[1]="onePlus"
print(myTuple)
```

### 3. Set:
Set is a collection which is unordered and unindexed. Sets are specified in curly brackets.

### Example:
```py
myset{"iPhone","Pixel","Samsung"}
print{myset}
```

### 4. Dictionary:

Dictionary is a collection of key value pairs which is unordered, can be changed, and indexed. They are written in curly brackets with key - value pairs. 

### Example:
```py
mydict = {
    "brand" :"iPhone",
    "model": "iPhone 11"
}
print(mydict)
```
