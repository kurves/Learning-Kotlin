
### Functions

A functions i a small program with a name that can be executed by calling the function followed by the arguments in the parenthesis

A function can be written as a block body or as an expression body

An expression body uses an equals sign while a block body uses parentheses

Kotlin infers the type of the utput in an expression body but returns unit in a block body if the type of the output is not expilicitly stated


Example of a block body function

```

fun addTwo(x:Int): Int {
 return x +2
 }
 
 addTwo(5)
 //returns 7
 ```
 
Example of an xpression body function

```
fun addTwo(x:Int):Int = x+2

```
