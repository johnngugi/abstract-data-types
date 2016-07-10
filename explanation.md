# Abstraction

Abstraction is the quality of dealing with ideas rather than events. In OOP abstraction is a process of hiding the implementation details from the user, only the functionality will be provided to the user.  

In java abstraction is acheived using abstract classes.

# Abstract class

A class which contains the abstract keyword in its declaration is known as abstract class.

If a class has at least one abstract method then it must be declared abstract. If a class is declared abstract it cannot be instantiated.

# Abstract method  

The abstract keyword is used to declare the method as abstract.  
You have to place the abstract keyword before the method name in the method declaration.

# Abstract Data Types

An abstract data type (ADT) is a model of a data structure that specifies:  
* the characteristics of the collection of data.  
* the operations that can be performed on the collection.

It's abstract because it doesn't specify how the ADT will be implemented.

An example of an ADT is a bag:  
* A bag is just a container for a group of data items.
* The positions of data items don't matter {3,2,10,6} is the same as {2,3,6,10}.  
* The items don't need to be unique unlike a set.

The operation of our bag ADT:  
* add(item): add item to bag.
* remove(item): remove item from bag.
* contains(item): check if item is in the bag.

# Arrays

Java provides a data structure, the array, which stores a fixed-size sequential collection of elements of the same type. An array is used to store a collection of data, but it is often more useful to think of an array as a collection of variables of the same type.
