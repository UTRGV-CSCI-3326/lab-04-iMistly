[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=17897565)
# Lab Assignment 04

In this lab you will practice writing Java code to **convert data types**.

Same as the previous labs, you need to set up your workspace (class and main() method).

## Let's get started!

First, let's look at the name of our .java file in the `src/` directory and name our class accordingly and remember to make it `public`. Next, **create your main() method inside your class**.

Now let's begin!

### Numerical Type Casting

In Java, using type casting is the fastest way to convert your numerical data types. Simply write the name of the desired numerical data type in front of your variable wrapped around parenthesis ().

**Example:**
```cpp
int wholeNum = 5;
float realNum = (float) wholeNum;
```

For more information on type casting in Java visit: https://www.w3schools.com/java/java_type_casting.asp

### String Conversion

To convert a numerical data type to a String we can take advantage of Java's automatic type conversion to String feature.

**Example:**
```cpp
int num = 7;
String text = "" + num;
```

Easy peasy!

Now, to convert a String to a numerical data type we need to call upon the class of the desired data type and invoke their parse method.

| Method | Description |
| --- | --- |
| Integer.parseInt( *string_value* ) | Converts a string value into an integer value and returns it. |
| Long.parseLong( *string_value* ) | Converts a string value into a long value and returns it. |
| Float.parseFloat( *string_value* ) | Converts a string value into a float value and returns it. |
| Double.parseDouble( *string_value* ) | Converts a string value into a double value and returns it. |

**Example:**
```cpp
int num = Integer.parseInt("123");
```

For more information on String conversion in Java visit: https://www.w3schools.in/java/examples/convert-string-int or https://www.javatpoint.com/java-string-to-double 

## Your Assignment

### Data Convertion

For this assignment you will practice the various conversion methods covered in lecture.

Copy the code snippet below and paste it inside your **main() method** in your java file.

```cpp
// Convert the string strFloat into a float.
String strFloat = "374.25";
float from_strFloat; // assign here

// Convert the string strInt into an integer.
String strInt = "1250";
int from_strInt; // assign here

// Convert the float floatNum into an integer.
float floatNum = 56.715f;
int from_floatNum; // assign here

// Convert the integer intNum into a float.
int intNum = 1500;
float from_intNum; // assign here

// Convert the double doubleNum into a string.
double doubleNum = 3.14159265;
String from_doubleNum; // assign here
```

Convert the values stored inside the variables according to the comments. Assign the converted values into the specified variables.

You don't need to output any messages for this lab.

## Submit your assignment

[Grading Criteria](https://joselitoguardado.dev/3326/labs/Lab_04.pdf)

[How to Submit Assignments to GitHub](https://joselitoguardado.dev/3326/How_to_Submit_Assignments_to_GitHub.pdf)
