#stat 

Group:: Maßzahl
Type:: Lagemaß 
Kürzel:: $x_{MD}$

Formel:: häufigste Merkmalsausprägung

Python:: df.mode(x)
Excel:: MODALWERT(A:A)
R:: 
```
getmode <- function(v) {
   uniqv <- unique(v)
   uniqv[which.max(tabulate(match(v, uniqv)))]
}
```