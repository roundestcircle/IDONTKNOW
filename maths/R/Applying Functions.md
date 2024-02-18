#R 

### Defining Functions

```
my_function <- function(parameter 1, parameter 2, ...) {
   ### indented: what to do with supplied parameters
   return(whatever you want out of the function)
}
   
```

By default (without return()), R will return the last computed value.

#### Defining default Values

```
function(parameter 1 = 12)
```

If the user defines a parameter, the default will be overridden. 

#### Suppressing Warnings

```
supressWarning(is.na())
```

Used to suppress warnings if you as the programmer handle the warnings yourself, for example with conditionals, or dont want them displayed to the user.

### Loops

#### repeat {}

Repeat repeats whatever code is inside the braces indefinitely (or until it hits break).

#### break

Break exits out of a loop. Return() also exits out of the loop.

#### next

Next skips to the next Loop-Iteration.

#### Example

```
# repeating blub three times
i <- 3

repeat {
 cat("blub\n")
 i <- i - 1
 if (i == 0) {
  break
 } else {
  next
 }
}
```

Next is just an example here, not necessary as the loop would repeat even withou it.


### while () {}

Repeat code while condition is true.

```
# repeating blub three times
i <- 3

while (i != 0) {
 cat("blub\n")
 i <- i - 1
}
```

### for () {}

Repeat some code for every element in a list or vector. The value of i changes every loop to the element in the vector at index i (starting at 1, increasing by 1 every loop).

```
# repeating blub three times
for (i in 1:3)) {
 cat("blub\n")
}
```

```
# iterate over rows
for (x in rownames(df)) {
}
```

### apply(df, ...)

Apply apllies fuctions row- or columnwise, iterating over every index.