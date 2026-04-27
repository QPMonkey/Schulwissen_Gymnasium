
## 📌 Metadaten

**Thema:** Verhalten von Funktionen im Unendlichen und an Lücken

**Übergeordnetes Kapitel:** [[Gebrochen-rationale Funktionen]]

**Status:** 🔵 (Verständnis-Fokus)

**Tags:** #Mathe8 #Funktionen #Asymptote #Analysis

---

## 💡 1. Intuition & Kernkonzept

> [!abstract] Das Konzept auf den Punkt gebracht
> 
> Eine Asymptote ist eine Gerade, der sich der Graph einer Funktion **beliebig nah annähert**, die er aber im betrachteten Bereich **niemals berührt oder schneidet**.
> 
> Stell es dir wie eine magnetische Barriere vor: Der Graph schmiegt sich eng an, darf aber nicht drüber.

---

## 📖 2. Die zwei Arten von Asymptoten

Es gibt zwei Richtungen, in denen sich ein Graph "verlieren" kann: nach oben/unten oder ganz weit nach links/rechts.

### A) Die senkrechte Asymptote (Die "Mauer")

Diese entsteht dort, wo der Nenner eines Bruchs **Null** wird. Da man durch Null nicht teilen darf, "explodiert" der Funktionswert dort ins Unendliche.

- **Wo?** An den Definitionslücken (Polstellen).
    
- **Gleichung:** Hat immer die Form **$x = a$** (z. B. $x = 3$).
    
- **Verhalten:** Der Graph haut nach $+\infty$ oder $-\infty$ ab.
    

### B) Die waagrechte Asymptote (Das "Ufer")

Diese zeigt dir, was passiert, wenn $x$ extrem groß ($1.000.000$) oder extrem klein ($-1.000.000$) wird.

- **Wo?** Siehst du oft direkt am konstanten Wert hinter dem Bruch.
    
- **Gleichung:** Hat immer die Form **$y = c$** (z. B. $y = 2$).
    
- **Verhalten:** Der Graph "legt sich flach" auf diese Linie.
    

---

## ✍️ 3. Beispiel-Analyse

Nehmen wir die Funktion:

$$f(x) = \frac{1}{x - 2} + 3$$

1. **Senkrechte Asymptote:**
    
    Schau in den Nenner: $x - 2 = 0 \Rightarrow \mathbf{x = 2}$.
    
    An der Stelle $2$ ist eine unsichtbare senkrechte Mauer.
    
2. **Waagrechte Asymptote:**
    
    Schau auf die Zahl am Ende: $\mathbf{y = 3}$.
    
    Wenn $x$ riesig wird, wird der Bruch $\frac{1}{\text{Riesenzahl}}$ fast Null. Übrig bleibt die $3$.
    

---

## ⚡ 4. Profi-Tipps zum Zeichnen

- 🖊️ **Gestrichelte Linien:** Zeichne Asymptoten in Koordinatensystemen **immer gestrichelt** ein. Sie sind Hilfslinien und gehören nicht direkt zum Funktionsgraphen.
    
- 🧭 **Orientierung:** Die Asymptoten teilen dein Koordinatensystem in Bereiche (Quadranten) auf. Der Graph einer einfachen Hyperbel liegt immer in zwei gegenüberliegenden Bereichen.
    
- 🚫 **Keine Berührung:** Achte beim Zeichnen darauf, dass deine Kurve die Asymptote wirklich nie berührt, auch wenn sie noch so nah dran ist.
    

---

## 🏃 5. Verständnis-Check

- [ ] **Frage 1:** Kann eine Funktion zwei senkrechte Asymptoten haben?
    
    - _Antwort:_ >! Ja, wenn der Nenner zwei Nullstellen hat (z. B. durch Ausklammern oder 3. Binomische Formel). Beispiel: $f(x) = \frac{1}{(x-1)(x+2)}$ hat Asymptoten bei $x=1$ und $x=-2$. !<
        
- [ ] **Frage 2:** Wo liegt die waagrechte Asymptote bei $f(x) = \frac{5}{x}$?
    
    - _Antwort:_ >! Da hinten keine Zahl steht (also $+0$), liegt sie genau auf der x-Achse: $y = 0$. !<
        

---

## 🔄 6. Vernetzung

- **Wichtig für:** [[Kurvendiskussion]] (höhere Klassen).
    
- **Zusammenhang:** Die senkrechte Asymptote bestimmt die [[Definitionsmenge]], die waagrechte oft die **Wertemenge**.