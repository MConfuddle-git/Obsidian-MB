## 1.0 Grundlagen: Axiome und Grundbegriffe

### 1.1 Definitionen der Grundbegriffe

- **Die Kraft (**`F`**):** Die Kraft ist eine Vektorgröße, die als **gebundener Vektor** durch drei Eigenschaften vollständig definiert ist:
    1. **Betrag:** Die Größe bzw. Intensität der Kraft.
    2. **Richtung:** Die Orientierung der Kraft im Raum, festgelegt durch ihre Wirkungslinie.
    3. **Angriffspunkt:** Der Punkt, an dem die Kraft auf den Körper wirkt.
- Die Formelzeichen sind **\vec{F}_{Index}** für den Kraftvektor und **F_{Index}** für den Betrag der Kraft.
- **Der starre Körper:** Der starre Körper ist eine grundlegende Idealisierung in der Statik (Stereostatik). Er beschreibt einen Körper, der unter der Einwirkung von Kräften keine Deformationen (Formänderungen) erfährt. Der Abstand zwischen zwei beliebigen Punkten des Körpers bleibt also stets konstant. Diese Vereinfachung ist für viele ingenieurtechnische Anwendungen hinreichend genau.
### 1.2 Die Axiome der Mechanik

Die gesamte klassische Mechanik basiert auf vier fundamentalen, durch Beobachtung gewonnenen Grundaussagen, den sogenannten Axiomen nach Newton.

1. **Trägheitsaxiom (1. Newtonsches Gesetz):** Ein Körper verharrt im Zustand der Ruhe oder der gleichförmig-geradlinigen Bewegung, solange die Summe aller auf ihn wirkenden Kräfte null ist. Für die Statik bedeutet dies, dass sich ein Körper im Gleichgewicht befindet, wenn die resultierende Kraft **\vec{F}_{R} = 0** ist.
2. **Verschiebungsaxiom:** Die Wirkung einer Kraft auf einen **starren Körper** ändert sich nicht, wenn ihr Angriffspunkt entlang ihrer Wirkungslinie verschoben wird. Eine Kraft ist somit ein "linienflüchtiger" Vektor.
3. **Reaktionsaxiom (3. Newtonsches Gesetz / Wechselwirkungsgesetz):** Übt ein Körper 1 auf einen Körper 2 eine Kraft aus (actio), so übt der Körper 2 auf den Körper 1 eine gleich große, aber entgegengesetzt gerichtete Kraft aus (reactio). Kurz: _actio gleich reactio_. Als Vektorgleichung formuliert: **\vec{F}_{1} = - \vec{F}_{2}**.
4. **Parallelogrammaxiom (4. Newtonsches Gesetz):** Die Wirkung zweier Kräfte, die an einem gemeinsamen Punkt angreifen, ist äquivalent zur Wirkung einer einzelnen Kraft, der Resultierenden **\vec{F}_{R}**. Diese Resultierende entspricht der Diagonalen des Parallelogramms, das aus den beiden Einzelkräften gebildet wird.
### 1.3 Kraftübertragungselemente in der Ebene

| Element               | Symbol (Beschreibung)                                         | Wertigkeit | Übertragene Komponenten                                           |
| --------------------- | ------------------------------------------------------------- | ---------- | ----------------------------------------------------------------- |
| **Pendelstütze**      | Ein Stab, der an beiden Enden gelenkig gelagert ist.          | einwertig  | Überträgt nur Druck- oder Zugkräfte entlang der Stabachse.        |
| **Loslager**          | Ein Lager, das Bewegungen parallel zur Auflagefläche zulässt. | einwertig  | Überträgt nur eine Kraftkomponente senkrecht zur Auflagefläche.   |
| **Festlager**         | Ein unverschiebliches, aber drehbares Lager.                  | zweiwertig | Überträgt zwei zueinander senkrechte Kraftkomponenten (F_x, F_y). |
| **Gelenkverbindung**  | Verbindet zwei Starrkörper drehbar miteinander.               | zweiwertig | Überträgt zwei zueinander senkrechte Kraftkomponenten (F_x, F_y). |
| **Feste Einspannung** | Ein Lager, das jegliche Bewegung unterbindet.                 | dreiwertig | Überträgt zwei Kraftkomponenten (F_x, F_y) und ein Moment (M).    |
## 2.0 Kräftesysteme und Gleichgewicht in der Ebene

### 2.1 Zentrales ebenes Kräftesystem (gemeinsamer Angriffspunkt)

Bei einem zentralen Kräftesystem ist für das Gleichgewicht nur das Kräftegleichgewicht relevant, da keine Momente entstehen.

- **Komponentendarstellung:** Zerlegung einer Kraft `F` in ihre kartesischen Komponenten bezüglich des Winkels \alpha zur x-Achse:
    - **F_x = F \cdot \cos(\alpha)**
    - **F_y = F \cdot \sin(\alpha)**
- **Betrag und Richtung:** Berechnung von Betrag und Richtung aus den gegebenen Komponenten:
    - **F = \sqrt{F_x^2 + F_y^2}**
    - **\alpha = \arctan\left(\frac{F_y}{F_x}\right)** (Achtung: Quadrant beachten!)
- **Addition von Kräften (Resultierende):** Die resultierende Kraft **\vec{F}_{R} = \sum \vec{F}_{i}** wird durch die komponentenweise Addition der Einzelkräfte ermittelt:
    - **F_{Rx} = \sum F_{ix}**
    - **F_{Ry} = \sum F_{iy}**
- **Gleichgewichtsbedingungen:** Ein zentrales ebenes Kräftesystem ist im Gleichgewicht, wenn die Resultierende eine Nullkraft ist. Daraus folgen zwei skalare Gleichungen:
    - **\sum F_{ix} = 0**
    - **\sum F_{iy} = 0**

### 2.2 Allgemeines ebenes Kräftesystem

Bei einem allgemeinen Kräftesystem muss zusätzlich zum Kräftegleichgewicht auch das Momentengleichgewicht erfüllt sein.

- **Kräftepaar und Moment:**
    - Ein **Kräftepaar** besteht aus zwei gleich großen, parallelen, aber entgegengesetzt gerichteten Kräften. Seine Wirkung ist eine reine Drehung.
    - Das Moment eines Kräftepaares ist das Produkt aus dem Kraftbetrag `F` und dem senkrechten Abstand `h` der Wirkungslinien: **M = F \cdot h**.
- **Moment einer Kraft:**
    - Das Moment einer Kraft \vec{F} mit den Komponenten (F_x, F_y) und dem Angriffspunkt (x, y) bezüglich eines Punktes A (x_A, y_A) berechnet sich zu: **M_A = (x - x_A) \cdot F_y - (y - y_A) \cdot F_x**
- **Resultierende:**
    - Ein allgemeines ebenes Kräftesystem kann auf eine **resultierende Kraft** **\vec{F}_{R}** und ein **resultierendes Moment** **M_{RA}** bezüglich eines Punktes A reduziert werden. Die Komponenten berechnen sich durch Summation:
        - **F_{Rx} = \sum F_{ix}**
        - **F_{Ry} = \sum F_{iy}**
        - **M_{RA} = \sum M_{iA}**
- **Gleichgewichtsbedingungen:** 
	- Ein allgemeines ebenes Kräftesystem ist im Gleichgewicht, wenn sowohl die resultierende Kraft als auch das resultierende Moment (bezüglich eines beliebigen Punktes A) null sind. Dies führt zu drei unabhängigen skalaren Gleichungen:
	    - **\sum F_{ix} = 0**
	    - **\sum F_{iy} = 0**
	    - **\sum M_{iA} = 0**
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
- **Mehrteilige Tragwerke:** Für Tragwerke, die aus mehreren starren Körpern bestehen, wird die Formel erweitert: **f = g \cdot n - a - z**
    - `n`: Anzahl der Starrkörper des Tragwerks
    - `z`: Anzahl der Zwischenreaktionen in den Gelenken/Verbindungen

### 3.2 Ebene Fachwerke (Knotenpunktverfahren)

Fachwerke sind Tragwerke, die idealisiert nur aus zug- oder druckbeanspruchten Stäben bestehen. Die Berechnung der Stabkräfte erfolgt unter folgenden Annahmen:

- Die Stäbe sind an den Knoten reibungsfrei und gelenkig verbunden.
- Äußere Kräfte und Lagerreaktionen greifen nur an den Knoten an. Kräfte, die auf einen Stab wirken, werden in äquivalente Kraftanteile zerlegt, die am Stabanfang und -ende im Knoten angreifen.
- Die Stabachsen sind gerade und schneiden sich in den Knotenpunkten.

Beim **Knotenpunktverfahren** wird jeder einzelne Knoten freigeschnitten und die Gleichgewichtsbedingungen (\sum F_x = 0, \sum F_y = 0) angewendet, um die Stabkräfte zu ermitteln. Zur Vereinfachung können sogenannte **Nullstäbe** (unbelastete Stäbe) oft vorab identifiziert werden:

1. An einem **unbelasteten Knoten** mit **zwei Stäben** (nicht auf einer Linie) sind beide Stäbe Nullstäbe.
2. An einem Knoten mit **zwei Stäben**, bei dem eine **äußere Kraft** in Richtung des einen Stabes wirkt, ist der andere Stab ein Nullstab.
3. An einem **unbelasteten Knoten** mit **drei Stäben**, von denen zwei auf einer Linie liegen, ist der dritte Stab ein Nullstab.
## 4.0 Räumliche Statik

### 4.1 Einleitung und strategische Bedeutung

Der Übergang von der zweidimensionalen zur dreidimensionalen Statik erweitert den Anwendungsbereich auf räumliche Strukturen. Die grundlegenden Prinzipien wie die Axiome und Gleichgewichtsbedingungen bleiben dabei vollständig erhalten. Allerdings müssen die Vektordarstellungen für Kräfte und Momente um eine dritte Dimension ergänzt werden, und die Anzahl der Gleichgewichtsbedingungen erhöht sich, um die zusätzlichen Freiheitsgrade (drei Translationen, drei Rotationen) im Raum zu erfassen.

### 4.2 Kraft und Moment im Raum

Die Beschreibung von Kräften und Momenten erfolgt konsequent über Vektoren in einem 3D-Koordinatensystem.

- **Kraftvektor** `F`**:**
    - Koordinatenschreibweise mit Einheitsvektoren: **\vec{F} = F_x \cdot \vec{e}_x + F_y \cdot \vec{e}_y + F_z \cdot \vec{e}_z**
    - Berechnung des Betrags aus den Komponenten: **F = \sqrt{F_x^2 + F_y^2 + F_z^2}**
- **Moment einer Kraft im Raum:**
    - Das Moment einer Kraft \vec{F}, die am Punkt mit dem Ortsvektor \vec{r} angreift, bezüglich des Koordinatenursprungs wird durch das Vektorprodukt (Kreuzprodukt) berechnet: **\vec{M} = \vec{r} \times \vec{F}**
    - In Komponentenschreibweise ergibt sich das Moment zu: **\vec{M} = \begin{pmatrix} y \cdot F_z - z \cdot F_y \\ z \cdot F_x - x \cdot F_z \\ x \cdot F_y - y \cdot F_x \end{pmatrix} = \begin{pmatrix} M_x \\ M_y \\ M_z \end{pmatrix}**

### 4.3 Gleichgewichtsbedingungen im Raum

Ein Körper im Raum ist im Gleichgewicht, wenn die Vektorsumme aller Kräfte und die Vektorsumme aller Momente (bezüglich eines beliebigen Punktes A) null sind.

- Vektorielle Gleichgewichtsbedingungen: **\sum \vec{F}_i = \vec{0}** und **\sum \vec{M}_{iA} = \vec{0}**
- Daraus ergeben sich sechs unabhängige skalare Gleichgewichtsbedingungen:
    - **\sum F_{ix} = 0**
    - **\sum F_{iy} = 0**
    - **\sum F_{iz} = 0**
    - **\sum M_{ix} = 0**
    - **\sum M_{iy} = 0**
    - **\sum M_{iz} = 0**

Um die resultierende Kraft einer verteilten Last (wie der Gewichtskraft) korrekt ansetzen zu können, wird die Berechnung von Schwerpunkten benötigt.

## 5.0 Schwerpunkte

### 5.1 Schwerpunkte von Linien, Flächen und Volumen

Die Koordinaten des Schwerpunkts (x_S, y_S, z_S) werden über integrale Beziehungen berechnet.

- **Streckenlast** `q(x)`**:**
    - Resultierende Kraft: **F_R = \int q(x) \,dx**
    - Schwerpunktskoordinate: **x_S = \frac{\int x \cdot q(x) \,dx}{\int q(x) \,dx}**
- **Flächenschwerpunkt:**
    - **x_S = \frac{\int x \,dA}{A}**
    - **y_S = \frac{\int y \,dA}{A}**
- **Linienschwerpunkt:**
    - **x_S = \frac{\int x \,ds}{s}**
    - **y_S = \frac{\int y \,ds}{s}**
- **Volumenschwerpunkt (homogener Körper):**
    - **x_S = \frac{\int x \,dV}{V}**, **y_S = \frac{\int y \,dV}{V}**, **z_S = \frac{\int z \,dV}{V}**

### 5.2 Schwerpunkte zusammengesetzter Gebilde

Der Schwerpunkt eines Körpers, der sich aus mehreren einfachen Teilgebilden zusammensetzen lässt, kann über Summenformeln berechnet werden. Die Formeln für einen Flächenschwerpunkt lauten exemplarisch:

- **x_S = \frac{\sum x_{Si} \cdot A_i}{\sum A_i}**
- **y_S = \frac{\sum y_{Si} \cdot A_i}{\sum A_i}**

Dabei sind x_{Si} und y_{Si} die bekannten Schwerpunktkoordinaten und A_i die Flächeninhalte der Teilgebilde. Ausschnitte oder Löcher werden in der Summe als negative Flächen behandelt.

Nachdem die äußeren Kräfte und deren Angriffspunkte bestimmt sind, folgt die Analyse der inneren Beanspruchungen eines Bauteils – der sogenannten Schnittgrößen.

### 6.0 Schnittgrößen

### 6.1 Schnittgrößen am geraden Balken (Ebene)

An einem gedachten Schnitt durch einen ebenen Balken treten drei Schnittgrößen auf:

- **Normalkraft (N):** Die Kraftkomponente in Längsrichtung der Balkenachse (x-Achse). Sie verursacht eine Dehnung oder Stauchung.
- **Querkraft (Q):** Die Kraftkomponente senkrecht zur Balkenachse (in z-Richtung). Sie verursacht eine Scherung.
- **Biegemoment (M):** Das Moment um die Achse, die senkrecht zur Ebene steht (y-Achse). Es verursacht eine Biegung des Balkens.

**Vorzeichenkonvention:** Ein Schnittufer wird als _positiv_ bezeichnet, wenn sein nach außen weisender Normalenvektor in die positive Koordinatenrichtung (z.B. x-Richtung) zeigt. Positive Schnittgrößen zeigen an diesem positiven Schnittufer in die positiven Koordinatenrichtungen.
### 6.2 Zusammenhang zwischen Belastung und Schnittgrößen

Zwischen der äußeren Belastung (Streckenlast `q(x)`) und den inneren Schnittgrößen (Querkraft `Q(x)`, Biegemoment `M(x)`) bestehen fundamentale Differentialbeziehungen:

- **\frac{dQ(x)}{dx} = -q(x)** (Die Ableitung der Querkraft entspricht der negativen Streckenlast.)
- **\frac{dM(x)}{dx} = Q(x)** (Die Ableitung des Biegemoments entspricht der Querkraft.)

Diese Beziehungen bedeuten umgekehrt, dass der Querkraftverlauf durch Integration der negativen Streckenlast und der Momentenverlauf durch Integration des Querkraftverlaufs ermittelt werden kann.
### 6.3 Räumliche Schnittgrößen

An einem Schnitt durch ein räumlich belastetes Bauteil können insgesamt sechs Schnittgrößen auftreten, die den sechs Freiheitsgraden entsprechen:

- Normalkraft: **N = F_{Sx}**
- Querkräfte: **Q_y = F_{Sy}**, **Q_z = F_{Sz}**
- Torsionsmoment (um die Längsachse): **M_T = M_{Sx}**
- Biegemomente (um die Querachsen): **M_y = M_{Sy}**, **M_z = M_{Sz}**

Das letzte Kapitel dieser Formelsammlung widmet sich der Reibung, einer wichtigen, nicht-idealen Kraft, die in realen Kontaktflächen auftritt.

## 7.0 Reibung

Die Reibung ist eine reale physikalische Kraft, die der relativen Bewegung zwischen zwei sich berührenden Körpern entgegenwirkt. Sie entsteht durch die Beschaffenheit der Kontaktoberflächen. In der Mechanik wird fundamental zwischen der **Haftung** (statischer Zustand ohne Bewegung) und der **Gleitreibung** (kinetischer Zustand bei Bewegung) unterschieden.
### 7.1 Coulombsches Reibungsgesetz

Das Coulombsche Reibungsgesetz beschreibt die Zusammenhänge zwischen Normalkraft und Reibungskraft für drei grundlegende Fälle. Dabei ist F_n die Normalkraft, \mu_0 die Haftzahl und \mu die Gleitreibungszahl.

- **Haftung (Ruhe):** Solange der Körper in Ruhe ist, ist die Haltekraft F_h genau so groß wie die angreifende äußere Kraft und kleiner als die maximal mögliche Haftkraft.
    - **F_h < \mu_0 \cdot F_n**
- **Grenzhaftung (Bewegungsbeginn):** Dies ist der Übergangszustand, bei dem die Haltekraft ihr Maximum erreicht hat. Eine infinitesimale Erhöhung der äußeren Kraft führt zur Bewegung.
    - **F_{h,max} = \mu_0 \cdot F_n**
- **Gleitreibung (Bewegung):** Sobald sich der Körper bewegt, wirkt eine konstante Reibungskraft F_r, die der Bewegungsrichtung entgegengesetzt ist. In der Regel ist \mu < \mu_0.
    - **F_r = \mu \cdot F_n**

### 7.2 Seilreibung (Eytelweinsche Gleichung)

Wird ein Seil um einen feststehenden Zylinder geschlungen, kann aufgrund der Reibung zwischen Seil und Zylinder eine kleine Haltekraft eine deutlich größere Lastkraft im Gleichgewicht halten. Dieses Phänomen wird durch die Eytelweinsche Gleichung beschrieben.

- **Formel:** **F_{S2} = F_{S1} \cdot e^{\mu_0 \cdot \alpha}**

Hierbei bedeuten:

- F_{S2}: Die größere, haltende Seilkraft.
- F_{S1}: Die kleinere, zu haltende Lastkraft.
- \mu_0: Die Haftzahl zwischen Seil und Zylinder.
- \alpha: Der Umschlingungswinkel im **Bogenmaß (Radiant)**.