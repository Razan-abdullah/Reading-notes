
# Object Orianted Programming-Part2


## dependency injection

 it's a transferring the task of creating the object to someone else and directly using the dependency .

 ---
## There are basically three types of dependency injection:

### 1-constructor injection: the dependencies are provided through a class constructor.

### 2-setter injection: the client exposes a setter method that the injector uses to inject the dependency.

### 3-interface injection: the dependency provides an injector method that will inject the dependency into any client passed to it. Clients must implement an interface that exposes a setter method that accepts the dependency.

---

#### dependency injection’s responsibility to:

1- Create the objects
2- Know which classes require those objects
3- provide them all those objects

---
## Libraries and Frameworks that implement DI
* Spring (Java)
* Google Guice (Java)
* Dagger (Java and Android)
* Castle Windsor (.NET)
* Unity(.NET)


---

# Risk Analysis

---

## Risk :

 The probability of any unwanted incident is defined 

 ## risk analysis:
 
  is the process of identifying the risks in applications or software that you built and prioritizing them to test. After that, the process of assigning the level of risk is done. The categorization of the risks takes place, hence, the impact of the risk is calculated.

  ### Why use Risk Analysis?

  In any software, using risk analysis at the beginning of a project highlights the potential problem areas. After knowing about the risk areas, it helps the developers and managers to mitigate the risks. When a test plan has been created, risks involved in testing the product are to be taken into consideration along with the possibility of the damage they may cause to your software along with solutions.

---

# design pattern:
 is only a description or template for how to solve a problem! that can be used in many different situations. So every design pattern provide a solution to commonly occurring software design problems. 
 
### Patterns:
  are formalized best practices that the Software Developer can use to solve common problems when designing an application.

---

## There is 3 major types of design patterns:


### 1- Creational Patterns:
Creational patterns provide ways to instantiate single or groups of objects. Making it easier to create objects in a way that suits the situation.


### 2- Structural Patterns:
Structural patterns provide a manner to define relationships between classes or objects. Making it easier for these entities to work together.


### 3- Behavioral Patterns:
Behavioral patterns define manners of communication between classes and objects. Making it easier and more flexible for these entities to communicate.