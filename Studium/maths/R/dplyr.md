#R

### piping

Mit piping lässt sich eine Funktion als erstes Argument in eine weitere Funktion einfügen. Dafür nutzt man den Piping Operator %>%
Einfaches Beispiel:
```
df %>%
head(10)
```
Wenn die vorherigen Dinge nicht als erstes Argument gepiped werden sollen, kann man mit einem Punkt in der nächsten Funktion festlegen, wo sie eingefügt werden sollen. Mit select lässt sich auch die Reihenfolge der Spalten ändern.
Einfaches Beispiel:
```
10 %>%
head(df, .)
```

### columnwise

#### select()

Select wählt die gewünschten Spalten aus und ignoriert den Rest. Andersrum lassen sich auch Spalten entferne, wenn ein - davor steht.

#### mutate()

Innerhalb von mutate lassen sich mit base-R Funktionen neue Spalten erzeugen.

### rowwise

#### filter()

Mit filter lassen sich Zeilen auswählen, die bestimmte Werte haben o.ä.. | als oder und & als und-Zeichen funktionieren innerhalb von Filter. Der Operator %in% überprüft für jeden Wert, ob er sich auch in einem spezifizierten Vektor befindet.

#### distinct()

Distinct zeigt alle Werte einer spezifischen Spalte, die unique sind.

### groupwise

#### groupby()

Gruppiert nach einer Spalte, aber braucht weitere Funtionen um "bemerkbar" zu werden.

#### summarise()

Mit summarise lassen sich Funktionen benutzen, die einen Vektor in eine Zahl herunterbrechen, wie mean etc. Wenn man aus der Groupby-Funktion in summarise piped, erhält summarise verschiedene Vektoren, die sie einzeln bewertet.

#### arrange()

Arrange sortiert nach einer oder mehreren Spalten.

#### count()

Count zählt, wie oft ein bestimmter Wert in jeder Spalte vorkommt.


### Beispiel mit Piping

```
df %>%
select(1.Spalte, 2.Spalte) %>%
mutate(3.Spalte = 1.Spalte + 2.Spalte) %>%
filter(3.Spalte >= 10) %>%
groupby(2.Spalte) %>%
summarise(avg = mean(2.Spalte)) 
```

Man kann auch direkt in ggplot pipen, da ggplot auch Teil des tidyverse ist.

