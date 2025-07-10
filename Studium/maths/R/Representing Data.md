#R 

## viewing values

```
# by index (starting at 1)
# if one argument left empty: full row/column as list
df[row, column]
# by name
df$name

```

## list of rownames/columnnames

```
colnames(df)
rownames(df)

```

## saving csv-files

```
write.csv(df, "filename.csv")
# this function also writes the row-index into the file
# pass row.names=FALSE to prevent
```

## get user input

```
readline("Prompt")
```

## combine elements

```
# combine strings
paste()
# combine anything
cat()
```

## convert data types

```
as.double()
as.integer()
as.string()
```

## count rows or columns

```
nrow(df)
ncol(df)
```

## show unique values in vector

```
unique(df$name)
```

## convert verctor to factor

```
factor(df$name)
# a factor has levels (unique values)
# these levels can be renamed
labels = c()
# or removed (returns NA)
exclude = c()
```