
## Loops

Computers are ideal for repetitive tasks.

The most basic form of repetition uses the while keyword. 
Repeats a block as long as the condition is true

Example 

```
fun counter(i: Int) 1 < 100

fun main() {

while(counter(i)){
print("-")
i+=10
}
````
You can also use while with do 

```
do {
  // Code to be repeated
} while (Boolean-expression)
```
The difference between while and do-while is that the body of the do-while always executes at least once, even if the Boolean expression initially produces false. In a while, if the conditional is false the first time, then the body never executes.

### The for keyword

The for word executes a block of code for each value in a sequence

Example 

```
fun main(){
 for i in (1..9){
    println("Kurves $i")
    }}
    ```
