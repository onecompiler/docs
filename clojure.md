# Clojure online compiler
Write, Run & Share Clojure code online using OneCompiler's Clojure online compiler for free. It's one of the robust, feature-rich online compilers for Clojure language, Getting started with the OneCompiler's Clojure editor is easy and fast. The editor shows sample boilerplate code when you choose language as Clojure and you can also choose hundreds of reference programs to get started. For example, if you want to write a program on Clojure collections choose the collections tag from reference and see hundreds of pre-written programs on collections. You can pick one of them to start your coding. 

# Read inputs from stdin
OneCompiler's Clojure online editor supports stdin and users can give inputs to programs using the STDIN textbox under the I/O tab. Following is a sample Clojure program which takes name as input and prints hello message with your name.

```lisp
(println "Hello" (read-line))
```

# About Clojure

Clojure is a dialect of Lisp and a dynamic general-purpose programming language
* Provides robust infrastructure for multithreaded programming
* Easy access to the Java frameworks
* Compiled language, yet is dynamic in nature

# Syntax help

## variable declaration

```lisp
(def var-name var-value)
```

## Loops

### While
```lisp
(while(expression)
   (do
      statements))
```
### Doseq(similar to for-each)
```lisp
(doseq (sequence)
   statement)
```

### Dotimes
```lisp
(dotimes (variable value)
   statements)
```

### Loop

```lisp
loop [binding]
(condition
   (statement)
   (recur (binding)))
```

## Functions

### Named Function

```lisp
(defn function-name  [parameters]  (codeblock) )
```
### Anonymous Functions
```lisp
(fn  [parameters]  (codeblock) )
```