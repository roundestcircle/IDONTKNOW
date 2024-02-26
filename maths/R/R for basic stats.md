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

## [[Wahrscheinlichkeit]]

```
# Überprüfung auf Normalverteilung
qqnorm(df$name)
# Unterschreitungswahrscheinlichkeit, return Propability
pnorm(value, mean, sd)
# Unterschreitungswahrscheinlichkeit, return Value
qnorm(P, mean, sd)
```

## [[Testen]]

```
# kritischer Wert für t-Test
qt(P, Freiheitsgrade)
# kritischer Wert für f-Test
qf(P, Freiheitsgrade1, Freiheitsgrade 2)
# kritischer Wert für Chi-Quadrat-Test
qchisq(P, Freiheitsgrade)
```

```
# ganzen Test durchführen
# die Funktionen brauchen evtl weitere Argumente
t.test(x, ...)
var.test(x,y, ...)
chisq.test(df)
```