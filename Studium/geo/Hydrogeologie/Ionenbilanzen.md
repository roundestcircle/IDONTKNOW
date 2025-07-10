#Hydrochemie #Hydrogeologie 

Ionenbilanzen werden wie folgt berechnet: 

$$Fehler=\frac{\text{Summe Kationen - Summe Anionen}[c(eq)]}{0,5 \cdot \text{Summe Kationen + Summe Anionen}[c(eq)]} \cdot 100$$

Der Fehler der Ionenbilanz darf bei Konzentrationen bis 2 mmol/l nicht über 5% liegen, darüber nicht über 2.

Beispielrechnung:

|      |                   |              |        |                     |
| ---- | ----------------- | ------------ | ------ | ------------------- |
| ion  | charge            | molar_weight | test_1 | c(eq)               |
|      |                   |              |        |                     |
| Na   | 1                 | 22,99        | 410    | 17,833840800348     |
| K    | 1                 | 39,1         | 0,02   | 0,00051150895140665 |
| NH4  | 1                 | 18,05        | 0      | 0                   |
| Mg   | 2                 | 24,31        | 130    | 10,6951871657754    |
| Ca   | 2                 | 40,06        | 100    | 4,99251123315028    |
| Mn   | 2                 | 54,94        | 0      | 0                   |
| Fe   | 2                 | 55,85        | 0      | 0                   |
| SUM  |                   |              |        | 33,5220507082251    |
|      |                   |              |        |                     |
| Cl   | 1                 | 35,45        | 100    | 2,82087447108604    |
| NO3  | 1                 | 62,01        | 0      | 0                   |
| HCO3 | 1                 | 61,017       | 1810   | 29,6638641690021    |
| HPO4 | 2                 | 95,97        | 0      | 0                   |
| SO4  | 2                 | 96,06        | 80     | 1,66562565063502    |
| SUM  |                   |              |        | 34,1503642907231    |
|      |                   |              |        |                     |
| IBF  | -1,85692673302067 |              |        |                     |
|      |                   |              |        |                     |

Mögliche weitere notwendige Rechenschritte:

- Umrechnung des M-Werts in Hydrogencarbonatgehalt (einfach mit dem Molgewicht multiplizieren, [[Kalk-Kohlensäure-Gleichgewicht#Titration]])
- Umrechnung des Härtegrads in Ionenkonzentrationen ([[Kalk-Kohlensäure-Gleichgewicht#Wasserhärte]])
- Bestimmung fehlender Ionenkonzentrationen über die Faustformel aus der Leitfähigkeit ([[Leitfähigkeit des Wassers]])
- Bei pH<4,3: H+-Ionen müssen mit einbezogen werden. Konz lässt sich aus pH berechnen.
- Wenn keine Hydrogencarbonatkonz gegeben, aber pH: überprüfen ob bei diesem pH Hydrogencarbonat überhaupt vorliegt.