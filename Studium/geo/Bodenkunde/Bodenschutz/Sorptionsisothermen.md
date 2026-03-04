#Bodenschutz

Ziel einer Sorptionsisotherme ist, die Sorptionskapazität eines Bodens zu bestimmen, sowie die (im)mobilisierbare Metallmnge einer Bodenlösung bekannter Konzentration abzuschätzen. Sie gilt für eine spezifische Temperatur (Isotherme!).  

Beispiel:

![[{93A6BB3B-12E2-46B7-9092-ECE8A421C85C}.png]]

Prinzip: X-Achse: Zugabemenge/Konzentration des Adsorptivs. Y-Achse: Sorption.
Es werden verschiedene Adsorptivkonzentrationen zugegeben, dann gewartet bis sich ein Adsorptionsgleichgewicht einstellt. Dabei sinkt die Konzentration in der Lösung. Daraufhin wird bei der nun bestehenden Konzentration auf der X-Achse die sorbierte Menge abgetragen (Achtung, nicht bei der zugegebenen Konzentration!). Eventuell wird auf der X-Achse daher nicht die zugegebene, sondern die Gleichgewichtskonzentration angegeben. Dabei ist zu beachten, dass die Kurve nach links gestaucht wird, da die GGC bei hoher geringer Konz immer durch Sorption gegen 0 sinken:

![[{FA78FF25-70CE-405B-93C5-23A0AC4D2FC6}.png]]

Beachte dass bei sehr niedrigen Konzentrationen die GG-Konz über der zugegebenen Konz liegt, da die SM vor allem desorbieren. Die Kurve steigt nicht unendlich weiter an, da die Böden irgendwann nicht weiter adsorbieren können, egal wie hoch die zugegeben Konz sind. Das entstehende Plateau zeigt die maximal sorbierbare Menge an Sm für den Boden.

## Typen von Sorptionsprozessen

In der Regel wird die maximale Adsorption in Versuchen nicht erreicht, daher muss die Isotherme mit mathematischen Modellen verlängert werden. Dies geschieht je nach Typ mit verschiedenen Modellen.

Alle diese Modelle haben zahlreiche Vorannahmen, die nicht unbedingt stimmen. Bekannte Modelle sind das Langmuir-Modell und das Freundlich Modell. Beide erlauben Abschätzungen der Bindungsaffinität K (Werte der zwei Gleichungen nicht vergeichbar!), die Langmuir-Gleichung auch die maximal adsorbierbare Menge $q_{max}$. Dafür werden K und $q_{max}$ per Algorithmus bestmöglich den empirischen Daten angepasst.

Langmuir:

$$
q=\frac{q_{max}KC}{(1+KC)}
$$ 

Freundlich:

$$
q=KC^n
$$

wobei q = sorbierte Menge (abhängige Var.) und C = gelöste Menge (unabh. Var.). n ist ein empirischer Korrekturfaktor.

### L-Typ

Häufigster, einfachster Fall: hohe Affinität bei geringer Belegung der Bindungsstellen, Affinität nimmt ab, Sorption erreicht Maximum.

Beispielverlauf:

![[{EADA8161-5F53-4EE9-93EC-E8051AC8B847}.png]]

### H-Typ

Sonderfall mit extrem hoher Affinität, typisch für Bildung von Durchdringungskomplexen/Innersphärischen Komplexen mit großen Polymeren.

Beispielverlauf:

![[{12C0F171-0849-4FE2-8157-6D33992194C9}.png]]

### C-Typ

Isotherme steigt unabhängig von der Konzentration. Die Verteilung des Adsorbtivs zwischen Adsorbens und Lösung bleibt gleich. Die Sorption ist weit vom Maximum entfernt. Dieser Typ ist typisch für die Sorption hydrophober Stoffe.

Beispielverlauf: 

![[{E3F52151-2AA4-41BD-B05A-E96477134080}.png]]

### S-Typ

Geringe Affinität des Adsorptivs, da sehr konkurrenzschwach. erst bei höheren Kontentrationen steigt die Adsorption. Später erreicht auch sie ein Limit.

Beispielverlauf:

![[{C8FFB890-C74F-4307-B007-DB52002872D2}.png]]

## Desorptionsprozesse

Da die Adsorption oft weitgehend irreversibel ist, aufgrund starker, kovalenter, oft multipler Bindungen, muss die Lösungskonzentration sehr stark sinken, um die sorbierte SM-Menge zu reduzieren.

Beispielkurven:

![[{1D79E77B-811D-4C48-AE33-15A1C75C1C1F}.png]]

Erst bei sehr geringen C beginnt q zu sinken. Der Abstand der zwei Kurven (Hysterese) unterscheidet sich je nach Metall aufgrund unterschiedlicher Affinitäten.