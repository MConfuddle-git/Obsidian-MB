## 1.0 Mathematische Grundlagen

### 1.1 Mengenlehre

#### 1. Definition und Darstellung

| Darstellungsform             | Beispiel                                                               |
| ---------------------------- | ---------------------------------------------------------------------- |
| **Aufzählung**               | `M = {a, b, c}` <br>`N = {1, 2, 3, ..., 100}` <br>`X = {1, 2, 3, ...}` |
| **Definierende Eigenschaft** | `A = {x                                                                |
#### 2. Grundlegende Schreibweisen

- `x ∈ M`: "x ist ein Element der Menge M" oder "x ist in M".
- `x ∉ M`: "x ist kein Element der Menge M" oder "x ist nicht in M".
- `∅` oder `{}`: Die leere Menge, welche kein einziges Element enthält.
#### 3. Vergleichsoperatoren

| Operator | Verbale Beschreibung       | Formale Definition |
| -------- | -------------------------- | ------------------ |
| `A ⊆ B`  | A ist eine Teilmenge von B | `x ∈ A ⇒ x ∈ B`    |
| `A ⊇ B`  | A ist eine Obermenge von B | `B ⊆ A`            |
| `A = B`  | A ist gleich B             | `x ∈ A ⇔ x ∈ B`    |
#### 4. Mengenoperationen

| Operation        | Schreibweise | Definition | Beschreibung       |
| ---------------- | ------------ | ---------- | ------------------ |
| **Durchschnitt** | `A ∩ B`      | `{x        | x ∈ A und x ∈ B}`  |
| **Vereinigung**  | `A ∪ B`      | `{x        | x ∈ A oder x ∈ B}` |
| **Differenz**    | `A \ B`      | `{x        | x ∈ A und x ∉ B}`  |
#### 5. Produktmenge
Die Produktmenge (auch Kreuzprodukt) zweier Mengen A und B ist die Menge aller **geordneten Paare** `(x, y)`, bei denen das erste Element aus A und das zweite aus B stammt. `A × B := {(x, y) | x ∈ A, y ∈ B}`

#### 6. Rechenregeln
Für die Mengenoperationen gelten folgende fundamentale Rechenregeln:

1. **Kommutativität:** `A ∪ B = B ∪ A` und `A ∩ B = B ∩ A`
2. **Assoziativität:** `A ∪ (B ∪ C) = (A ∪ B) ∪ C` und `A ∩ (B ∩ C) = (A ∩ B) ∩ C`
3. **Distributivität:** `A ∪ (B ∩ C) = (A ∪ B) ∩ (A ∪ C)` und `A ∩ (B ∪ C) = (A ∩ B) ∪ (A ∩ C)`

Von diesen abstrakten Mengenkonzepten leiten wir nun die konkreten Zahlenmengen ab, die das Fundament aller Berechnungen bilden.

### 1.2 Zahlenmengen und Intervalle

#### 1. Zahlenmengen
Die fundamentalen Zahlenmengen werden sukzessive erweitert, um immer komplexere Operationen zu ermöglichen.

| Menge                   | Symbol | Definition                    | Charakterisierung                                                                                   |
| ----------------------- | ------ | ----------------------------- | --------------------------------------------------------------------------------------------------- |
| **Natürliche Zahlen**   | `ℕ`    | `{1, 2, 3, ...}`              | Die grundlegenden Zählzahlen.                                                                       |
| **Nat. Zahlen inkl. 0** | `ℕ₀`   | `{0, 1, 2, 3, ...}`           |                                                                                                     |
| **Ganze Zahlen**        | `ℤ`    | `{..., -2, -1, 0, 1, 2, ...}` | Erweitert `ℕ₀` um die negativen Zahlen. Uneingeschränkte Subtraktion wird möglich.                  |
| **Rationale Zahlen**    | `ℚ`    | `{m/n                         | m, n ∈ ℤ, n ≠ 0}`                                                                                   |
| **Reelle Zahlen**       | `ℝ`    | Menge aller Dezimalzahlen     | Umfasst rationale und irrationale Zahlen (z.B. `√2`, `π`) und füllt den Zahlenstrahl lückenlos aus. |

Die Teilmengenbeziehung lässt sich wie folgt visualisieren: `ℕ ⊂ ℕ₀ ⊂ ℤ ⊂ ℚ ⊂ ℝ`.
<div class="page-break" style="page-break-before: always;"></div>

#### 2. Intervalle
Intervalle sind Teilmengen der reellen Zahlen. Für `a, b ∈ ℝ` mit `a < b` gilt:

| Typ               | Schreibweise           | Mengendefinition | Beschreibung           |
| ----------------- | ---------------------- | ---------------- | ---------------------- |
| **Abgeschlossen** | `[a, b]`               | `{x ∈ ℝ          | a ≤ x ≤ b}`            |
| **Offen**         | `(a, b)`               | `{x ∈ ℝ          | a < x < b}`            |
| **Halboffen**     | `(a, b]` oder `[a, b)` | `{x ∈ ℝ          | a < x ≤ b}`oder`{x ∈ ℝ |

_Anmerkung:_ Für offene Intervalle `(a, b)` ist in manchen Lehrbüchern auch die Schreibweise `]a, b[` gebräuchlich.

**Unendliche Intervalle:** Schreibweisen wie `[a, ∞)` (`{x ∈ ℝ | x ≥ a}`) oder `(-∞, a)` (`{x ∈ ℝ | x < a}`) beschreiben Intervalle, die sich unendlich in eine Richtung erstrecken. `ℝ` selbst entspricht `(-∞, ∞)`.

#### 3. Betrag einer Zahl
Der Betrag `|a|` einer reellen Zahl `a` ist ihr Abstand zum Nullpunkt auf dem Zahlenstrahl. Formal ist er definiert als: `|a| := a` falls `a ≥ 0`, und `|a| := -a` falls `a < 0`.

**Wesentliche Eigenschaften:**
1. `|x · y| = |x| · |y|`
2. `|x| = |-x|`
3. `|x - y| = |y - x|`
4. `|x| ≥ x` und `|x| ≥ -x`

#### 4. Dreiecksungleichung
Eine fundamentale Eigenschaft der reellen Zahlen ist die Dreiecksungleichung, die besagt, dass der Betrag einer Summe nie größer ist als die Summe der Beträge: `|x + y| ≤ |x| + |y|`

Um lange Summen und Produkte effizient handhaben zu können, wurden spezielle Notationen entwickelt.
<div class="page-break" style="page-break-before: always;"></div>

### 1.3 Summen- und Produktzeichen

#### 1. Definitionen
- **Summenzeichen (**`Σ`**):** Dient zur kompakten Darstellung von Summen. `Σ_{k=m}^n a_k := a_m + a_{m+1} + ... + a_n` Hierbei ist `k` der Laufindex, `m` der Startindex und `n` der Endindex.
- **Produktzeichen (**`Π`**):** Dient zur kompakten Darstellung von Produkten. `Π_{k=m}^n a_k := a_m · a_{m+1} · ... · a_n`

#### 2. Rechenregeln für das Summenzeichen
1. **Linearität:**
    - `Σ_{k=1}^n (a_k + b_k) = Σ_{k=1}^n a_k + Σ_{k=1}^n b_k`
    - `Σ_{k=1}^n (c · a_k) = c · Σ_{k=1}^n a_k`
2. **Indexverschiebung:**
    - `Σ_{k=1}^n a_k = Σ_{k=2}^{n+1} a_{k-1} = Σ_{k=3}^{n+2} a_{k-2}`

#### 3. Fakultät
Die Fakultät `n!` ist das Produkt der ersten `n` natürlichen Zahlen. `n! := Π_{k=1}^n k = 1 · 2 · 3 · ... · n` Für `n=0` ist `0! := 1` definiert. Es gilt die rekursive Rechenregel: `(n+1)! = n! · (n+1)`.

Von diesen allgemeinen Notationen wenden wir uns nun den spezifischen Regeln für Potenzen, Wurzeln und Logarithmen zu, die auf wiederholten Multiplikationen und deren Umkehrungen basieren.
<div class="page-break" style="page-break-before: always;"></div>

### 1.4 Potenzen, Wurzeln und Logarithmen
#### 1. Potenzen
Potenzen sind eine Kurzschreibweise für wiederholte Multiplikation.

| Exponent                             | Definition                            | Anmerkung   |
| ------------------------------------ | ------------------------------------- | ----------- |
| **Positiv ganzzahlig (**`n ∈ ℕ`**)** | `a^n := a · a · ... · a` (n Faktoren) |             |
| **Null**                             | `a^0 := 1`                            | für `a ≠ 0` |
| **Negativ ganzzahlig (**`n ∈ ℕ`**)** | `a^-n := 1 / a^n`                     | für `a ≠ 0` |
| **Rational (**`m/n`**)**             | `a^(m/n) := ⁿ√(a^m)`                  | für `a > 0` |
#### 2. Potenzgesetze
1. `a^n · a^m = a^(n+m)`
2. `a^m / a^n = a^(m-n)`
3. `(a^m)^n = a^(m·n)`
4. `a^0 = 1`
5. `a^n · b^n = (a·b)^n`
6. `a^n / b^n = (a/b)^n`
7. `1^n = 1`

#### 3. Wurzeln
Die n-te Wurzel `ⁿ√a` ist die nicht-negative Lösung der Gleichung `xⁿ = a` (für `a ≥ 0`).

- **Ausnahme:** Für ungerade `n` ist `ⁿ√a` auch für `a < 0` als die eindeutige reelle Lösung definiert.

| Regel               | Formel                |
| ------------------- | --------------------- |
| **Produkt**         | `ⁿ√(a·b) = ⁿ√a · ⁿ√b` |
| **Potenz**          | `ⁿ√(a^m) = (ⁿ√a)^m`   |
| **Quotient**        | `ⁿ√(a/b) = ⁿ√a / ⁿ√b` |
| **Verschachtelung** | `ᵐ√(ⁿ√a) = ᵐⁿ√a`      |
<div class="page-break" style="page-break-before: always;"></div>

#### 4. Logarithmen
Der Logarithmus von `b` zur Basis `a`, geschrieben `log_a(b)`, ist die Lösung `x` der Gleichung `a^x = b`.

- **Bedingungen:** `a > 0`, `a ≠ 1` und `b > 0`.

**Rechenregeln:**
1. `log_a(a) = 1`
2. `log_a(1) = 0`
3. `log_a(u · v) = log_a(u) + log_a(v)`
4. `log_a(u / v) = log_a(u) - log_a(v)`
5. `log_a(u^r) = r · log_a(u)`

**Umkehrformeln:** `log_a(a^x) = x` und `a^(log_a(x)) = x`.

#### 5. Spezielle Logarithmen
- **Natürlicher Logarithmus:** `ln(x) := log_e(x)` mit Basis `e ≈ 2.718`
- **Dekadischer Logarithmus:** `lg(x) := log₁₀(x)`
- **Dualer Logarithmus:** `log₂(x)`, fundamental in der Informatik zur Beschreibung von binären Prozessen, z.B. bei der Analyse von Datenmengen (Bits) oder Algorithmenkomplexität.

#### 6. Binomische Formeln
1. `(a + b)² = a² + 2ab + b²`
2. `(a - b)² = a² - 2ab + b²`
3. `(a + b)(a - b) = a² - b²`
<div class="page-break" style="page-break-before: always;"></div>

### 1.5 Lineare Gleichungssysteme (LGS)

#### 1. Definition
Ein lineares Gleichungssystem besteht aus `m` linearen Gleichungen mit `n` Unbekannten. Es kann in Matrixform als `A·x = b` geschrieben werden.

- **Koeffizientenmatrix** `A`**:** Enthält die Koeffizienten `a_ij` der Unbekannten.
- **Erweiterte Koeffizientenmatrix** `[A|b]`**:** Enthält zusätzlich die rechte Seite `b` des Systems.

#### 2. Gauß-Algorithmus
Das Gauß'sche Eliminationsverfahren ist ein systematischer Algorithmus zur Lösung von LGS in zwei Schritten:

1. **Vorwärtselimination:** Das System wird durch elementare Zeilenumformungen (Zeilen vertauschen, Zeile mit Faktor ≠ 0 multiplizieren, Vielfaches einer Zeile zu einer anderen addieren) in die **Zeilen-Stufen-Form** gebracht.
2. **Rückwärtseinsetzen:** Ausgehend von der letzten Zeile werden die Unbekannten schrittweise durch Einsetzen bestimmt.

#### 3. Lösungsverhalten
Ein LGS kann genau eine der drei folgenden Lösungsmengen haben:

1. **Eindeutige Lösung:** Das System hat exakt eine Lösung. In der Zeilen-Stufen-Form gibt es keine Widersprüche und keine freien Variablen.
2. **Keine Lösung:** Das System ist unlösbar. In der Zeilen-Stufen-Form tritt ein Widerspruch auf, typischerweise eine Zeile der Form `0 0 ... 0 | c` mit `c ≠ 0`.
3. **Unendlich viele Lösungen:** Das System hat eine unendliche Lösungsmenge. In der Zeilen-Stufen-Form gibt es mindestens eine Variable, die nicht als führendes Element (Pivot) einer Zeile auftritt und somit frei wählbar ist.
<div class="page-break" style="page-break-before: always;"></div>

## 2.0 Differential- und Integralrechnung

### 2.1 Differentialrechnung

#### 1. Ableitung als Grenzwert

Die Ableitung `f'(x₀)` einer Funktion `f` an einer Stelle `x₀` ist definiert als der Grenzwert des Differenzenquotienten. Sie gibt die exakte Steigung der Funktion an diesem Punkt an.

`f'(x₀) = lim_{x→x₀} (f(x) - f(x₀)) / (x - x₀)`

- **Geometrische Interpretation:** Steigung der Tangente an den Graphen von `f` im Punkt `(x₀, f(x₀))`.
- **Physikalische Interpretation:** Momentangeschwindigkeit zum Zeitpunkt `t₀`, wenn `f(t)` die Weg-Zeit-Funktion ist.
#### 2. Ableitungsregeln
Die folgenden Regeln ermöglichen die systematische Berechnung von Ableitungen, ohne auf die Grenzwertdefinition zurückgreifen zu müssen.

| Regel               | Formel                                               |
| ------------------- | ---------------------------------------------------- |
| **Potenzregel**     | `(x^r)' = r · x^(r-1)`                               |
| **Faktorregel**     | `(c · f(x))' = c · f'(x)`                            |
| **Summenregel**     | `(f(x) ± g(x))' = f'(x) ± g'(x)`                     |
| **Produktregel**    | `(f(x) · g(x))' = f'(x)g(x) + f(x)g'(x)`             |
| **Quotientenregel** | `(f(x) / g(x))' = (f'(x)g(x) - f(x)g'(x)) / (g(x))²` |
| **Kettenregel**     | `(f(g(x)))' = f'(g(x)) · g'(x)`                      |
#### 3. Ableitungen elementarer Funktionen

| Funktion `f(x)` | Ableitung `f'(x)` |
| --------------- | ----------------- |
| `sin(x)`        | `cos(x)`          |
| `cos(x)`        | `-sin(x)`         |
| `e^x`           | `e^x`             |
| `ln(x)`         | `1/x`             |
#### 4. Tangentengleichung
Die Gleichung der Tangente an den Graphen von `f` an der Stelle `x₀` lautet: 
`y = f(x₀) + f'(x₀) · (x - x₀)`
### 2.2 Integralrechnung

#### 1. Das bestimmte Integral
Das bestimmte Integral `∫_a^b f(x)dx` ist formal als Grenzwert von Riemann-Summen definiert. Es summiert unendlich viele, unendlich schmale Rechtecke unter dem Funktionsgraphen auf.

- **Interpretation:** Es entspricht der **vorzeichenbehafteten Fläche** zwischen dem Graphen von `f` und der x-Achse im Intervall `[a, b]`. Flächenanteile unterhalb der x-Achse werden negativ gewertet.

#### 2. Stammfunktion und unbestimmtes Integral
- Eine Funktion `F(x)` heißt **Stammfunktion** von `f(x)`, wenn ihre Ableitung wieder `f(x)` ergibt: `F'(x) = f(x)`.
- Das **unbestimmte Integral** `∫f(x)dx` bezeichnet die Menge aller Stammfunktionen von `f(x)`, die sich nur durch eine additive Konstante `C` unterscheiden: `F(x) + C`.
#### 3. Hauptsatz der Differential- und Integralrechnung
Der Hauptsatz verbindet die Konzepte von Ableitung und Integral. Sein zweiter Teil bietet ein mächtiges Werkzeug zur Berechnung bestimmter Integrale: Ist `F` eine beliebige Stammfunktion von `f`, so gilt: `∫_a^b f(x)dx = [F(x)]_a^b = F(b) - F(a)`
#### 4. Grundintegrale
Die folgende Tabelle listet Stammfunktionen für wesentliche elementare Funktionen auf.

| Funktion `f(x)`      | Stammfunktion `∫f(x)dx`   |
| -------------------- | ------------------------- |
| `x^n` (für `n ≠ -1`) | `(1/(n+1)) · x^(n+1) + C` |
| `1/x`                | `ln                       |
| `e^x`                | `e^x + C`                 |
| `sin(x)`             | `-cos(x) + C`             |
| `cos(x)`             | `sin(x) + C`              |
#### 5. Rechenregeln für Integrale
- **Linearität:** `∫(c·f(x) ± g(x))dx = c·∫f(x)dx ± ∫g(x)dx`
- **Vertauschen der Grenzen:** `∫_a^b f(x)dx = -∫_b^a f(x)dx`
- **Aufspalten des Intervalls:** `∫_a^b f(x)dx = ∫_a^c f(x)dx + ∫_c^b f(x)dx`
<div class="page-break" style="page-break-before: always;"></div>

## 3.0 Vektorrechnung im ℝ³

### 3.1 Vektoroperationen

#### 1. Grundlagen
- **Vektor:** Eine Klasse äquivalenter Pfeile, die durch Parallelverschiebung ineinander überführt werden können. Sie haben dieselbe Länge und Richtung.
- **Betrag** `|a⃗|`**:** Die Länge des Vektors, eine nicht-negative skalare Größe.
- **Nullvektor** `0⃗`**:** Ein Vektor mit dem Betrag Null und unbestimmter Richtung.
- **Gegenvektor** `-a⃗`**:** Ein Vektor mit gleichem Betrag wie `a⃗`, aber entgegengesetzter Richtung.

#### 2. Addition und Subtraktion
- **Addition** `a⃗ + b⃗`**:** Grafisch durch Aneinandersetzen der Vektoren ("Pfeil-an-Spitze"-Methode) oder durch die Diagonale des von `a⃗` und `b⃗` aufgespannten Parallelogramms (Parallelogrammregel).
- **Subtraktion** `a⃗ - b⃗`**:** Definiert als Addition des Gegenvektors: `a⃗ + (-b⃗)`

#### 3. Skalare Multiplikation
Das Produkt `λ · a⃗` eines Skalars `λ ∈ ℝ` mit einem Vektor `a⃗` ist ein Vektor, dessen Betrag `|λ| · |a⃗|` ist.

- Für `λ > 0` ist die Richtung gleich der von `a⃗`.
- Für `λ < 0` ist die Richtung entgegengesetzt zu `a⃗`.
- Für `λ = 0` ergibt sich der Nullvektor `0⃗`.

#### 4. Koordinatendarstellung
Im `ℝⁿ` wird ein Vektor durch ein n-Tupel seiner Koordinaten dargestellt, meist als Spaltenvektor. Für `a⃗ = (a₁, ..., aₙ)ᵀ` und `b⃗ = (b₁, ..., bₙ)ᵀ` gilt:

- **Addition:** `a⃗ + b⃗ = (a₁ + b₁, ..., aₙ + bₙ)ᵀ`
- **Skalare Multiplikation:** `λ · a⃗ = (λa₁, ..., λaₙ)ᵀ`
- **Betrag:** `|a⃗| = √(a₁² + a₂² + ... + aₙ²)`
<div class="page-break" style="page-break-before: always;"></div>

### 3.2 Produkte von Vektoren

#### 1. Skalarprodukt
Das Skalarprodukt zweier Vektoren a⃗ und b⃗ ist eine skalare Größe.
- **Geometrische Definition:** a⃗ · b⃗ = |a⃗| · |b⃗| · cos(φ), wobei `φ` der von den Vektoren eingeschlossene Winkel ist.
- **Koordinatenform:** a⃗ · b⃗ = a₁b₁ + a₂b₂ + ... + aₙbₙ

**Anwendungen und Eigenschaften:**
- **Längenberechnung:** |a⃗| = √a⃗·a⃗
- **Winkelberechnung:** cos(φ) = (a⃗ · b⃗) / (|a⃗| · |b⃗|)
- **Orthogonalitätstest:** Zwei Vektoren sind genau dann orthogonal (senkrecht) zueinander, wenn ihr Skalarprodukt Null ist: a⃗ ⊥ b⃗ ⇔ a⃗ · b⃗ = 0 (für a⃗, b⃗ ≠ 0⃗ ).

#### 2. Vektorprodukt (Kreuzprodukt) im ℝ³
Das Vektorprodukt a⃗ × b⃗ ist nur im ℝ³ definiert und sein Ergebnis ist wieder ein Vektor.
- **Definition:** Der Ergebnisvektor a⃗ × b⃗ steht senkrecht auf der von a⃗ und b⃗ aufgespannten Ebene. Seine Orientierung wird durch die **Rechte-Hand-Regel** bestimmt.
- **Betrag und Anwendung:** Der Betrag |a⃗ × b⃗| = |a⃗| · |b⃗| · sin(φ) entspricht der **Fläche des Parallelogramms**, das von a⃗ und b⃗ aufgespannt wird.
- **Koordinatenform:** Für a⃗ = (a₁, a₂, a₃)ᵀ und b⃗ = (b₁, b₂, b₃)ᵀ werden die Komponenten des Ergebnisvektors c⃗ = a⃗ × b⃗ mithilfe von 2x2-Determinanten berechnet:
    - `c₁ = |a₂ b₂| / |a₃ b₃| = a₂b₃ - a₃b₂`
    - `c₂ = |a₃ b₃| / |a₁ b₁| = a₃b₁ - a₁b₃`
    - `c₃ = |a₁ b₁| / |a₂ b₂| = a₁b₂ - a₂b₁`
- **Eigenschaft:** Zwei Vektoren sind genau dann parallel, wenn ihr Vektorprodukt der Nullvektor ist: a⃗ || b⃗ ⇔ a⃗ × b⃗ = 0⃗.
#### 3. Spatprodukt im ℝ³
Das Spatprodukt kombiniert Vektor- und Skalarprodukt.
- **Definition:** [a⃗, b⃗, c⃗] := a⃗ · (b⃗ × c⃗)
- **Geometrische Bedeutung:** Der Betrag des Spatprodukts |[a⃗, b⃗, c⃗]| entspricht dem **Volumen des Spats** (Parallelepipeds), das von den drei Vektoren a⃗, b⃗ und c⃗ aufgespannt wird.
- **Eigenschaft:** Drei Vektoren sind genau dann komplanar (liegen in einer Ebene), wenn ihr Spatprodukt Null ist: [a⃗, b⃗, c⃗] = 0.
<div class="page-break" style="page-break-before: always;"></div>

## 4.0 Analytische Geometrie

### 4.1 Darstellung von Geraden und Ebenen

#### 1. Geraden im ℝ³
Eine Gerade im Raum ist durch einen Punkt und eine Richtung eindeutig bestimmt.

| Darstellungsform                   | Gleichung                                                                                              |
| ---------------------------------- | ------------------------------------------------------------------------------------------------------ |
| **Parameterform (Punkt-Richtung)** | `g: x⃗ = p⃗ + t · v⃗, t ∈ ℝ` <br> (`p⃗` ist der Stützvektor, `v⃗` der Richtungsvektor)                 |
| **Zwei-Punkte-Form**               | `g: x⃗ = p⃗₁ + t · (p⃗₂ - p⃗₁), t ∈ ℝ` <br> (Gerade durch die Punkte mit Ortsvektoren `p⃗₁` und `p⃗₂`) |
#### 2. Ebenen im ℝ³
Ebenen können auf verschiedene Weisen beschrieben werden, je nachdem, welche Informationen gegeben sind.

| Darstellungsform     | Gleichung und Bedingungen                                                                                                                |
| -------------------- | ---------------------------------------------------------------------------------------------------------------------------------------- |
| **Parameterform**    | `E: x⃗ = p⃗ + t · v⃗₁ + s · v⃗₂, t, s ∈ ℝ` <br> (`p⃗` ist der Stützvektor, `v⃗₁` und `v⃗₂` sind zwei nicht-kollineare Richtungsvektoren) |
| **Normalenform**     | `E: (x⃗ - p⃗) · n⃗ = 0` <br> (`p⃗` ist der Stützvektor, `n⃗` ist ein Normalenvektor, der senkrecht auf der Ebene steht)                  |
| **Koordinatenform**  | `E: n₁x + n₂y + n₃z = d` <br> (Die Koeffizienten `n₁, n₂, n₃` bilden den Normalenvektor `n⃗`)                                            |
| **Hesse-Normalform** | `E: n⃗₀ · x⃗ = d` <br> (Eine spezielle Normalenform, bei der `                                                                           |
<div class="page-break" style="page-break-before: always;"></div>

### 4.2 Lagebeziehungen, Abstände und Winkel

#### 1. Lagebeziehungen zweier Geraden
Zwei Geraden im Raum können vier verschiedene Lagen zueinander einnehmen:

| Lagebeziehung  | Beschreibung                                                                       |
| -------------- | ---------------------------------------------------------------------------------- |
| **Identisch**  | Die Geraden fallen zusammen.                                                       |
| **Parallel**   | Die Geraden haben keine gemeinsamen Punkte, ihre Richtungsvektoren sind kollinear. |
| **Schneidend** | Die Geraden haben genau einen gemeinsamen Schnittpunkt.                            |
| **Windschief** | Die Geraden sind nicht parallel und haben keine gemeinsamen Punkte.                |
#### 2. Abstandsberechnungen
Mit Vektorprodukten lassen sich Abstände elegant berechnen.
- **Abstand Punkt-Gerade:** Der Abstand des Punktes Q von der Geraden g (Stützvektor `p⃗`, Richtungsvektor `v⃗`): `d(Q, g) = |v⃗ × (q⃗ - p⃗)| / |v⃗|`
- **Abstand Punkt-Ebene:** Der Abstand des Punktes Q von der Ebene E (Hesse-Form `n⃗₀ · x⃗ = d`): `d(Q, E) = |n⃗₀ · q⃗ - d|`
- **Abstand windschiefer Geraden:** Der Abstand der Geraden g₁ (`p⃗₁`, `v⃗₁`) und g₂ (`p⃗₂`, `v⃗₂`): `d(g₁, g₂) = |(p⃗₂ - p⃗₁) · (v⃗₁ × v⃗₂)| / |v⃗₁ × v⃗₂|`

#### 3. Winkelberechnungen
Winkel werden über das Skalarprodukt der relevanten Vektoren (Richtungs- oder Normalenvektoren) bestimmt.

| Winkel zwischen      | Formel    |
| -------------------- | --------- |
| **Zwei Geraden**     | `cos(φ) = |
| **Gerade und Ebene** | `sin(φ) = |
| **Zwei Ebenen**      | `cos(φ) = |
<div class="page-break" style="page-break-before: always;"></div>

## 5.0 Elementare Funktionen und ihre Eigenschaften

### 5.1 Polynome und Gebrochen Rationale Funktionen

#### 1. Polynome
- **Definition:** Ein Polynom n-ten Grades hat die allgemeine Form: `P(x) = a_n x^n + a_{n-1} x^{n-1} + ... + a₁x + a₀`
- **Nullstellen:** Eine Stelle `x₀`, an der `P(x₀) = 0` ist, wird Nullstelle genannt. Jeder Nullstelle `x₀` entspricht ein Linearfaktor `(x - x₀)`.
    - **Vielfachheit:** Die Vielfachheit einer Nullstelle gibt an, wie oft der entsprechende Linearfaktor vorkommt. Bei ungerader Vielfachheit schneidet der Graph die x-Achse (mit Vorzeichenwechsel). Bei gerader Vielfachheit berührt der Graph die x-Achse (ohne Vorzeichenwechsel).
- **Verhalten für** `|x| → ∞`**:** Das Verhalten für betragsmäßig große `x` wird ausschließlich durch den Leitterm `a_n x^n` bestimmt.
#### 2. Gebrochen Rationale Funktionen
- **Definition:** Eine Funktion der Form `f(x) = P(x) / Q(x)`, wobei `P(x)` und `Q(x)` Polynome sind.
- **Definitionslücken:** Die Nullstellen des Nenners `Q(x)` sind Definitionslücken.
    - **Hebbare Lücken:** Eine Nullstelle des Nenners, die auch eine Nullstelle des Zählers ist, führt zu einer hebbaren Lücke, wenn der entsprechende Linearfaktor gekürzt werden kann.
    - **Pole:** Eine Nullstelle des Nenners, die nach dem Kürzen verbleibt, ist ein Pol. An dieser Stelle hat der Graph eine vertikale Asymptote.
- **Asymptotisches Verhalten (**`|x| → ∞`**):**
    - **Zählergrad < Nennergrad:** Die x-Achse (`y = 0`) ist eine horizontale Asymptote.
    - **Zählergrad = Nennergrad:** Die horizontale Gerade `y = a_m / b_n` (Verhältnis der Leitkoeffizienten) ist eine Asymptote.
    - **Zählergrad > Nennergrad:** Das asymptotische Verhalten entspricht dem Polynom, das sich aus der Polynomdivision `P(x) : Q(x)` ergibt (schräge oder polynomielle Asymptote).
<div class="page-break" style="page-break-before: always;"></div>

### 5.2 Exponential- und Logarithmusfunktionen

#### 1. Exponentialfunktion
- **Definition:** `f(x) = a^x` mit Basis `a > 0, a ≠ 1`.
- **Eigenschaften:**
    - Definitionsbereich: `ℝ`, Wertebereich: `ℝ⁺` (nur positive Werte).
    - Keine Nullstellen, gemeinsamer Punkt aller Graphen bei `(0, 1)`.
    - Monotonie: streng monoton steigend für `a > 1`, streng monoton fallend für `0 < a < 1`.
    - Die **natürliche Exponentialfunktion** `f(x) = e^x` mit der Euler'schen Zahl `e ≈ 2.718` ist von zentraler Bedeutung.
#### 2. Logarithmusfunktion
- **Definition:** `f(x) = log_a(x)` ist die Umkehrfunktion der Exponentialfunktion `a^x`.
- **Eigenschaften:**
    - Definitionsbereich: `ℝ⁺`, Wertebereich: `ℝ`.
    - Gemeinsame Nullstelle aller Graphen bei `x = 1`.
    - Die y-Achse (`x = 0`) ist eine vertikale Asymptote.
    - Der **natürliche Logarithmus** `f(x) = ln(x)` ist die Umkehrfunktion von `e^x`.
<div class="page-break" style="page-break-before: always;"></div>

### 5.3 Trigonometrische und Hyperbelfunktionen

#### 1. Trigonometrische Funktionen
Die Funktionen Sinus, Cosinus und Tangens beschreiben periodische Vorgänge.

| Eigenschaft            | `sin(x)`                    | `cos(x)`                   | `tan(x) = sin(x)/cos(x)`    |
| ---------------------- | --------------------------- | -------------------------- | --------------------------- |
| **Definitionsbereich** | `ℝ`                         | `ℝ`                        | `ℝ \ {π/2 + kπ, k ∈ ℤ}`     |
| **Wertebereich**       | `[-1, 1]`                   | `[-1, 1]`                  | `ℝ`                         |
| **Periode**            | `2π`                        | `2π`                       | `π`                         |
| **Symmetrie**          | Punktsymmetrisch (ungerade) | Achsensymmetrisch (gerade) | Punktsymmetrisch (ungerade) |
| **Nullstellen**        | `kπ, k ∈ ℤ`                 | `π/2 + kπ, k ∈ ℤ`          | `kπ, k ∈ ℤ`                 |

- **Allgemeine Cosinus-Funktion:** `f(t) = A cos(ωt + φ)`
    - `A`: Amplitude (maximale Auslenkung)
    - `ω`: Kreisfrequenz
    - `φ`: Phasenwinkel
    - Periode `T = 2π / ω`

#### 2. Umkehrfunktionen (Arcusfunktionen)
`arcsin(x)`, `arccos(x)` und `arctan(x)` sind die Umkehrfunktionen der trigonometrischen Funktionen, deren Definitionsbereiche eingeschränkt wurden, um Eindeutigkeit zu gewährleisten.

- `arcsin`: D = `[-1, 1]`, W = `[-π/2, π/2]`
- `arccos`: D = `[-1, 1]`, W = `[0, π]`
- `arctan`: D = `ℝ`, W = `(-π/2, π/2)`

#### 3. Hyperbelfunktionen
Diese Funktionen sind Kombinationen der e-Funktion und weisen Analogien zu den trigonometrischen Funktionen auf.

- **Definitionen:**
    - `sinh(x) = (e^x - e^-x) / 2` (Sinus Hyperbolicus)
    - `cosh(x) = (e^x + e^-x) / 2` (Cosinus Hyperbolicus)
    - `tanh(x) = sinh(x) / cosh(x)` (Tangens Hyperbolicus)
- **Fundamentale Identität:** `cosh²(x) - sinh²(x) = 1`
<div class="page-break" style="page-break-before: always;"></div>

## 6.0 Matrizen und Determinanten

### 6.1 Rechnen mit Matrizen

#### 1. Grundoperationen
Für Matrizen `A` und `B` vom gleichen Typ `m × n` sind Addition und skalare Multiplikation elementweise definiert:
- **Addition:** `A + B` entsteht durch Addition der korrespondierenden Elemente.
- **Skalare Multiplikation:** `c · A` entsteht durch Multiplikation jedes Elements von `A` mit dem Skalar `c`.

#### 2. Matrixmultiplikation
Das Produkt `C = A · B` ist nur definiert, wenn die Spaltenanzahl von `A` (Typ `m × r`) der Zeilenanzahl von `B` (Typ `r × n`) entspricht. Das Ergebnis `C` hat den Typ `m × n`.
- Das Element `c_ik` in der i-ten Zeile und k-ten Spalte von `C` berechnet sich als Skalarprodukt der i-ten Zeile von `A` und der k-ten Spalte von `B`: `c_ik = Σ_{j=1}^r a_{ij} · b_{jk}`
- **Wichtig:** Die Matrixmultiplikation ist im Allgemeinen **nicht kommutativ** (`A · B ≠ B · A`). Die Reihenfolge der Faktoren ist entscheidend und darf nicht vertauscht werden – ein fundamentaler Unterschied zur Multiplikation reeller Zahlen.

#### 3. Spezielle Matrizen
- **Nullmatrix:** Eine Matrix, deren Elemente alle Null sind.
- **Einheitsmatrix** `E`**:** Eine quadratische Matrix mit Einsen auf der Hauptdiagonale und Nullen ansonsten. Sie ist das neutrale Element der Matrixmultiplikation (`A · E = A`).
- **Transponierte Matrix** `**Aᵀ**`**:** Entsteht durch Vertauschen von Zeilen und Spalten von `A`.
- **Symmetrische Matrix:** Eine quadratische Matrix, für die `A = Aᵀ` gilt.

#### 4. Inverse Matrix
Die inverse Matrix `A⁻¹` zu einer quadratischen Matrix `A` ist diejenige Matrix, für die gilt: 
`A · A⁻¹ = A⁻¹ · A = E`
- Eine Inverse existiert nur, wenn `A` **regulär** (oder invertierbar) ist.
- **Formel für 2x2-Matrizen:** Für `A = [[a, b], [c, d]]` ist `A⁻¹ = (1/(ad-bc)) · [[d, -b], [-c, a]]`, vorausgesetzt `det(A) = ad-bc ≠ 0`.
<div class="page-break" style="page-break-before: always;"></div>

#### 5. Gauß-Jordan-Algorithmus
Dieses Verfahren dient zur Berechnung der Inversen einer Matrix `A`. Man bildet die erweiterte Matrix `[A | E]` und überführt diese durch elementare Zeilenumformungen in die Form `[E | A⁻¹]`
### 6.2 Determinanten
#### 1. Definitionen
- **2x2-Fall:** `det([[a, b], [c, d]]) = ad - bc`
- **3x3-Fall (Regel von Sarrus):** Eine schematische Methode zur Berechnung der Determinante, die nur für 3x3-Matrizen gilt.
#### 2. Geometrische Interpretation
Der Betrag der Determinante `|det(A)|` einer Matrix `A` entspricht:
- im `ℝ²`: der **Fläche** des Parallelogramms, das von den Spaltenvektoren aufgespannt wird.
- im `ℝ³`: dem **Volumen** des Spats, das von den Spaltenvektoren aufgespannt wird.
#### 3. Laplace'scher Entwicklungssatz
Eine rekursive Methode zur Berechnung der Determinante einer n×n-Matrix. Die Determinante wird durch "Entwicklung" nach einer beliebigen Zeile oder Spalte berechnet, was die Berechnung auf Determinanten von (n-1)×(n-1)-Untermatrizen zurückführt.
#### 4. Eigenschaften und Invertierbarkeit
- Eine quadratische Matrix `A` ist genau dann **invertierbar**, wenn `det(A) ≠ 0`.
- `det(A·B) = det(A) · det(B)` (Produktsatz)
- `det(Aᵀ) = det(A)`
- `det(A) = 0` genau dann, wenn die Spalten- (oder Zeilen-)vektoren **linear abhängig** sind.
#### 5. Cramersche Regel
Eine explizite Lösungsformel für quadratische lineare Gleichungssysteme `A·x = b` mit `det(A) ≠ 0`. Die i-te Komponente der Lösung `x` ist gegeben durch: `x_i = det(A_i) / det(A)` wobei `A_i` die Matrix ist, die entsteht, wenn die i-te Spalte von `A` durch den Vektor `b` ersetzt wird.