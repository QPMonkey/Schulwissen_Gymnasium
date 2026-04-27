# 📄 Grundlegendes Vorgehen bei der Faktorisierung

## 📌 Metadaten

**Thema:** Strategien zur Termzerlegung

**Übergeordnetes Kapitel:** [[Termumformungen]]

**Status:** 🟡 (Wichtige Methode)

**Tags:** #Mathe8 #Algebra #Faktorisieren #Ausklammern #Binome

---

## 💡 1. Die "Drei-Stufen-Prüfung"

Wenn du einen Term vor dir hast, den du faktorisieren sollst, gehst du **immer** in dieser festen Reihenfolge vor. Das spart Zeit und verhindert Fehler.

### Stufe 1: Gemeinsame Faktoren ausklammern

Prüfe zuerst: Haben alle Glieder eine gemeinsame Zahl oder Variable?

- **Beispiel:** $4x^2 + 8x$
    
- **Aktion:** Die $4$ und ein $x$ stecken in beiden Teilen.
    
- **Ergebnis:** $4x \cdot (x + 2)$
    

### Stufe 2: Binomische Formeln prüfen (Rückwärts)

Wenn du nichts mehr ausklammern kannst, schau dir die Anzahl der Glieder an:

- **2 Glieder & Minus dazwischen?** $\rightarrow$ Verdacht auf **3. Binomische Formel**.
    
    - $x^2 - 25 = (x + 5)(x - 5)$
        
- **3 Glieder?** $\rightarrow$ Verdacht auf **1. oder 2. Binomische Formel**.
    
    - $x^2 + 10x + 25 = (x + 5)^2$
        

### Stufe 3: Mehrfache Anwendung (Kombinieren)

Oft musst du erst ausklammern, um dann ein Binom zu finden.

- **Beispiel:** $2x^2 - 18$
    
- 1. Ausklammern: $2 \cdot (x^2 - 9)$
        
- 2. Binom anwenden: $2 \cdot (x + 3)(x - 3)$
        

---

## 🛠️ 2. Die Werkzeugkiste: Techniken im Detail

### Das "Minus-Eins"-Manöver

Besonders nützlich bei Bruchtermen, wenn die Vorzeichen im Nenner genau falsch herum stehen.

- Term: $b - a$
    
- Ziel: Es soll wie $(a - b)$ aussehen.
    
- Tricks: Klammere $-1$ aus: $-1 \cdot (-b + a) = \mathbf{-1 \cdot (a - b)}$
    

### Variablen-Check

Achte beim Ausklammern von Variablen immer auf die **kleinste Potenz**, die in allen Gliedern vorkommt.

- $x^5 + x^3 + x^2 = \mathbf{x^2} \cdot (x^3 + x + 1)$
    

---

## ✍️ 3. Zusammenfassung: Der "Entscheidungsbaum"

|**Frage**|**Methode**|**Beispiel**|
|---|---|---|
|Haben alle Teile etwas Gemeinsames?|**Ausklammern**|$ax + ay = a(x+y)$|
|Zwei Quadrate mit Minus dazwischen?|**3. Binom**|$a^2 - b^2 = (a+b)(a-b)$|
|Drei Teile mit zwei Quadraten am Rand?|**1. / 2. Binom**|$a^2 \pm 2ab + b^2 = (a \pm b)^2$|

---

## ⚠️ 4. Stolperfallen

- ❌ **Zu früh aufhören:** Viele klammern aus, sehen aber das Binom in der Klammer nicht mehr.
    
- ❌ **Summen kürzen:** Erinnere dich: Faktorisieren dient dazu, dass du **Mal-Punkte** bekommst. Nur dann darfst du in Brüchen kürzen!
    
- ❌ **Rechenzeichen-Fehler:** Achte beim Ausklammern negativer Zahlen darauf, dass sich **alle** Zeichen in der Klammer umdrehen.
    

---

## 🌐 5. Ressourcen

- 🎥 **[Lehrer Schmidt: Faktorisieren - Alles was man wissen muss](https://www.google.com/search?q=lehrer+schmidt+faktorisieren+zusammenfassung)**
    
- 🎥 **[Daniel Jung: Terme faktorisieren Basics](https://www.google.com/search?q=daniel+jung+terme+faktorisieren)**
    
- 🧩 **[Schlaukopf: Training Ausklammern & Binome](https://www.schlaukopf.de/)**