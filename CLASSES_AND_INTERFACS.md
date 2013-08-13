
## Classes

Classes generally follow the following format

`
visibilityOfClass class NameOfClass {

    visibilityOfProperty dataTypeOfProperty propertyName;
    
    visibilityOfProperty dataTypeOfProperty propertyName = value;
    
    visibilityOfMethod returnTypeOfMethod nameOfMethod(arguments) {
        // contents of method
    }
    
    visibilityOfMethod returnTypeOfMethod nameOfMethod() {
        // contents of method
    }
}
`

## Example of a Class

```java

public class Student {

    private int age;
    
    private String hairColor;

    private double tution;
    
    public void setAge(int ageValue) {
        this.age = ageValue;
    }
    
    public int getAge() {
        return this.age;
    }
    
    public void setHairColor(String hairColorValue) {
        this.hairColor = hairColorValue;
    }
    
    public String getHairColor() {
        return this.hairColor;
    }
    
    public void setTution(double tutionValue) {
        this.tution = tutionValue;
    }
    
    public double getTution() {
        return this.tution;
    }
}

```


## Examples of an Interface

`
public interface InterfaceName {

    public returnTypeOfMethod nameOfMethod(arguments if any);
}
`


```java

public interface Runner {
    
    public void run();
    
    public boolean isRunning();
}


public interface Flyer {

    public void fly();
    
    public boolean isFlying();
}

public interface Swimmer {

    public void swim();
    
    public boolean isSwimming();
}


```
