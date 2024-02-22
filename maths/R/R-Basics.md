#R 

Everything that exists is an object.
Everything that happens is a function call

### Operators

1. + - /  * (Algebraic Operators, Return Int or Double)
2.  ==  !=  >  <  >=  <= (Logical Operators, Return Logical)
3. &  |  (Combine Logical Operators, single for vectors, double for individual Values)

### Datatypes

1. String (Anything, no maths possible)
2. Int (Whole Numbers)
3. Double (Decimal Numbers)
4. Logical (True/False)

#### Special Data

1. inf/-inf
2. NA (not available: there could be Data here, but there isnt. Unresolved NAs prevent functions from running)
3. NaN (not a Number)
4. null (absolutely nothing, there coudnnt be data here)

### Escape-Characters

1. \n (newline)
2. \t (tab)

### Conditionals

1. if {}, else {}
2. ifelse(Function, return if TRUE, return if FALSE)

### Vector manipulation

#### Create empty Vector

```
vector <- c()
```

#### Add named Elements

```
vector[name] <- value
```

#### Adding vectors together

```
vector <- c(vector1, vector2)
```