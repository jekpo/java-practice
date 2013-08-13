
## Program Drivers

A driver is the class where the computer interacts with the computer program

This class must have a main function with the following signature

```java

public static void main(String[] args) {


}

```

## Example of A Driver class

This is an example of a driver class.

In the main function we write statements that prints a message.


```java

package animal.planet.stage;

public class Driver {

    public static void main(String[] args) {
    
        String fullName = "June Ekpo";
        
        String message = "My Name is " + fullName;
        
        System.out.println(message);
        
    }
}

```