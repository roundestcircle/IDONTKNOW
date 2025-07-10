#R 

### Store R-Datatypes

```
# create Rdata File
create.file("xyz.RData")
# save RData Files
save(xyz, file == "xyz.RData")
# load Rdata File
load("xyz.RData")
```

### Outliers 

```
# if you know which indexes the ouliers are at

# use a vector of indexes, returns vector of values at indexes
xyz[c(2,5,8)]

# return a vector without certain indexes
xyz[-c(2,5,8)]

# if you dont know which indexes the outliers are at

# compare Values at indexes to certain value, returs logical
xyz[1] < 0
# compare all values at once, returns vector of logicals
xyz < 0

# compare with combined logical operators and which, return list of indexes 
at which logical=TRUE
which(xyz < 0 | xyz > 10)

# Find out if Outliers exist: Return single logical TRUE if any or all Logical  Operations are True
any(xyz < 0)
all(xyz < 0)

# create vector without outliers autmatically
xyz[-which(xyz < 0 | xyz > 10)]
# "which" is redundand here: the following works identically
filter <- xyz < 0 | xyz > 10
xyz[-filter]

# invert logicals, returns value of logicals opposite the actual results of Logicals Operations
filter <- !(xyz < 0 | xyz > 10)

# all combined, final processing
xyz_nooutliers <- xyz[!(xyz < 0 | xyz > 10)]
xyz_outliers <- xyz[(xyz < 0 | xyz > 10)]
```

### NA-Values

You have to make a decision about what to do with NA-Values, remove or replace them, you cannot just compute with them!

```
# remove NA-Values in a function
mean(xyz$1, na.rm = TRUE)

# remove NA-Values form Dataset
# use a logical function, returns vector of logicals
is.na(xyz$1)
# create filter with inverted vector
filter <- !is.na(xyz$1)
# create vector with only existing values
xyz <- xyz[filter, ]

# Count number of NA-Values
sum(is.na(xyz$1))
# This works because:
as.integer(TRUE) == 1
```

### Grouping/Subsetting

```
# subsetting a dataframe
# subsetting by index, in this example all colums for rows 1 to 3
xyz_subset <- xyz[1:3, ]
mean(xyz_subset$1)

# subsetting with logical expressions
# create vector of logicals
filter <- xyz$1 == "nice"
# filter by vector of logicals
xyz_subset <- xyz[filter, ]

# using subset()
# remove all rows where 1 == NA
subset(xyz, !is.na(1))
# grouping using subset
subset(xyz, 1 == "nice")

# attention: rownames disappear with removed rows
# reset rownames to restore proper indexing
rownames(xyz) <- NULL
```

### Menus/Subsetting with User Input

```
# create menu yourself
# determine options 
options <- unique(xyz$1)

# prompt the user
# combine vectors first to return 1. Option1, 2. Option2 etc
# this allows the user to enter a number instead of text to choose
formatted_options <- paste0(1:length(options), ". ", options)
cat(formatted_options, sep = "/n")
option_choice <- as.integer("readline(Option Picked: "))
# return integer to value
option_choice <- options[option_choice]

# return subset of data for user
print(subset(xyz, 1 == option_choice))

# guard against invalid input and reprompt if invalid
if(option_choice < 1 || option_ choice > length(options) ||         is.integer(option_choice) == FALSE) {
  cat("Invalid choice.")
  cat(formatted_options, sep = "/n")
  option_choice <- as.integer("readline(Option Picked: "))
} else {
  option_choice <- options[option_choice]
  print(subset(xyz, 1 == option_choice))
}

# use inbuilt menu function, automatically numbers options and reprompts for invalid answers
option_choice <- menu(
  options,
  title = "Option picked: "
)
```

### Combine Dataframes

```
# same number and names of colums
rbind(xyz, xcv, vbn)
# adding a column to differentiate sets in big df
# do it for all dfs and combine afterwards
xyz$dings <- xyz
```

### Categorisation

```
# add a new category-column, pass condition, value if true, value if false
xyz$cat <- ifelse(xyz$1 > 10, "Big", "Small")
```