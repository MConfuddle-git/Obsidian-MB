---
cssclasses:
  - cornell-left
---
### Gebrochen Rationale Funktionen
- **Definition:** Eine Funktion der Form `f(x) = P(x) / Q(x)`, wobei `P(x)` und `Q(x)` Polynome sind.
- Der **maximale Definitionsbereich** einer gebrochen rationalen Funktion ![[Pasted image 20260114164823.png]] ist also![[Pasted image 20260114165010.png]]. 
- **Definitionslücken:** Die Nullstellen des Nenners `Q(x)` sind Definitionslücken.
    - **Hebbare Lücken:** Eine Nullstelle des Nenners, die auch eine Nullstelle des Zählers ist, führt zu einer hebbaren Lücke, wenn der entsprechende Linearfaktor gekürzt werden kann.
    - **Pole:** Eine Nullstelle des Nenners, die nach dem Kürzen verbleibt, ist ein Pol. An dieser Stelle hat der Graph eine vertikale Asymptote.
    - **Ordnung**: 
- **Asymptotisches Verhalten (**`|x| → ∞`**):**
    - **Zählergrad < Nennergrad:** Die x-Achse (`y = 0`) ist eine horizontale Asymptote.
    - **Zählergrad = Nennergrad:** Die horizontale Gerade `y = a_m / b_n` (Verhältnis der Leitkoeffizienten) ist eine Asymptote.
    - **Zählergrad > Nennergrad:** Das asymptotische Verhalten entspricht dem Polynom, das sich aus der Polynomdivision `P(x) : Q(x)` ergibt (schräge oder polynomielle Asymptote).

>[!cue] Verhalten an Definitionslücken

![[Pasted image 20260114165412.png]]


>[!cue] Asymptoten

>[!cue] y-Achsenabschnitt


>[!cue] Vorzeichenschema


------
>[!cue] Funktionsanalyse (Kurvendiskussion)

1. Nullstellen finden f(x) = 0
	1. Ordnung
2. Steigung analysieren f'
	1. f'(x) > 0 steigt
	2. f'(x) < 0 fällt
3. Extrempunkte f'(x) = 0
4. Krümmung analysieren f''
	1. f''(x) > 0 linksgekrümmt (konvex)
	2. f''(x) < 0 rechtsgekrümmt (konkav)
5. Wendepunkte finden f''(x) = 0

f'(x) = 0 + f''(x0) < 0 Lokales Maximum
f'(x) = 0 + f''(x0) > 0 Lokales Minimum

>[!cue] Potenzieren


>[!cue] Potenzieren




----------------------------------------
>[!cue] Funktionsvorschrift

**Allgemeine Cosinus-Funktion:** `f(t) = A cos(ωx + φ) + b`
    - `A`: Amplitude (maximale Auslenkung)
    - `ω`: Kreisfrequenz
    - `φ`: Phasenwinkel
    - Periode `T = 2π / ω`

>[!cue] Ruhelage b

Bestimmen Sie das Maximum und das Minimum des Graphen. 
b ist der Mittelwert dieser beiden Werte. b = ymax + ymin / 2

>[!cue] Amplitude A

Messen Sie den vertikalen Abstand von der Ruhelage zu einem Hoch- oder Tiefpunkt.

>[!cue] Primitive Periode T

Lesen Sie die Periodenlänge T direkt aus dem Graphen ab, indem Sie den horizontalen Abstand zwischen zwei aufeinanderfolgenden Hochpunkten oder Tiefpunkten messen.

>[!cue] Kreisfrequenze w

w = 2pi / T

>[!cue] Phasenwinkel/-verschiebung φ

 Suchen Sie den x-Wert des ersten Hochpunkts rechts von der y-Achse. 
 Dieser Wert ist die Phasenverschiebung φ.

>[!cue] Laufzeitdifferenz L

𝐿 = 𝜙 / 𝜔= 𝜙⋅𝑇 / 2𝜋 

----------------------------------------

>[!cue] Ableitungsregeln

| Regel               | Formel                                               |
| ------------------- | ---------------------------------------------------- |
| **Potenzregel**     | `(x^r)' = r · x^(r-1)`                               |
| **Faktorregel**     | `(c · f(x))' = c · f'(x)`                            |
| **Summenregel**     | `(f(x) ± g(x))' = f'(x) ± g'(x)`                     |
| **Produktregel**    | `(f(x) · g(x))' = f'(x)g(x) + f(x)g'(x)`             |
| **Quotientenregel** | `(f(x) / g(x))' = (f'(x)g(x) - f(x)g'(x)) / (g(x))²` |
| **Kettenregel**     | `(f(g(x)))' = f'(g(x)) · g'(x)`                      |
>[!cue] Ableitungen elementarer Funktionen

| Funktion `f(x)` | Ableitung `f'(x)`   |
| --------------- | ------------------- |
| `sin(x)`        | `cos(x)`            |
| `cos(x)`        | `-sin(x)`           |
| `e^x`           | `e^x`               |
| `ln(x)`         | `1/x`               |
| `arcsin`        | 1 / √1-x²           |
| `arccos`        |                     |
| `arctan (g(x))` | `g'(x) / 1+(g(x))²` |

----------------------------------------
>[!cue] Tangente


-------
>[!cue] Grenzwert berechnen

Um einen Grenzwert zu bestimmen, gehst du so vor:
1. Prüfe, ob du den Grenzwert gegen **unendlich** oder gegen eine **Zahl** (z.B. 2) suchst.
2. Erstelle eine Wertetabelle mit **großen** x-Werten (z.B. 1.000.000) 
   oder x-Werten **nah an der Zahl** (z.B. 2,001).
3. Ließ den Grenzwert an den y-Werten ab.

Das x mit dem **meisten Einfluss** bestimmt den **Grenzwert** der gesamten Funktion:
1. x im Exponent (z.B. e^x) → sehr viel Einfluss
2. x mit höchstem Exponenten (z.B. x³)
3. x ohne Exponent
4. x in der Wurzel → sehr wenig Einfluss
----------------------------------------
>[!cue] Vektoren
#### Skalarprodukt 
- **Geometrische Definition:** a⃗ · b⃗ = |a⃗| · |b⃗| · cos(φ), wobei `φ` der von den Vektoren eingeschlossene Winkel ist. 
- **Koordinatenform:** a⃗ · b⃗ = a₁b₁ + a₂b₂ + ... + aₙbₙ
- **Betrag eines Vektors:** |𝑎⃗|=√𝑎²𝑥+𝑎²𝑦+𝑎²𝑧
 
**Zusammenhang zwischen Skalarprodukt und Winkel:** 
- a⃗ · b⃗  > 0: Spitzer Winkel (α < 90°)
- a⃗ · b⃗  = 0: Rechter Winkel (α =90°)
- a⃗ · b⃗  < 0: Stumpfer Winkel (α > 90°)
- Der exakte Winkel lässt sich mit der Formel α = arccos(a⃗⋅b⃗ / |a⃗|⋅|b⃗|) bestimmen.

**Anwendungen und Eigenschaften:**
- **Längenberechnung:** |a⃗| = √a⃗·a⃗
- **Winkelberechnung:** cos(φ) = (a⃗ · b⃗) / (|a⃗| · |b⃗|)
- **Orthogonalitätstest:** Zwei Vektoren sind genau dann orthogonal (senkrecht) zueinander, 
  wenn ihr Skalarprodukt Null ist: a⃗ ⊥ b⃗ ⇔ a⃗ · b⃗ = 0 (für a⃗, b⃗ ≠ 0⃗ ).
#### Vektorprodukt (Kreuzprodukt) im ℝ³
- **Definition:** Der Ergebnisvektor a⃗ × b⃗ steht senkrecht auf der von a⃗ und b⃗ aufgespannten Ebene. Seine Orientierung wird durch die **Rechte-Hand-Regel** bestimmt.
- **Betrag und Anwendung:** Der Betrag |a⃗ × b⃗| = |a⃗| · |b⃗| · sin(φ) entspricht der **Fläche des Parallelogramms**, das von a⃗ und b⃗ aufgespannt wird.
- **Koordinatenform:** Für a⃗ = (a₁, a₂, a₃)ᵀ und b⃗ = (b₁, b₂, b₃)ᵀ werden die Komponenten des Ergebnisvektors c⃗ = a⃗ × b⃗ mithilfe von 2x2-Determinanten berechnet:
    - `c₁ = |a₂ b₂| / |a₃ b₃| = a₂b₃ - a₃b₂`
    - `c₂ = |a₃ b₃| / |a₁ b₁| = a₃b₁ - a₁b₃`
    - `c₃ = |a₁ b₁| / |a₂ b₂| = a₁b₂ - a₂b₁`
- **Eigenschaft:** Zwei Vektoren sind genau dann parallel, wenn ihr Vektorprodukt der Nullvektor ist: a⃗ || b⃗ ⇔ a⃗ × b⃗ = 0⃗.
#### Spatprodukt im ℝ³
Das Spatprodukt kombiniert Vektor- und Skalarprodukt.
- **Definition:** [a⃗, b⃗, c⃗] := a⃗ · (b⃗ × c⃗)
- **Geometrische Bedeutung:** Der Betrag des Spatprodukts |[a⃗, b⃗, c⃗]| entspricht dem **Volumen des Spats** (Parallelepipeds), das von den drei Vektoren a⃗, b⃗ und c⃗ aufgespannt wird.
- **Eigenschaft:** Drei Vektoren sind genau dann komplanar (liegen in einer Ebene), wenn ihr Spatprodukt Null ist: [a⃗, b⃗, c⃗] = 0.

----------------------------------------
>[!cue] LGS
### 1. Schritt: Finde die Zeilenstufenform
Beim Umformen darfst du nur diese drei Dinge mit dem linearen Gleichungssystem tun:
1. Addieren und Subtrahieren von Zeilen
2. Multiplizieren und Dividieren von Zeilen mit einer Zahl
3. Vertauschen von Zeilen
### 2. Schritt: Erste Lösung ablesen
### 3. Schritt: Rückwärts einsetzen
#### Lösungsverhalten
Ein LGS kann genau eine der drei folgenden Lösungsmengen haben:

1. **Eindeutige Lösung:** Das System hat exakt eine Lösung. In der Zeilen-Stufen-Form gibt es keine Widersprüche und keine freien Variablen.
2. **Keine Lösung:** Das System ist unlösbar. In der Zeilen-Stufen-Form tritt ein Widerspruch auf, typischerweise eine Zeile der Form `0 0 ... 0 | c` mit `c ≠ 0`.
3. **Unendlich viele Lösungen:** Das System hat eine unendliche Lösungsmenge. In der Zeilen-Stufen-Form gibt es mindestens eine Variable, die nicht als führendes Element (Pivot) einer Zeile auftritt und somit frei wählbar ist.

----------------------------------------
>[!cue] Inverse Matrix

1. Invertierbar? Quadtratisch + Determinate =/ 0
2. Einheitsmatrix notieren
3. Umformen
4. Inverse Matrix ablesen
------
>[!cue] Matrizen

