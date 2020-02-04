# VIsual basic (vb.net) Online Compiler

Write, Run & Share VB.net code online using OneCompiler's VB.net online compiler. It's one of the robust, feature-rich online compilers for VB.net language, running on the latest version 16. Getting started with the OneCompiler's VB.net compiler is simple and pretty fast. The editor shows sample boilerplate code when you choose language as `VB.net`. OneCompiler also has reference programs, where you can look for the sample code to get started with.

# Read input from STDIN in VB.net

OneCompiler's VB.net online editor supports stdin and users can give inputs to programs using the STDIN textbox under the I/O tab. Following is a sample VB.net program which takes name as input and prints hello message with your name.

```vb
Public Module Program
	Public Sub Main(args() As string)
	 Dim name as String = Console.ReadLine()          ' Reading input from STDIN
   Console.WriteLine("Hello " & name)           ' Writing output to STDOUT
	End Sub
End Module
```

# About VB.net

Visual Basic is a event driven programming language by Microsoft, first released in the year 1991.

## Key Features

* Beginner's friendly language.
* Simple and object oriented programming language.
* User friendly language and easy to develop GUI based applications.

# Syntax help

## Variables

Variable is a name given to the storage area in order to identify them in our programs.

Simple syntax of Variable declaration is as follows

```vb
Dim variableName [ As [ New ] dataType ] [ = initializer ]
```
### Variable initialization

```vb
variableName = value
```

## Loops and control statements

### 1. If family:

If, If-else, Nested-Ifs are used when you want to perform a certain set of operations based on conditional expressions.

#### If

```vb
If (conditional-expression) Then
' code 
End If   
```

#### If-else
```vb
If (conditional-expression) Then
' code 
Else   
'code if condition is false  
End If   
```

#### Nested-If
```vb
If (conditional-expression) Then
    ' code if above condition is true
    If (conditional-expression) Then
        ' code if above condition is true
        If (conditional-expression) Then
            ' code if above condition is true
        End If
    End If
End If
```

### 2. For-Each:

For-Each loop is used to iterate a set of statements for each element in a collection

```vb
For Each element [ As datatype ] In group
   'code
   [ Continue For ]
   ' code
   [ Exit For ]
   ' code
Next [ element ]
```

### 3. While:

While is also used to iterate a set of statements based on a condition. Usually while is preferred when number of ierations is not known in advance.

```vb
While conditional-expr
    'code
End While  
```
### 4. Do-While:

Do-while is also used to iterate a set of statements based on a condition. It is mostly used when you need to execute the statements atleast once.

```vb
Do
'code
Loop { While | Until } condition-expr
```
## Procedures

Procedure is a sub-routine which contains set of statements. Usually Procedures are written when multiple calls are required to same set of statements which increases re-usuability and modularity.

Procedures are of two types.

### 1. Functions

Functions return a value when they are called.

```vb
[accessModifiers] Function functionName [(parameterList)] As returnType
   'code
End Function
```
### 2. Sub-Procedures

Sub-procedures are similar to functions but they don't return any value.

```vb
Sub ProcedureName (parameterList)
'Code
End Sub
```
