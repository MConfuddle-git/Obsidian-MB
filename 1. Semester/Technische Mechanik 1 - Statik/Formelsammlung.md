## 1.0 Grundlagen: Axiome und Grundbegriffe

### 1.1 Definitionen der Grundbegriffe

- **Die Kraft (**`F`**):** Die Kraft ist eine Vektorgröße, die als **gebundener Vektor** durch drei Eigenschaften vollständig definiert ist:
    1. **Betrag:** Die Größe bzw. Intensität der Kraft.
    2. **Richtung:** Die Orientierung der Kraft im Raum, festgelegt durch ihre Wirkungslinie.
    3. **Angriffspunkt:** Der Punkt, an dem die Kraft auf den Körper wirkt.
- Die Formelzeichen sind 𝐹⃑𝐼𝑛𝑑𝑒𝑥 für den Kraftvektor und 𝐹𝐼𝑛𝑑𝑒𝑥 für den Betrag der Kraft.
- **Der starre Körper:** Der starre Körper ist eine grundlegende Idealisierung in der Statik (Stereostatik). Er beschreibt einen Körper, der unter der Einwirkung von Kräften keine Deformationen (Formänderungen) erfährt. Der Abstand zwischen zwei beliebigen Punkten des Körpers bleibt also stets konstant. Diese Vereinfachung ist für viele ingenieurtechnische Anwendungen hinreichend genau.
### 1.2 Die Axiome der Mechanik

Die gesamte klassische Mechanik basiert auf vier fundamentalen, durch Beobachtung gewonnenen Grundaussagen, den sogenannten Axiomen nach Newton.

1. **Trägheitsaxiom (1. Newtonsches Gesetz):** Ein Körper verharrt im Zustand der Ruhe oder der gleichförmig-geradlinigen Bewegung, solange die Summe aller auf ihn wirkenden Kräfte null ist. Für die Statik bedeutet dies, dass sich ein Körper im Gleichgewicht befindet, wenn die resultierende Kraft 𝐹⃑𝑅 = 0 ist.
2. **Verschiebungsaxiom:** Die Wirkung einer Kraft auf einen **starren Körper** ändert sich nicht, wenn ihr Angriffspunkt entlang ihrer Wirkungslinie verschoben wird. Eine Kraft ist somit ein "linienflüchtiger" Vektor.
3. **Reaktionsaxiom (3. Newtonsches Gesetz / Wechselwirkungsgesetz):** Übt ein Körper 1 auf einen Körper 2 eine Kraft aus (actio), so übt der Körper 2 auf den Körper 1 eine gleich große, aber entgegengesetzt gerichtete Kraft aus (reactio). Kurz: _actio gleich reactio_. Als Vektorgleichung formuliert: 𝐹⃗1 = − 𝐹⃗2.
4. **Parallelogrammaxiom (4. Newtonsches Gesetz):** Die Wirkung zweier Kräfte, die an einem gemeinsamen Punkt angreifen, ist äquivalent zur Wirkung einer einzelnen Kraft, der Resultierenden 𝐹⃑𝑅. Diese Resultierende entspricht der Diagonalen des Parallelogramms, das aus den beiden Einzelkräften gebildet wird.
### 1.3 Kraftübertragungselemente in der Ebene

![[Pasted image 20251222174307.png]]
## 2.0 Kräftesysteme und Gleichgewicht in der Ebene

### 2.1 Zentrales ebenes Kräftesystem (gemeinsamer Angriffspunkt)

Bei einem zentralen Kräftesystem ist für das Gleichgewicht nur das Kräftegleichgewicht relevant, da keine Momente entstehen.

- **Komponentendarstellung:** Zerlegung einer Kraft `F` in ihre kartesischen Komponenten bezüglich des Winkels α zur x-Achse:
    - **Fx = F · cos(α)**
    - **Fy = F · sin(α)**
- **Betrag und Richtung:** Berechnung von Betrag und Richtung aus den gegebenen Komponenten:
    - **F = √𝐹𝑥 2 + 𝐹𝑦 2**
    - **α = arctan (Fy / Fx)  (Achtung: Vorzeichen beachten!)
- **Addition von Kräften (Resultierende):** Die resultierende Kraft **𝐹⃗𝑅 = ∑ 𝐹⃗i** wird durch die komponentenweise Addition der Einzelkräfte ermittelt:
    - **F{Rx} = ∑ F{ix}**
    - **F{Ry} = ∑ F{iy}**
- **Gleichgewichtsbedingungen:** Ein zentrales ebenes Kräftesystem ist im Gleichgewicht, wenn die Resultierende eine Nullkraft ist. Daraus folgen zwei skalare Gleichungen:
    - **∑ F{ix} = 0**
    - **∑ F{iy} = 0**

### 2.2 Allgemeines ebenes Kräftesystem

Bei einem allgemeinen Kräftesystem muss zusätzlich zum Kräftegleichgewicht auch das Momentengleichgewicht erfüllt sein.

- **Kräftepaar und Moment:**
    - Ein **Kräftepaar** besteht aus zwei gleich großen, parallelen, aber entgegengesetzt gerichteten Kräften. Seine Wirkung ist eine reine Drehung.
    - Das Moment eines Kräftepaares ist das Produkt aus dem Kraftbetrag `F` und dem senkrechten Abstand `h` der Wirkungslinien: **M = F · h**.
- **Moment einer Kraft:**
    - Das Moment einer Kraft 𝐹⃗ mit den Komponenten (Fx, Fy) und dem Angriffspunkt (x, y) bezüglich eines Punktes A (xA, yA) berechnet sich zu: **MA = (x - xA) · Fy - (y - yA) · Fx**
- **Resultierende:**
    - Ein allgemeines ebenes Kräftesystem kann auf eine **resultierende Kraft** **𝐹⃗𝑅** und ein **resultierendes Moment** **M{RA}** bezüglich eines Punktes A reduziert werden. Die Komponenten berechnen sich durch Summation:
        - **F{Rx} = ∑ F{ix}**
        - **F{Ry} = ∑ F{iy}**
        - **M{RA} = ∑ M{iA}**
- **Gleichgewichtsbedingungen:** 
	- Ein allgemeines ebenes Kräftesystem ist im Gleichgewicht, wenn sowohl die resultierende Kraft als auch das resultierende Moment (bezüglich eines beliebigen Punktes A) null sind. Dies führt zu drei unabhängigen skalaren Gleichungen:
	    - **∑ F{ix} = 0**
	    - **∑ F{iy} = 0**
	    - **∑ M{iA} = 0**
## 3.0 Ebene Tragwerke und statische Bestimmtheit

### 3.1 Statische Bestimmtheit

Die statische Bestimmtheit wird durch den Freiheitsgrad `f` des Systems beschrieben.

- **Einteilige Tragwerke:** Für ein einzelnes starres Bauteil in der Ebene gilt die Formel: **f = g - a**
    - `f`: Anzahl der verbleibenden Freiheitsgrade
    - `g`: Anzahl der Gleichgewichtsbedingungen in der Ebene (`g=3`)
    - `a`: Anzahl der Auflagerreaktionen (Wertigkeiten der Lager)
- **Bewertung:**
    - `f = 0`: **Statisch bestimmt** (stabil und berechenbar)
    - `f < 0`: **Statisch unbestimmt** (stabil, aber nicht allein mit Statik-Mitteln lösbar)
    - `f > 0`: **Kinematisch** (instabil/verschieblich)
- **Achtung:** `f=0` ist eine notwendige, aber keine hinreichende Bedingung. Das Tragwerk ist trotzdem kinematisch (instabil), wenn die Lagerung fehlerhaft ist, z. B. wenn:
    - die Lagerkräfte parallel zueinander sind.
    - die Wirkungslinien der Lagerkräfte sich in einem gemeinsamen Punkt schneiden.
- **Mehrteilige Tragwerke:** Für Tragwerke, die aus mehreren starren Körpern bestehen, wird die Formel erweitert: **f = g · n - a - z**
    - `n`: Anzahl der Starrkörper des Tragwerks
    - `z`: Anzahl der Zwischenreaktionen in den Gelenken/Verbindungen

### 3.2 Ebene Fachwerke (Knotenpunktverfahren)

Fachwerke sind Tragwerke, die idealisiert nur aus zug- oder druckbeanspruchten Stäben bestehen. Die Berechnung der Stabkräfte erfolgt unter folgenden Annahmen:

- Die Stäbe sind an den Knoten reibungsfrei und gelenkig verbunden.
- Äußere Kräfte und Lagerreaktionen greifen nur an den Knoten an. Kräfte, die auf einen Stab wirken, werden in äquivalente Kraftanteile zerlegt, die am Stabanfang und -ende im Knoten angreifen.
- Die Stabachsen sind gerade und schneiden sich in den Knotenpunkten.

Beim **Knotenpunktverfahren** wird jeder einzelne Knoten freigeschnitten und die Gleichgewichtsbedingungen (∑ Fx = 0, ∑ Fy = 0) angewendet, um die Stabkräfte zu ermitteln. Zur Vereinfachung können sogenannte **Nullstäbe** (unbelastete Stäbe) oft vorab identifiziert werden:

1. An einem **unbelasteten Knoten** mit **zwei Stäben** (nicht auf einer Linie) sind beide Stäbe Nullstäbe.
2. An einem Knoten mit **zwei Stäben**, bei dem eine **äußere Kraft** in Richtung des einen Stabes wirkt, ist der andere Stab ein Nullstab.
3. An einem **unbelasteten Knoten** mit **drei Stäben**, von denen zwei auf einer Linie liegen, ist der dritte Stab ein Nullstab.
## 4.0 Räumliche Statik

### 4.1 Einleitung und strategische Bedeutung

Der Übergang von der zweidimensionalen zur dreidimensionalen Statik erweitert den Anwendungsbereich auf räumliche Strukturen. Die grundlegenden Prinzipien wie die Axiome und Gleichgewichtsbedingungen bleiben dabei vollständig erhalten. Allerdings müssen die Vektordarstellungen für Kräfte und Momente um eine dritte Dimension ergänzt werden, und die Anzahl der Gleichgewichtsbedingungen erhöht sich, um die zusätzlichen Freiheitsgrade (drei Translationen, drei Rotationen) im Raum zu erfassen.

### 4.2 Kraft und Moment im Raum

Die Beschreibung von Kräften und Momenten erfolgt konsequent über Vektoren in einem 3D-Koordinatensystem.

- **Kraftvektor** `F`**:**
    - Koordinatenschreibweise mit Einheitsvektoren: **F⃗⃗  = Fx ·  𝑒𝑥⃗⃗⃗⃗  + Fy · 𝑒𝑦⃗⃗⃗⃗⃗  + Fz · 𝑒𝑧⃗⃗⃗⃗
    - Berechnung des Betrags aus den Komponenten: **F = √{Fx² + Fy² + Fz²}**
- **Moment einer Kraft im Raum:**
    - Das Moment einer Kraft F⃗⃗ , die am Punkt mit dem Ortsvektor r⃗ angreift, bezüglich des Koordinatenursprungs wird durch das Vektorprodukt (Kreuzprodukt) berechnet: **M⃗⃗⃗⃗ = r⃗ × F⃗⃗ 
    - In Komponentenschreibweise ergibt sich das Moment zu:
     ![[Pasted image 20251222175101.png]]

### 4.3 Gleichgewichtsbedingungen im Raum

Ein Körper im Raum ist im Gleichgewicht, wenn die Vektorsumme aller Kräfte und die Vektorsumme aller Momente (bezüglich eines beliebigen Punktes A) null sind.

- Vektorielle Gleichgewichtsbedingungen: **∑ F⃗⃗ i =  0⃗⃗  und ∑ F⃗ _{iA} =  0⃗⃗ 
- Daraus ergeben sich sechs unabhängige skalare Gleichgewichtsbedingungen:
    - **∑ F{ix} = 0**
    - **∑ F{iy} = 0**
    - **∑ F{iz} = 0**
    - **∑ M{ix} = 0**
    - **∑ M{iy} = 0**
    - **∑ M{iz} = 0**

Um die resultierende Kraft einer verteilten Last (wie der Gewichtskraft) korrekt ansetzen zu können, wird die Berechnung von Schwerpunkten benötigt.
### 4.4 Kraftübertragungselemente in der Ebene
![[Pasted image 20251222181422.png]]
## 5.0 Schwerpunkte
### 5.1 Schwerpunkte von Linien, Flächen und Volumen

Die Koordinaten des Schwerpunkts (xS, yS, zS) werden über integrale Beziehungen berechnet.

- **Streckenlast** `q(x)`**:**
    - Resultierende Kraft: **FR = ∫ q(x) \,dx**
    - Schwerpunktskoordinate: **xS = (∫x · q(x) \,dx) / (∫q(x) \,dx)**
- **Flächenschwerpunkt:**
    - **xS = (∫x \,dA) / (A)**
    - **yS = (∫y \,dA) / (A)**
- **Linienschwerpunkt:**
    - **xS = (∫x \,ds) / (s)**
    - **yS = (∫y \,ds) / (s)**
- **Volumenschwerpunkt (homogener Körper):**
    - **xS = (∫x \,dV) / (V)**, **yS = (∫y \,dV) / (V)**, **zS = (∫z \,dV) / (V)**

### 5.2 Schwerpunkte zusammengesetzter Gebilde

Der Schwerpunkt eines Körpers, der sich aus mehreren einfachen Teilgebilden zusammensetzen lässt, kann über Summenformeln berechnet werden. Die Formeln für einen Flächenschwerpunkt lauten exemplarisch:

- **xS = (∑ x{Si} · Ai) / (∑ Ai)**
- **yS = (∑ y{Si} · Ai) / (∑ Ai)**

Dabei sind x{Si} und y{Si} die bekannten Schwerpunktkoordinaten und Ai die Flächeninhalte der Teilgebilde. Ausschnitte oder Löcher werden in der Summe als negative Flächen behandelt.

Nachdem die äußeren Kräfte und deren Angriffspunkte bestimmt sind, folgt die Analyse der inneren Beanspruchungen eines Bauteils – der sogenannten Schnittgrößen.

## 6.0 Schnittgrößen
### 6.1 Schnittgrößen am geraden Balken (Ebene)

An einem gedachten Schnitt durch einen ebenen Balken treten drei Schnittgrößen auf:

- **Normalkraft (N):** Die Kraftkomponente in Längsrichtung der Balkenachse (x-Achse). 
  Sie verursacht eine Dehnung oder Stauchung.
- **Querkraft (Q):** Die Kraftkomponente senkrecht zur Balkenachse (in z-Richtung). 
  Sie verursacht eine Scherung.
- **Biegemoment (M):** Das Moment um die Achse, die senkrecht zur Ebene steht (y-Achse). 
  Es verursacht eine Biegung des Balkens.

**Vorzeichenkonvention:** Ein Schnittufer wird als _positiv_ bezeichnet, wenn sein nach außen weisender Normalenvektor in die positive Koordinatenrichtung (z.B. x-Richtung) zeigt. Positive Schnittgrößen zeigen an diesem positiven Schnittufer in die positiven Koordinatenrichtungen.
### 6.2 Zusammenhang zwischen Belastung und Schnittgrößen

Zwischen der äußeren Belastung (Streckenlast `q(x)`) und den inneren Schnittgrößen (Querkraft `Q(x)`, Biegemoment `M(x)`) bestehen fundamentale Differentialbeziehungen:

- **(dQ(x)) / (dx) = -q(x)** (Die Ableitung der Querkraft entspricht der negativen Streckenlast.)
- **(dM(x)) / (dx) = Q(x)** (Die Ableitung des Biegemoments entspricht der Querkraft.)

Diese Beziehungen bedeuten umgekehrt, dass der Querkraftverlauf durch Integration der negativen Streckenlast und der Momentenverlauf durch Integration des Querkraftverlaufs ermittelt werden kann.
### 6.3 Räumliche Schnittgrößen

An einem Schnitt durch ein räumlich belastetes Bauteil können insgesamt sechs Schnittgrößen auftreten, die den sechs Freiheitsgraden entsprechen:

- Normalkraft: **N = F{Sx}**
- Querkräfte: **Qy = F{Sy}**, **Qz = F{Sz}**
- Torsionsmoment (um die Längsachse): **MT = M{Sx}**
- Biegemomente (um die Querachsen): **My = M{Sy}**, **Mz = M{Sz}**

Das letzte Kapitel dieser Formelsammlung widmet sich der Reibung, einer wichtigen, nicht-idealen Kraft, die in realen Kontaktflächen auftritt.

## 7.0 Reibung

Die Reibung ist eine reale physikalische Kraft, die der relativen Bewegung zwischen zwei sich berührenden Körpern entgegenwirkt. Sie entsteht durch die Beschaffenheit der Kontaktoberflächen. In der Mechanik wird fundamental zwischen der **Haftung** (statischer Zustand ohne Bewegung) und der **Gleitreibung** (kinetischer Zustand bei Bewegung) unterschieden.
### 7.1 Coulombsches Reibungsgesetz

Das Coulombsche Reibungsgesetz beschreibt die Zusammenhänge zwischen Normalkraft und Reibungskraft für drei grundlegende Fälle. Dabei ist `Fn` die Normalkraft, `μ0` die Haftzahl und `μ` die Gleitreibungszahl.

- **Haftung (Ruhe):** Solange der Körper in Ruhe ist, ist die Haltekraft Fh genau so groß wie die angreifende äußere Kraft und kleiner als die maximal mögliche Haftkraft.
    - **Fh < μ0 · Fn**
- **Grenzhaftung (Bewegungsbeginn):** Dies ist der Übergangszustand, bei dem die Haltekraft ihr Maximum erreicht hat. Eine infinitesimale Erhöhung der äußeren Kraft führt zur Bewegung.
    - **F{h,max} = μ0 · Fn**
- **Gleitreibung (Bewegung):** Sobald sich der Körper bewegt, wirkt eine konstante Reibungskraft F_r, die der Bewegungsrichtung entgegengesetzt ist. In der Regel ist \mu < \mu_0.
    - **Fr = μ · Fn**

### 7.2 Seilreibung (Eytelweinsche Gleichung)

Wird ein Seil um einen feststehenden Zylinder geschlungen, kann aufgrund der Reibung zwischen Seil und Zylinder eine kleine Haltekraft eine deutlich größere Lastkraft im Gleichgewicht halten. Dieses Phänomen wird durch die Eytelweinsche Gleichung beschrieben.

- **Formel:** **F{S2} = F{S1} · e^{μ0 · α}**

Hierbei bedeuten:

- `F{S2}`: Die größere, haltende Seilkraft.
- `F{S1}`: Die kleinere, zu haltende Lastkraft.
- `μ0`: Die Haftzahl zwischen Seil und Zylinder.
- `α`: Der Umschlingungswinkel im **Bogenmaß (Radiant)**.