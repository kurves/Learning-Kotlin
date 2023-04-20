### Objects Everywhere 

Kotlin supports both a functional programming and object oriented programming Language

Objects contain val and var  to store data called properties and fuctions to perform operations within a class called *member functions*

 When you create a val or var of a class, it's called creating an object or creating an instance.
 
 An useful type of object is the container also known as a collection. A collection is an object that conatins other objects

## Classes

### Creating Classes

A class definition contains the *class* keyword , name for the class and an optional body.

The body contains the *properties* and the *member functions*

Example

- An empty animal class
```
class Animal
````

Example 

- Class with properties

```
class Animal{
var dog ='Bosco'
}
```

Example 

- Class with member functions

```
class Animal{
var dog = 'Bosco'
fun bark(){
println("Woof ! Woof !"
}
}
```

### Constructors

A constructor is used to create new objects

A constructior returns an object of the class

### Constraining Visibility

Kotlin provides access modifiers 

These allow components designers to decide on what is available to the client programmer

The access modifiers include:

- Public - A public definition is available to everyone
- Private - Only available within that file 
- Protected
- Internal

