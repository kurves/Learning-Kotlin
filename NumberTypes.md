
### Number types in Kotlin

Different type of numbers are stored in different ways

If you create an identifier and assign it an integer value Kotlin infers to it the Int type.

Example
```
 func main() {
 var age =25 //infers Int
 println(age
 }
 ```
 
 ### Operators
  
 The basic Operators for numbers are addition, multiplication, subtraction, modulusand division.
 
 Integer Division produces a truncated result 
 Use double to prevent truncation and providing wrong results.
 
 The order of the execution follows the basic mathematical order
 
 IF you want to enforce a certain execution order use paranthesis
 
 
 ### Maximum Values
 - Int
 
 Kotlin's Int type can take values between -2<sup>31</sup> and +2<sup>31</sup>-1, a constraint of the Int 32-bit representation
 
Int.MAX_VALUE is a predefined value which is the largest number an Int can hold.

- Long

Long  which accommodate values from -2<sup>63</sup> to +2<sup>63</sup>-1
