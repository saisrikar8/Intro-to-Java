>.java file = All of our code

>.md file = Text, defenitions, etc.

___

## Intro to Java

Java Program can be characterized as an **object** represented in a **class**. Currently, our program as a *Main* object. Inside of this object, we can have the *Main* class.


```java
class Main {
  public static void main(String[] args) { // Main Method
    System.out.print("Hello world!"); // Output to console
		
	}
}
```
___

## Comments

A comment is used as a user annotation with the purpose of being human readable. 

**Line Comments** follow double backslashes: `//`

**Block Commments** are contained within `/* Comments */`

___

## Identifiers

In Java, use the term __identifier__ to describe a variable, parameter, constant, user-defined method, or user-defined class.

- Cannot begin with digit
- Can only contain letters, digits, and and underscores
- Case-senstive `age != Age`

*Note: *

- *class name starts with a capital letter*

- *reserved words are entirely lowercase and may not be used as Identifiers*

## Types ##

**Primitive** or **built-in** types in Java are

- `int`: An Integer
- `boolean`: True or False (boolean shirtColor = false)
`double`: floating-point number (2.73)
- `char`: single character

*Note: Integers have a fixed amount of memory, so there is a limit to how many digits you can store(2^31 - 1)*

## Variables ##
Variables are a type of identifier that stores a value of a specific type.

We can create variables using **declaration**

- `int age;`
- `double x, y;`
- `boolean found;`
- `char letter;`

We can alse intitialize a variable in its **declaration**.
- `int count = 1;`
- `double p = 3.14`;
- `char c = '8'`

## Chars ##
[Ascii Chart](https://docs.google.com/document/d/1oubLTqAHmdkadtjbR8xxREG7auvuUqiQ/edit)

Each character is associated with an ASCII value. 

## Type cast ##

One type can be cast to another compatible type if appropriate.

```java
char letter = 'c';`

int value = (int)letter;

```
___

The code below shows another example.

``` java
int total, n;
double average;
average = (double)total/n; //total cast to double to ensure real division is used
```

*Note: Casting a floating-point number to an integer simply truncates the number (rounds down)*
___

## Final Variables

A *final variable* or *user-defined constant*, identified by the keyword `final`, is a quantity whose value will not change..
___

An example is shown below.

```java
final double TAX_RATE = 0.08;
```
___
- Constant identifiers are, by convention, capitalized.
- `final` variable can be declared without initializing immediately.