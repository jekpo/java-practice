## Method Signatures

A method signature follows the following syntax:

```java

// returnType functionName(arguments if any)


```

If the function or method does not return any values then the returnType of void is used

```java

int addition(int firstNumber, int secondNumber)

String getCategoryFromAge(int age)

boolean isAdult(int age)


```

## How to Create a Function

A function or method in Java typically starts with the visibility classifiers (public, protected, private)

The next item is the return type of the function.

Next, we need to specify the name of the function that identifies the function

After this we insert a bracket and then specify all the variables that make the parameters.

After all the parameters are listed we insert a bracket to mark the end of parameters.

Then a curly brace is inserted to indicate the beginning of the function

Another curly brace is inserted to mark the end of the function

All statements for this function/method must be placed within the start and end braces.

```java

// This function performs an addition
public int addition(int firstNumber, int secondNumber) {
    int result = firstNumber + secondNumber;
    
    return result;
}

// This function returns the age category from the age
public String getCategoryFromAge(int ageValue) {

    String result = "";
    
    if (age > 17) {
        result = "Adult";
    } else if (age > 12 && age < 18) {
        result = "Teen";
    } else if (age > 2 && age < 13) {
        result = "Child";
    } else {
        result = "Infant";
    }

    return result;
}


// This function returns if the person is an Adult
public boolean isAdult(int ageValue) {

    if (ageValue > 17) {
    
        return true;
    } else {
        return false;
    }
}


```
