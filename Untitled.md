Formelsammlung: Mathematische Grundlagen für Studium und Praxis


--------------------------------------------------------------------------------


1.0 Mathematische Grundlagen

Das Verständnis mathematischer Grundlagen ist das Fundament für alle weiterführenden ingenieurwissenschaftlichen und technischen Disziplinen. Konzepte wie die Mengenlehre, das Rechnen mit verschiedenen Zahlenmengen und grundlegende algebraische Operationen bilden die Sprache, in der technische Probleme formuliert und gelöst werden. Eine solide Beherrschung dieser Werkzeuge ist daher von strategischer Bedeutung für den Erfolg in Studium und Praxis.

1.1 Mengenlehre

1. Definition und Darstellung

Eine Menge ist nach Cantor eine Zusammenfassung von bestimmten, wohlunterschiedenen Objekten unserer Anschauung oder unseres Denkens zu einem Ganzen. Die Objekte, aus denen eine Menge besteht, werden als ihre Elemente bezeichnet.

Darstellungsform	Beispiel
Aufzählung	M = {a, b, c} <br> N = {1, 2, 3, ..., 100} <br> X = {1, 2, 3, ...}
Definierende Eigenschaft	`A = {x

2. Grundlegende Schreibweisen

* x ∈ M: "x ist ein Element der Menge M" oder "x ist in M".
* x ∉ M: "x ist kein Element der Menge M" oder "x ist nicht in M".
* ∅ oder {}: Die leere Menge, welche kein einziges Element enthält.

3. Vergleichsoperatoren

Operator	Verbale Beschreibung	Formale Definition
A ⊆ B	A ist eine Teilmenge von B	x ∈ A ⇒ x ∈ B
A ⊇ B	A ist eine Obermenge von B	B ⊆ A
A = B	A ist gleich B	x ∈ A ⇔ x ∈ B

4. Mengenoperationen

Operation	Schreibweise	Definition	Beschreibung
Durchschnitt	A ∩ B	`{x	x ∈ A und x ∈ B}`
Vereinigung	A ∪ B	`{x	x ∈ A oder x ∈ B}`
Differenz	A \ B	`{x	x ∈ A und x ∉ B}`

5. Produktmenge

Die Produktmenge (auch Kreuzprodukt) zweier Mengen A und B ist die Menge aller geordneten Paare (x, y), bei denen das erste Element aus A und das zweite aus B stammt. A × B := {(x, y) | x ∈ A, y ∈ B}

6. Rechenregeln

Für die Mengenoperationen gelten folgende fundamentale Rechenregeln:

1. Kommutativität: A ∪ B = B ∪ A und A ∩ B = B ∩ A
2. Assoziativität: A ∪ (B ∪ C) = (A ∪ B) ∪ C und A ∩ (B ∩ C) = (A ∩ B) ∩ C
3. Distributivität: A ∪ (B ∩ C) = (A ∪ B) ∩ (A ∪ C) und A ∩ (B ∪ C) = (A ∩ B) ∪ (A ∩ C)

Von diesen abstrakten Mengenkonzepten leiten wir nun die konkreten Zahlenmengen ab, die das Fundament aller Berechnungen bilden.

1.2 Zahlenmengen und Intervalle

1. Zahlenmengen

Die fundamentalen Zahlenmengen werden sukzessive erweitert, um immer komplexere Operationen zu ermöglichen.

Menge	Symbol	Definition	Charakterisierung
Natürliche Zahlen	ℕ	{1, 2, 3, ...}	Die grundlegenden Zählzahlen.
Nat. Zahlen inkl. 0	ℕ₀	{0, 1, 2, 3, ...}	
Ganze Zahlen	ℤ	{..., -2, -1, 0, 1, 2, ...}	Erweitert ℕ₀ um die negativen Zahlen. Uneingeschränkte Subtraktion wird möglich.
Rationale Zahlen	ℚ	`{m/n	m, n ∈ ℤ, n ≠ 0}`
Reelle Zahlen	ℝ	Menge aller Dezimalzahlen	Umfasst rationale und irrationale Zahlen (z.B. √2, π) und füllt den Zahlenstrahl lückenlos aus.

Die Teilmengenbeziehung lässt sich wie folgt visualisieren: ℕ ⊂ ℕ₀ ⊂ ℤ ⊂ ℚ ⊂ ℝ.

2. Intervalle

Intervalle sind Teilmengen der reellen Zahlen. Für a, b ∈ ℝ mit a < b gilt:

Typ	Schreibweise	Mengendefinition	Beschreibung
Abgeschlossen	[a, b]	`{x ∈ ℝ	a ≤ x ≤ b}`
Offen	(a, b)	`{x ∈ ℝ	a < x < b}`
Halboffen	(a, b] oder [a, b)	`{x ∈ ℝ	a < x ≤ b}oder{x ∈ ℝ

Anmerkung: Für offene Intervalle (a, b) ist in manchen Lehrbüchern auch die Schreibweise ]a, b[ gebräuchlich.

Unendliche Intervalle: Schreibweisen wie [a, ∞) ({x ∈ ℝ | x ≥ a}) oder (-∞, a) ({x ∈ ℝ | x < a}) beschreiben Intervalle, die sich unendlich in eine Richtung erstrecken. ℝ selbst entspricht (-∞, ∞).

3. Betrag einer Zahl

Der Betrag |a| einer reellen Zahl a ist ihr Abstand zum Nullpunkt auf dem Zahlenstrahl. Formal ist er definiert als: |a| := a falls a ≥ 0, und |a| := -a falls a < 0.

Wesentliche Eigenschaften:

1. |x · y| = |x| · |y|
2. |x| = |-x|
3. |x - y| = |y - x|
4. |x| ≥ x und |x| ≥ -x

5. Dreiecksungleichung

Eine fundamentale Eigenschaft der reellen Zahlen ist die Dreiecksungleichung, die besagt, dass der Betrag einer Summe nie größer ist als die Summe der Beträge: |x + y| ≤ |x| + |y|

Um lange Summen und Produkte effizient handhaben zu können, wurden spezielle Notationen entwickelt.

1.3 Summen- und Produktzeichen

1. Definitionen

* Summenzeichen (Σ): Dient zur kompakten Darstellung von Summen. Σ_{k=m}^n a_k := a_m + a_{m+1} + ... + a_n Hierbei ist k der Laufindex, m der Startindex und n der Endindex.
* Produktzeichen (Π): Dient zur kompakten Darstellung von Produkten. Π_{k=m}^n a_k := a_m · a_{m+1} · ... · a_n

2. Rechenregeln für das Summenzeichen

3. Linearität:
  * Σ_{k=1}^n (a_k + b_k) = Σ_{k=1}^n a_k + Σ_{k=1}^n b_k
  * Σ_{k=1}^n (c · a_k) = c · Σ_{k=1}^n a_k
2. Indexverschiebung:
  * Σ_{k=1}^n a_k = Σ_{k=2}^{n+1} a_{k-1} = Σ_{k=3}^{n+2} a_{k-2}

3. Fakultät

Die Fakultät n! ist das Produkt der ersten n natürlichen Zahlen. n! := Π_{k=1}^n k = 1 · 2 · 3 · ... · n Für n=0 ist 0! := 1 definiert. Es gilt die rekursive Rechenregel: (n+1)! = n! · (n+1).

Von diesen allgemeinen Notationen wenden wir uns nun den spezifischen Regeln für Potenzen, Wurzeln und Logarithmen zu, die auf wiederholten Multiplikationen und deren Umkehrungen basieren.

1.4 Potenzen, Wurzeln und Logarithmen

1. Potenzen

Potenzen sind eine Kurzschreibweise für wiederholte Multiplikation.

Exponent	Definition	Anmerkung
Positiv ganzzahlig (n ∈ ℕ)	a^n := a · a · ... · a (n Faktoren)	
Null	a^0 := 1	für a ≠ 0
Negativ ganzzahlig (n ∈ ℕ)	a^-n := 1 / a^n	für a ≠ 0
Rational (m/n)	a^(m/n) := ⁿ√(a^m)	für a > 0

2. Potenzgesetze

3. a^n · a^m = a^(n+m)
4. a^m / a^n = a^(m-n)
5. (a^m)^n = a^(m·n)
6. a^0 = 1
7. a^n · b^n = (a·b)^n
8. a^n / b^n = (a/b)^n
9. 1^n = 1

10. Wurzeln

Die n-te Wurzel ⁿ√a ist die nicht-negative Lösung der Gleichung xⁿ = a (für a ≥ 0).

* Ausnahme: Für ungerade n ist ⁿ√a auch für a < 0 als die eindeutige reelle Lösung definiert.

Regel	Formel
Produkt	ⁿ√(a·b) = ⁿ√a · ⁿ√b
Potenz	ⁿ√(a^m) = (ⁿ√a)^m
Quotient	ⁿ√(a/b) = ⁿ√a / ⁿ√b
Verschachtelung	ᵐ√(ⁿ√a) = ᵐⁿ√a

4. Logarithmen

Der Logarithmus von b zur Basis a, geschrieben log_a(b), ist die Lösung x der Gleichung a^x = b.

* Bedingungen: a > 0, a ≠ 1 und b > 0.

Rechenregeln:

1. log_a(a) = 1
2. log_a(1) = 0
3. log_a(u · v) = log_a(u) + log_a(v)
4. log_a(u / v) = log_a(u) - log_a(v)
5. log_a(u^r) = r · log_a(u)

Umkehrformeln: log_a(a^x) = x und a^(log_a(x)) = x.

5. Spezielle Logarithmen

* Natürlicher Logarithmus: ln(x) := log_e(x) mit Basis e ≈ 2.718
* Dekadischer Logarithmus: lg(x) := log₁₀(x)
* Dualer Logarithmus: log₂(x), fundamental in der Informatik zur Beschreibung von binären Prozessen, z.B. bei der Analyse von Datenmengen (Bits) oder Algorithmenkomplexität.

6. Binomische Formeln

Diese Formeln sind essenzielle Werkzeuge zur Termumformung:

1. (a + b)² = a² + 2ab + b²
2. (a - b)² = a² - 2ab + b²
3. (a + b)(a - b) = a² - b²

Diese grundlegenden algebraischen Werkzeuge werden nun zur systematischen Lösung von Gleichungen und insbesondere von linearen Gleichungssystemen angewendet, die in unzähligen technischen Modellen auftreten.

1.5 Lineare Gleichungssysteme (LGS)

1. Definition

Ein lineares Gleichungssystem besteht aus m linearen Gleichungen mit n Unbekannten. Es kann in Matrixform als A·x = b geschrieben werden.

* Koeffizientenmatrix A: Enthält die Koeffizienten a_ij der Unbekannten.
* Erweiterte Koeffizientenmatrix [A|b]: Enthält zusätzlich die rechte Seite b des Systems.

2. Gauß-Algorithmus

Das Gauß'sche Eliminationsverfahren ist ein systematischer Algorithmus zur Lösung von LGS in zwei Schritten:

1. Vorwärtselimination: Das System wird durch elementare Zeilenumformungen (Zeilen vertauschen, Zeile mit Faktor ≠ 0 multiplizieren, Vielfaches einer Zeile zu einer anderen addieren) in die Zeilen-Stufen-Form gebracht.
2. Rückwärtseinsetzen: Ausgehend von der letzten Zeile werden die Unbekannten schrittweise durch Einsetzen bestimmt.

3. Lösungsverhalten

Ein LGS kann genau eine der drei folgenden Lösungsmengen haben:

1. Eindeutige Lösung: Das System hat exakt eine Lösung. In der Zeilen-Stufen-Form gibt es keine Widersprüche und keine freien Variablen.
2. Keine Lösung: Das System ist unlösbar. In der Zeilen-Stufen-Form tritt ein Widerspruch auf, typischerweise eine Zeile der Form 0 0 ... 0 | c mit c ≠ 0.
3. Unendlich viele Lösungen: Das System hat eine unendliche Lösungsmenge. In der Zeilen-Stufen-Form gibt es mindestens eine Variable, die nicht als führendes Element (Pivot) einer Zeile auftritt und somit frei wählbar ist.

Die Beherrschung dieser fundamentalen algebraischen Konzepte ist eine wesentliche Voraussetzung für die Analyse von Funktionen und deren Änderungsraten, welche das Kernstück des nächsten Kapitels bildet.


--------------------------------------------------------------------------------


2.0 Differential- und Integralrechnung

Die Differential- und Integralrechnung sind die zwei zentralen Säulen der Analysis. Die Differentialrechnung beschäftigt sich mit der Beschreibung momentaner Änderungsraten und liefert Werkzeuge, um die Steigung oder das Verhalten von Funktionen an einem einzigen Punkt zu analysieren. Im Gegensatz dazu analysiert die Integralrechnung die Akkumulation von Größen über ein Intervall, was der Berechnung von Flächen oder Volumina entspricht. Der Hauptsatz der Analysis offenbart die fundamentale Verbindung zwischen diesen beiden scheinbar getrennten Konzepten: sie sind Umkehroperationen voneinander.

2.1 Differentialrechnung

1. Ableitung als Grenzwert

Die Ableitung f'(x₀) einer Funktion f an einer Stelle x₀ ist definiert als der Grenzwert des Differenzenquotienten. Sie gibt die exakte Steigung der Funktion an diesem Punkt an.

f'(x₀) = lim_{x→x₀} (f(x) - f(x₀)) / (x - x₀)

* Geometrische Interpretation: Steigung der Tangente an den Graphen von f im Punkt (x₀, f(x₀)).
* Physikalische Interpretation: Momentangeschwindigkeit zum Zeitpunkt t₀, wenn f(t) die Weg-Zeit-Funktion ist.

2. Ableitungsregeln

Die folgenden Regeln ermöglichen die systematische Berechnung von Ableitungen, ohne auf die Grenzwertdefinition zurückgreifen zu müssen.

Regel	Formel
Potenzregel	(x^r)' = r · x^(r-1)
Faktorregel	(c · f(x))' = c · f'(x)
Summenregel	(f(x) ± g(x))' = f'(x) ± g'(x)
Produktregel	(f(x) · g(x))' = f'(x)g(x) + f(x)g'(x)
Quotientenregel	(f(x) / g(x))' = (f'(x)g(x) - f(x)g'(x)) / (g(x))²
Kettenregel	(f(g(x)))' = f'(g(x)) · g'(x)

3. Ableitungen elementarer Funktionen

Funktion f(x)	Ableitung f'(x)
sin(x)	cos(x)
cos(x)	-sin(x)
e^x	e^x
ln(x)	1/x

4. Tangentengleichung

Die Gleichung der Tangente an den Graphen von f an der Stelle x₀ lautet: y = f(x₀) + f'(x₀) · (x - x₀)

Während die Differentialrechnung Funktionen analysiert, indem sie sie in infinitesimale Teile zerlegt, löst die Integralrechnung das inverse Problem: die Rekonstruktion einer Funktion aus ihrer bekannten Änderungsrate.

2.2 Integralrechnung

1. Das bestimmte Integral

Das bestimmte Integral ∫_a^b f(x)dx ist formal als Grenzwert von Riemann-Summen definiert. Es summiert unendlich viele, unendlich schmale Rechtecke unter dem Funktionsgraphen auf.

* Interpretation: Es entspricht der vorzeichenbehafteten Fläche zwischen dem Graphen von f und der x-Achse im Intervall [a, b]. Flächenanteile unterhalb der x-Achse werden negativ gewertet.

2. Stammfunktion und unbestimmtes Integral

* Eine Funktion F(x) heißt Stammfunktion von f(x), wenn ihre Ableitung wieder f(x) ergibt: F'(x) = f(x).
* Das unbestimmte Integral ∫f(x)dx bezeichnet die Menge aller Stammfunktionen von f(x), die sich nur durch eine additive Konstante C unterscheiden: F(x) + C.

3. Hauptsatz der Differential- und Integralrechnung

Der Hauptsatz verbindet die Konzepte von Ableitung und Integral. Sein zweiter Teil bietet ein mächtiges Werkzeug zur Berechnung bestimmter Integrale: Ist F eine beliebige Stammfunktion von f, so gilt: ∫_a^b f(x)dx = [F(x)]_a^b = F(b) - F(a)

4. Grundintegrale

Die folgende Tabelle listet Stammfunktionen für wesentliche elementare Funktionen auf.

Funktion f(x)	Stammfunktion ∫f(x)dx
x^n (für n ≠ -1)	(1/(n+1)) · x^(n+1) + C
1/x	`ln
e^x	e^x + C
sin(x)	-cos(x) + C
cos(x)	sin(x) + C

5. Rechenregeln für Integrale

* Linearität: ∫(c·f(x) ± g(x))dx = c·∫f(x)dx ± ∫g(x)dx
* Vertauschen der Grenzen: ∫_a^b f(x)dx = -∫_b^a f(x)dx
* Aufspalten des Intervalls: ∫_a^b f(x)dx = ∫_a^c f(x)dx + ∫_c^b f(x)dx

Nachdem wir nun die zentralen Konzepte der Analysis für eindimensionale Funktionen betrachtet haben, wenden wir diese Denkweise auf mehrdimensionale Objekte wie Vektoren an, um komplexe geometrische und physikalische Probleme im Raum zu lösen.


--------------------------------------------------------------------------------


3.0 Vektorrechnung im ℝ³

In den Natur- und Ingenieurwissenschaften wird zwischen skalaren und vektoriellen Größen unterschieden. Skalare Größen wie Masse oder Temperatur sind vollständig durch eine einzige Maßzahl bestimmt. Vektorielle Größen hingegen, wie Kraft oder Geschwindigkeit, sind durch einen Betrag und eine Richtung definiert. Vektoren sind daher ein unverzichtbares Werkzeug, um physikalische Phänomene und räumliche Beziehungen mathematisch präzise zu beschreiben.

3.1 Vektoroperationen

1. Grundlagen

* Vektor: Eine Klasse äquivalenter Pfeile, die durch Parallelverschiebung ineinander überführt werden können. Sie haben dieselbe Länge und Richtung.
* Betrag |a⃗|: Die Länge des Vektors, eine nicht-negative skalare Größe.
* Nullvektor 0⃗: Ein Vektor mit dem Betrag Null und unbestimmter Richtung.
* Gegenvektor -a⃗: Ein Vektor mit gleichem Betrag wie a⃗, aber entgegengesetzter Richtung.

2. Addition und Subtraktion

* Addition a⃗ + b⃗: Grafisch durch Aneinandersetzen der Vektoren ("Pfeil-an-Spitze"-Methode) oder durch die Diagonale des von a⃗ und b⃗ aufgespannten Parallelogramms (Parallelogrammregel).
* Subtraktion a⃗ - b⃗: Definiert als Addition des Gegenvektors: a⃗ + (-b⃗).

3. Skalare Multiplikation

Das Produkt λ · a⃗ eines Skalars λ ∈ ℝ mit einem Vektor a⃗ ist ein Vektor, dessen Betrag |λ| · |a⃗| ist.

* Für λ > 0 ist die Richtung gleich der von a⃗.
* Für λ < 0 ist die Richtung entgegengesetzt zu a⃗.
* Für λ = 0 ergibt sich der Nullvektor 0⃗.

4. Koordinatendarstellung

Im ℝⁿ wird ein Vektor durch ein n-Tupel seiner Koordinaten dargestellt, meist als Spaltenvektor. Für a⃗ = (a₁, ..., aₙ)ᵀ und b⃗ = (b₁, ..., bₙ)ᵀ gilt:

* Addition: a⃗ + b⃗ = (a₁ + b₁, ..., aₙ + bₙ)ᵀ
* Skalare Multiplikation: λ · a⃗ = (λa₁, ..., λaₙ)ᵀ
* Betrag: |a⃗| = √(a₁² + a₂² + ... + aₙ²)

3.2 Produkte von Vektoren

1. Skalarprodukt

Das Skalarprodukt zweier Vektoren a⃗ und b⃗ ist eine skalare Größe.

* Geometrische Definition: a⃗ · b⃗ = |a⃗| · |b⃗| · cos(φ), wobei φ der von den Vektoren eingeschlossene Winkel ist.
* Koordinatenform: a⃗ · b⃗ = a₁b₁ + a₂b₂ + ... + aₙbₙ

Anwendungen und Eigenschaften:

* Längenberechnung: |a⃗| = √a⃗·a⃗
* Winkelberechnung: cos(φ) = (a⃗ · b⃗) / (|a⃗| · |b⃗|)
* Orthogonalitätstest: Zwei Vektoren sind genau dann orthogonal (senkrecht) zueinander, wenn ihr Skalarprodukt Null ist: a⃗ ⊥ b⃗ ⇔ a⃗ · b⃗ = 0 (für a⃗, b⃗ ≠ 0⃗).

2. Vektorprodukt (Kreuzprodukt) im ℝ³

Das Vektorprodukt a⃗ × b⃗ ist nur im ℝ³ definiert und sein Ergebnis ist wieder ein Vektor.

* Definition: Der Ergebnisvektor a⃗ × b⃗ steht senkrecht auf der von a⃗ und b⃗ aufgespannten Ebene. Seine Orientierung wird durch die Rechte-Hand-Regel bestimmt.
* Betrag und Anwendung: Der Betrag |a⃗ × b⃗| = |a⃗| · |b⃗| · sin(φ) entspricht der Fläche des Parallelogramms, das von a⃗ und b⃗ aufgespannt wird.
* Koordinatenform: Für a⃗ = (a₁, a₂, a₃)ᵀ und b⃗ = (b₁, b₂, b₃)ᵀ werden die Komponenten des Ergebnisvektors c⃗ = a⃗ × b⃗ mithilfe von 2x2-Determinanten berechnet:
  * c₁ = |a₂ b₂| / |a₃ b₃| = a₂b₃ - a₃b₂
  * c₂ = |a₃ b₃| / |a₁ b₁| = a₃b₁ - a₁b₃
  * c₃ = |a₁ b₁| / |a₂ b₂| = a₁b₂ - a₂b₁
* Eigenschaft: Zwei Vektoren sind genau dann parallel, wenn ihr Vektorprodukt der Nullvektor ist: a⃗ || b⃗ ⇔ a⃗ × b⃗ = 0⃗.

3. Spatprodukt im ℝ³

Das Spatprodukt kombiniert Vektor- und Skalarprodukt.

* Definition: [a⃗, b⃗, c⃗] := a⃗ · (b⃗ × c⃗)
* Geometrische Bedeutung: Der Betrag des Spatprodukts |[a⃗, b⃗, c⃗]| entspricht dem Volumen des Spats (Parallelepipeds), das von den drei Vektoren a⃗, b⃗ und c⃗ aufgespannt wird.
* Eigenschaft: Drei Vektoren sind genau dann komplanar (liegen in einer Ebene), wenn ihr Spatprodukt Null ist: [a⃗, b⃗, c⃗] = 0.

Vektoren und die Werkzeuge der Analysis ermöglichen es nun, geometrische Objekte wie Geraden und Ebenen im Raum präzise zu beschreiben und zu analysieren, was den Kern der analytischen Geometrie ausmacht.


--------------------------------------------------------------------------------


4.0 Analytische Geometrie

Die analytische Geometrie schlägt eine Brücke zwischen Algebra und Geometrie. Sie ermöglicht es, geometrische Objekte wie Geraden und Ebenen durch algebraische Gleichungen zu beschreiben. Dieser Ansatz erlaubt die präzise Berechnung von Schnittpunkten, Abständen und Winkeln, die in rein geometrischen Betrachtungen oft nur qualitativ erfasst werden können.

4.1 Darstellung von Geraden und Ebenen

1. Geraden im ℝ³

Eine Gerade im Raum ist durch einen Punkt und eine Richtung eindeutig bestimmt.

Darstellungsform	Gleichung
Parameterform (Punkt-Richtung)	g: x⃗ = p⃗ + t · v⃗, t ∈ ℝ <br> (p⃗ ist der Stützvektor, v⃗ der Richtungsvektor)
Zwei-Punkte-Form	g: x⃗ = p⃗₁ + t · (p⃗₂ - p⃗₁), t ∈ ℝ <br> (Gerade durch die Punkte mit Ortsvektoren p⃗₁ und p⃗₂)

2. Ebenen im ℝ³

Ebenen können auf verschiedene Weisen beschrieben werden, je nachdem, welche Informationen gegeben sind.

Darstellungsform	Gleichung und Bedingungen
Parameterform	E: x⃗ = p⃗ + t · v⃗₁ + s · v⃗₂, t, s ∈ ℝ <br> (p⃗ ist der Stützvektor, v⃗₁ und v⃗₂ sind zwei nicht-kollineare Richtungsvektoren)
Normalenform	E: (x⃗ - p⃗) · n⃗ = 0 <br> (p⃗ ist der Stützvektor, n⃗ ist ein Normalenvektor, der senkrecht auf der Ebene steht)
Koordinatenform	E: n₁x + n₂y + n₃z = d <br> (Die Koeffizienten n₁, n₂, n₃ bilden den Normalenvektor n⃗)
Hesse-Normalform	E: n⃗₀ · x⃗ = d <br> (Eine spezielle Normalenform, bei der `

4.2 Lagebeziehungen, Abstände und Winkel

1. Lagebeziehungen zweier Geraden

Zwei Geraden im Raum können vier verschiedene Lagen zueinander einnehmen:

Lagebeziehung	Beschreibung
Identisch	Die Geraden fallen zusammen.
Parallel	Die Geraden haben keine gemeinsamen Punkte, ihre Richtungsvektoren sind kollinear.
Schneidend	Die Geraden haben genau einen gemeinsamen Schnittpunkt.
Windschief	Die Geraden sind nicht parallel und haben keine gemeinsamen Punkte.

2. Abstandsberechnungen

Mit Vektorprodukten lassen sich Abstände elegant berechnen.

* Abstand Punkt-Gerade: Der Abstand des Punktes Q von der Geraden g (Stützvektor p⃗, Richtungsvektor v⃗): d(Q, g) = |v⃗ × (q⃗ - p⃗)| / |v⃗|
* Abstand Punkt-Ebene: Der Abstand des Punktes Q von der Ebene E (Hesse-Form n⃗₀ · x⃗ = d): d(Q, E) = |n⃗₀ · q⃗ - d|
* Abstand windschiefer Geraden: Der Abstand der Geraden g₁ (p⃗₁, v⃗₁) und g₂ (p⃗₂, v⃗₂): d(g₁, g₂) = |(p⃗₂ - p⃗₁) · (v⃗₁ × v⃗₂)| / |v⃗₁ × v⃗₂|

3. Winkelberechnungen

Winkel werden über das Skalarprodukt der relevanten Vektoren (Richtungs- oder Normalenvektoren) bestimmt.

Winkel zwischen	Formel
Zwei Geraden	`cos(φ) =
Gerade und Ebene	`sin(φ) =
Zwei Ebenen	`cos(φ) =

Diese geometrischen und algebraischen Werkzeuge werden nun auf die Untersuchung der fundamentalen Bausteine der mathematischen Modellierung angewendet: den elementaren Funktionen und ihren charakteristischen Eigenschaften.


--------------------------------------------------------------------------------


5.0 Elementare Funktionen und ihre Eigenschaften

Elementare Funktionen – wie Polynome, Exponential-, Logarithmus- und trigonometrische Funktionen – sind die fundamentalen Bausteine, mit denen reale Phänomene in Wissenschaft und Technik modelliert werden. Das Verständnis ihrer charakteristischen Eigenschaften, wie Nullstellen, Symmetrien und asymptotisches Verhalten, ist entscheidend für die Analyse und Anwendung dieser Modelle.

5.1 Polynome und Gebrochen Rationale Funktionen

1. Polynome

* Definition: Ein Polynom n-ten Grades hat die allgemeine Form: P(x) = a_n x^n + a_{n-1} x^{