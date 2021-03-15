# Module1

## Introduction to Java - Brief introduction to the Java world
* **A small history of Java** 
 
  * Java is a programming language created by James Gosling from Sun Microsystems (Sun) in 1991
  * The target of Java is to write a program once and then run this program on multiple operating systems.
  * The first publicly available version of Java (Java 1.0) was released in 1995. 
  * Sun Microsystems was acquired by the Oracle Corporation in 2010. 
  * Oracle has now the steermanship for Java.
  * Over time new enhanced versions of Java have been released. 
  * Currently we are going to discuss about Java 1.8 which is also known as Java 8

## What is Java
#### Def 1:
  * Java is a programming language and a platform. Java is a high level, robust, object-oriented and secure programming language. (OR)
  * Java is a general-purpose, class-based, object-oriented programming language designed for having lesser implementation dependencies. 
  * It is a computing platform for application development. 
  * Java is fast, secure, and reliable, therefore. 
  * It is widely used for developing Java applications in laptops, data centers, game consoles, scientific supercomputers, cell phones, etc.

## Introduction to Java - Verify the installation of Java JDK 8
* Java download link : https://www.oracle.com/in/java/technologies/javase/javase-jdk8-downloads.html
* Once you installed in your computer , then set Java_Home and class path.
* Check Java installation in your computer bu running beolw command
* java -version

## Introduction to Java - Preparation of the first program - Introduction to variables and operators

* Java  frist program - Example 1

```java
// a small Java program
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello World");
    }
}
```
Output:
```Console
Hello World
```

* Example 2 : Java program using variables

```java
// a small Java program
public class HelloWorld {
   String name = "manuel";
    public static void main(String[] args) {
        System.out.println("Hello +name+ Welcome to Java program");
    }
}
```
Output:
```Console
Hello manuel Welcome to Java program
```

## Introduction to Java - The variables: type, declaration, initialization and assignment

#### What is a Variable in Java?

* Variable in Java is a data container that stores the data values during Java program execution.
* Every variable is assigned data type which designates the type and quantity of value it can hold. 
* Variable is a memory location name of the data. 
* The Java variables have mainly three types : Local, Instance and Static.

* In order to use a variable in a program you to need to perform 2 steps 
* **1. Variable Declaration**
* **2. Variable Initialization**

#### Variable Declaration:

* To declare a variable, you must specify the data type & give the variable a unique name.

![](https://www.guru99.com/images/uploads/2012/07/VriableTypeNameDeclaration.jpg)

* Examples of other Valid Declarations are 

```console
int a,b,c;

float pi;

double d;

char a;
```

##### Variable Initialization:

To initialize a variable, you must assign it a valid value.

![java-varibale-initialization](https://www.guru99.com/images/uploads/2012/07/java-varibale-initialization.jpg)

Example of other Valid Initializations are 

```console
int a=2,b=4,c=6;

float pi=3.14f;

double do=20.22d;

char a=’v’;
```

#### Types of variables

* In Java, there are three types of variables: 

**1.Local Variables**

**2.Instance Variables**

**3. Static Variables**


#### 1) Local Variables

* Local Variables are a variable that are declared inside the body of a method. 

#### 2) Instance Variables

* Instance variables are defined without the STATIC keyword .They are defined Outside a method declaration. They are Object specific and are known as instance variables. 

#### 3) Static Variables

* Static variables are initialized only once, at the start of the program execution. These variables should be initialized first, before the initialization of any instance variables. 

Example: Types of Variables in Java
```java
class Demo {
    static int a = 1; //static variable  
    int data = 99; //instance variable  
    void method() {
        int b = 90; //local variable  
    }
}
```
## Primitive Data Types
#### What is Data Types in Java?

* Data Types in Java are defined as specifiers that allocate different sizes and types of values that can be stored in the variable or an identifier. Java has a rich set of data types. 
* Data types in Java can be divided into two parts : 
* **1.Primitive Data Types :-**  which include integer, character, boolean, and float 
* **2.Non-primitive Data Types :-**  which include classes, arrays and interfaces. 

#### Primitive Data Types

* Primitive Data Types are predefined and available within the Java language. 
* Primitive values do not share state with other primitive values.
* There are 8 primitive types: byte, short, int, long, char, float, double, and boolean Integer data types 

```Console
byte (1 byte)
short (2 bytes)
int (4 bytes)
long (8 bytes)
```
![java-varaibles](https://www.guru99.com/images/uploads/2012/07/java-varaibles.jpg)

#### Floating Data Type 
```Console
float (4 bytes)

double (8 bytes)
```
* char 
```java
(2 bytes)
```
* Logical
```java
boolean (1 byte) (true/false)
```

**Data Type** | **Default Value**  | **Default size**
----------|--------------|---------------
byte      |   0       |      1 byte  
short    |    0       |      2 bytes  
int     |     0       |      4 bytes  
long   |     0L       |     8 bytes  
float  |   0.0f      |      4 bytes  
double   |  0.0d      |      8 bytes  
boolean  |  false     |      1 bit  
char    |  '\u0000'    |     2 bytes  
 
