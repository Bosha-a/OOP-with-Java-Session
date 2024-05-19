# Object Orinted Programming With Java 

 Is a Computer Programming Model That Organizes Software Design around Data, or ""Objects"" , Rather than Functions and Logic .

 OOP was developed to increase the reusability and maintainability of source code. Transparent representation of the control flow had no priority and was meant to be handled by a compiler. With the increasing relevance of parallel hardware and multithreaded coding, developing transparent control flow becomes more important, something hard to achieve with OOP

### Part1
## [Session](https://cisuezedu.sharepoint.com/:v:/s/TROSE/ESrqltJ57pVEifpxqsyXa9IBTphJ2Dj3WBQzYWQA2dNVWQ?e=ooeHnl)
### Part2
## [Session](https://cisuezedu.sharepoint.com/:v:/s/TROSE/EXJXWDaX0rdPtRvPxlCvVREBMap2xYE7sYdmABKysm9giA?e=Kfr3Od)
### Part3
## [Session](https://cisuezedu.sharepoint.com/:v:/s/TROSE/EZ0besXpwqNEu_zhCthb7XwB-aKxpuHWM7NTBwd0neuZgA?e=etP6h2)
### Part4
## [Session](https://cisuezedu.sharepoint.com/:v:/s/TROSE/ETelVywOTGpCljRYrvCUlGgBeuqsqdoUgzeFxNhT9lkGoA?e=Ee2dw2)

## OutLines
- Structure of object-oriented programming
- Principles Of OOP
- Calsses
- Objects
- Access Modifers
- Taking Input
- Final and Static Access Modifier
- Accessors And Mutators
- This Reference
- Principles of OOP 
    - Inheritance
    - Encapsulation
    - Polymorphism
    - Abstraction
- Interface
- toString Method
- Enumeration 
--------------------------------------------------


### Structure of object-oriented programming
  ## ![Alt text](/Images/image-1.png)

 Class: A class is a data type that provides a framework for creating objects. You can define a class to create multiple objects without writing additional code.

 Object: In OOP, an object represents an instance, or creation, of a class. Objects define specific data, such as properties and 
 behaviors, to implement code.

 Method: A method is a function that performs a task or action. For example, a method may return information about an object's data.
 
 Attribute or Properites: This structure stores information about an object and defines its state. You can define an attribute as part of the class.

 
 ## Calss in Java
- It is a user-defined blueprint or prototype from which objects are created.

- used to represent real-world concepts and entities .

- represents a group of objects having similar properties / attributes and behavior. 

- Class does not occupy memory

- A Class in Java can contain:
> Data member

> Method

> Constructor

> Nested Class

> Interface

## Object in Java 

An object in Java is a basic unit of Object-Oriented Programming and represents real-life entities. Objects are the instances of a class that are created to use the attributes and methods of a class. 

- State : It is represented by attributes / characteristics of an object. It also reflects the properties of an object.

- Behavior: It is represented by the methods of an object. It also reflects the response of an object with other objects.

### Simple Class in Java
 ## ![Alt text](/Images/simple%20class.png)

##### >Try it with Yourself to Support Idea<

### Components of Java Classes

- Modifiers: A class can be public , private , protected or has default access

- Class keyword: class keyword is used to create a class.

- Class name: The name should begin with an initial letter 

- Constructors: used for initializing new objects .

- Body: The class body is surrounded by braces { }.

### Access Modifers in Java

The access modifiers in Java specifies the accessibility or scope of a field, method, constructor, or class. We can change the access level of fields, constructors, methods, and class by applying the access modifier on it. 

#### There are four types of Java access modifiers:

- Private: The access level of a private modifier is only within the class. It cannot be accessed from outside the class.

- Default: The access level of a default modifier is only within the package. It cannot be accessed from outside the package. If you do not specify any access level, it will be the default.

- Protected: The access level of a protected modifier is within the package and outside the package through child class. If you do not make the child class, it cannot be accessed from outside the package.

- Public: The access level of a public modifier is everywhere. It can be accessed from within the class, outside the class, within the package and outside the package.

## ![Alt text](/Images/image-8.png)

## Taking Input With Scanner 

There are two ways by which we can take Java input from the user or from a file

- Scanner Class
- BufferedReader Class

### Scanner Class 
To use the Scanner we need to import the Scanner class from the util package as 
> import java.util.Scanner ;  

#### Inbuilt Scanner functions are as follows:
- Integer : nextInt()
- Float : nextFloat()
- String : next() and nextLine()
- Double : nextDouble() 

## ![](/Images/Scanner.png)

## Final and Static Access Modifier
### Final

is a modifier applicable to classes, methods, and variables. If we declare a parent class method as final then we can’t override that method in the child class because its implementation is final and if a class is declared as final we can’t extend the functionality of that class

### Static

Static keyword in java in Java indicates that a particular member is not an instance, but rather part of a type. The static member will be shared among all instances of the class, so we will only create one instance of it.


## Accessors And Mutators Methods in Java
In Java accessors are used to get the value of a private field and mutators are used to set the value of a private field.

- An Accessor method is commonly known as a get method or simply a "getter" .

- A Mutator method is commonly known as a set method or simply a "setter" .

## This Reference in Java

is a reference variable that refers to the current object, or can be said “this” in Java is a keyword that refers to the current object instance

## ![Alt text](/Images/Dog%20class.png)

### OUTPUT

## ![Alt text](/Images/image-4.png)

## Principles of OOP

  ## ![Alt text](/Images/image.png)

 ### Object-oriented programming is based on the following principles:

- Inheritance: Classes can reuse code from other classes. Relationships and subclasses between objects can be assigned, enabling developers to reuse common logic while still maintaining a unique hierarchy. This property of OOP forces a more thorough data analysis, reduces development time and ensures a higher level of accuracy.

- Encapsulation: This principle states that all important information is contained inside an object and only select information is exposed. The implementation and state of each object are privately held inside a defined class. Other objects do not have access to this class or the authority to make changes. They are only able to call a list of public functions or methods. This characteristic of data hiding provides greater program security and avoids unintended data corruption.

- Polymorphism: Objects are designed to share behaviors and they can take on more than one form. The program will determine which meaning or usage is necessary for each execution of that object from a parent class, reducing the need to duplicate code. A child class is then created, which extends the functionality of the parent class. Polymorphism allows different types of objects to pass through the same interface.

- Abstraction: Objects only reveal internal mechanisms that are relevant for the use of other objects, hiding any unnecessary implementation code. The derived class can have its functionality extended. This concept can help developers more easily make additional changes or additions over time.

## Inheritance in Java

Code Reusability: The code written in the Superclass is common to all subclasses. Child classes can directly use the parent class code.

Method Overriding: Method Overriding is achievable only through Inheritance. It is one of the ways by which Java achieves Run Time Polymorphism.

Abstraction: The concept of abstract where we do not have to provide all details is achieved through inheritance. Abstraction only shows the functionality to the user.

### Types Of Inheritance 

- Single Inheritance

- Multilevel Inheritance

- Hierarchical Inheritance.

#### Important Terminologies Used in Java Inheritance : 

- Class: Class is a set of objects which shares common characteristics/ behavior and common properties/ attributes. Class is not a real-world entity. It is just a template or blueprint or prototype from which objects are created.

- Super Class/Parent Class: The class whose features are inherited is known as a superclass(or a base class or a parent class).

- Sub Class/Child Class: The class that inherits the other class is known as a subclass(or a derived class, extended class, or child class). The subclass can add its own fields and methods in addition to the superclass fields and methods.

## How to Use Inheritance in Java?

The extends keyword is used for inheritance in Java. Using the extends keyword indicates you are derived from an existing class. In other words, “extends” refers to increased functionality.

### Super Keyword 

super is used to call a superclass constructor: When a subclass is created, its constructor must call the constructor of its parent class. This is done using the super() keyword, which calls the constructor of the parent class.

### Simple Example on Inheritance
## ![Alt text](/Images/Inheritance.png)

## Encapsulation in Java 

 is a fundamental concept in object-oriented programming (OOP) that refers to the bundling of data and methods that operate on that data within a single unit, which is called a class in Java. Java Encapsulation is a way of hiding the implementation details of a class from outside access and only exposing a public interface that can be used to interact with the class.

 In Java, encapsulation is achieved by declaring the instance variables of a class as private, which means they can only be accessed within the class.

## ![Alt text](/Images/image-5.png)

#### Look at This Image to Understand 

## ![Alt text](/Images/encapsulation.png)

## Polymorphism in Java

The word polymorphism means having many forms. In simple words, we can define Java Polymorphism as the ability of a message to be displayed in more than one form. In this article, we will learn what is polymorphism and it’s type.

Polymorphism is considered one of the important features of Object-Oriented Programming. Polymorphism allows us to perform a single action in different ways. In other words, polymorphism allows you to define one interface and have multiple implementations. The word “poly” means many and “morphs” means forms, So it means many forms.

### Types of Java Polymorphism

- Compile-time Polymorphism

- Runtime Polymorphism


#### Compile-time Polymorphism

It is also known as static polymorphism. This type of polymorphism is achieved by function overloading or operator overloading. 

> Overloading : When there are multiple functions with the same name but different parameters
Functions can be overloaded by changes in the number of arguments or/and a change in the type of arguments.

## ![](/Images/overloading.png)


#### Runtime Polymorphism

It is also known as Dynamic Method Dispatch. It is a process in which a function call to the overridden method is resolved at Runtime. This type of polymorphism is achieved by Method Overriding. Method overriding, on the other hand, occurs when a derived class has a definition for one of the member functions of the base class. That base function is said to be overridden.

> Overriding : When there are multiple functions with the same name but different Signatures with changing Paramiter list that
make the code more readable and providing a way to create flexible and reusable code.

## ![](/Images/Overriding.png)

## Abstraction in Java

 is the property by virtue of which only the essential details are displayed to the user.

Data Abstraction may also be defined as the process of identifying only the required characteristics of an object ignoring the irrelevant details. The properties and behaviors of an object differentiate it from other objects of similar type and also help in classifying/grouping the objects.

 abstraction is achieved by interfaces and abstract classes. We can achieve 100% abstraction using interfaces.

 - An abstract class is a class that is declared with an abstract keyword.
 
 - An abstract method is a method that is declared without implementation.

 - A method-defined abstract must always be redefined in the subclass, thus making overriding compulsory or making the subclass itself abstract.

 ## ![](/Images/abstraction.png)

 #### Output

 ## ![Alt text](/Images/image-6.png)



### Advantages of Abstraction

- It reduces the complexity of viewing things.

- Avoids code duplication and increases reusability.

- Helps to increase the security of an application or program as only essential details are provided to the user.

- It improves the maintainability of the application. 

## Interface in Java

An Interface in Java programming language is defined as an abstract type used to specify the behavior of a class. An interface in Java is a blueprint of a behavior. A Java interface contains static constants and abstract methods.

The interface in Java is a mechanism to achieve abstraction. There can be only abstract methods in the Java interface, not the method body. It is used to achieve abstraction and multiple inheritances in Java using Interface. In other words, you can say that interfaces can have abstract methods and variables. It cannot have a method body. Java Interface also represents the IS-A relationship.

## ![Alt text](/Images/image-7.png)

## ![](/Images/interface1.png)

## toString() Method in Java 

If you want to represent any object as a string, toString() method comes into existence.

The toString() method returns the String representation of the object.

If you print any object, Java compiler internally invokes the toString() method on the object. So overriding the toString() method, returns the desired output, it can be the state of an object etc. depending on your implementation.

## ![](/Images/tostring.png)

#### Advantage of Java toString() method

By overriding the toString() method of the Object class, we can return values of the object, so we don't need to write much code.

## Enum in Java

A Java enumeration is a class type. Although we don’t need to instantiate an enum using new, it has the same capabilities as other classes. This fact makes Java enumeration a very powerful tool. Just like classes, you can give them constructors, add instance variables and methods, and even implement interfaces.

## ![Alt text](/Images/ENUM.png)

--------------------------------------------------------------------------------

### To Read More About OOP 
#### Articles : 

-  #### [Java Article](https://www.geeksforgeeks.org/classes-objects-java/)

-  #### [Java Article 2](https://medium.com/@TechiesSpot/exploring-advanced-object-oriented-programming-oop-concepts-in-java-b0b394e1c187)

### Videos : 
-  #### [Arabic Content](https://www.youtube.com/watch?v=FaaM6uVbuJM&list=PLCInYL3l2AagY7fFlhCrjpLiIFybW3yQv)

-  #### [English Content](https://youtu.be/6T_HgnjoYwM?si=cWadglygZzMTaenp)
