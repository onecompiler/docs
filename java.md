# Java online compiler
OneCompiler's Java online compiler is one of the robust, feature-rich online compilers for Java language, running the latest Java version which is Java 11. Users can write, run and share the code online and can track all the code history. Getting started with the OnCompiler's Java editor is easy and fast. The editor shows sample boilerplate code when you choose Java language and you can also choose hundreds of reference programs to get started. For example, if you want to write a program on Java collections choose the collections tag from reference and see hundreds of pre-written programs on collections you can pick one of them to start your coding. 

# Taking inputs (stdin)
OneCompiler's Java editor supports stdin and users can give inputs to programs using the STDIN textbox under the I/O tab. Using Scanner class in Java program can read the inputs. Following is a sample program shows how to read STDIN ( A string in this case ).

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
We support Gradle for dependency management. Users can add dependencies in the `build.gradle` file and use them in their programs. When you add the dependencies for the first time the first run might be a little slow as we download the dependencies but the subsequent runs will be faster. Following is a sample Gradle configuration shows how to add dependencies

```groovy
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

