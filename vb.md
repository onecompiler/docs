# Visual basic (VB.net) Online Compiler

Write, Run & Share VB.net code online using OneCompiler's VB.net online compiler for free. It's one of the robust, feature-rich online compilers for VB.net language, running on the latest version 16. Getting started with the OneCompiler's VB.net compiler is simple and pretty fast. The editor shows sample boilerplate code when you choose language as `VB.net`. OneCompiler also has reference programs, where you can look for the sample code to get started with.

# Read input from STDIN in VB.net

OneCompiler's VB.net online editor supports stdin and users can give inputs to programs using the STDIN textbox under the I/O tab. Following is a sample VB.net program which takes name as input and prints hello message with your name.

```vb
Public Module Program
	Public Sub Main(args() As string)
	 Dim name as String = Console.ReadLine()    ' Reading input from STDIN
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

## Conditional Statements

### 1. If

```vb
If condition-expression Then 
    'code
End If
```
### 2. If-else

```vb
If(conditional-expression)Then
   'code if the conditional-expression is true 
Else
  'code if the conditional-expression is false 
End If
```

### 3. If-else-if ladder

```vb
If(conditional-expression)Then
   'code if the above conditional-expression is true 
Else If(conditional-expression) Then
        'code if the above conditional-expression is true 
    Else
        'code if the above conditional-expression is false 
End If
```

### 4. Nested-If

```vb
If(conditional-expression)Then
   'code if the above conditional-expression is true
   If(conditional-expression)Then
         'code if the above conditional-expression is true 
   End If
End If
```

### 5. Select Case

```vb
Select [ Case ] expression
   [ Case expressionlist
      'code ]
   [ Case Else
      'code ]
End Select
```
## Loops

### 1. For..Next

```vb
For counter [ As datatype ] = begin To end [ Step step ]
   'code
   [ Continue For ]
   'code
   [ Exit For ]
   'code
Next [ counter ]
```

### 2. For..Each

```vb
For Each element [ As datatype ] In group
   'code
   [ Continue For ]
   'code
   [ Exit For ]
   'code
Next [ element ]
```

### 3. While

```vb
While conditional-expression
   'Code 
   [ Continue While ]
   'Code
   [ Exit While ]
   'Code
End While
```
### 4. Do-while

```vb
Do { While | Until } conditional-expression
   'Code
   [ Continue Do ]
   'Code
   [ Exit Do ]
   'Code
Loop
```
```vb
Do
   'Code
   [ Continue Do ]
   'Code
   [ Exit Do ]
   'Code
Loop { While | Until } conditional-expression
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
