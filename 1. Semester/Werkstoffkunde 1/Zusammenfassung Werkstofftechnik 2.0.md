## 1. Einführung in die Werkstofftechnik
### 1.1. Klassifizierung von Werkstoffen

Werkstoffe werden üblicherweise in vier Hauptgruppen eingeteilt, die sich durch ihre atomare Bindung und ihre charakteristischen Eigenschaften unterscheiden.

| Werkstoffgruppe       | Charakteristische Eigenschaften                                                                                                  | Beispiele aus den Folien                                                                   |
| --------------------- | -------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------ |
| **Metalle**           | Gute elektrische & thermische Leitfähigkeit, metallischer Glanz, plastische Verformbarkeit (Duktilität).                         | Stahl, Aluminiumlegierungen, Titanlegierungen, Kupfer                                      |
| **Keramiken**         | Hohe Härte und Druckfestigkeit, hohe Temperaturbeständigkeit, elektrische Isolatoren, sprödes Verhalten.                         | Aluminiumoxid (Al₂O₃), Siliziumnitrid (Si₃N₄), Polykristallines kubisches Bornitrid (PCBN) |
| **Polymere**          | Geringe Dichte, elektrische und thermische Isolatoren, oft elastisch oder plastisch verformbar, geringe Temperaturbeständigkeit. | Polycarbonat (PC), Polyetheretherketon (PEEK), Polyamid (PA)                               |
| **Verbundwerkstoffe** | Kombination von Eigenschaften verschiedener Werkstoffgruppen, oft hohe spezifische Festigkeit und Steifigkeit.                   | Kohlefaserverstärkter Kunststoff (CFK), Metall-Keramik-Verbund (AlSi-Legierung mit Al₂O₃)  |

### 1.2. Der Werkstoff-Engineering-Ansatz

Der Kern des Werkstoff-Engineerings liegt in der Optimierung des Zusammenspiels von **Leistung** (z.B. Festigkeit, Zähigkeit), **Kosten**, **Werkstoff/Chemie** (Legierungszusammensetzung), **Konstruktion/Fertigung** (Herstellungsverfahren) und der resultierenden **Mikrostruktur** (Gefüge). Diese Faktoren beeinflussen sich gegenseitig und bestimmen letztendlich die finalen Eigenschaften und die Wirtschaftlichkeit eines Bauteils.
<div class="page-break" style="page-break-before: always;"></div>

## 2. Allgemeine Werkstoffeigenschaften

### 2.1. Kategorien von Werkstoffeigenschaften

Die Eigenschaften von Werkstoffen lassen sich in vier Hauptkategorien einteilen:

- **Fertigungstechnische Eigenschaften:** 
  Beschreiben die Eignung eines Werkstoffs für bestimmte Herstellungsverfahren (z.B. Gießbarkeit, Schweißbarkeit, Zerspanbarkeit).
- **Chemisch-technologische Eigenschaften:** 
  Betreffen die chemische Zusammensetzung und das Verhalten gegenüber umgebenden Stoffen (z.B. Korrosionsbeständigkeit, Zunderbeständigkeit).
- **Mechanisch-technologische Eigenschaften:** 
  Beschreiben das Verhalten unter mechanischer Beanspruchung (z.B. Festigkeit, Härte, Verformungsverhalten).
- **Physikalische Eigenschaften:** 
  Umfassen grundlegende Materialkonstanten, die auf dem atomaren Aufbau basieren.

### 2.2. Physikalische Schlüsseleigenschaften

#### Dichte (ρ)

- **Definition:** Die Dichte ist das Verhältnis der Masse (m) eines Körpers zu seinem Volumen (V). `ρ = m / V`
- **Technische Relevanz:** Die Dichte ist eine entscheidende Größe im Leichtbau. Werkstoffe mit hoher Festigkeit bei geringer Dichte (hohe _spezifische Festigkeit_) sind für Anwendungen wie den Flugzeugbau (Aluminium, Titan) oder die Automobilindustrie essenziell, um Gewicht und damit Energieverbrauch zu reduzieren.

#### Thermischer Ausdehnungskoeffizient (α)

- **Definition:** Der thermische Ausdehnungskoeffizient beschreibt die relative Längenänderung (Δl) eines Werkstoffs pro Grad Temperaturänderung (ΔT). `Δl = l₀ · α · ΔT`
- **Technische Relevanz:** Dieser Koeffizient muss in Konstruktionen berücksichtigt werden, die Temperaturschwankungen ausgesetzt sind. Werden unterschiedliche Materialien kombiniert, können unterschiedliche Ausdehnungskoeffizienten zu Wärmespannungen führen. Beispiele sind Dehnungsfugen bei Eisenbahnschienen oder Schiebesitze bei doppelwandigen Abgasrohren.
<div class="page-break" style="page-break-before: always;"></div>

#### Elektrische Leitfähigkeit (σ)

- **Definition:** Die elektrische Leitfähigkeit ist ein Maß für die Fähigkeit eines Stoffes, elektrischen Strom zu leiten. Sie ist der Kehrwert des spezifischen elektrischen Widerstands (ebenfalls mit ρ bezeichnet, nicht zu verwechseln mit der Dichte). `σ = 1 / ρ`
- **Technische Relevanz:** Metalle sind aufgrund ihrer metallischen Bindung gute elektrische Leiter. Reine Metalle leiten den Strom am besten, da Fremdatome den Elektronenfluss stören. Mit steigender Temperatur nimmt die Leitfähigkeit bei Metallen ab, da die zunehmenden Gitterschwingungen die Elektronenbewegung behindern. Kupfer und Aluminium sind typische Werkstoffe für elektrische Leitungen.

#### Wärmeleitfähigkeit (λ)

- **Definition:** Die Wärmeleitfähigkeit gibt an, welche Wärmemenge pro Zeit durch eine definierte Fläche bei einem bestimmten Temperaturgefälle transportiert wird.
- **Technische Relevanz:** Für Metalle besteht ein direkter Zusammenhang zwischen elektrischer und thermischer Leitfähigkeit, beschrieben durch das **Wiedemann-Franz'sche Gesetz**. Elektronen transportieren sowohl Ladung als auch Wärme. Werkstoffe mit hoher Wärmeleitfähigkeit (z.B. Kupfer) werden für Kühlkörper eingesetzt, während Materialien mit geringer Leitfähigkeit (z.B. Keramiken, Polymere) zur Wärmeisolierung dienen.
<div class="page-break" style="page-break-before: always;"></div>

## 3. Aufbau metallischer Werkstoffe

Die einzigartigen Eigenschaften von Metallen wie ihre hohe Leitfähigkeit, ihr Glanz und ihre Verformbarkeit resultieren direkt aus ihrer atomaren Struktur und der Art der chemischen Bindung zwischen den Atomen.

### 3.1. Die Metallische Bindung

Im Gegensatz zur gerichteten **kovalenten Bindung** (Elektronenpaarbindung, typisch für Polymere) oder der **Ionenbindung** (elektrostatische Anziehung, typisch für Keramiken) zeichnet sich die metallische Bindung durch ein besonderes Modell aus: Die Atomrümpfe (positive Ionen) sind in einem regelmäßigen Gitter angeordnet und werden von einer frei beweglichen Wolke aus Valenzelektronen, dem sogenannten **Elektronengas**, zusammengehalten. Dieses Elektronengas ist nicht an einzelne Atome gebunden und ermöglicht die hohe elektrische und thermische Leitfähigkeit. Die ungerichtete Natur dieser Bindung erlaubt zudem das Abgleiten von Atom-Ebenen gegeneinander, was die gute plastische Verformbarkeit (Duktilität) von Metallen erklärt.

### 3.2. Kristalliner vs. Amorpher Aufbau

- **Kristalline Werkstoffe:** Die Atome sind in einer regelmäßigen, sich periodisch wiederholenden dreidimensionalen Struktur angeordnet. Man spricht von **Nah- und Fernordnung**. Fast alle Metalle erstarren kristallin. Die plastische Verformung erfolgt durch das Verschieben von Atomen entlang dicht gepackter Ebenen, den sogenannten **Gleitebenen**.
- **Amorphe Werkstoffe:** Die Atome weisen weder eine Fern- noch eine definierte Nahordnung auf; ihre Anordnung ist unregelmäßig (z.B. Glas). Metalle können durch extrem schnelles Abkühlen (ca. 10⁶ K/s) amorph erstarren ("metallische Gläser"), was zu einzigartigen Eigenschaften wie hoher Härte bei gleichzeitiger Elastizität führt.
<div class="page-break" style="page-break-before: always;"></div>

### 3.3. Kristallgitter und Gleitsysteme

Die regelmäßige Anordnung der Atome im Kristall wird durch die Elementarzelle beschrieben. Für Metalle sind drei Kristallstrukturen von besonderer Bedeutung. Die Verformbarkeit eines Metalls hängt maßgeblich von der Anzahl der verfügbaren Gleitsysteme ab (Kombination aus Gleitebene und Gleitrichtung).

| Kristallstruktur                     | Beispielmetalle  | Anzahl Gleitsysteme | Bewertung der Verformbarkeit                 |
| ------------------------------------ | ---------------- | ------------------- | -------------------------------------------- |
| **krz** (kubisch-raumzentriert)      | α-Fe, Cr, Mo, W  | 48/12               | Gut, aber höhere Schubspannung erforderlich. |
| **kfz** (kubisch-flächenzentriert)   | γ-Fe, Al, Cu, Ni | 12                  | Sehr gut, da dichtest gepackte Ebenen.       |
| **hdp** (hexagonal dichtest gepackt) | Mg, Zn, α-Ti     | 3                   | Gering, da wenige Gleitsysteme.              |

### 3.4. Gitterbaufehler im Realkristall

Ein **Idealkristall** mit einem perfekt periodischen Aufbau existiert in der Realität nicht. Technische Werkstoffe sind **Realkristalle** und enthalten stets Störungen im Gitteraufbau, sogenannte **Gitterbaufehler**. Diese Fehler sind nicht zwangsläufig negativ, sondern bestimmen viele wichtige Werkstoffeigenschaften. Sie werden nach ihrer Dimensionalität klassifiziert:

- **0D (punktförmig):**
    - **Leerstelle:** Ein unbesetzter Gitterplatz.
    - **Fremdatom:** Ein Atom eines anderen Elements. Es kann ein Gitteratom ersetzen (**Substitutionsatom**) oder sich auf einem Zwischengitterplatz einlagern (**Zwischengitteratom** oder interstitielles Atom).
- **1D (linienförmig):**
    - **Versetzung:** Eine eingeschobene oder fehlende Halbebene von Atomen im Kristallgitter.
- **2D (flächenförmig):**
    - **Korngrenzen:** Grenzflächen zwischen unterschiedlich orientierten Kristallen (Körnern) in einem polykristallinen Gefüge.
<div class="page-break" style="page-break-before: always;"></div>

### 3.5. Bedeutung von Gitterbaufehlern

Gitterbaufehler sind entscheidend für viele technologisch relevante Prozesse und Eigenschaften:

- **Fremdatome:** Sie verspannen das Kristallgitter und behindern die Bewegung von Versetzungen. Dies führt zu einer Festigkeitssteigerung, die als **Mischkristallverfestigung** bezeichnet wird.
- **Versetzungen:** Sie sind die Träger der **plastischen Verformung**. Anstatt ganze Atomblöcke auf einmal zu verschieben (was enorme Kräfte erfordern würde), bewegt sich die Versetzungslinie durch das Gitter. Eine Erhöhung der Versetzungsdichte durch Kaltumformung führt zur **Kaltverfestigung**. Die zunehmende Dichte führt zu einem "Verhaken" und gegenseitiger Behinderung der Versetzungen, was eine höhere äußere Spannung für eine weitere Verformung erfordert. Ohne Versetzungen wären Metalle spröde.
- **Leerstellen & Zwischengitteratome:** Sie sind die Voraussetzung für die **Diffusion** im festen Zustand, also den Materialtransport durch Atomwanderung. Beim **Leerstellenmechanismus** springen Atome auf benachbarte freie Gitterplätze. Beim **Zwischengittermechanismus** wandern kleine Atome (wie C in Fe) von einem Zwischengitterplatz zum nächsten.

Der Übergang vom flüssigen in den festen Zustand ist der Prozess, bei dem sich diese Kristallstrukturen und ihre Fehler ausbilden. Dieser wird im nächsten Kapitel behandelt.
<div class="page-break" style="page-break-before: always;"></div>

## 4. Mechanismus der Erstarrung

Die Erstarrung ist der Phasenübergang von einer ungeordneten Schmelze zu einer geordneten kristallinen Struktur. Dieser Prozess ist fundamental für die Ausbildung des Gefüges und damit für die Eigenschaften eines metallischen Bauteils.

### 4.1. Erstarrung reiner Metalle

Bei der Abkühlung einer reinen Metallschmelze zeigt die Abkühlkurve (Temperatur vs. Zeit) einen charakteristischen **Haltepunkt** bei der Erstarrungstemperatur. Während des Phasenübergangs von flüssig zu fest bleibt die Temperatur konstant, da die freiwerdende **Kristallisationswärme** die durch die Abkühlung entzogene Wärme kompensiert. Erst wenn das gesamte Metall erstarrt ist, sinkt die Temperatur weiter.

### 4.2. Keimbildung und Kristallwachstum

Die Erstarrung beginnt an winzigen, stabilen Kristallisationszentren, den sogenannten **Keimen**. Von diesen Keimen aus wachsen die Kristalle, indem sich weitere Atome aus der Schmelze anlagern (**Kristallwachstum**).

- **Homogene Keimbildung:** Keime entstehen spontan aus der reinen Schmelze durch statistische Anlagerung von Atomen. Dies erfordert eine erhebliche Unterkühlung unter die eigentliche Erstarrungstemperatur.
- **Heterogene Keimbildung:** Keime bilden sich an bereits vorhandenen Grenzflächen wie Verunreinigungen, Impfpartikeln oder der Kokillenwand. Dieser Prozess erfordert eine deutlich geringere Unterkühlung und ist daher in der technischen Praxis der dominierende Mechanismus.

### 4.3. Kornfeinung

Ein feinkörniges Gefüge führt in der Regel zu besseren mechanischen Eigenschaften (z.B. höhere Festigkeit und Zähigkeit), da die vielen Korngrenzen die Versetzungsbewegung behindern. Um ein feines Korn zu erzielen, muss eine hohe Keimzahl erreicht werden. Dies gelingt durch zwei Hauptmethoden:

1. **Erhöhung der Abkühlgeschwindigkeit:** Eine schnelle Abkühlung führt zu einer stärkeren Unterkühlung und fördert die Bildung vieler Keime, bevor diese zu stark wachsen können.
2. **Zugabe von Fremdkeimen ("Impfen"):** Durch gezieltes Einbringen von feinen Partikeln (z.B. Al-Ti-B-Legierungen in Aluminiumschmelzen) werden künstlich heterogene Keimbildungsstellen geschaffen.

Während reine Metalle bei einer festen Temperatur erstarren, ist der Prozess bei Legierungen komplexer und wird durch Zustandsdiagramme beschrieben.
<div class="page-break" style="page-break-before: always;"></div>

## 5. Zustandsdiagramme

Zustandsdiagramme sind essenzielle Werkzeuge für Werkstoffingenieure. Sie fungieren als "Landkarten", die im Gleichgewichtszustand (d.h. bei sehr langsamer Abkühlung) zeigen, welche Phasen (z.B. Schmelze, feste Mischkristalle) in einer Legierung bei einer bestimmten Temperatur und chemischen Zusammensetzung stabil sind.

### 5.1. Systeme mit vollständiger Löslichkeit (Mischkristall)

In Systemen wie Kupfer-Nickel (Cu-Ni) sind die beiden Metalle in jedem Verhältnis sowohl im flüssigen als auch im festen Zustand vollständig ineinander löslich und bilden einen einzigen **Mischkristall**.

- Die **Liquiduslinie** trennt den Bereich der reinen Schmelze vom Zweiphasengebiet (Schmelze + Mischkristall).
- Die **Soliduslinie** trennt das Zweiphasengebiet vom Bereich des vollständig erstarrten Mischkristalls.

Im Gegensatz zu reinen Metallen haben solche Legierungen keinen Schmelzpunkt, sondern einen **Erstarrungsbereich** zwischen Liquidus- und Solidustemperatur.

### 5.2. Das Hebelgesetz

Das Hebelgesetz ist eine mathematische Regel zur Bestimmung der relativen Mengenanteile der beiden Phasen in einem Zweiphasengebiet. Es besagt, dass der Massenanteil einer Phase proportional zur Länge des "gegenüberliegenden Hebelarms" auf der Konoden (horizontale Temperaturlinie) ist.

### 5.3. Systeme mit begrenzter Löslichkeit (Eutektikum)

Viele Legierungssysteme, wie Blei-Zinn (Pb-Sn), weisen nur eine begrenzte Löslichkeit der Komponenten im festen Zustand auf. Dies führt zu komplexeren Diagrammen mit besonderen Merkmalen:

- **Eutektikum:** Ein Punkt im Diagramm, der eine spezifische Legierungszusammensetzung und Temperatur definiert. Bei dieser **eutektischen Temperatur** erstarrt die Schmelze mit eutektischer Zusammensetzung direkt zu einem feinen Gemisch aus zwei festen Phasen (α + β), ohne einen Erstarrungsbereich zu durchlaufen.
- **Eutektische Reaktion:** Der isotherme (bei konstanter Temperatur) Zerfall der Schmelze in zwei feste Phasen: `Schmelze → α + β`. Das resultierende Gefüge ist oft lamellar.
<div class="page-break" style="page-break-before: always;"></div>

### 5.4. Weitere Reaktionen und Phasen

- **Peritektische Reaktion:** Eine weitere isotherme Reaktion, bei der eine feste Phase (α) mit der Schmelze reagiert, um eine neue feste Phase (β) zu bilden: `Schmelze + α → β`. Eine Eselsbrücke lautet hierzu: **„Peri = Darum Herum“**, da sich die neue Phase β um die bereits vorhandene Phase α bildet.
- **Intermetallische Phase:** Eine chemische Verbindung zwischen zwei oder mehr Metallen mit einer eigenen, oft komplexen Kristallstruktur und stöchiometrischen Zusammensetzung. Diese Phasen sind typischerweise sehr hart und spröde.

### 5.5. Nichtgleichgewichtserstarrung

Zustandsdiagramme gelten streng genommen nur für unendlich langsame Abkühlungen. In der Praxis kühlen Bauteile schneller ab, sodass Diffusionsprozesse nicht vollständig ablaufen können. Dies führt zu Konzentrationsunterschieden im Gefüge, einem Phänomen, das als **Seigerung** bekannt ist. Die zuerst erstarrten Bereiche sind reicher an der höher schmelzenden Komponente, während die zuletzt erstarrte Restschmelze an der niedriger schmelzenden Komponente angereichert ist.

Die in den Zustandsdiagrammen dargestellten Phasen und Gefüge sind nicht statisch. Das folgende Kapitel beleuchtet, wie diese Mikrostrukturen durch gezielte thermomechanische Prozesse manipuliert werden, um die mechanischen Eigenschaften über **Ver- und Entfestigungsmechanismen** gezielt einzustellen.
<div class="page-break" style="page-break-before: always;"></div>

## 6. Mechanismen der Ver- und Entfestigung

Die mechanischen Eigenschaften von metallischen Werkstoffen, insbesondere ihre Festigkeit und Zähigkeit, sind keine festen Größen. Sie können durch gezielte Prozesse, die die Mikrostruktur verändern, maßgeschneidert werden. Diese Prozesse werden in Verfestigungs- (Festigkeitssteigerung) und Entfestigungsmechanismen (Wiederherstellung der Verformbarkeit) unterteilt.

### 6.1. Verfestigungsmechanismen (Festigkeitssteigerung)

Alle Verfestigungsmechanismen beruhen auf dem Prinzip, die Bewegung von Versetzungen im Kristallgitter zu behindern.

| Mechanismus              | Physikalisches Prinzip                                                                                                                                        | Besonderheit                                                                                                                                     |
| ------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Kaltverfestigung**     | Erhöhung der Versetzungsdichte durch plastische Verformung. Versetzungen behindern sich gegenseitig.                                                          | Führt zu einer Abnahme der Duktilität. Kann durch Glühen rückgängig gemacht werden.                                                              |
| **Mischkristallhärtung** | Einlagerung von Fremdatomen (substitutionell oder interstitiell), die das Gitter verspannen und die Versetzungsbewegung erschweren.                           | Grundlegender Mechanismus in fast allen Legierungen.                                                                                             |
| **Ausscheidungshärtung** | Bildung fein verteilter, kohärenter Teilchen einer zweiten Phase im Matrixgitter durch eine gezielte Wärmebehandlung (Lösungsglühen, Abschrecken, Auslagern). | Sehr effektiver Mechanismus, zentral für hochfeste Al-Legierungen. Bei Überalterung (zu lange/heiße Auslagerung) nimmt die Festigkeit wieder ab. |
| **Dispersionshärtung**   | Einlagerung von thermisch stabilen, inkohärenten Fremdpartikeln (z.B. Oxide) in die Matrix (oft pulvermetallurgisch).                                         | Behält die Festigkeit auch bei sehr hohen Temperaturen bei, da sich die Partikel nicht auflösen.                                                 |
| **Feinkornhärtung**      | Blockade der Versetzungsbewegung an Korngrenzen. Je kleiner das Korn, desto mehr Korngrenzen existieren.                                                      | **Einziger Mechanismus, der gleichzeitig Festigkeit und Zähigkeit steigert.** Die Beziehung wird durch die Hall-Petch-Gleichung beschrieben.     |
<div class="page-break" style="page-break-before: always;"></div>

### 6.2. Entfestigungsmechanismen (Glühverfahren)

Glühverfahren sind Wärmebehandlungen, die darauf abzielen, die Effekte der Verfestigung (insbesondere Kaltverfestigung) rückgängig zu machen oder unerwünschte Gefügezustände zu beseitigen.

- **Erholungsglühen (Spannungsarmglühen):**
    - **Ziel:** Abbau von Eigenspannungen, die durch Bearbeitung oder ungleichmäßige Abkühlung entstanden sind, ohne die Festigkeit stark zu reduzieren.
    - **Mechanismus:** Bei relativ niedrigen Temperaturen (< 0,4 Tₛ) ordnen sich Versetzungen neu an und annihilieren teilweise. Es findet keine Neubildung von Körnern statt.
- **Rekristallisationsglühen:**
    - **Ziel:** Wiederherstellung der Duktilität und des Umformvermögens eines kaltverformten Werkstoffs.
    - **Mechanismus:** Bei höheren Temperaturen (ca. 0,4 Tₛ) bilden sich neue, versetzungsarme Körner im verformten Gefüge, die anschließend wachsen und die alte Struktur vollständig ersetzen.
- **Diffusionsglühen (Homogenisieren):**
    - **Ziel:** Beseitigung von chemischen Inhomogenitäten (Seigerungen), die bei der Erstarrung entstanden sind.
    - **Mechanismus:** Langzeitiges Glühen bei sehr hohen Temperaturen (knapp unter der Solidustemperatur), um den Konzentrationsausgleich durch Diffusion zu ermöglichen.

Diese Mechanismen sind von zentraler Bedeutung für die wichtigste und meistverwendete Werkstoffgruppe, die Stähle.
<div class="page-break" style="page-break-before: always;"></div>

## 7. Stahl: Herstellung, Fe-C-Diagramm und Einteilung

Stahl, eine Legierung aus Eisen und Kohlenstoff (C-Gehalt < 2,06%), ist der mit Abstand wichtigste und meistverwendete metallische Werkstoff. Seine Popularität verdankt er seiner Vielseitigkeit, den guten mechanischen Eigenschaften und seiner vergleichsweise kostengünstigen Herstellung.

### 7.1. Stahlherstellung

Die moderne Stahlproduktion ist ein mehrstufiger Prozess, der von Eisenerz zu fertigem Stahl führt:

1. **Roheisenerzeugung:** Im **Hochofen** wird Eisenerz zusammen mit Koks und Zuschlägen erhitzt. Der Koks dient als Brennstoff und Reduktionsmittel, um den Sauerstoff aus dem Eisenerz zu entfernen. Das Ergebnis ist flüssiges, kohlenstoffreiches Roheisen (C-Gehalt 3-5%).
2. **Rohstahlherstellung (Frischen):** Das spröde Roheisen wird zu zähem Stahl weiterverarbeitet, indem der überschüssige Kohlenstoff und andere Begleitelemente durch Oxidation entfernt werden. Dies geschieht hauptsächlich im **Sauerstoff-Konverter (LD-Verfahren)** durch Einblasen von reinem Sauerstoff oder im **Elektroofen** durch Einschmelzen von Stahlschrott.
3. **Sekundärmetallurgie & Vergießen:** In der Pfannenbehandlung wird die Schmelze veredelt. Hier werden die finale chemische Zusammensetzung durch Zulegieren exakt eingestellt und unerwünschte Elemente wie Schwefel oder Gase entfernt. Anschließend wird der flüssige Stahl meist im **Stranggussverfahren** zu Brammen oder Knüppeln vergossen.

### 7.2. Das Eisen-Kohlenstoff (Fe-C) Diagramm

Das Fe-C-Diagramm ist das wichtigste Zustandsdiagramm in der Werkstofftechnik. Es beschreibt die Phasen und Gefüge, die sich in Eisen-Kohlenstoff-Legierungen im Gleichgewichtszustand einstellen.

- **Phasen:**
    - **Ferrit (α-Fe):** Kubisch-raumzentrierte (krz) Struktur, magnetisch, weich und duktil, mit sehr geringer Löslichkeit für Kohlenstoff.
    - **Austenit (γ-Fe):** Kubisch-flächenzentrierte (kfz) Struktur, unmagnetisch, gut verformbar, mit hoher Löslichkeit für Kohlenstoff (bis 2,06%). Existiert nur bei hohen Temperaturen.
    - **Zementit (Fe₃C):** Eine **intermetallische Phase** (Eisenkarbid), die sehr hart und spröde ist.
- **Eutektoide Reaktion:** Bei 723°C und einem Kohlenstoffgehalt von 0,8% wandelt sich der Austenit vollständig in ein feines, lamellares Gemisch aus Ferrit und Zementit um. Dieses Gefüge wird **Perlit** genannt. `Austenit → Ferrit + Zementit`.
- **Gefüge bei Raumtemperatur:**
    - **Untereutektoide Stähle (< 0,8% C):** Das Gefüge besteht aus Ferritkörnern und Perlitinseln.
    - **Eutektoider Stahl (= 0,8% C):** Das Gefüge besteht zu 100% aus Perlit.
    - **Übereutektoide Stähle (> 0,8% C):** Das Gefüge besteht aus Perlitkörnern, die von einem Netzwerk aus Zementit an den ehemaligen Austenitkorngrenzen umgeben sind.

### 7.3. Einteilung und Bezeichnung von Stählen

Die Vielfalt der Stähle erfordert ein systematisches Bezeichnungssystem. Nach DIN EN 10027-1 werden Stähle durch Kurznamen klassifiziert:

| Gruppe                                               | Bezeichnungslogik                                                                                                                                                                              | Beispiel                                                                      |
| ---------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------- |
| **1. Baustähle**                                     | Beginnt mit 'S' (Stahlbau), gefolgt von der Mindeststreckgrenze in N/mm².                                                                                                                      | **S235JR**: Baustahl mit 235 N/mm² Mindeststreckgrenze.                       |
| **2. Unlegierte Stähle nach C-Gehalt**               | Beginnt mit 'C', gefolgt vom 100-fachen mittleren Kohlenstoffgehalt.                                                                                                                           | **C45**: Unlegierter Stahl mit ca. 0,45% Kohlenstoff.                         |
| **3. Niedriglegierte Stähle (< 5% Leg.elemente)**    | Beginnt mit dem 100-fachen C-Gehalt, gefolgt von den chem. Symbolen der Hauptlegierungselemente und deren Gehalten, die mit normierten Faktoren multipliziert sind (z.B. Faktor 4 für Mn, Cr). | **16MnCr5**: Stahl mit 0,16% C, Mangan und Chrom als Hauptlegierungselemente. |
| **4. Hochlegierte Stähle (≥ 5% eines Leg.elements)** | Beginnt mit 'X', gefolgt vom 100-fachen C-Gehalt, den chem. Symbolen und den direkten Prozentangaben der Legierungselemente.                                                                   | **X10CrNi18-8**: Nichtrostender Stahl mit 0,10% C, 18% Chrom und 8% Nickel.   |

Die im Fe-C-Diagramm gezeigten Gleichgewichtsgefüge können durch gezielte Wärmebehandlung grundlegend verändert werden, um ein breites Spektrum an Eigenschaften zu erzielen.
<div class="page-break" style="page-break-before: always;"></div>

## 8. Wärmebehandlung und Oberflächenhärtung von Stahl

Die Wärmebehandlung ist ein entscheidender Prozessschritt, um die mechanischen Eigenschaften von Stahlbauteilen gezielt für ihren jeweiligen Einsatzzweck zu optimieren. Sie umfasst kontrollierte Erwärmungs- und Abkühlzyklen, um das Gefüge zu verändern.

### 8.1. Glühverfahren

Glühen bezeichnet eine Wärmebehandlung mit langsamem Erwärmen, Halten auf Temperatur und langsamem Abkühlen. Jedes Verfahren hat ein spezifisches Ziel:

- **Normalglühen:** Erzeugung eines gleichmäßigen, feinkörnigen Gefüges zur Verbesserung der mechanischen Eigenschaften (Festigkeit und Zähigkeit).
- **Weichglühen:** Umwandlung des lamellaren Zementits (in Perlit) in eine kugelige Form, um die Härte zu reduzieren und die Zerspanbarkeit, insbesondere bei kohlenstoffreichen Stählen, zu verbessern.
- **Rekristallisationsglühen:** Beseitigung der Kaltverfestigung nach einer Umformung, um die Duktilität für weitere Umformschritte wiederherzustellen.
- **Spannungsarmglühen:** Reduzierung von inneren Eigenspannungen (z.B. aus Schweiß- oder Zerspanungsprozessen) bei relativ niedrigen Temperaturen, um Verzug zu minimieren.
- **Grobkornglühen:** Einsatz bei C-armen Stählen, um eine bessere Spanbarkeit durch Erzeugung eines kurzbrechenden Spans zu erhalten.

### 8.2. Härten und Anlassen

Diese Verfahren zielen auf eine maximale Festigkeits- und Härtesteigerung ab und basieren auf der Umgehung der Gleichgewichtsumwandlungen des Fe-C-Diagramms.

- **Härten:** Der Prozess besteht aus zwei Schritten:
    1. **Austenitisieren:** Erwärmen des Stahls in das Austenitgebiet, um den Kohlenstoff im kfz-Gitter zu lösen.
    2. **Abschrecken:** Sehr schnelles Abkühlen (in Wasser, Öl oder Luft), das die diffusionsgesteuerte Bildung von Ferrit und Perlit unterdrückt. Stattdessen klappt das Gitter diffusionslos in eine tetragonal verzerrte, mit Kohlenstoff zwangsgelöste Struktur um. Dieses Gefüge nennt man **Martensit**. Es ist extrem hart, aber auch sehr spröde.
- **Anlassen:** Ein auf das Härten folgender Erwärmungsschritt auf moderate Temperaturen (z.B. 200-600°C). Ziel ist es, die extreme Sprödigkeit des Martensits zu reduzieren und die Zähigkeit zu erhöhen. Dabei wird ein Teil der Härte und Festigkeit kontrolliert "geopfert".<div class="page-break" style="page-break-before: always;"></div>

- **Vergüten:** Dies ist die Kombination aus Härten und anschließendem Anlassen auf höhere Temperaturen (z.B. 500-700°C). Das Ziel ist nicht maximale Härte, sondern ein optimaler Kompromiss aus hoher Festigkeit und guter Zähigkeit, wie er für dynamisch beanspruchte Bauteile erforderlich ist.

### 8.3. Verfahren der Oberflächenhärtung

Für viele Bauteile (z.B. Zahnräder) ist es ideal, eine sehr harte, verschleißfeste Oberfläche mit einem zähen, stoßunempfindlichen Kern zu kombinieren. Dies wird durch die Randschichthärtung erreicht.

| Verfahrenstyp      | Prinzip & Beispiele                                                                                                                                                                                                                                                                                        |
| ------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Thermochemisch** | **Prinzip:** Änderung der chemischen Zusammensetzung der Randschicht durch Eindiffundieren von Elementen bei hoher Temperatur.<br>**Beispiele:**<ul><li>**Einsatzhärten** (Anreicherung mit Kohlenstoff - _Aufkohlen_)</li><li>**Nitrieren** (Anreicherung mit Stickstoff - _Aufsticken_)</li></ul>        |
| **Thermisch**      | **Prinzip:** Keine Änderung der chemischen Zusammensetzung. Nur die Randschicht wird lokal kurzzeitig austenitisiert und dann abgeschreckt.<br>**Beispiele:**<ul><li>**Induktionshärten** (Erwärmung durch ein magnetisches Wechselfeld)</li><li>**Flammhärten** (Erwärmung mit einer Gasflamme)</li></ul> |
<div class="page-break" style="page-break-before: always;"></div>

### 8.4. Vergleich: Vergüten vs. Einsatzhärten

Dies sind zwei der wichtigsten Wärmebehandlungsverfahren mit fundamental unterschiedlichen Zielen und Ergebnissen.

|                | **Vergüten**                                                                                                       | **Einsatzhärten**                                                                                                                 |
| -------------- | ------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------- |
| **Ziel**       | Homogenes Eigenschaftsprofil (hohe Festigkeit & Zähigkeit) über das gesamte Bauteilvolumen.                        | Harte, verschleißfeste Randschicht und ein zäher Kern (Verbundcharakter).                                                         |
| **Ansatz**     | Durchhärtung des Bauteils. C-Gehalt > 0,3% erforderlich. Legierungselemente steuern die Einhärtungstiefe.          | Aufkohlung einer kohlenstoffarmen Randschicht, gefolgt von Härten. Kern bleibt zäh.                                               |
| **Werkstoffe** | Vergütungsstähle mit mittlerem C-Gehalt (ca. 0,3 - 0,6%), z.B. **C45**, **42CrMo4**.                               | Einsatzstähle mit niedrigem C-Gehalt (< 0,25%), z.B. **16MnCr5**.                                                                 |
| **Anwendung**  | Dynamisch hoch beanspruchte Bauteile, die durch den gesamten Querschnitt tragen, z.B. Kurbelwellen, Pleuelstangen. | Bauteile mit hoher Oberflächenbeanspruchung (Verschleiß, Wälzbelastung) und Stoßbelastung im Kern, z.B. Zahnräder, Getriebeteile. |
