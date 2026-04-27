**Thema:** Funktionen mit $x$ im Nenner

**Übergeordnetes Kapitel:** [[Map of Content - Mathematik 8]]

**Status:** 🔴 (Neu & Wichtig!)

**Tags:** #Mathe8 #Funktionen #Hyperbel #Asymptoten

---

## 💡 1. Intuition & Kernkonzept

> [!abstract] Das Konzept auf den Punkt gebracht
> 
> Eine gebrochen-rationale Funktion ist ein Bruch, bei dem das **$x$ im Nenner** steht.
> 
> Das Problem: In der Mathematik darf man **niemals durch 0 teilen**. Das führt dazu, dass der Graph an bestimmten Stellen "reißt" oder eine unsichtbare Mauer (Asymptote) hat.

---

## 📖 2. Erklärung & Regeln

### A) Die Grundform

Die einfachste Form ist die **Hyperbel**:

$$f(x) = \frac{k}{x}$$

- Ist $k$ positiv, liegt der Graph im I. und III. Quadranten.
    
- Ist $k$ negativ, liegt er im II. und IV. Quadranten.
    

### B) Die Definitionsmenge $D$ (Das Mathe-Verbot)

Du musst immer prüfen, für welches $x$ der Nenner Null wird. Diese Zahl fliegt aus der Definitionsmenge raus.

- Beispiel: bei $f(x) = \frac{5}{x-2}$ ist $D = \mathbb{Q} \setminus \{2\}$, denn $2-2=0$.
    

### C) Asymptoten (Die unsichtbaren Mauern)

Der Graph nähert sich diesen Linien immer weiter an, berührt sie aber nie.


1. **Senkrechte Asymptote (Polstelle):** Dort, wo der Nenner Null wird (bei $x = 2$ im Beispiel oben).
    
2. **Waagrechte Asymptote:** Beschreibt das Verhalten, wenn $x$ riesig groß oder winzig klein wird. Bei $f(x) = \frac{k}{x} + c$ ist die waagrechte Asymptote bei $y = c$.

Siehe auch‚ [[Asymptoten verstehen]]

---

## ✍️ 3. Durchgerechnetes Beispiel: Analyse von $f(x) = \frac{1}{x-3} + 2$

1. **Definitionsmenge:** Der Nenner $x-3$ wird Null, wenn $x=3$. Also $D = \mathbb{Q} \setminus \{3\}$.
    
2. **Senkrechte Asymptote:** Eine senkrechte Gerade bei **$x = 3$**.
    
3. **Waagrechte Asymptote:** Die Zahl am Ende ist $+2$. Also eine waagrechte Gerade bei **$y = 2$**.
    
4. **Graph:** Es ist eine Hyperbel, deren "Zentrum" vom Ursprung auf den Punkt $(3|2)$ verschoben wurde.
    

---

## ⚡ 4. Typische Fehler & Stolperfallen

- ❌ **Definitionslücke vergessen:** In Schulaufgaben gibt es fast immer einen Punkt Abzug, wenn du $D$ nicht angibst.
    
- ❌ **Asymptote mit Graph verwechseln:** Die Asymptote gehört nicht zum Graphen selbst, sie ist nur eine Orientierungshilfe (zeichne sie am besten gestrichelt!).
    
- ❌ **Rechenfehler beim Einsetzen:** Wenn du Punkte für die Wertetabelle berechnest, achte auf die Vorzeichen im Nenner! $\frac{1}{-2 - 3}$ ist $-\frac{1}{5}$.
    

---

## 🏃 5. Übungsaufgaben

- [ ] **Aufgabe 1 (Definitionsmenge):** Bestimme $D$ für $f(x) = \frac{10}{2x - 8}$.
    
    - _Lösungsweg:_ >! $2x - 8 = 0 \rightarrow 2x = 8 \rightarrow x = 4$. Also $D = \mathbb{Q} \setminus \{4\}$. !<
        
- [ ] **Aufgabe 2 (Asymptoten):** Wo liegen die Asymptoten von $f(x) = \frac{1}{x+5} - 4$?
    
    - _Lösungsweg:_ >! Senkrecht bei $x = -5$ (da $-5+5=0$). Waagrecht bei $y = -4$. !<
        
- [ ] **Aufgabe 3 (Punktprobe):** Liegt der Punkt $P(1|0,5)$ auf dem Graphen von $f(x) = \frac{1}{x}$?
    
    - _Lösungsweg:_ >! Einsetzen: $0,5 = \frac{1}{1}$? Nein, $0,5 \neq 1$. Der Punkt liegt nicht darauf. !<
        

---

## 🌐 6. Ressourcen & Externe Links

- 🎥 **Video:** [Lehrer Schmidt - Gebrochen rationale Funktionen](https://www.google.com/search?q=lehrer+schmidt+gebrochen+rationale+funktionen+einf%C3%BChrung)
    
- 🧩 **Interaktiv:** [GeoGebra: Hyperbeln verschieben](https://www.google.com/search?q=geogebra+gebrochen+rationale+funktionen+verschieben)
    

---

## 🔄 7. Vernetzung

- **Basiert auf:** [[Indirekte Proportionalität (Antiproportionalität)]] (das ist der einfachste Fall dieser Funktionen).
    
- **Basiert auf:** [[Bruchrechnung]] (Division durch Terme).
    
- **Wird benötigt für:** [[Bruchgleichungen lösen]] (hier suchen wir die Schnittpunkte mit der x-Achse).