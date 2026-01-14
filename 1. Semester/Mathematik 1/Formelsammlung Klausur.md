---
cssclasses:
  - cornell-left
  - cornell-border
---
# Unecht gebrochene Funktionen
x e R mit Ausnahme x0 des Nennerpolynoms h(x)
f(x) = g(x)^m / h(x)^n
g(x) Zähler
h(x) Nenner

n>m = Echt gebrochen!

>[!cue] Definitionslücke bestimmen

Die Nullstellen des Nennerpolynoms q(x) liefern die **Definitionslücken** einer gebrochen rationalen Funktion f. Der **maximale Definitionsbereich** einer gebrochen rationalen Funktion ![[Pasted image 20260114164823.png]] ist also![[Pasted image 20260114165010.png]]. Das Nennerpolynom gleich 0 setzen.

>[!cue] Verhalten an Definitionslücken

![[Pasted image 20260114165412.png]]
>[!cue] Potenzieren


>[!cue] Potenzieren


>[!cue] Potenzieren


>[!cue] Potenzieren


>[!cue] Vorzeichenschema

----------------------------------------

>[!cue] Ruhelage b

>[!cue] Amplitude A

>[!cue] Primitive Periode T

>[!cue] Kreisfrequenze w

>[!cue] Phasenwinkel sigma

>[!cue] Laufzeitdifferenz L

>[!cue] Funktionsvorschrift

----------------------------------------

>[!cue] Funktionsvorschrift

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

| Funktion `f(x)` | Ableitung `f'(x)` |
| --------------- | ----------------- |
| `sin(x)`        | `cos(x)`          |
| `cos(x)`        | `-sin(x)`         |
| `e^x`           | `e^x`             |
| `ln(x)`         | `1/x`             |

----------------------------------------
>[!cue] Tangente


>[!cue] Grenzwert berechnen

>[!cue] Matrix


----------------------------------------
>[!cue] Vektoren
#### Skalarprodukt
Das Skalarprodukt zweier Vektoren a⃗ und b⃗ ist eine skalare Größe.
- **Geometrische Definition:** a⃗ · b⃗ = |a⃗| · |b⃗| · cos(φ), wobei `φ` der von den Vektoren eingeschlossene Winkel ist.
- **Koordinatenform:** a⃗ · b⃗ = a₁b₁ + a₂b₂ + ... + aₙbₙ

**Anwendungen und Eigenschaften:**
- **Längenberechnung:** |a⃗| = √a⃗·a⃗
- **Winkelberechnung:** cos(φ) = (a⃗ · b⃗) / (|a⃗| · |b⃗|)
- **Orthogonalitätstest:** Zwei Vektoren sind genau dann orthogonal (senkrecht) zueinander, wenn ihr Skalarprodukt Null ist: a⃗ ⊥ b⃗ ⇔ a⃗ · b⃗ = 0 (für a⃗, b⃗ ≠ 0⃗ ).

#### Vektorprodukt (Kreuzprodukt) im ℝ³
Das Vektorprodukt a⃗ × b⃗ ist nur im ℝ³ definiert und sein Ergebnis ist wieder ein Vektor.
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
>[!cue] Matrizen
