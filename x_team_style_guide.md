# X-Team 64 Style Guide

We will keep our code concise and our methods short.

## Naming conventions

Pascal case will be used to name classes, i.e. "MyClass.java". Camel case will be used to name variables and methods, i.e. "myVariable". Variables will be named with nouns and methods with verbs. Both variables and functions will be named such that their basic functionality can be determined by looking at the name.

### Examples
* interfaces
* classes
* exception types
* fields
* methods
* parameters
* local variables
* instance constants
* class constants

## Commenting style for public and private members of a class or interface:

Inline comments will be used to clarify code that requires further explanation (really important for communications). JavaDoc block comments will be used to document both classes and methods. 

### Examples

* classes
```java
/**
 * Short class description.
 * @param variable description
 */
public void myClass(int variable) {
}
```
* fields
```java
//Comment used to clarify confusing field
```
* constructors
```java
/**
 * Short constructor description
 */
public MyClass() {
}
```
* methods
```java
/**
 * Short method description
 * @param variable description
 */
public void doSomething(int variable) {
}
```
* coding style (brackets, horizontal, and vertical spacing) for:
  * if statements
  ```java
  if(2+2 == 4) {
    //code
  }
  ```
  * switch statement
  ```java
  String output;
  int num = 1;
  switch (num) {
    case 1:  output = "1";
             break;
    case 2:  output = "2";
             break;
    default: output = "none";
             break;
  }
  ```
  * while loops
  ```java
  while(true) {
    //code
  }
  ```
  * for loops
  ```java
  for(int i=0; i<10; i++) {
  }
  ```
  * enhanced for loops
  ```java
  ArrayList<String> myList = new ArrayList<String>();
  myList.add("a");
  
  for(String str : myList) {
    //code
  }
  ```
