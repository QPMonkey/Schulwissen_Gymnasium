Die **Definitionsmenge $D$** (auch Definitionsbereich genannt) ist in der 8. Klasse – sowohl in Mathematik als auch in Physik – ein extrem wichtiges Thema. Sie legt fest, welche Zahlen du überhaupt in einen Term oder eine Gleichung einsetzen **darfst**, damit das Ergebnis mathematisch Sinn ergibt.

Diese Notiz gehört in den Ordner: **📁 01_Mathematik / 📁 01_Grundlagen**.

---

# 📄 Definitionsmenge $D$

## 📌 Metadaten

**Thema:** Erlaubte Einsetzwerte

**Übergeordnetes Kapitel:** [[Map of Content - Mathematik 8]]

**Status:** 🟡 (Wichtig für Bruchterme)

**Tags:** #Mathe8 #Definitionsmenge #Bruchterme #Nullstellen

---

## 💡 1. Das Kernkonzept

In der Mathematik gibt es ein "strenges Verbot": **Du darfst niemals durch Null teilen!**

Sobald eine Variable (wie $x$) im Nenner eines Bruchs steht, musst du prüfen, für welche Werte von $x$ der Nenner genau Null werden würde. Diese Werte müssen aus der Grundmenge $G$ (meistens die rationalen Zahlen $\mathbb{Q}$) ausgeschlossen werden.

> [!important] Merkregel
> 
> Nenner $\neq 0$

---

## 📖 2. Bestimmung der Definitionsmenge

Um $D$ zu bestimmen, gehst du in drei Schritten vor:

1. **Nenner gleich Null setzen:** Finde heraus, wann der Nenner verschwindet.
    
2. **Gleichung lösen:** Bestimme den Wert von $x$.
    
3. **Menge notieren:** Schreibe die Definitionsmenge in der korrekten Form auf.
    

### Beispiel 1: Einfacher Nenner

Term: $\frac{5}{x - 3}$

- **Rechnung:** $x - 3 = 0 \Rightarrow x = 3$
    
- **Definitionsmenge:** $D = \mathbb{Q} \setminus \{3\}$
    
    _(Gelesen: "D ist die Menge der rationalen Zahlen ohne die Zahl 3")_
    

### Beispiel 2: Quadratischer Nenner

Term: $\frac{10}{x^2 - 16}$

- **Rechnung:** $x^2 - 16 = 0 \Rightarrow x^2 = 16 \Rightarrow x = 4$ oder $x = -4$
    
- **Definitionsmenge:** $D = \mathbb{Q} \setminus \{-4; 4\}$
    
    _(Tipp: Hier hilft oft das Faktorisieren mit dem 3. Binom: $(x-4)(x+4)$)_
    

---

## ✍️ 3. Besonderheit: Faktorisierte Nenner

Wenn der Nenner aus mehreren Klammern besteht, musst du jede Klammer einzeln prüfen.

Term: $\frac{x + 1}{x \cdot (x - 5)}$

- **Teil 1:** $x = 0$
    
- **Teil 2:** $x - 5 = 0 \Rightarrow x = 5$
    
- **Ergebnis:** $D = \mathbb{Q} \setminus \{0; 5\}$
    

---

## ⚡ 4. Warum ist das so wichtig?

1. **Bruchgleichungen:** Wenn du eine Gleichung löst und am Ende $x = 3$ herauskommt, dein $D$ aber $\{3\}$ ausschließt, hat die Gleichung **keine Lösung** ($L = \emptyset$).
    
2. **Funktionen:** In der Analysis bestimmt die Definitionsmenge, wo der Graph der Funktion unterbrochen ist (z. B. eine Polstelle).
    

---

## ⚠️ 5. Typische Fehler & Stolperfallen

- ❌ **Zähler beachten:** Die Definitionsmenge hängt **nur** vom Nenner ab. Was im Zähler steht, ist völlig egal – der Zähler darf ruhig Null werden.
    
- ❌ **Vorzeichen-Fehler:** Bei $(x + 2)$ im Nenner ist die Definitionslücke $-2$, nicht $+2$.
    
- ❌ **Leere Menge vergessen:** Wenn der Nenner niemals Null werden kann (z. B. $x^2 + 1$), dann ist $D = \mathbb{Q}$.
    

---

## 🌐 6. Internetressourcen

- 🎥 **[Lehrer Schmidt: Definitionsmenge bestimmen](https://www.google.com/search?q=lehrer+schmidt+definitionsmenge)** – Sehr klare Beispiele für den Einstieg.
    
- 🎥 **[simpleclub: Definitionsbereich von Bruchtermen](https://www.google.com/search?q=simpleclub+definitionsmenge+bruchterme)** – Gute grafische Darstellung.
    

---

## 🔄 7. Vernetzung

- **Basiert auf:** [[Lineare Gleichungen lösen]], [[Faktorisieren bei Bruchtermen]].
    
- **Anwendung in:** [[Bruchgleichungen lösen]], [[Funktionen]].