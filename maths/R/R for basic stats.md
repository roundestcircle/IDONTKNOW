#R #Stat 

## [[Lagemaße]]

```
mean()
mode()
median()
```

## [[Streuungsmaße]]

```
sd()
```

## [[Regression]]

```
# linear model von zwei Variablen, y ~ (in Abhängigkeit von) x
lm(df$name ~ df$name2)
# die Ausgabe enthält den intercept (y-Achsenabschnitt) und einen Koefficient (Steigung), mit dem Namen der unabh. Variable gekennzeichnet
# für weitere Informationen: Analysis of varaiance Models oder summary
summary(lm(y~x))
aov(lm(y~x))
# Ausgabe enthält zum Beispiel: multiple R-Squared
```