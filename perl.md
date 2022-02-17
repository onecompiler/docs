# Perl Online Compiler

Write, Run & Share Perl code online using OneCompiler's Perl online compiler for free. It's one of the robust, feature-rich online compilers for Perl language, running on the latest version 5.22.1. Getting started with the OneCompiler's Perl compiler is simple and pretty fast. The editor shows sample boilerplate code when you choose language as `Perl` and start coding. 

# Taking inputs (stdin)

OneCompiler's Perl online editor supports stdin and users can give inputs to programs using the STDIN textbox under the I/O tab. Following is a sample Perl program which takes name as input and prints hello message with your name.

```perl
my $name = <STDIN>;             
print "Hello $name.\n";          
```
# About Perl

Perl(Practical Extraction and Report Language) is especially desined for text processing by Larry Wall. 

## Key features
* Cross-platform
* Efficient for mission critical applications.
* Open-source
* Supports both procedural and object-oriented programming.
* Perl interpreter is embeddable with other systems.
* Loosely typed language

# Syntax help

## Data types

There is no need to specify the type of the data in Perl as it is loosely typed language. 

|Type|Description|Usage|
|----|----|----|
|Scalar|Scalar is either a number or a string or an address of a variable(reference)|$var|
|Arrays|Array is an ordered list of scalars, you can access arrays with indexes which starts from 0|@arr = (1,2,3)|
|Hash|Hash is an unordered set of key/value pairs|%ul = (1,'foo', 2, 'bar)|


## Variables

In Perl, there is no need to explicitly declare variables to reserve memory space. When you assign a value to a variable, declaration happens automatically.

```perl
$var-name =value; #scalar-variable
@arr-name = (values); #Array-variables
%hashes = (key-value pairs); # Hash-variables 
```
## Loops

### 1. If family:

If, If-else, Nested-Ifs are used when you want to perform a certain set of operations based on conditional expressions.

#### If

```perl
if(conditional-expression){    
//code    
} 
```

#### If-else
```perl
if(conditional-expression){  
//code if condition is true  
}else{  
//code if condition is false  
} 
```

#### Nested-If-else
```perl
if(condition-expression1){  
//code if above condition is true  
}else if(condition-expression2){  
//code if above condition is true  
}  
else if(condition-expression3){  
//code if above condition is true  
}  
...  
else{  
//code if all the conditions are false  
}  
```

### 2. Switch:

There is no case or switch in perl, instead we use given and when to check the code for multiple conditions.

```perl
given(expr){    
when (value1)  
{//code if above value is matched;}    
when (value2)  
{//code if above value is matched;}   
when (value3)  
{//code if above value is matched;}  
default  
{//code if all the above cases are not matched.}     
} 
```

### 3. For:

For loop is used to iterate a set of statements based on a condition.

```perl
for(Initialization; Condition; Increment/decrement){  
  // code  
} 
```


### 4. While:

While is also used to iterate a set of statements based on a condition. Usually while is preferred when number of iterations are not known in advance.

```perl
while(condition) {  
 // code 
}  
```
### 5. Do-While:

Do-while is also used to iterate a set of statements based on a condition. It is mostly used when you need to execute the statements atleast once.

```perl
do {
  // code 
} while (condition); 
```

## Sub-routines

Sub-routines are similar to functions which contains set of statements. Usually sub-routines are written when multiple calls are required to same set of statements which increases re-usuability and modularity.

### How to define a sub-routine
```perl
sub subroutine_name 
{
	# set of Statements
}
```

### How to call a sub-routine
```perl
subroutine_name();
subroutine_name(arguments-list); // if arguments are present 
```
