
## PRACTICE QUESTIONS FOR JAVA TUTORIALS

Here are the questions

### Create the Java Project for AnimalPlanet

Create a Java Project called AnimalPlanet

### Create Packages for the Project 

* Create a package called animal.planet.behaviors
* Create a package called animal.planet.stage
* Create a package called animal.planet.categories
* Create a package called animal.planet.examples

### Create Classes in the animal.planet.categories Package

In the package animal.planet.categories, create a new class called Animal with the following protected properties: 

* color
* weight
* age

Also create getters and setters for each property.

### Create classes in the animal.planet.categories Package

In the package animal.planet.categories, create the following classes and properties with getters and setters

All these classes must be children of the Animal class

* Bird : featherCount
* Fish : scalesCount, gillLength
* Mammal: hairCount


### Create the following interfaces in the animal.planet.behaviors Package

Create public interfaces with the following public void methods

* Runner : run();
* Swimmer : swim();
* Flyer : fly();


### Example Classes the Extend Parent Classes and Implement Interfaces (Specific Behavior)

* Ostrich is a Bird that can run.
* Tilapia is a Fish that can swim.
* Bat is a Mammal that can fly.
* Eagle is a Bird that can fly, swim and run
* Penguin is a Bird that can swim
* Horse is a Mammal that can run and swim
* Seal is a Mammal that can swim

When implementing the interface, you need to print out the name of the of the animal and what it is doing.

For example in the swim() method for Tilapia, you need to say "Swim like a Tilapia"


For parent classes, basically you need to make sure that the class extends from the parent class and implements the interface

### Bringing it All Together

In the animal.planet.stage package, create a driver class called EagleDriver.

In this class, that create an instance of Eagle class.

Set the number of feathers for the Eagle.

Call the fly(), swim() and run() methods on the class instance.

Print out the number of feathers on the Eagle instance

```java

public class EagleDriver {

    public static void main(String[] args) {
    
        Eagle a = new Eagle();
        
        a.setFeatherCount(500);
        
        a.fly();
        
        a.swim();
        
        a.run();
        
        System.out.println("The eagle instance has " + a.getFeatherCount() + " feathers";
    }
}

```


In the animal.planet.stage package, create a driver class called SealDriver.

In this class, that create an instance of Seal class.

Set the number of hair for the Seal.

Call the swim() methods on the class instance.

Print out the number of feathers on the Seal instance

```java

public class SealDriver {

    public static void main(String[] args) {
    
    
    }
}


```



