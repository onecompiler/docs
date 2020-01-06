# Java online compiler
Write, Run & Share Java code online using OneCompiler's Java online compiler. It's one of the robust, feature-rich online compilers for Java language, running the latest Java version which is Java 11. Getting started with the OneCompiler's Java editor is easy and fast. The editor shows sample boilerplate code where you can choose language as Java and you can also choose hundreds of reference programs to get started. For example, if you want to write a program on Java collections choose the collections tag from reference and see hundreds of pre-written programs on collections. You can pick one of them to start your coding. 

# Taking inputs (stdin)
OneCompiler's Java online editor supports stdin and users can give inputs to the programs using the STDIN textbox under the I/O tab. Using Scanner class in Java program can we can read the inputs. Following is a sample program shows how to read STDIN ( A string in this case ).

```java
import java.util.Scanner;
class Input {
    public static void main(String[] args) {
    	Scanner input = new Scanner(System.in);
    	System.out.println("Enter your name: ");
    	String inp = input.next();
    	System.out.println("Hello, " + inp);
    }
}
```

# Adding dependencies 
OneCompiler supports Gradle for dependency management. Users can add dependencies in the `build.gradle` file and use them in their programs. When you add the dependencies for the first time, the first run might be a little slow as we download the dependencies but the subsequent runs will be faster. Following is a sample Gradle configuration shows how to add dependencies

```java
apply plugin:'application'
mainClassName = 'HelloWorld'

run { standardInput = System.in }
sourceSets { main { java { srcDir './' } } }

repositories {
    jcenter()
}

dependencies {
    // add dependencies here like following
    compile group: 'org.apache.commons', name: 'commons-lang3', version: '3.9'
}
```
# About Java

Java is a very popular general-purpose programming language, it is class-based and object-oriented. Java was developed by James Gosling at Sun Microsystems ( later acquired by Oracle) the initial release of Java was in 1995. Java 11 is the latest long-term supported version (LTS). As of today, Java is the world's number one server programming language with a 12 million developer community, 5 million students studying worldwide and it's #1 choice for the cloud development.

# Syntax help 

## Loops
### 1. If Else:

When ever you want to perform a set of operations based on a condition If-Else is used.

```java
if(conditional-expression) {
  // code
} else {
  // code
}
```
### 2. Switch:

Switch is an alternative to If-Else-If ladder and to select one among many blocks of code.

```java
switch(conditional-expression) {    
case value1:    
 // code    
 break;  // optional  
case value2:    
 // code    
 break;  // optional  
...    
    
default:     
 //code to be executed when all the above cases are not matched;    
} 
```
### 3. For:

For loop is used to iterate a set of statements based on a condition. Usually for loop is preferred when number of ierations is known in advance.

```java
for(Initialization; Condition; Increment/decrement){  
//code  
} 
```
### 4. While:

While is also used to iterate a set of statements based on a condition. Usually while is preferred when number of ierations is not known in advance.

```java
while(condition){  
 // code 
}  
```
### 5. Do-While:
Do-while is also used to iterate a set of statements based on a condition. It is mostly used when you need to execute the statements atleast once.

```java
do {
  // code 
} while (condition); 
```
## Classes and Objects

Class is the blueprint of an object, which is also referred as user-defined data type with variables and functions. Object is a basic unit in OOP, and is an instance of the class.

### How to create a Class:

`class` keyword is required to create a class.

### Example:

```java
class Mobile {
    public:    // access specifier which specifies that accessibility of class members 
    string name; // string variable (attribute)
    int price; // int variable (attribute)
};

```
### How to create a Object:

```java
Mobile m1;
```
### How to define methods in a class:

```java
public class Greeting {
    static void hello() {
        System.out.println("Hello.. Happy learning!!");
    }

    public static void main(String[] args) {
        hello();
    }
}
``` 

## Collections

Collection is a group of objects which can be represented as a single unit. Collections are introduced to bring a unified common interface to all the objects.

Collection Framework was introduced since JDK 1.2 which is used to represent and manage Collections and it contains:

1. Interfaces
2. Classes
3. Algorithms

This framework also defines map interfaces and several classes in addition to Collections.

### Advantages:
* High performance
* Reduces developer's effort
* Unified architecture which has common methods for all objects.

|Collection|Description|
|-----|-----|
|Set| Set is a collection of elements which can not contain duplicate values. Set is implemented in HashSets, LinkedHashSets, TreeSet etc|
|List| List is a ordered collection of elements which can have duplicates. Lists are classified into ArrayList, LinkedList, Vectors|
|Queue| FIFO approach, while instantiating Queue interface you can either choose LinkedList or PriorityQueue.|
|Deque| Deque(Double Ended Queue) is used to add or remove elements from both the ends of the Queue(both head and tail)|
|Map| Map contains key-values pairs which don't have any duplicates. Map is implemented in HashMap, TreeMap etc.|




