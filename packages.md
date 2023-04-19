
### Packages

Any number of reusable library components can be bundled under a single library name using the package keyword:

```
package com.yoururl.libraryename

//components to reuse
 fun math() = "calculate"
 
 ```
In Kotlin, the package name can be independent from the directory where its contents are located.

### Import

An import statement brings one or more names into the current namespace:

```
import com.yoururl.libraryname

fun main() {

val x = math()

````
