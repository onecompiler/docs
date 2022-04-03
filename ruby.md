# Ruby Online Compiler

Write, Run & Share Ruby code online using OneCompiler's Ruby online compiler for free. It's one of the robust, feature-rich online compilers for Ruby language, running on the latest version 2.3.1. Getting started with the OneCompiler's Ruby compiler is simple and pretty fast. The editor shows sample boilerplate code when you choose language as `Ruby` and start coding. 

# Read input from STDIN in Ruby

OneCompiler's Ruby online editor supports stdin and users can give inputs to programs using the STDIN textbox under the I/O tab. Following is a sample Ruby program which takes name as input and prints hello message with your name.

```ruby
name = gets.chomp               
print "Hello #{name}.\n" 
```

# About Ruby

Ruby is a general purpose object oriented programming language developed by Yukihiro Matsumoto.

## Key features

* More commonly used in Rails applications.
* Concise and simple to read and powerful too.
* Open-source
* Expressive features and visual appearance
* Flexible language

# Syntax help

## Data types

|Data type|	Description| Usage|
|----|----|----|
|Fixnum| Represents normal numbers|	x = 10|
|Bignum| Represents big numbers|	x =9999999999|
|Float| Represents decimal numbers|	x = 3.14|
|Complex| Represents imaginary numbers|	x = 1 + 2i|
|Rational| Represents fractional numbers| x = 1/4|
|BigDecimal| Represents precision decimal numbers| x=1.0|
|Hash| Represents key value pairs|{"Website"=>"onecompiler","message" => "Happy learning"}|

## Variables

In Ruby, there is no need to explicitly declare variables to reserve memory space. When you assign a value to a variable, declaration happens automatically and a prefix is needed to indicate the following variable types.

|Variable type|Description|
|----|----|
|Local variables|Scope is limited to the block of the variable initialization. Variable name must start with either `_` or lowercase letter. |
|Class variables|Class variables belongs to whole class and can be accessible anywhere inside the class. Variable name must start with `@@`. They must be initialized before use.|
|Instance variables|Instance variables belongs to a instance of the class. They can be accessed from any instance of the class within a method. Variable name must start `@`|
|Global variables|Scope is global and hence they can be accessible anywhere in the program. Variable name must start with `$`|

## Loops and conditional statements

### 1. If family:

If, If-else, Nested-Ifs are used when you want to perform a certain set of operations based on conditional expressions.

#### If

```ruby
if(conditional-expression)
    #code    
end
```

#### If-else
```ruby
if(conditional-expression)  
    #code if condition is true  
else   
    #code if condition is false  
end 
```

#### Nested-If-else
```ruby
if(condition-expression1)   
    #code if above condition is true  
 elsif(condition-expression2)  
    #code if above condition is true  
elsif(condition-expression3)   
    #code if above condition is true  
...  
else   
    #code if all the conditions are false  
end  
```

### 2. Case:

Case is similar to Switch statement, where it is used to execute one set of a statement from multiple conditions.

```ruby
case expression  
[when expression [, expression ...] [then]  
   # code ]...  
[else  
   # code ]  
end  
```

### 3. For:

For loop is used to iterate a set of statements based on a condition.

```ruby
for variable in expression do   
  # code  
end
```
### 4. While:

While is also used to iterate a set of statements based on a condition. Usually while is preferred when number of iterations are not known in advance.

```ruby
while condition do   
 # code 
end  
```
### 5. Do-while:

Do-while is also used to iterate a set of statements based on a condition. It is mostly used when you need to execute the statements atleast once.

```ruby
loop do   
  #code  
  break if conditional-expression  
end 
```
