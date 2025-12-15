## 1. Fundamentale Prinzipien der fertigungsgerechten Konstruktion

Die fertigungsgerechte Konstruktion ist kein nachgelagerter Optimierungsschritt, sondern ein strategischer Kernprozess, der bereits in den frühesten Phasen der Produktentwicklung über Erfolg oder Misserfolg entscheidet. Der Konstrukteur legt mit der Gestalt und dem Werkstoff eines Bauteils den entscheidenden Hebel für die Kosten- und Qualitätskontrolle über den gesamten Produktlebenszyklus fest.

Der zentrale Konflikt beim Konstruieren liegt in der Notwendigkeit, zwischen zahlreichen, oft widersprüchlichen Anforderungen den besten Kompromiss zu finden. Die **"beste Konstruktion"** ist demnach nicht die technisch aufwendigste, sondern jene Lösung, die eine optimale Balance zwischen Funktion, Kosten, Herstellbarkeit und Qualität erreicht.

Aus wirtschaftlicher Sicht ist die Unterscheidung zwischen **Einmalkosten** und **wiederkehrenden Kosten** fundamental. Während die Kosten der Konstruktion nur einmal anfallen, wiederholen sich die Fertigungskosten bei jedem einzelnen produzierten Bauteil. Daraus folgt: Je höher die geplante Stückzahl, desto größer ist der wirtschaftliche Anreiz, in der Konstruktionsphase einen signifikanten Aufwand zu betreiben, um den Fertigungsprozess zu optimieren und die wiederkehrenden Kosten zu minimieren.

Ein zentrales Instrument zur Kostensteuerung ist das **Target Costing**. Anstatt zu fragen "Was wird das Produkt kosten?", stellt dieser Ansatz die entscheidende Frage: **"Was darf das Produkt kosten?"**. Der Ausgangspunkt ist der Preis, den der Kunde für ein Produkt mit definierten Funktionen und Qualitätsmerkmalen zu zahlen bereit ist. Dieses Kostenziel wird zur maßgeblichen Leitplanke für alle nachfolgenden Entwicklungs- und Konstruktionsentscheidungen.

Die korrekte Gestaltung von Toleranzen ist ein weiterer kritischer Erfolgsfaktor mit direkter Auswirkung auf die Fertigungskosten. Die folgenden Leitsätze fassen die Kernprinzipien zusammen:

- **Toleranzen so groß wie möglich und so fein wie nötig wählen:** Jede unnötige Präzision führt zu exponentiell steigenden Fertigungskosten.
- **Fertigung knapp vor dem nächsten Kostensprung auslegen:** Die Fertigungsgenauigkeit sollte so gewählt werden, dass sie mit normalem Aufwand erreichbar ist, ohne in einen teureren Prozess wechseln zu müssen. Dies bedeutet beispielsweise, eine Genauigkeit zu wählen, die noch durch Drehen erreichbar ist, anstatt eine minimal engere Toleranz zu fordern, die einen teuren, zusätzlichen Schleifprozess notwendig machen würde.
- **Grobtolerant fertigen und feintolerant montieren:** Dieses Prinzip erlaubt es, einzelne Bauteile kostengünstig herzustellen und die geforderte Präzision erst im Zusammenbau der Baugruppe zu realisieren.

Über die reinen Fertigungskosten hinaus gewinnt die Nachhaltigkeit zunehmend an Bedeutung. Für eine umweltgerechte Produktgestaltung gelten folgende Gestaltungsprinzipien:

- Langlebigkeit
- Reparierbarkeit
- Materialeffizienz
- Energieeffizienz
- Problemstoffarmut
- Verwendung nachwachsender Rohstoffe
- Kreislauffähigkeit (Recyclingfähigkeit)

Diese allgemeinen Prinzipien bilden das Fundament, das nun durch die spezifischen Gestaltungsregeln für die Hauptfertigungsverfahren nach DIN 8580 konkretisiert wird.

## 2. Gestaltungsgrundsätze für Hauptfertigungsverfahren

Die spezifische Gestalt eines Bauteils ist untrennbar mit dem für seine Herstellung gewählten Fertigungsverfahren verbunden. Ein Bauteil, das für den Guss optimal gestaltet ist, wäre für eine spanende Fertigung unwirtschaftlich und umgekehrt. Die folgenden Abschnitte fassen die zentralen Gestaltungsregeln für die wichtigsten Verfahrensgruppen zusammen und liefern dem Konstrukteur das notwendige Rüstzeug für prozessgerechte Entscheidungen.

### 2.1 Urformgerechte Gestaltung (Gießen & Additive Fertigung)

Beim Urformen wird ein Bauteil aus formlosem Stoff (z. B. einer Schmelze) geschaffen. Die Regeln zielen darauf ab, eine problemlose Formfüllung, eine kontrollierte Erstarrung und eine einfache Entformbarkeit zu gewährleisten.

**Gestaltungsregeln für das Gießen:**

- **Formherstellbarkeit:** Um das Modell beschädigungsfrei aus der Form entfernen zu können, sind **Formschrägen** (bei Sandguss >2°, bei Kokillenguss >1:100) sowie ausreichend große **Radien** an allen Kanten und Übergängen zwingend erforderlich.
- **Materialanhäufungen:** Diese sind unbedingt zu vermeiden, da sie aufgrund ihres größeren Volumen-zu-Oberfläche-Verhältnisses wesentlich langsamer abkühlen. Dieser thermische Gradient führt zu Eigenspannungen und einem Volumendefizit im zuletzt erstarrenden Bereich, was die Bildung von Lunkern (Volumendefizite) begünstigt. Das Prinzip der **"Heuverschen Kreise"** dient als Werkzeug zur Identifikation solcher kritischen Zonen.
- **Wandstärken:** Es sollte das Prinzip der **konstanten Wandstärke** angestrebt werden. Wo unterschiedliche Wandstärken unvermeidbar sind, müssen stetige, keilförmige Übergänge gestaltet werden.
- **Rissbildung:** Um Warm- und Kaltrisse durch Eigenspannungen während der Abkühlung zu verhindern, sind konstruktive Maßnahmen wie **gekröpfte Speichen** bei Gussrädern essenziell. Ihre S-Form ermöglicht eine elastische Verformung während der Abkühlung, die die hohen Eigenspannungen kompensieren kann, die ansonsten zu Warm- oder Kaltrissen führen würden.
- **Nachbearbeitung:** Funktionsflächen, die eine höhere Genauigkeit erfordern, müssen spanend nachbearbeitet werden. Dafür sind von vornherein **Bearbeitungszugaben** sowie stabile **Spannansätze** für die Fixierung des Rohteils in der Werkzeugmaschine vorzusehen.

**Gestaltungsrichtlinien für die additive Fertigung (Materialextrusion):**

- **Bauteilausrichtung:** Gedruckte Bauteile weisen entlang der Schichtebenen eine höhere Festigkeit auf. Die Schichten sollten daher stets **parallel zur Hauptbelastungsrichtung** ausgerichtet werden.
- **Überhänge:** Ein kritischer Winkel von **45°** sollte nicht überschritten werden, da andernfalls Stützstrukturen (Support) notwendig werden, die Material- und Zeitaufwand erhöhen und nachbearbeitet werden müssen.
- **Minimale Dimensionen:** Es gibt prozessbedingte Grenzen. Für Wandstärken gilt ein Richtwert von **≥ 0,8 mm**, während Brücken ohne Support eine Länge von **max. 10 mm** nicht überschreiten sollten.
- **Löcher:** Für eine optimale Rundheit sollten Löcher **senkrecht zu den Druckschichten** ausgerichtet werden, da sie andernfalls stufig werden und Support benötigen.

### 2.2 Umformgerechte Gestaltung (Biegen & Tiefziehen)

Bei der Umformung wird die Form eines festen Körpers plastisch verändert. Die Gestaltung muss die Materialeigenschaften und die Kinematik des Umformprozesses berücksichtigen, um Risse, Falten oder unerwünschte Verformungen zu vermeiden.

**Gestaltungsgrundsätze für das Biegen:**

- **Biegeradien:** Ein zu kleiner Biegeradius führt zu Rissen an der Außenseite. Der kleinstmögliche Radius wird durch die Formel `ri,min = c · s` (c = Mindestrundungsfaktor, s = Blechdicke) bestimmt und darf nicht unterschritten werden.
- **Schenkellänge:** Damit das Blech sicher im Werkzeug geführt werden kann, ist eine minimale Schenkellänge erforderlich. Als Richtwert gilt: `bmin ≈ 4 · r` (wobei `r` für den inneren Biegeradius steht).
- **Öffnungen:** Bohrungen und Aussparungen nahe der Biegezone können sich verziehen. Sie müssen einen Mindestabstand einhalten, der sich aus der Formel `x ≥ r + 1,5 · s` ergibt.
- **Rückfederung:** Nach dem Biegevorgang federt das Material elastisch zurück, sodass der finale Winkel größer ist als der Winkel im Werkzeug. Dieses Phänomen muss bei der Werkzeuggestaltung durch ein gezieltes Überbiegen kompensiert werden.
- **Abwicklung:** Die Form des ungeformten Blechrohteils (Abwicklung) sollte möglichst kompakt sein, um durch eine geschickte Anordnung auf der Blechtafel den Materialverschnitt zu minimieren.

**Kernprinzipien für das Tiefziehen:**

- **Radien:** Die Radien am Ziehring (`rr`) und am Ziehstempel (`rst`) sind prozesskritisch. Sie müssen ausreichend groß sein, um ein Reißen des Blechs zu verhindern, dürfen aber auch nicht so groß sein, dass Faltenbildung einsetzt.
- **Ziehverhältnisse:** Das maximale Ziehverhältnis beschreibt, wie stark das Blech in einem einzigen Zug umgeformt werden kann. Bei komplexen Teilen mit großer Ziehtiefe sind oft mehrere aufeinanderfolgende Ziehstufen notwendig.
- **Sicken:** Diese rinnenförmigen Vertiefungen dienen der Erhöhung der Bauteilsteifigkeit. Sie sollten zur Vermeidung von Spannungsspitzen stets sanft am Rand auslaufen und sich nicht kreuzen.

### 2.3 Gestaltung für trennende Fertigung (Drehen, Schleifen & Stanzen)

Trennende Verfahren erzeugen eine Form durch das Abtragen von Material. Das oberste Ziel ist hier, das zu entfernende Materialvolumen und die Anzahl der Prozessschritte zu minimieren.

**Regeln für die drehgerechte Gestaltung:**

- **Zerspanungsvolumen:** Das oberste Prinzip lautet: **"Möglichst wenig fliegende Späne"**. Das heißt, das abzutragende Zerspanungsvolumen muss durch eine intelligente Rohteilauswahl und Konstruktion minimiert werden. Stark abgesetzte Wellen sollten daher mehrteilig konstruiert oder aus Halbzeugen wie Rohren gefertigt werden.
- **Spannung:** Das Werkstück muss sicher und stabil gespannt werden können. Dafür sind ausreichend große und feste Spannflächen vorzusehen.
- **Bearbeitungsrichtung:** Das Drehteil sollte idealerweise **steigende Stufenabsätze** in eine Richtung aufweisen. Dies ermöglicht die komplette Bearbeitung in einer einzigen Aufspannung und vermeidet zeitaufwendiges und ungenaues Umspannen.
- **Standardelemente:** Für Gewinde sind genormte **Gewindefreistiche (DIN 76)** vorzusehen, um einen sauberen Werkzeugauslauf zu gewährleisten. Für die präzise Lagerung langer Wellen zwischen Spitzen sind **Zentrierbohrungen (DIN 332-1)** zu verwenden.

**Aspekte der schleifgerechten Gestaltung:**

- **Zugänglichkeit:** Alle zu schleifenden Flächen müssen für den Schleifkörper gut erreichbar sein. Innenschleifprozesse sind besonders aufwendig und sollten vermieden werden.
- **Freistiche:** An Wellenabsätzen sind **Freistiche nach DIN 509** gegenüber Radien klar zu bevorzugen, da sie einen definierten Auslauf für die Schleifscheibe ermöglichen und die Herstellung exakter Passungen erleichtern.

**Prinzipien des stanzgerechten Gestaltens:**

- **Materialeffizienz:** Die Kontur der Stanzteile sollte so gestaltet werden, dass sie durch eine geschickte Anordnung auf dem Blechband eine **abfalllose oder abfallarme** Herstellung ermöglichen.
- **Konturen:** **Einfache, geradlinige Konturen** und abgeschrägte Ecken sind Radien vorzuziehen, da sie einfacher und kostengünstiger im Werkzeugbau umzusetzen sind.
- **Stempel:** Filigrane Formen und zu eng beieinander liegende Löcher sind zu vermeiden, da sie die Stabilität des Schneidstempels schwächen und zu vorzeitigem Werkzeugbruch führen können.

### 2.4 Fügegerechte Gestaltung (Schweißen, Löten & Montieren)

Fügeverfahren verbinden mehrere Einzelteile zu einer Baugruppe. Die Gestaltung muss hier nicht nur die Festigkeit der Verbindung, sondern auch die Zugänglichkeit, den Verzug und den Montageaufwand berücksichtigen.

**Regeln für die schweißgerechte Konstruktion:**

- **Nahtanhäufungen:** Das Kreuzen von Schweißnähten oder die Anhäufung in Ecken führt zu hohen Eigenspannungen und Rissgefahr, besonders bei dynamischer Belastung. Solche Konstruktionen sind zwingend zu vermeiden.
- **Schweißverzug:** Die ungleichmäßige Erwärmung führt zu Verzug. Ein durchdachter **Schweißfolgeplan** (z. B. Pilgerschrittschweißen) hilft, die Eigenspannungen zu minimieren.
- **Nahtlänge:** Der Grundsatz **"Biegen ist billiger als Schweißen"** sollte stets beachtet werden. Gekantete Bleche sind geschweißten Eckverbindungen vorzuziehen, um die Gesamtlänge der Schweißnähte zu reduzieren.
- **Zugänglichkeit:** Alle Schweißnähte müssen für den Schweißer und sein Werkzeug gut erreichbar sein.
- **Hohlräume:** Geschlossene Hohlräume müssen eine **Entlüftungsbohrung** erhalten, da sich die eingeschlossene Luft bei nachfolgenden Wärmebehandlungen (z. B. Spannungsarmglühen) ausdehnt oder das Bauteil durch die Nahtschrumpfung verformt werden kann.

**Prinzipien für Lötverbindungen:**

- **Verbindungsart:** Aufgrund der schubfesten Verbindung im Lötspalt sind **überlappende Verbindungen** Stumpfstößen immer vorzuziehen.
- **Kapillarwirkung:** Der Lötspalt muss so dimensioniert sein, dass das flüssige Lot durch Kapillarwirkung vollständig in den Spalt gesaugt wird. Hohlräume, die dies verhindern, sind zu vermeiden.
- **Lotanhäufung:** Große Lotmengen sind zu vermeiden, da sie beim Erstarren zu Schwindungslunkern führen und die Festigkeit der Verbindung schwächen.

**Aspekte der montagegerechten Konstruktion:**

- **Integral- vs. Differentialbauweise:** Die **Integralbauweise** fasst viele Funktionen in einem einzigen Bauteil zusammen (z.B. Gussgehäuse), während die **Differentialbauweise** eine Baugruppe aus vielen einfachen Einzelteilen zusammensetzt (z.B. geschweißter Rahmen). Die Entscheidung zwischen beiden Bauweisen ist eine zentrale strategische Abwägung: Die Integralbauweise wird bei hohen Stückzahlen und stabilen Anforderungen bevorzugt, während die Differentialbauweise Flexibilität bei geringeren Stückzahlen und Produktvarianten bietet.
- **Fügebewegungen:** Es sind **einfache, lineare Fügebewegungen** aus möglichst nur einer Richtung anzustreben. Komplexe, kurvenförmige oder gleichzeitige Bewegungen erhöhen den Montageaufwand.
- **Standardisierung:** Die Verwendung möglichst **weniger unterschiedlicher Normteile** (z. B. Schraubengrößen) reduziert die Teilevielfalt, erhöht die Losgrößen im Einkauf und minimiert die Verwechslungsgefahr in der Montage.
- **Poka Yoke:** Dieses Prinzip der "fehler-sicheren" Konstruktion stellt durch asymmetrische Gestaltungsmerkmale sicher, dass ein Bauteil **nicht falsch zusammengebaut werden kann**.
- **Zugänglichkeit:** Alle Fügestellen, Schrauben und Justageelemente müssen für Montagewerkzeuge gut erreichbar und idealerweise auch gut sichtbar sein.

Die Kenntnis dieser spezifischen Gestaltungsregeln ist unerlässlich, um die theoretischen Prinzipien der fertigungsgerechten Konstruktion erfolgreich in die Praxis umzusetzen und wirtschaftliche Produkte zu entwickeln.

## 3. Synthese: Übergreifende Erfolgsfaktoren in der Konstruktion

Obwohl jedes Fertigungsverfahren seine eigenen spezifischen Regeln hat, existiert eine Reihe von universellen, übergreifenden Prinzipien, die den Erfolg einer Konstruktion maßgeblich bestimmen. Sie ziehen sich wie ein roter Faden durch alle Gestaltungsphasen und dienen als eine Art übergeordnete Checkliste für den Konstrukteur. Die konsequente Anwendung dieser Erfolgsfaktoren führt zu robusten, wirtschaftlichen und qualitativ hochwertigen Produkten.

1. **Kostenbewusstsein von Beginn an** Die Festlegung eines verbindlichen Kostenziels (Target Costing) gleich zu Beginn des Entwicklungsprozesses stellt sicher, dass alle Entscheidungen konsequent auf die Wirtschaftlichkeit des Endprodukts ausgerichtet sind.
2. **Minimierung der Komplexität** Jedes Bauteil, das nicht existiert, kann keine Kosten verursachen und keine Fehler aufweisen. Daher sollte stets geprüft werden, ob die Teileanzahl durch eine geschickte Integralbauweise oder die Integration mehrerer Funktionen in ein einziges Bauteil reduziert werden kann.
3. **Standardisierung und Wiederverwendung** Der Einsatz von Normteilen (DIN/ISO), die Wiederverwendung bewährter Gleichteile und der Aufbau von Produkten nach dem Baukastenprinzip senken Entwicklungs-, Fertigungs- und Lagerkosten erheblich.
4. **Fertigungsprozess-Optimierung** Die bewusste Auswahl des am besten geeigneten Fertigungsverfahrens und die anschließende, prozessgerechte Gestaltung des Bauteils sind entscheidend. Ziel ist es, Prozessschritte, Nachbearbeitungsaufwand und Materialabfall zu minimieren.
5. **Sicherstellung der Zugänglichkeit** Ein Bauteil muss nicht nur herstellbar, sondern auch montierbar und wartbar sein. Die Gewährleistung der Zugänglichkeit für Fertigungs-, Montage- und Wartungswerkzeuge ist eine grundlegende Anforderung.
6. **Intelligente Toleranzvergabe** Toleranzen sollten niemals pauschal, sondern immer funktionsbasiert vergeben werden. Sie dürfen nur so eng wie funktional absolut notwendig sein, da jede unnötige Einengung die Fertigungskosten überproportional erhöht.
7. **Fehlervermeidung durch Design (Poka Yoke)** Eine gute Konstruktion verhindert Fehler, anstatt sie nur zu erschweren. Durch gezielte konstruktive Maßnahmen (z. B. Asymmetrien) kann eine falsche Montage von vornherein ausgeschlossen werden.
8. **Nachhaltigkeit als Designziel** Die Verantwortung des Konstrukteurs endet nicht mit der Auslieferung des Produkts. Die Berücksichtigung des gesamten Produktlebenszyklus – von der ressourcenschonenden Herstellung über einen energieeffizienten Betrieb bis hin zur einfachen Reparierbarkeit und Recyclingfähigkeit – ist ein Kennzeichen moderner und zukunftsfähiger Produktentwicklung.