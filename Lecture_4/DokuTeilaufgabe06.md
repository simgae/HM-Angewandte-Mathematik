In der Aufgabe 6 sollen wir einen Datensatz konstruieren und plotten, welcher ein Mensch leicht klassifizieren kann. Dem Adaline soll dies jedoch nicht möglich sein.
Um eine Lösung für dieses Problem finden zu können muss man sich zuerst die Grenzen der Adaline anschauen. Unsere Adaline nutzt für die Kategorisierung die Gleichung f(x) = $w₀ + w₁ * x \over -w₂$
Dabei handelt es sich um eine Geradengleichung. Deswegen kann unsere Grenzlinie zwischen den zwei Kategorien keine Biegungen haben.
Somit sind Funktionsverläufe wessen höchster Grad größer 1 ist, mathematisch nicht möglich.
Um es dem Adaline nun nicht möglich zu machen, wurde in unserem Fall die nächsthöhere Funktion ausgewählt, die quadratische Funktion.

![Teilaufgabe06Abbild01.png](../Teilaufgabe06Abbild01.png)
Abbildung 01

Es wurden die neuen Punkte mithilfe zweier Parabeln gesetzt. Die erste Kategorie an Plots sind außerhalb der grünen Parabel f(x) gesetzt worden. Die zweite Kategorie wurde innerhalb der blauen Parabel g(x) gesetzt. Somit soll die Grenze für die Einkategorisierung zwischen f(x) und g(x) liegen, welche von der schwarzen Funktion h(x) repräsentiert wird. Zur Veranschaulichung, Abbild 01.
Dies sollte es für einen Menschen einfacher machen die Punkte einzuteilen. Für das Adaline ändert dies nichts, da es weiterhin unmöglich bleibt solch ein Datensatz zu kategorisieren, da eine quadratische Gleichung nötig wäre. 

![Teilaufgabe06Abbild02.png](../Teilaufgabe06Abbild02.png)
Abbildung 02

Unser Datensatz sieht nun so wie in Abbild 02 aus.

Somit zeigt sich auch eine Möglichkeit, dieses Problem lösen zu können.
Wenn das Adaline mit einer Funktion höheren Grades implementiert wird sollte es auch diesen Datensatz lösen können, da es in der Lage sein sollte, Parabeln und ähnliches konstruieren zu können.
