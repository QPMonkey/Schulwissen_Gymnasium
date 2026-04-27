# 📄 Vektoraddition (Ketten-Methode)

## 📌 Metadaten
**Thema:** Grafische Addition von Vektoren
**Übergeordnetes Kapitel:** [[Der Geschwindigkeitsvektor]]
**Fach:** #Mathemathe8 #Physik8
**Status:** 🟢 (Basis-Skill)

---

## 💡 1. Das "Endpunkt-an-Anfangspunkt"-Prinzip
Die intuitivste Art, Vektoren zu addieren, ist das Aneinanderreihen zu einer Kette. Man stellt sich die Vektoren dabei wie aufeinanderfolgende Wegbeschreibungen vor.

### Die Konstruktionsregel:
1. **Erster Vektor:** Zeichne den Vektor $\vec{a}$ an seinem Startpunkt ein.
2. **Verschieben:** Nimm den zweiten Vektor $\vec{b}$ und verschiebe ihn parallel so, dass sein **Anfangspunkt** (Fuß) genau auf dem **Endpunkt** (Spitze) von $\vec{a}$ liegt.
3. **Ergebnisvektor:** Die Summe $\vec{s} = \vec{a} + \vec{b}$ ist der direkte Pfeil vom **Startpunkt des ersten** Vektors zum **Endpunkt des letzten** Vektors.



---

## 🏗️ 2. Die Vektorkette (Mehrere Vektoren)
Das Prinzip lässt sich auf beliebig viele Vektoren erweitern. Es entsteht ein sogenanntes **Vektorpolygon** (Vektorzugeck).

> [!abstract] Regel für die Kette
> $\vec{s} = \vec{a} + \vec{b} + \vec{c} + \dots$
> Man verbindet alle Vektoren so, dass der Startpunkt des nächsten immer der Endpunkt des Vorgängers ist. Der Summenvektor schließt die Lücke vom Start zum Ziel.



---

## ⚖️ 3. Spezialfall: Geschlossene Kette
Wenn du eine Kette aus Vektoren zeichnest und die letzte Spitze landet **exakt wieder am ersten Startpunkt**, nennt man das eine geschlossene Kette.

* **Das Ergebnis:** Die Summe aller Vektoren ist der **Nullvektor** ($\vec{0}$).
* **Bedeutung in der Physik:** Wenn alle Kraftvektoren an einem Körper eine geschlossene Kette bilden, herrscht **Kräftegleichgewicht** (der Körper beschleunigt nicht).



---

## ✍️ 4. Vergleich: Zeichnung vs. Rechnung
In der 8. Klasse prüfen wir das oft rechnerisch mit Koordinaten:

| Schritt | Grafisch (Kette) | Rechnerisch (Komponenten) |
| :--- | :--- | :--- |
| **Aktion** | Pfeile aneinander hängen | $x$-Werte und $y$-Werte addieren |
| **Vorteil** | Man sieht die Richtung sofort | Man muss nicht genau zeichnen |

**Beispiel:** $\vec{a} = \begin{pmatrix} 3 \\ 1 \end{pmatrix}$ (3 rechts, 1 hoch) + $\vec{b} = \begin{pmatrix} 1 \\ 2 \end{pmatrix}$ (1 rechts, 2 hoch) 
$\rightarrow \vec{s} = \begin{pmatrix} 3+1 \\ 1+2 \end{pmatrix} = \begin{pmatrix} 4 \\ 3 \end{pmatrix}$

---

## 🔄 Vernetzung
- **Anwendung:** [[Geschwindigkeitsvektor]] (Boot im Fluss)
- **Alternative:** [[Vektorparallelogramm]] (wenn beide am selben Punkt starten)