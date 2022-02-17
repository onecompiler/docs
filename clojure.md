# Clojure online compiler
Write, Run & Share Clojure code online using OneCompiler's Clojure online compiler for free. It's one of the robust, feature-rich online compilers for Clojure language, Getting started with the OneCompiler's Clojure editor is easy and fast. The editor shows sample boilerplate code when you choose language as Clojure and start coding.  

# Read inputs from stdin
OneCompiler's Clojure online editor supports stdin and users can give inputs to programs using the STDIN textbox under the I/O tab. Following is a sample Clojure program which takes name as input and prints hello message with your name.

```py
(println "Hello" (read-line))
```

# About Clojure

Clojure is a dialect of Lisp and a dynamic general-purpose programming language
* Provides robust infrastructure for multithreaded programming
* Easy access to the Java frameworks
* Compiled language, yet is dynamic in nature

# Syntax help

## variable declaration

```py
(def var-name var-value)
```

## Loops

### While
```py
(while(expression)
   (do
      statements))
```
### Doseq(similar to for-each)
```py
(doseq (sequence)
   statement)
```

### Dotimes
```py
(dotimes (variable value)
   statements)
```

### Loop

```py
loop [binding]
(condition
   (statement)
   (recur (binding)))
```

## Functions

### Named Function

```py
(defn function-name  [parameters]  (codeblock) )
```
### Anonymous Functions
```py
(fn  [parameters]  (codeblock) )
```