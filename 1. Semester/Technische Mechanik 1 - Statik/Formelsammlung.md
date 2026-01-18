## Kraftübertragungselemente in der Ebene
![[Pasted image 20251222174307.png]]
## Kraftübertragungselemente im Raum
![[Pasted image 20251222181422.png]]
<div class="page-break" style="page-break-before: always;"></div>

Ein Körper ist im Gleichgewicht, wenn die Vektorsumme aller Kräfte und die Vektorsumme aller Momente (bezüglich eines beliebigen Punktes A) null sind. **Bezugspunkt am besten immer nach Wertigkeit wählen**.
- Daraus ergeben sich drei (2D) oder sechs (3D) unabhängige skalare Gleichgewichtsbedingungen:
    - **∑ F{ix} = 0 =**
    - **∑ F{iy} = 0 =**
    - **∑ F{iz} = 0 =**
    - **∑ M{ix} = 0 =**
    - **∑ M{iy} = 0 =**
    - **∑ M{iz} = 0 =**

**Alle Längen in Meter umrechnen!
Schräge Kräfte müssen in beiden Summen eingerechnet werden!
Momente auf der gleichen Achse sind = 0 !!!**
![[Pasted image 20260118152631.png]]
## Statische Bestimmtheit
- **Einteilige Tragwerke:** Für ein einzelnes starres Bauteil in der Ebene gilt die Formel: **f = g - a**
    - `f`: Anzahl der verbleibenden Freiheitsgrade
    - `g`: Anzahl der Gleichgewichtsbedingungen in der Ebene (`In 2D g=3 / In 3D g=6`)
    - `a`: Anzahl der Auflagerreaktionen (Wertigkeiten der Lager z.B. FAx, FAy, FBz)
- **Bewertung:**
    - `f = 0`: **Statisch bestimmt** (stabil und berechenbar)
    - `f < 0`: **Statisch unbestimmt** (stabil, aber nicht allein mit Statik-Mitteln lösbar)
    - `f > 0`: **Kinematisch** (instabil/verschieblich)
- **Achtung:** `f=0` ist eine notwendige, aber keine hinreichende Bedingung. 
  Das Tragwerk ist trotzdem kinematisch (instabil), wenn die Lagerung fehlerhaft ist, z. B. wenn:
    - die Lagerkräfte parallel zueinander sind.
    - die Wirkungslinien der Lagerkräfte sich in einem gemeinsamen Punkt schneiden.
- **Mehrteilige Tragwerke:** Für Tragwerke, die aus mehreren starren Körpern bestehen, wird die Formel erweitert: **f = g · n - a - z**
    - `n`: Anzahl der Starrkörper des Tragwerks
    - `z`: Anzahl der Zwischenreaktionen in den Gelenken/Verbindungen
<div class="page-break" style="page-break-before: always;"></div>

### Ebene Fachwerke (Knotenpunktverfahren)

Fachwerke sind Tragwerke, die idealisiert nur aus zug- oder druckbeanspruchten Stäben bestehen. Die Berechnung der Stabkräfte erfolgt unter folgenden Annahmen:

- Die Stäbe sind an den Knoten reibungsfrei und gelenkig verbunden.
- Äußere Kräfte und Lagerreaktionen greifen nur an den Knoten an. Kräfte, die auf einen Stab wirken, werden in äquivalente Kraftanteile zerlegt, die am Stabanfang und -ende im Knoten angreifen.
- Die Stabachsen sind gerade und schneiden sich in den Knotenpunkten.

Beim **Knotenpunktverfahren** wird jeder einzelne Knoten freigeschnitten und die Gleichgewichtsbedingungen (∑ Fx = 0, ∑ Fy = 0) angewendet, um die Stabkräfte zu ermitteln. Zur Vereinfachung können sogenannte **Nullstäbe** (unbelastete Stäbe) oft vorab identifiziert werden:

1. An einem **unbelasteten Knoten** mit **zwei Stäben** (nicht auf einer Linie) sind beide Stäbe Nullstäbe.
2. An einem Knoten mit **zwei Stäben**, bei dem eine **äußere Kraft** in Richtung des einen Stabes wirkt, ist der andere Stab ein Nullstab.
3. An einem **unbelasteten Knoten** mit **drei Stäben**, von denen zwei auf einer Linie liegen, ist der dritte Stab ein Nullstab.
<div class="page-break" style="page-break-before: always;"></div>
## Schwerpunkte
### Schwerpunkte von Linien, Flächen und Volumen

- **Streckenlast**
    ![[Pasted image 20260118133353.png]]
<div class="page-break" style="page-break-before: always;"></div>

- **Flächenschwerpunkt:**
    ![[Pasted image 20260118132732.png]]
- **Linienschwerpunkt:**
    ![[Pasted image 20260118132748.png]]

![[Pasted image 20260118132829.png]]
<div class="page-break" style="page-break-before: always;"></div>

- **Volumenschwerpunkt (homogener Körper):**
    - **xS = (∫x \,dV) / (V)**
    - **yS = (∫y \,dV) / (V)**
    - **zS = (∫z \,dV) / (V)**

![[Pasted image 20260118133140.png]]
<div class="page-break" style="page-break-before: always;"></div>

## Schwerpunkte zusammengesetzter Gebilde

![[Pasted image 20260118131027.png]]

![[Pasted image 20260115144141.png]]

![[Pasted image 20260115144743.png]]
<div class="page-break" style="page-break-before: always;"></div>

## Schnittgrößen
### Schnittgrößen am geraden Balken (Ebene)

An einem gedachten Schnitt durch einen ebenen Balken treten drei Schnittgrößen auf:

- **Normalkraft (N):** Die Kraftkomponente in Längsrichtung der Balkenachse (x-Achse). 
  Sie verursacht eine Dehnung oder Stauchung. (Gerader Verlauf)
- **Querkraft (Q):** Die Kraftkomponente senkrecht zur Balkenachse (in z-Richtung). 
  Sie verursacht eine Scherung. (Gerader Verlauf)
- **Biegemoment (M):** Das Moment um die Achse, die senkrecht zur Ebene steht (y-Achse). 
  Es verursacht eine Biegung des Balkens. (Parabelverlauf)

Zwischen der äußeren Belastung (Streckenlast `q(x)`) und den inneren Schnittgrößen (Querkraft `Q(x)`, Biegemoment `M(x)`) bestehen fundamentale Differentialbeziehungen:

- **(dQ(x)) / (dx) = -q(x)** (Die Ableitung der Querkraft entspricht der negativen Streckenlast.)
- **(dM(x)) / (dx) = Q(x)** (Die Ableitung des Biegemoments entspricht der Querkraft.)

Diese Beziehungen bedeuten umgekehrt, dass der Querkraftverlauf durch Integration der negativen Streckenlast und der Momentenverlauf durch Integration des Querkraftverlaufs ermittelt werden kann.

1. Punkte einzeichnen, Ende und Anfang eines Schnitts ist ein Punkt, Kräfte sind Punkte.
2. Koordinatensysteme lokal anpassen. **Vorzeichenkonvention beachten!**		Positives/negatives Schnittufer
3. Ablaufen der Punkte von links oder rechts.
4. Schnittgrößendiagramm aufzeichnen
### Räumliche Schnittgrößen

An einem Schnitt durch ein räumlich belastetes Bauteil können insgesamt sechs Schnittgrößen auftreten, die den sechs Freiheitsgraden entsprechen:

- Normalkraft: **N = F{Sx}**
- Querkräfte: **Qy = F{Sy}**, **Qz = F{Sz}**
- Torsionsmoment (um die Längsachse): **MT = M{Sx}**
- Biegemomente (um die Querachsen): **My = M{Sy}**, **Mz = M{Sz}**

<div class="page-break" style="page-break-before: always;"></div>

## Reibung
Die Reibung ist eine reale physikalische Kraft, die der relativen Bewegung zwischen zwei sich berührenden Körpern entgegenwirkt. Sie entsteht durch die Beschaffenheit der Kontaktoberflächen. In der Mechanik wird fundamental zwischen der **Haftung** (statischer Zustand ohne Bewegung) und der **Gleitreibung** (kinetischer Zustand bei Bewegung) unterschieden.
### Coulombsches Reibungsgesetz
Das Coulombsche Reibungsgesetz beschreibt die Zusammenhänge zwischen Normalkraft und Reibungskraft für drei grundlegende Fälle. Dabei ist `Fn` die Normalkraft, `μ0` die Haftzahl und `μ` die Gleitreibungszahl.

- **Haftung (Ruhe):** Solange der Körper in Ruhe ist, ist die Haltekraft Fh genau so groß wie die angreifende äußere Kraft und kleiner als die maximal mögliche Haftkraft.
    - **Fh < μ0 · Fn**
- **Grenzhaftung (Bewegungsbeginn):** Dies ist der Übergangszustand, bei dem die Haltekraft ihr Maximum erreicht hat. Eine infinitesimale Erhöhung der äußeren Kraft führt zur Bewegung.
    - **F{h,max} = μ0 · Fn**
- **Gleitreibung (Bewegung):** Sobald sich der Körper bewegt, wirkt eine konstante Reibungskraft `Fr`, die der Bewegungsrichtung entgegengesetzt ist. In der Regel ist `μ < μ0`.
    - **Fr = μ · Fn**

### Seilreibung (Eytelweinsche Gleichung)
Wird ein Seil um einen feststehenden Zylinder geschlungen, kann aufgrund der Reibung zwischen Seil und Zylinder eine kleine Haltekraft eine deutlich größere Lastkraft im Gleichgewicht halten. 

- **Formel:** **F{S2} = F{S1} · e^(μ0 · α)**

Hierbei bedeuten:
- `F{S2}`: Die größere, haltende Seilkraft.
- `F{S1}`: Die kleinere, zu haltende Lastkraft.
- `μ0`: Die Haftzahl zwischen Seil und Zylinder.
- `α`: Der Umschlingungswinkel im **Bogenmaß (Radiant)**.