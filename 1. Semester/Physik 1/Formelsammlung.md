## 1.0 Kinematik: Beschreibung von Bewegungen

### 1.1 Geradlinige Bewegung
Die Kinematik beschreibt die Bewegung von Körpern im Raum, ohne die Ursachen (Kräfte) zu betrachten. Die grundlegendsten Fälle sind die gleichförmige und die gleichmäßig beschleunigte Bewegung entlang einer Geraden.

| Bewegungsart                           | Zentrale Formeln                                                                                                                | Bedingungen                                    |
| -------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------- |
| **Gleichförmige Bewegung**             | **Weg:** `s(t) = v₀ ∙ t + s₀` <br>**Geschwindigkeit:** `v(t) = v₀` <br>**Beschleunigung:** `a(t) = 0`                           | Geschwindigkeit ist konstant. <br>`v = konst.` |
| **Gleichmäßig beschleunigte Bewegung** | **Weg:** `s(t) = ½ ∙ a₀ ∙ t² + v₀ ∙ t + s₀` <br> **Geschwindigkeit:** `v(t) = a₀ ∙ t + v₀` <br> **Beschleunigung:** `a(t) = a₀` | Beschleunigung ist konstant. <br>`a = konst.`  |
### 1.2 Gekrümmte Bewegung & Kreisbewegung
Bewegungen auf gekrümmten Bahnen sind immer beschleunigte Bewegungen, selbst wenn die Bahngeschwindigkeit (der Betrag des Geschwindigkeitsvektors) konstant bleibt. Dies liegt daran, dass der Geschwindigkeitsvektor seine Richtung kontinuierlich ändert, was per Definition eine Beschleunigung darstellt. Diese Beschleunigung lässt sich in zwei Komponenten zerlegen.

- **Tangentialbeschleunigung** `a_t`: Beschreibt die Änderung des _Betrags_ der Geschwindigkeit. `a_t = d|v|/dt`
- **Normal-/Radialbeschleunigung** `a_n`: Beschreibt die Änderung der _Richtung_ der Geschwindigkeit. Sie steht senkrecht auf der Bahn und zeigt zum Krümmungsmittelpunkt. `a_n = |v|²/ρ` (wobei `ρ` der Krümmungsradius der Bahn ist)
<div class="page-break" style="page-break-before: always;"></div>

#### Formeln der Kreisbewegung
Für den Spezialfall der Kreisbewegung (konstanter Radius `r = ρ`) gelten folgende Zusammenhänge:

| Größe                                                                                          | Formel                | Einheit             |
| ---------------------------------------------------------------------------------------------- | --------------------- | ------------------- |
| **Winkelgeschw.**<br>`ω`<br>Gibt die Änderung des Winkels pro Zeit an.                         | `ω = 2π ∙ f = 2π / T` | `1/s` o.<br>`rad/s` |
| **Bahngeschw.** <br>`v`<br>Geschw. eines Punktes auf der Kreisbahn.                            | `v = ω ∙ r`           | `m/s`               |
| **Radialbeschl.**<br>`a_r`<br>Zeigt zum Kreismittelpunkt (Zentripetalbeschl.).                 | `a_r = v²/r = ω² ∙ r` | `m/s²`              |
| **Tangentialbeschl.** `a_t`<br>Tritt nur bei ungleichmäßiger Kreisbewegung auf (`ω ≠ konst.`). | `a_t = α_φ ∙ r`       | `m/s²`              |

#### Analogie zwischen Translation und Rotation
Viele Gesetze der geradlinigen Bewegung (Translation) lassen sich direkt auf die Drehbewegung (Rotation) übertragen, indem man die entsprechenden Größen austauscht.

| Translation (geradlinig) | Rotation (Kreisbewegung)   |
| ------------------------ | -------------------------- |
| Weg `s`                  | Winkel `φ`                 |
| Geschwindigkeit `v`      | Winkelgeschwindigkeit `ω`  |
| Beschleunigung `a`       | Winkelbeschleunigung `α_φ` |
| Masse `m` (Trägheit)     | Massenträgheitsmoment `J`  |
| Kraft `F`                | Drehmoment `M`             |
| Impuls `p`               | Drehimpuls `L`             |

**Gleichmäßig beschleunigte Kreisbewegung** (`α_φ = konst.`):
- **Winkel:** `φ(t) = ½ ∙ α_φ ∙ t² + ω₀ ∙ t + φ₀`
- **Winkelgeschwindigkeit:** `ω(t) = α_φ ∙ t + ω₀`
- **Winkelbeschleunigung:** `α_φ(t) = konst.`
<div class="page-break" style="page-break-before: always;"></div>

## 2.0 Dynamik: Ursachen von Bewegungen
Die Dynamik beschäftigt sich mit den Ursachen von Bewegungsänderungen. Die zentrale Größe hierfür ist die **Kraft**, die einem Körper eine Beschleunigung erteilt oder ihn verformt.
### 2.1 Newtonsche Axiome und Impuls
Die Grundlage der klassischen Dynamik bilden die Newtonschen Axiome.
- **Dynamisches Grundgesetz:** Die auf einen Körper wirkende Kraft `F` ist proportional zur resultierenden Beschleunigung `a`. Die Proportionalitätskonstante ist die träge Masse `m` des Körpers. `F = m ∙ a`
- **Impuls und allgemeines Grundgesetz:** Der Impuls `p` eines Körpers ist das Produkt aus seiner Masse und seiner Geschwindigkeit. Die Kraft ist allgemeiner definiert als die zeitliche Änderung des Impulses.
    - **Impuls:** `p = m ∙ v`
    - **Allgemeines Grundgesetz:** `F = dp/dt`
- **3. Newtonsches Axiom (Wechselwirkungsgesetz):** Übt ein Körper 1 eine Kraft `F₁₂` auf einen Körper 2 aus, so übt Körper 2 eine gleich große, aber entgegengesetzt gerichtete Kraft `F₂₁` auf Körper 1 aus. `F₁₂ = -F₂₁` (Actio = Reactio)
- **Superpositionsprinzip:** Wirken mehrere Kräfte auf einen Körper, so addieren sich diese vektoriell zur Gesamtkraft `F_ges`. `F_ges = Σ F_i`

#### Trägheitskräfte (Scheinkräfte)
In beschleunigten Bezugssystemen treten für einen mit bewegten Beobachter sogenannte Trägheits- oder Scheinkräfte auf. Sie sind real messbar, wirken stets entgegen der Beschleunigung des Systems und haben keine Gegenkraft im Sinne des 3. Newtonschen Axioms. Sie entstehen nicht durch eine Wechselwirkung zwischen zwei Körpern, sondern aus der Trägheit der Masse im beschleunigten Bezugssystem.

- **Zentrifugalkraft:** `F_z = m ∙ ω² ∙ r` 
  (tritt bei Kreisbewegungen auf und wirkt nach außen)
- **Coriolis-Kraft:** `F_C = 2 ∙ m ∙ (v × ω)` 
  (tritt bei einer Bewegung `v` in einem rotierenden System `ω` auf)
<div class="page-break" style="page-break-before: always;"></div>

### 2.2 Arbeit, Energie und Leistung
Arbeit, Energie und Leistung sind zentrale Größen zur Beschreibung von mechanischen Prozessen. **Arbeit** und **Leistung** sind Prozessgrößen, die einen Vorgang beschreiben, während **Energie** eine Zustandsgröße ist, die die gespeicherte Arbeitsfähigkeit eines Systems charakterisiert.

#### Arbeit
Mechanische Arbeit `W` wird verrichtet, wenn ein Körper durch eine Kraft `F` entlang eines Weges `s` bewegt wird.

- **Allgemeine Definition (variable Kraft):** `W = ∫ F ⋅ ds`
- **Hubarbeit** (Anheben gegen die Schwerkraft): `W_H = m ∙ g ∙ h`
- **Beschleunigungsarbeit** (Änderung der Bewegungsenergie): 
  `W_B = ½ ∙ m ∙ v_end² - ½ ∙ m ∙ v_anf²`
- **Elastische Verformungsarbeit (Spannarbeit)** (Dehnung/Stauchung einer Feder): 
  `W_E = ½ ∙ D ∙ s²` (aus der Ruhelage)

#### Energie und Energieerhaltung
Energie ist die Fähigkeit eines Systems, Arbeit zu verrichten. In der Mechanik unterscheidet man hauptsächlich kinetische und potentielle Energie.

- **Kinetische Energie** (Bewegungsenergie): `W_kin = ½ ∙ m ∙ v²`
- **Potentielle Energie** (Lageenergie im Schwerefeld): `W_pot = m ∙ g ∙ h`
- **Potentielle Energie** (Spannenergie in einer Feder): `W_elast = ½ ∙ D ∙ s²`

**Energiesatz der Mechanik:**
- **Ohne Reibung:** Die mechanische Gesamtenergie eines abgeschlossenen Systems bleibt konstant. `(W_kin + W_pot)_Anfang = (W_kin + W_pot)_Ende`
- **Mit Reibung:** Die Differenz der mechanischen Energie entspricht der verrichteten Reibungsarbeit `W_R`. `(W_kin + W_pot)_Anfang = (W_kin + W_pot)_Ende + W_R`
#### Leistung und Wirkungsgrad
- **Leistung** `P`: Die pro Zeit verrichtete Arbeit.
    - **Definition:** `P = dW/dt`
    - **Praktische Formel:** `P = F ∙ v` (für Kraft parallel zur Geschwindigkeit)
- **Wirkungsgrad** `η`: Das Verhältnis von nutzbarer Arbeit/Leistung `W_N / P_N` zur zugeführten Gesamt-Arbeit/Leistung `W_ges / P_ges`. `η = W_N / W_ges = P_N / P_ges`
<div class="page-break" style="page-break-before: always;"></div>

### 2.3 Stoßvorgänge
Stoßvorgänge sind kurzzeitige Wechselwirkungen zwischen Körpern. In einem abgeschlossenen System (ohne äußere Kräfte) ist der **Gesamtimpuls** eine Erhaltungsgröße, was die Analyse von Stößen ermöglicht.

- **Impulserhaltungssatz (Zwei-Körper-Stoß):** `m₁v₁ + m₂v₂ = m₁v₁' + m₂v₂'` 
  (Die gestrichenen Größen `v'` bezeichnen die Geschwindigkeiten nach dem Stoß.)
#### Stoßarten

| Stoßart                           | Energieerhaltung                                                               | Geschwindigkeiten nach Stoß `v'`                                                                    | Besonderheiten                                                                                                                                                                                 |
| --------------------------------- | ------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Vollkommen unelastischer Stoß** | Kinetische Energie wird in Verformungsarbeit/Wärme umgewandelt (`ΔW_kin ≠ 0`). | Beide Körper bewegen sich gemeinsam weiter: <br>`v₁' = v₂' = v'` <br>`v' = (m₁v₁ + m₂v₂)/(m₁ + m₂)` | Maximaler Energieverlust. Die Körper "kleben" aneinander. `ΔW = m₁m₂/(2(m₁+m₂)) ∙ (v₁ - v₂)²`                                                                                                  |
| **Vollkommen elastischer Stoß**   | Die kinetische Gesamtenergie bleibt erhalten (`ΔW_kin = 0`).                   | `v₁' = ((m₁-m₂)v₁ + 2m₂v₂)/(m₁+m₂)` <br>`v₂' = ((m₂-m₁)v₂ + 2m₁v₁)/(m₁+m₂)`                         | Idealisierter Stoß ohne Energieverlust (z.B. Billardkugeln).                                                                                                                                   |
| **Teilelastischer Stoß**          | Ein Teil der kinetischen Energie geht verloren.                                | Die Geschwindigkeiten hängen von der Stoßziffer `k` ab.                                             | Realer Stoßvorgang. Die Elastizität wird durch die **Stoßziffer** `k` beschrieben (`0 ≤ k ≤ 1`). `k = 0` (unelastisch), `k = 1` (elastisch). <br> `k = sqrt(h₂/h₁)` (Rückprallhöhe / Fallhöhe) |
<div class="page-break" style="page-break-before: always;"></div>

## 3.0 Rotation starrer Körper
Bei der Drehung starrer Körper kann die Masse nicht mehr als einzelner Punkt betrachtet werden, da die Verteilung der Masse um die Drehachse entscheidend ist. An die Stelle der Masse `m` tritt das **Massenträgheitsmoment** `J`. Die kinetische Energie eines rollenden Körpers setzt sich aus dem Translations- und dem Rotationsanteil zusammen.
### 3.1 Rotationsenergie und Massenträgheitsmoment

- **Kinetische Energie der Rotation:** `W_kin,rot = ½ ∙ J ∙ ω²`
- **Gesamte kinetische Energie (Rollbewegung):** 
  `W_kin = W_kin,tr + W_kin,rot = ½ ∙ m ∙ v² + ½ ∙ J ∙ ω²`
- **Massenträgheitsmoment** `J` **(Definition):** `J = ∫ r² dm`
- **Satz von Steiner:** Erlaubt die Berechnung des Trägheitsmoments `J_A` für eine Achse A, die parallel im Abstand `a` zu einer Achse durch den Schwerpunkt (mit Trägheitsmoment `J_S`) verläuft. `J_A = J_S + m ∙ a²` **Wichtiger Sonderfall:** Für einen langen, dünnen Stab, der um ein Ende rotiert, ergibt sich das Trägheitsmoment zu `J_Ende = ⅓ ∙ m ∙ l²`.
#### Trägheitsmomente wichtiger Körper (Achse durch Schwerpunkt S)

| Körperform                                      | Trägheitsmoment `J_S` |
| ----------------------------------------------- | --------------------- |
| **Vollzylinder** (um Symmetrieachse)            | `J_S = ½ ∙ m ∙ R²`    |
| **Langer, dünner Stab** (senkrecht durch Mitte) | `J_S = 1/12 ∙ m ∙ l²` |
| **Vollkugel** (durch Mittelpunkt)               | `J_S = ⅖ ∙ m ∙ R²`    |
### 3.2 Drehmoment und Drehimpuls
Analog zur Kraft `F`, die eine translatorische Beschleunigung verursacht, bewirkt ein **Drehmoment** `M` eine Winkelbeschleunigung (Änderung der Rotation). Der **Drehimpuls** `L` ist das Rotations-Analogon zum Impuls `p`.

- **Drehmoment** `M`**:** `M = r × F`
- **Dynamische Grundgleichung der Rotation:** `M = J ∙ α_φ`
- **Drehimpuls** `L`**:** `L = J ∙ ω`
- **Beziehung Drehmoment und Drehimpuls:** `M = dL/dt`
#### Drehimpulserhaltungssatz
In einem abgeschlossenen System, auf das kein äußeres Drehmoment wirkt 
(`M_ext = 0`), bleibt der Gesamtdrehimpuls `L` konstant. 
`Wenn M_ext = 0, dann L = J ∙ ω = konst.`
Dies führt zu der Beziehung `J₁ω₁ = J₂ω₂`. Eine Verringerung des Trägheitsmoments führt demnach zu einer Erhöhung der Winkelgeschwindigkeit.
<div class="page-break" style="page-break-before: always;"></div>

## 4.0 Mechanische Schwingungen
Eine mechanische Schwingung ist eine zeitlich periodische Bewegung eines Körpers um seine Ruhelage. Die grundlegendste und wichtigste Form ist die **harmonische Schwingung**, die sich durch eine Sinus- oder Kosinusfunktion beschreiben lässt.

### 4.1 Grundbegriffe und Harmonische Schwingung

#### Kenngrößen einer Schwingung

- **Amplitude (**`ŷ` **oder** `A₀`**):** Maximale Auslenkung aus der Ruhelage.
- **Elongation (**`y(t)`**):** Momentane Auslenkung zur Zeit `t`.
- **Schwingungsdauer (**`T`**):** Zeit für eine vollständige Schwingung.
- **Frequenz (**`f`**):** Anzahl der Schwingungen pro Sekunde. `f = 1/T`.
- **Kreisfrequenz (**`ω`**):** `ω = 2π ∙ f = 2π / T`.

#### Harmonische Schwingung

- **Differentialgleichung (DGL) des Federpendels:** `m ∙ ÿ + k ∙ y = 0`
- **Allgemeine Lösung (Orts-Zeit-Gesetz):** `y(t) = ŷ ∙ sin(ωt + φ₀)`
- **Geschwindigkeits-Zeit-Gesetz:** `v(t) = ẏ(t) = ŷ ∙ ω ∙ cos(ωt + φ₀)`
- **Beschleunigungs-Zeit-Gesetz:** `a(t) = ÿ(t) = -ŷ ∙ ω² ∙ sin(ωt + φ₀)`
- **Eigenkreisfrequenz des Federpendels:** `ω = sqrt(k/m)`

### 4.2 Energie der harmonischen Schwingung
Bei einer ungedämpften harmonischen Schwingung wird potentielle Energie periodisch in kinetische Energie umgewandelt und umgekehrt. Die mechanische Gesamtenergie bleibt dabei konstant.

- **Potentielle Energie:** `W_pot(t) = ½ ∙ k ∙ y(t)²`
- **Kinetische Energie:** `W_kin(t) = ½ ∙ m ∙ v(t)²`
- **Gesamtenergie:** `W_ges = W_pot + W_kin = ½ ∙ k ∙ ŷ² = konst.`
<div class="page-break" style="page-break-before: always;"></div>

### 4.3 Spezifische schwingende Systeme

| Pendelart                       | Formel für Schwingungsdauer `T` | Wichtige Annahmen/Bedingungen                                                                                                       |
| ------------------------------- | ------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------- |
| **Federpendel**                 | `T = 2π ∙ sqrt(m/k)`            | Lineares Kraftgesetz, masselose Feder.                                                                                              |
| **Torsionspendel**              | `T = 2π ∙ sqrt(J/D*)`           | Lineares Rückstellmoment. Analogie: `m → J`, `k → D*`.                                                                              |
| **Mathematisches Pendel**       | `T = 2π ∙ sqrt(l/g)`            | Punktmasse an masselosem Faden, **kleine Auslenkung (**`sin φ ≈ φ`**)**. Für große Winkel ist die Schwingung nicht mehr harmonisch! |
| **Physikalisches Pendel**       | `T = 2π ∙ sqrt(J_P / (mgl))`    | Starrer Körper, der um einen Punkt P außerhalb des Schwerpunkts S schwingt (`l` = Abstand P-S). Kleine Auslenkung.                  |
| **Flüssigkeitspendel (U-Rohr)** | `T = 2π ∙ sqrt(l / (2g))`       | `l` = Länge der gesamten Flüssigkeitssäule. Reibungsfrei.                                                                           |
### 4.4 Gedämpfte Schwingung
In realen Systemen führt Reibung zu Energieverlusten, wodurch die Amplitude einer freien Schwingung mit der Zeit abnimmt. Eine häufige Form ist die geschwindigkeitsproportionale Reibungskraft `F_R = -β ∙ ẏ`.

#### Zentrale Gleichungen

- **Differentialgleichung:** `ÿ + 2δẏ + ω₀²y = 0`
    - **Abklingkoeffizient:** `δ = β/(2m)`
    - **Ungedämpfte Eigenkreisfrequenz:** `ω₀ = sqrt(k/m)`
- **Lösungsgleichung (Elongation):** 
  `y(t) = ŷ₀ ∙ e^(-δt) ∙ sin(ω_d ∙ t + φ₀)`
- **Kreisfrequenz der gedämpften Schwingung:** `ω_d = sqrt(ω₀² - δ²)`
- **Logarithmisches Dekrement** `Λ`**:** Ein Maß für die Dämpfung. 
  `Λ = δ ∙ T_d = ln(ŷ_i / ŷ_{i+1})`
<div class="page-break" style="page-break-before: always;"></div>
#### Fallunterscheidung
Je nach Stärke der Dämpfung (`δ`) im Verhältnis zur Eigenfrequenz (`ω₀`) ergeben sich drei Fälle:

1. **Schwingfall (**`δ² < ω₀²`**):** Das System schwingt mit exponentiell abnehmender Amplitude.
2. **Kriechfall (**`δ² > ω₀²`**):** Das System kehrt nach Auslenkung langsam und ohne Schwingung in die Ruhelage zurück (starke Dämpfung).
3. **Aperiodischer Grenzfall (**`δ² = ω₀²`**):** Das System kehrt am schnellstmöglichen Weg ohne Überschwingen in die Ruhelage zurück.

### 4.5 Erzwungene Schwingung und Resonanz
Wird ein schwingfähiges, gedämpftes System durch eine äußere periodische Kraft `F_E(t)`angeregt, spricht man von einer erzwungenen Schwingung. Die äußere Kraft gleicht die Dämpfungsverluste aus und zwingt dem System ihre Frequenz (Erregerfrequenz `ω_E`) auf.

#### Gleichungen und Formeln

- **Differentialgleichung:** `ÿ + 2δẏ + ω₀²y = (F̂_E/m) ∙ cos(ω_E ∙ t)`
- **Amplitude im stationären Zustand:** 
  `ŷ(ω_E) = (F̂_E/m) / sqrt((ω₀² - ω_E²)² + (2δω_E)²)`
- **Phasenverschiebung** (zwischen Erreger und Schwinger): 
  `φ(ω_E) = arctan(2δω_E / (ω₀² - ω_E²))`
- **Resonanzfrequenz** (Frequenz der maximalen Amplitude): 
  `ω_res = sqrt(ω₀² - 2δ²)`
- **Resonanz-Überhöhung** 
  (Verhältnis der Amplitude bei Resonanz zur statischen Auslenkung): 
  `Resonanz-Überhöhung = ŷ_res / ŷ_stat = ω₀² / (2δ ∙ ω_d)`
<div class="page-break" style="page-break-before: always;"></div>

### 4.6 Überlagerung von Schwingungen
Mehrere Schwingungen, die auf einen Körper wirken, überlagern sich nach dem Superpositionsprinzip (vektorielle Addition der Auslenkungen). Ein wichtiger Spezialfall ist die Überlagerung zweier Schwingungen mit sehr ähnlichen Frequenzen.

#### Spezialfall: Schwebung (`ω₁ ≈ ω₂`)
Die Überlagerung zweier harmonischer Schwingungen gleicher Amplitude, deren Frequenzen sich nur geringfügig unterscheiden, führt zu einer **Schwebung**.

- **Resultierende Schwingung:** `x_R(t) ≈ [2ŷ₀ ∙ cos((Δω/2)t)] ∙ sin(ω̄t)`
    - Der erste Term `[...]` beschreibt eine langsam variierende Amplitude.
    - Der zweite Term `sin(...)` beschreibt eine schnelle Schwingung mit der mittleren Frequenz `ω̄ = (ω₁ + ω₂)/2`.
- **Schwebungsdauer** `T_S`**:** Die Zeit zwischen zwei Amplitudenminima. 
  `T_S = 2π / Δω` (wobei `Δω = |ω₁ - ω₂|`)