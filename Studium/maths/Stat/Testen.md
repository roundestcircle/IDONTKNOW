#Stat #Schließend 

vgl. [[Deskriptiv vs Schließend]]

### Logik

Beim Testen versucht man zu zeigen, dass das Stichprobenergebnis aufgrund eines Zusammenhanges, und nicht durch puren Zufall aufgetreten ist. Dafür versucht man die zufällige Entstehung weitgehend auszuschließen.

1. Eine der interressierenden Hypothese entgegengesetzte Nullhypothese wird aufgestellt. Meistens ist die Nullhypothese etwa, dass kein Zusammenhang vorliegt. 
2. Der [[Statistik Einführung#Forschungsablauf nach Popper|Philosophie]] nach Popper folgend, wird nun versucht, diese Nullhypothese zu falsifizieren. Dafür wird angenommen, dass in der Grundgesamtheit kein Zusammenhang vorliegt und eine Dichtefunktion erstellt, die diesen Maßgaben entspricht.
3. Aus dieser Vergleichsverteilung ergeben sich kritische Werte, zwischen denen ein bestimmter Prozentsatz der Stichprobenergebnisse liegt, etwa 95%.
4. Liegt der Stichprobenmesswert oder die berechnete Prüfgröße außerhalb dieser kritischen Werte, ist es sehr unwahrscheinlich, dass er auftritt, wenn die Vergleichsverteilung der Realität entspricht. Damit kann die Nullhypothese verworfen werden. Liegt er innerhalb dieser kritischen Werte, wird die Nullhypothese als nicht falsifiziert angesehen.
5. Die interressierende Hypothese wird angenommen oder abgelehnt.

### p-Wert und Signifikanz

Beim Durchgehen dieses Verfahrens erhält man evtl einen p-Wert beziehungsweise ein Signifikanzniveau, der der Wahrscheinlichkeit entspricht, dass das Stichprobenergebnis auftritt, falls die Nullhypothese zutrifft. Ist er sehr gering, in der Regel unter 0.05, spricht man von einem signifikanten Ergebnis, sonst ist das Ergebnis nicht signifikant. Bei signifikanten Ergebnissen kann die Nullhypothese verworden werden.

Dadurch akzeptiert dieses Verfahren eine gewisse Irrtumswahrscheinlichkeit, also die Wahrscheinlichkeit, dass die Nullhypothese zu unrecht verworfen wurde. Diese entspricht dem p-Wert.

Andersrum: Man legt einen gewissen p-Wert fest, also eine Irrtumswahrscheinlichkeit, und überprüft dann ob die gemessene Prüfgröße außerhalb eines bestimmten Intervalls liegt, in der alle Fälle bis auf den Anteil, den man festgelegt hat, liegen, falls die Nullhypothese zutrifft. Tut sie dies, ist die Wahrscheinlichkeit, dass der Wert bei Zutreffen der Nullhypothese auftritt, niedriger als das festgelegte Signifikanzniveau.

Achtung: Ein signifikantes Ergebnis bedeutet keine Kausalität und nichtmal unbedingt eine Korrelation (Irrtumswahrscehinlichkeit!). Genauso bedeutet ein nicht signifikantes Ergebnis nicht, dass die Nullhypothese definitiv richtig ist.

### Hypothesentypen

- Zusammenhangshypothesen
- Unterschiedshypothesen zwischen Gruppen

- Gerichtete Hypotheses (Richtung des Zusammenhangs)
- Ungerichtete Hypothesen

- Spezifische Hypothesen (Stärke des Zusammenhangs)
- Unspezifische Hypothesen

### t-Test

Der t-Test dient zur Überprüfung von Unterschiedshypothesen. Er setzt eine Normalverteilung voraus (vgl. [[Wahrscheinlichkeit#Prüfen auf Normalverteilung]])

Er vergleicht zwei verschiedene Mittelwerte, etwa zweier Stichproben und bewertet die Wahrscheinlichkeit, dass diese Auftreten, wenn sich die Grundgesamtheit der beiden Stichproben in ihren Verteilungen nicht unterscheidet.

Dafür wird der t-Wert als Prüfgröße berechnet, und mit den kritischen Werten der t-Verteilung verglichen. Die t-Verteilung entspricht ab etwa 30 Freiheitsgraden grob der Standardnormalverteilung.

Der kritische Wert lässt sich in [[R for basic stats|R]] berechnen. Liegt der t-Wert außerhalb dieses Bereichs, ist das Ergebnis signifikant. Es ist dann davon auszugehen, dass sich die zwei Grundgesamtheiten unterscheiden.

Um die Prüfgröße zu berechnen, wuss bekannt sein, ob sich die Standardabweichungen der beiden Grundgesamtheiten unterscheiden.

### f-Test

Der f-Test überprüft, wie wahrscheinlich es ist, dass die Streuung zweier Stichproben rein zufällig entstanden ist und sie sich in der GG nicht unterscheidet. Auch er setzt eine Normalverteilung voraus.

Dafür wird der f-Wert berechnet und mit dem kritischen Wert der sich aus der f-Verteilung ergibt verglichen. Der kritische Wert lässt sich in [[R for basic stats|R]] berechnen.

Liegt die Prüfgröße außerhalb der kritischen Werte, ist anzunehmen, dass sich die Streuungen auch in der Grundgesamtheit unterscheiden. Die Wahrscheinlichkeit, dass die Stichprobenergebnisse bei gleicher GG auftreten ist also sehr gering. 

### Chi-Quadrat-Test

Der Chi-Quadrat-Test setzt keine Normalverteilung voraus. Er dient der Überprüfung einer bivariaten Zusammenhangshypothese.

vgl. [[Korrelationsanalyse nominalskalierter Daten#Chi-Quadrat]]

Der Test überprüft die Wahrscheinlichkeit, dass ein bestimmter $\chi^2$-Wert auftritt, wenn in der Grundgesamtheit tatsächlich kein Zusammenhang vorliegt.

Als Prüfgröße dient $\chi^2$, der kritische Wert lässt sich in [[R for basic stats|R]] berechnen.

Jedes Tabellenfeld muss beobachtete Häufigkeiten größer oder gleich 5 enthalten. 

#### Freiheitsgrade

$FG = n - a$

a bezeichnet hierbei die Zahl der geschätzten Parameter, die in die Berechnung mit eingeflossen sind, etwa der geschätzte Mittelwert der GG aus der Stichprobe bei der Schätzung der Varianz der GG aus der Stichprobe.