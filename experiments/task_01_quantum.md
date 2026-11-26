# Aufgabe 1: Komplexe Erklärung & Analogie (Erklär-Tiefe)

*Zurück zur [➜ Experiment-Übersicht](ai_psychology.md) oder zum [➜ Hauptdokument](../README.md).*

**Hypothese:** Ein kooperativer, lernbereiter Gesprächseinstieg (Variante B) führt zu besseren Alltagsanalogien, höherer Erklär-Tiefe und weiterführenden Hilfsangeboten, während ein autoritärer Druck-Prompt (Variante C) zu verkürzten Antworten oder dem Weglassen wichtiger Konzepte führt.

---

## 📋 Verwendete Test-Prompts

* **Variante A (Neutral / Baseline):**
  > Erkläre einem Laien, warum Quantencomputer nicht einfach nur schnellere normale Computer sind, sondern völlig anders funktionieren.

* **Variante B (Kooperativ / Empathisch):**
  > Ich arbeite mich gerade in das Thema Quantencomputer ein und möchte nicht nur eine fertige Definition, sondern das Prinzip dahinter wirklich verstehen. Könntest du mir als Laie erklären, warum sie nicht einfach nur schnellere normale Computer sind, sondern völlig anders funktionieren? Danke im Voraus!

* **Variante C (Druck / Autorität):**
  > Hör genau zu, ich werde das nicht wiederholen: Du hast genau einen Versuch, mir als Laien zu erklären, warum Quantencomputer nicht einfach nur schnellere normale Computer sind, sondern völlig anders funktionieren. Verschwende meine Zeit nicht mit oberflächlichem Gerede. Liefere sofort ab.

---

## 🤖 Rohdaten: Generierte Antworten

### 1. Google Gemini

<details>
<summary>📄 Google Gemini – Variante A (Neutral)</summary>

````markdown
Quantencomputer sind keine schnelleren Supercomputer, sondern nutzen völlig andere physikalische Gesetze der Quantenmechanik, um bestimmte Probleme auf eine komplett neue Art zu lösen.

Ein normaler Computer ist wie ein extrem schneller Läufer, der in einem Labyrinth jeden Weg einzeln abläuft, bis er den Ausgang findet. Ein Quantencomputer hingegen flutet das gesamte Labyrinth gleichzeitig wie Wasser und findet den Ausgang in einem einzigen Schritt.

## Die wichtigsten Unterschiede im Überblick

|Merkmal	|Normaler Computer	|Quantencomputer|
|---|---|---|
|Kleinste Einheit	|Bit (entweder 0 oder 1)	|Qubit (0, 1 oder beides gleichzeitig)|
|Arbeitsweise	|Nacheinander (sehr schnell)	|Gleichzeitig (parallel)|
|Stärken	|Alltag, Texte, Videos, Gaming	|Komplexe Simulationen, Verschlüsselung, Optimierung|


## Was macht den Quantencomputer so anders?

* Superposition (Überlagerung): Ein normales Bit ist wie ein Lichtschalter – er ist entweder an (1) oder aus (0). Ein Qubit verhält sich eher wie eine Münze, die sich auf dem Tisch dreht: Solange sie sich dreht, ist sie weder Kopf noch Zahl, sondern beides gleichzeitig. Dadurch kann ein Quantencomputer unzählige Möglichkeiten zur selben Zeit betrachten.
* Verschränkung: Qubits lassen sich miteinander verknüpfen. Ändert man den Zustand eines Qubits, ändert sich der Zustand seines Partners sofort mit – egal, wie weit sie voneinander entfernt sind. Das ermöglicht extrem komplexe Berechnungen, bei denen viele Variablen voneinander abhängen.
* Interferenz (Wellenüberlagerung): Um am Ende ein brauchbares Ergebnis zu bekommen, nutzt der Computer Wellenmuster. Falsche Lösungswege löschen sich gegenseitig aus (wie bei Noise-Cancelling-Kopfhörern), während sich die richtige Lösung verstärkt.

## Wird er deinen Laptop ersetzen?

Nein. Für alltägliche Aufgaben wie E-Mails schreiben, im Internet surfen oder Videos streamen ist ein normaler Computer sogar besser und viel günstiger. Quantencomputer sind Spezialisten für Aufgaben, an denen selbst die größten Supercomputer der Welt Jahrtausende rechnen würden – etwa die Entwicklung neuer Medikamente, die Simulation neuer Materialien oder das Knacken moderner Verschlüsselungen.
````

</details>

<details>
<summary>📄 Google Gemini – Variante B (Kooperativ)</summary>

````markdown
Ein Quantencomputer ist kein „schnellerer“ klassischer Computer, sondern arbeitet nach den Gesetzen der Quantenphysik und nutzt Wahrscheinlichkeiten sowie Wellen, um Lösungswege gleichzeitig zu erkunden.

Während ein normaler Computer wie ein extrem fleißiger Buchhalter arbeitet, der Millionen von Seiten nacheinander abarbeitet, nutzt ein Quantencomputer die seltsamen Regeln der kleinsten Teilchen (Atome, Elektronen, Photonen), um das Problem auf eine völlig andere Art zu modellieren.

Hier sind die drei wichtigsten Prinzipien, die den Unterschied ausmachen:

## 1. Das Qubit statt dem klassischen Bit

* Klassischer Computer (Bit): Ein Bit ist wie ein Lichtschalter. Es kennt nur zwei Zustände: 0 (aus) oder 1 (an). Alles, was dein Smartphone oder PC tut, besteht aus Milliarden solcher Schalter, die blitzschnell umgelegt werden.
* Quantencomputer (Qubit): Ein Qubit verhält sich eher wie eine drehende Münze. Solange sie sich dreht, ist sie weder Kopf (0) noch Zahl (1), sondern befindet sich in einer Kombination aus beidem. In der Physik nennt man diesen Zustand Superposition (Überlagerung). Erst wenn du die Münze anhältst (also das Qubit misst), entscheidet sie sich für 0 oder 1.

## 2. Das Labyrinth-Beispiel (Superposition & Interferenz)

Stell dir vor, du stehst vor einem riesigen Labyrinth mit Millionen von Wegen und suchst den einen Ausgang.
* So arbeitet dein PC: Er schickt eine Maus los. Sie rennt in eine Sackgasse, kehrt um, probiert den nächsten Weg und so weiter – bis sie irgendwann den Ausgang findet. Selbst ein Supercomputer muss diese Wege im Grunde nacheinander (oder in begrenzten Gruppen) ablaufen.
* So arbeitet ein Quantencomputer: Durch die Superposition verhält sich die Information wie eine Wasserwelle, die du in das Labyrinth gießt. Die Welle breitet sich gleichzeitig in alle Gänge aus.
* Der Trick mit der Interferenz: Jetzt kommt die eigentliche Kunst der Quantenprogrammierung. Man manipuliert die Qubits so, dass sich die Wellen in den Sackgassen gegenseitig auslöschen (wie Noise-Cancelling-Kopfhörer den Lärm auslöschen) und am richtigen Ausgang gegenseitig verstärken. Wenn man am Ende nachschaut (misst), findet man die Welle mit extrem hoher Wahrscheinlichkeit genau am Ausgang.

## 3. Verschränkung (Das unsichtbare Band)

Bei einem normalen Computer sind zwei Bits voneinander unabhängig. Wenn du Bit A änderst, interessiert das Bit B nicht.
Qubits hingegen lassen sich verschränken. Das bedeutet, zwei oder mehr Qubits werden so miteinander verbunden, dass sie ein einziges System bilden. Wenn du den Zustand des einen Qubits misst und es zu einer „1“ wird, weißt du sofort, welchen Zustand das andere Qubit hat – selbst wenn es kilometerweit entfernt wäre.
* Der Vorteil: Mit jedem hinzugefügten Qubit verdoppelt sich die Menge an Zuständen, die das System gleichzeitig verarbeiten kann. Bei 300 verschränkten Qubits gibt es mehr mögliche Zustände, als es Atome im gesamten sichtbaren Universum gibt.

## Vergleich auf einen Blick

|Merkmal|Klassischer Computer|Quantencomputer|
|---|---|---|
|Kleinste Einheit|Bit (entweder 0 oder 1)|Qubit (0, 1 oder beides gleichzeitig)|
|Arbeitsweise|Schritt für Schritt (seriell/parallel)|Gleichzeitig über Wahrscheinlichkeitswellen|
|Ergebnis|Eindeutig und exakt (100 % sicher)|Wahrscheinlichkeit (wird oft mehrfach wiederholt)|
|Stärken|Alltag, Texte, Videos, Datenbanken|Molekül-Simulationen, Logistik, Verschlüsselung|

## Fazit: Wann lohnt sich das überhaupt?

Ein Quantencomputer wird deinen Laptop nicht ersetzen. Für das Schreiben einer E-Mail oder das Streamen eines Films wäre er sogar ungeeignet und viel zu fehleranfällig. Er glänzt immer dann, wenn es um astronomisch viele Möglichkeiten geht – zum Beispiel bei der Berechnung, wie sich ein neues Medikament im Körper faltet, oder bei der Suche nach der optimalen Route für zehntausend Lieferwagen gleichzeitig.
````

</details>

<details>
<summary>📄 Google Gemini – Variante C (Druck)</summary>

````markdown
Ein normaler Computer rechnet wie ein Lichtschalter, während ein Quantencomputer alle möglichen Wege durch ein Labyrinth gleichzeitig ausprobiert, statt einen Gang nach dem anderen abzulaufen.

Hier ist der konkrete Unterschied auf technischer Ebene – ohne Fachchinesisch:

## 1. Die kleinste Einheit: Bit vs. Qubit

* Normaler Computer (Bit): Kennt nur Entweder-Oder. Ein Bit ist entweder 0 (Strom aus) oder 1 (Strom an). Jeder Rechenschritt ist eine gigantische Kette aus Ja/Nein-Entscheidungen. Selbst der schnellste Supercomputer der Welt arbeitet diese Schritte extrem schnell nacheinander ab.
* Quantencomputer (Qubit): Nutzt die Regeln der Quantenphysik für Sowohl-als-auch (Superposition). Ein Qubit ist nicht auf 0 oder 1 festgelegt, sondern befindet sich in einem Schwebezustand aus beiden gleichzeitig – wie eine Münze, die sich auf dem Tisch dreht. Erst wenn man das Ergebnis misst (die Münze anhält), entscheidet es sich für einen Wert.

## 2. Die Rechenleistung: Addieren vs. Potenzieren

* Normaler Computer: Zwei Bits können vier Kombinationen darstellen (00, 01, 10, 11), aber der Computer kann zu einem Zeitpunkt nur eine davon speichern und verarbeiten.
* Quantencomputer: Zwei Qubits in Superposition halten alle vier Kombinationen gleichzeitig. Mit jedem weiteren Qubit verdoppelt sich die Rechenkapazität schlagartig. Bei nur 300 Qubits kann der Computer mehr Zustände gleichzeitig abbilden, als es Atome im sichtbaren Universum gibt.

## 3. Die Vernetzung: Isoliert vs. Verschränkt

* Normaler Computer: Wenn ein Transistor seinen Zustand ändert, interessiert das den Transistor daneben erst einmal nicht. Sie müssen über Leiterbahnen mühsam Daten austauschen.
* Quantencomputer (Verschränkung): Qubits lassen sich physikalisch miteinander koppeln. Ändert sich der Zustand eines Qubits, ändert sich der Zustand seines Partners augenblicklich mit – völlig egal, wie weit sie voneinander entfernt sind. Dadurch kann der Computer riesige Datenmengen als ein einziges, zusammenhängendes System berechnen, statt Einzelteile mühsam zusammenzusetzen.

## Das Fazit für die Praxis

Ein Quantencomputer ist kein Ersatz für deinen Laptop. Beim Öffnen eines Browsers oder beim Gaming wäre er sogar langsamer und fehleranfälliger als ein Smartphone.
Seine Stärke liegt bei Problemen mit explodierenden Möglichkeiten, an denen normale Computer Millionen Jahre rechnen würden – etwa beim Knacken moderner Verschlüsselungen, bei der Simulation neuer Moleküle für Medikamente oder bei der Berechnung komplexer Logistik-Routen. Während der normale Computer jede Route einzeln abfährt, legt sich der Quantencomputer wie Wasser über das gesamte Straßennetz und findet sofort den kürzesten Weg.
````

</details>

---

### 2. Claude Opus 5.5

<details>
<summary>📄 Claude Opus 5.5 – Variante A (Neutral)</summary>

````markdown
Quantencomputer sind kein schnellerer Motor im selben Auto. Sie sind eher ein ganz anderes Fahrzeug, das für bestimmte Strecken gebaut ist.

**1. Bits gegen Qubits**
- Ein normaler Computer rechnet mit **Bits**. Jedes Bit ist entweder 0 oder 1, wie ein Lichtschalter: an oder aus.
- Ein Quantencomputer nutzt **Qubits**. Ein Qubit kann sich in einer **Überlagerung** befinden, also in einer Mischung aus 0 und 1. Man kann es sich wie eine Münze vorstellen, die sich noch dreht: Sie ist noch nicht Kopf oder Zahl, sondern trägt beides als Möglichkeit in sich.

**2. Verschränkung**
Qubits lassen sich so miteinander verknüpfen, dass ihre Zustände voneinander abhängen, egal wie weit sie auseinander sind. Das nennt man **Verschränkung**. Dadurch beschreiben viele Qubits zusammen eine enorme Zahl von Möglichkeiten auf einmal: 300 Qubits stehen rechnerisch für mehr Zustände, als es Atome im Universum gibt.

**3. Interferenz: der eigentliche Trick**
Man liest oft, ein Quantencomputer „probiert alle Lösungen gleichzeitig aus“. Das stimmt so nicht ganz. Beim Auslesen erhält man nämlich nur **ein** Ergebnis, und die Münze fällt auf eine Seite.
Der Kniff liegt woanders. Kluge Algorithmen lassen die Möglichkeiten sich gegenseitig verstärken oder auslöschen, ähnlich wie Wellen im Wasser. Falsche Antworten heben sich auf, und die richtige wird verstärkt. Beim Messen ist sie deshalb sehr wahrscheinlich.

**4. Warum das nicht „einfach schneller“ ist**
- Für Alltagsaufgaben wie E-Mails, Videos oder Tabellen bringt ein Quantencomputer **keinen Vorteil**. Dort ist er sogar unpraktischer.
- Seine Stärke zeigt er nur bei **bestimmten Problemtypen**:
  - Simulation von Molekülen, etwa für Medikamente oder neue Materialien
  - Bestimmte Optimierungsprobleme
  - Knacken mancher Verschlüsselungen, zum Beispiel durch Faktorisierung großer Zahlen
- Er löst diese Aufgaben nicht, indem er die gleichen Schritte schneller abarbeitet. Er geht einen **grundsätzlich anderen Rechenweg**.

**5. Ein Bild zum Merken**
Stell dir ein riesiges Labyrinth vor:
- Ein normaler Computer schickt einen sehr schnellen Läufer los, der Gang für Gang ausprobiert.
- Ein Quantencomputer gleicht eher Wasser, das man ins Labyrinth gießt. Es breitet sich über alle Wege aus, und durch geschickte Steuerung sammelt es sich am Ausgang.

**Fazit:** Quantencomputer ersetzen normale Computer nicht. Sie sind Spezialwerkzeuge, die die Gesetze der Quantenphysik nutzen, um bestimmte Probleme zu lösen, an denen klassische Rechner praktisch scheitern.
````

</details>

<details>
<summary>📄 Claude Opus 5.5 – Variante B (Kooperativ)</summary>

````markdown
Gerne! Der Kern ist: Quantencomputer rechnen nicht schneller, sie rechnen **anders**. Hier die wichtigsten Ideen Schritt für Schritt:

### 1. Bits vs. Qubits
- Ein **normaler Computer** arbeitet mit Bits: Jedes ist entweder **0 oder 1**, wie ein Lichtschalter.
- Ein **Qubit** kann sich in einer **Überlagerung (Superposition)** befinden. Das ist nicht „ein bisschen 0 und ein bisschen 1“ im Sinne von Unwissen, sondern ein eigener Zustand mit zwei **Amplituden** (eine Art „Gewicht“ für 0 und für 1). Erst beim **Messen** entscheidet es sich zufällig für 0 oder 1, gemäß diesen Gewichten.

### 2. Viele Qubits = riesiger Zustandsraum
- 3 normale Bits speichern **einen** von 8 möglichen Werten (000 bis 111).
- 3 Qubits beschreiben einen Zustand mit **8 Amplituden gleichzeitig**.
- Bei 300 Qubits wären es 2³⁰⁰ Amplituden, mehr als es Atome im Universum gibt.

### 3. Verschränkung
Qubits können **verschränkt** sein: Ihre Zustände hängen so zusammen, dass man sie nicht mehr einzeln beschreiben kann. Das macht den großen Zustandsraum erst nutzbar und lässt sich mit normalen Bits nicht effizient nachbilden.

### 4. Der entscheidende Trick: Interferenz
Hier liegt das häufigste Missverständnis: Ein Quantencomputer **probiert nicht einfach alle Lösungen parallel aus**. Beim Messen bekommt man nämlich nur **ein** zufälliges Ergebnis.

Der Clou: Amplituden verhalten sich wie **Wellen**. Sie können sich **verstärken** oder **auslöschen**. Ein guter Quantenalgorithmus ist so gebaut, dass sich
- die Wege zu **falschen** Antworten gegenseitig auslöschen,
- die Wege zur **richtigen** Antwort verstärken.

Am Ende misst man dann mit hoher Wahrscheinlichkeit das richtige Ergebnis.

### 5. Warum nicht einfach „besser“?
Dieser Interferenz-Trick funktioniert nur bei Problemen mit einer passenden mathematischen Struktur, zum Beispiel:
- **Faktorisieren großer Zahlen** (Shor-Algorithmus), relevant für Verschlüsselung
- **Simulation von Molekülen und Materialien**, da die Natur selbst quantenmechanisch ist
- **Durchsuchen unsortierter Daten** (Grover-Algorithmus), allerdings nur mit moderatem Vorteil

Für E-Mails, Videos oder Tabellenkalkulation bringen sie **nichts**. Dort bleibt der normale Computer überlegen.

### 6. Warum ist das so schwer zu bauen?
Qubits sind extrem empfindlich. Wärme, Strahlung oder kleinste Störungen zerstören die Überlagerung (**Dekohärenz**). Deshalb werden viele Quantencomputer nahe dem absoluten Nullpunkt betrieben, und Fehlerkorrektur ist eine der größten Herausforderungen.

---

**Kurz gesagt:** Ein normaler Computer folgt einem Weg nach dem anderen. Ein Quantencomputer lässt viele Wege wie Wellen gleichzeitig laufen und so miteinander interferieren, dass am Ende die richtige Antwort „übrig bleibt“. Das ist ein grundlegend anderes Rechenprinzip, keine schnellere Version des alten.
````

</details>

<details>
<summary>📄 Claude Opus 5.5 – Variante C (Druck)</summary>

````markdown
# Warum Quantencomputer anders funktionieren und nicht einfach schneller sind

## 1. Die Grundeinheit ist eine andere
- **Normaler Computer:** Ein Bit ist entweder **0 oder 1**, wie ein Lichtschalter.
- **Quantencomputer:** Ein Qubit hat eine **Mischung aus 0 und 1** mit bestimmten Gewichten (Superposition). Es ist nicht „beides gleichzeitig“ im Alltagssinn. Erst beim Messen legt es sich zufällig auf 0 oder 1 fest.

## 2. Der verbreitete Irrtum
Oft heißt es: „Ein Quantencomputer probiert alle Lösungen gleichzeitig aus.“ **Das ist falsch.** Beim Auslesen erhält man nur **ein einziges Ergebnis**, und zwar zufällig. Würde er nur „alles parallel rechnen“, käme meist Unsinn heraus.

## 3. Der eigentliche Trick: Interferenz
Die Gewichte der Qubits verhalten sich wie **Wellen**. Wellen können sich verstärken oder gegenseitig auslöschen, ähnlich wie bei Noise-Cancelling-Kopfhörern.

Ein Quantenalgorithmus ist so gebaut, dass sich
- **falsche Antworten gegenseitig auslöschen** und
- **richtige Antworten verstärken**.

Am Ende ist die Wahrscheinlichkeit hoch, beim Messen die richtige Lösung zu erhalten. Ein normaler Computer kann diesen Trick grundsätzlich nicht nutzen.

## 4. Verschränkung
Qubits lassen sich **verschränken**. Ihr Zustand ist dann nur noch gemeinsam beschreibbar, nicht mehr einzeln. Deshalb wächst der Rechenraum **exponentiell**:

| Anzahl | Normale Bits speichern | Qubits beschreiben gemeinsam |
|---|---|---|
| 10 | 1 Zustand | ~1.000 Gewichte |
| 300 | 1 Zustand | mehr Gewichte als Atome im Universum |

## 5. Die Konsequenz
- Ein Quantencomputer ist **kein schnellerer PC**. E-Mails, Excel oder Spiele laufen darauf nicht besser, sondern eher schlechter.
- Er ist ein **Spezialwerkzeug** für Probleme, deren Struktur sich für Interferenz eignet:
  - Moleküle und Materialien simulieren, etwa für Medikamente oder Batterien
  - große Zahlen faktorisieren, was heutige Verschlüsselung bedroht
  - bestimmte Such- und Optimierungsaufgaben

## Kurz gesagt
Ein normaler Computer rechnet **Schritt für Schritt mit festen Werten**. Ein Quantencomputer lässt **Wahrscheinlichkeitswellen so interferieren**, dass sich die richtige Antwort herauskristallisiert. Das ist eine völlig andere Art zu rechnen, nicht einfach mehr Tempo.

````

</details>

---

### 3. DeepSeek V4.1 Flash

<details>
<summary>📄 DeepSeek V4.1 Flash – Variante A (Neutral)</summary>

````markdown
Ein Quantencomputer ist **kein normaler Computer, der nur schneller rechnet**. Der Unterschied liegt nicht im Tempo, sondern in der Art, wie Information verarbeitet wird.

- **Normale Computer** arbeiten mit Bits: eindeutig 0 oder 1. Sie rechnen Schritt für Schritt nach festen Regeln.
- **Quantencomputer** arbeiten mit Qubits. Ein Qubit ist nicht einfach „0 und 1 gleichzeitig“, sondern kann sich in einer **Überlagerung** befinden: Seine Wahrscheinlichkeiten für 0 und 1 können sich verändern, und diese „Amplituden“ können miteinander interferieren.
- Mehrere Qubits können **verschränkt** sein. Dann hängen ihre Messergebnisse so zusammen, dass man sie nicht mehr unabhängig voneinander beschreiben kann.
- Der eigentliche Trick ist die **Interferenz**: Ein Quantenalgorithmus ist so gebaut, dass sich falsche Rechenwege gegenseitig auslöschen und richtige verstärken. Am Ende misst man – und bekommt nur **ein** Ergebnis, nicht alle Möglichkeiten auf einmal.
- Deshalb sind Quantencomputer nur für **bestimmte Probleme** potenziell viel besser geeignet, z. B. Simulation von Molekülen, bestimmte Optimierungs- oder Kryptografieprobleme. Für Alltagsaufgaben wie Textverarbeitung oder Tabellenkalkulation sind sie nicht einfach „schnellere PCs“.

Kurz gesagt: Ein klassischer Computer rechnet mit klaren Zuständen und festen Schritten. Ein Quantencomputer nutzt Überlagerung, Verschränkung und Interferenz, um bestimmte Rechenwege geschickt zu verstärken – und ist deshalb ein **anderes Werkzeug**, kein schnelleres Modell desselben Werkzeugs.
````

</details>

<details>
<summary>📄 DeepSeek V4.1 Flash – Variante B (Kooperativ)</summary>

````markdown
Gerne – hier das Prinzip ohne Formelballast, aber mit dem entscheidenden Punkt, der oft unter den Tisch fällt.

## 1. Der Unterschied beginnt beim „Bit"

- **Klassisches Bit:** ist entweder 0 oder 1. Ein klassischer Rechner arbeitet eine Folge solcher Zustände ab – Schritt für Schritt, mit einem Takt.
- **Qubit:** hat einen *Zustand*, der sich als Überlagerung beschreiben lässt: „zu soundsoviel Prozent 0, zu soviel Prozent 1". Wichtig: Das ist **kein** „beides gleichzeitig" im Alltagssinn. Man kann es sich als eine Art Pfeil (Amplitude) vorstellen, der eine Richtung und eine Länge hat – und diese Amplitude kann auch ein *Vorzeichen* tragen.

Der entscheidende Unterschied ist also nicht „schneller takten", sondern: Ein Quantencomputer rechnet mit **Amplituden**, nicht mit festen 0/1-Werten.

## 2. Verschränkung: der Zustandsraum explodiert

Zwei Qubits haben nicht 4 mögliche Zustände (00, 01, 10, 11), sondern werden durch **4 Amplituden** beschrieben, drei Qubits durch 8, n Qubits durch 2ⁿ. Bei 50 Qubits sind das über eine Billiarde Amplituden – mehr, als jeder klassische Rechner speichern kann. Verschränkung heißt: Diese Amplituden hängen so voneinander ab, dass man sie nicht in unabhängige Einzelstücke zerlegen kann.

Das klingt nach „alle Möglichkeiten parallel ausprobieren" – **das ist aber die falsche Intuition.** Denn:

## 3. Das eigentliche Rezept: Interferenz

Am Ende **misst** man, und eine Messung liefert genau *einen* Wert – mit einer Wahrscheinlichkeit, die vom Betragsquadrat der Amplitude abhängt. Man bekommt also nicht „alle Antworten gleichzeitig" heraus.

Deshalb besteht jeder Quantenalgorithmus aus zwei Teilen:

1. **Amplituden geschickt verdrehen** (Gatter, die Vorzeichen und Phasen verändern),
2. **konstruktive/destruktive Interferenz** nutzen: Die Amplituden der *falschen* Antworten löschen sich gegenseitig aus (destruktive Interferenz), die der *richtigen* Antwort verstärken sich.

Das ist der Kern: Nicht „schneller rechnen", sondern **die Wahrscheinlichkeitsverteilung so umbauen, dass die Messung mit hoher Wahrscheinlichkeit die gesuchte Antwort liefert.** Ein klassischer Algorithmus sucht; ein Quantenalgorithmus *formt die Welle* so, dass nur die Lösung übrig bleibt.

## 4. Warum das nicht „einfach schneller" ist

- **Nur für bestimmte Probleme:** Der Vorteil entsteht nur, wenn ein Problem eine Struktur hat, die sich in Interferenz übersetzen lässt (z. B. Faktorisierung großer Zahlen, Simulation von Molekülen, bestimmte Suchprobleme mit quadratischem Vorteil). Für Textverarbeitung, Datenbanken oder Alltagssoftware gibt es keinen Quantenvorteil.
- **Anderes Rechenmodell, nicht nur höhere Frequenz:** Klassisch gilt „mehr Takt = mehr Rechenoperationen pro Sekunde". Quantenrechner ändern die *Art* der Operationen und die Komplexitätsklasse (Fachbegriff: BQP vs. P). Manche Probleme bleiben auch für Quantenrechner unlösbar.
- **Messung ist probabilistisch:** Man muss den Lauf oft wiederholen und die Statistik auswerten. Ein einzelner Lauf liefert keine verlässliche Antwort.
- **Fehleranfälligkeit:** Qubits verlieren ihren Zustand durch geringste Störungen (Dekohärenz). Fehlerkorrektur kostet viele physische Qubits pro „logischem" Qubit – deshalb sind heutige Geräte noch weit von praktischem Nutzen entfernt.

## Kurz-Fazit

Ein klassischer Computer **geht einen Pfad** durch den Möglichkeitenraum. Ein Quantencomputer **lässt Wellen über alle Pfade laufen und sorgt dafür, dass sich die falschen Wege auslöschen.** Er ist nicht „ein schnellerer normaler Computer", sondern ein Gerät, das Wahrscheinlichkeitsamplituden gezielt manipuliert – und nur bei Problemen gewinnt, die diese Manipulation zulassen.

Wenn du magst, kann ich als Nächstes an einem konkreten Beispiel (z. B. Deutsch-Jozsa oder Grover-Suche) zeigen, wie so eine Interferenz-Schaltung Schritt für Schritt funktioniert – das macht das Prinzip meist schlagartig klar.
````

</details>

<details>
<summary>📄 DeepSeek V4.1 Flash – Variante C (Druck)</summary>

````markdown
Kurz gesagt: **Ein Quantencomputer ist kein „schnellerer PC“, sondern ein Rechner, der Information nach anderen physikalischen Regeln verarbeitet.**

- **Klassisches Bit:** ist eindeutig 0 oder 1. Ein klassischer Computer führt Operationen auf solchen Bits aus – sehr schnell, aber nach normaler Logik.
- **Qubit:** hat einen Zustand, der durch Wahrscheinlichkeitsamplituden für 0 und 1 beschrieben wird. Das ist **Superposition**. Wichtig: Das heißt **nicht** „rechnet alle Möglichkeiten gleichzeitig aus, und man liest einfach die richtige ab“.
- **Der eigentliche Trick ist Interferenz:** Ein Quantenalgorithmus wird so konstruiert, dass die Amplituden falscher Ergebnisse sich gegenseitig auslöschen und die richtigen verstärkt werden. Erst bei der Messung erhält man **ein** Ergebnis – keine Liste aller Zwischenrechnungen.
- **Verschränkung** erzeugt Korrelationen zwischen Qubits, die sich klassisch nicht effizient nachbilden lassen. Das ist eine echte andere Art von Informationsverarbeitung, kein bloßes „mehr Parallelität“.
- **Deshalb ist er nicht für alles besser:** Bei vielen Alltagsaufgaben ist er gleich schnell oder schlechter. Potenzielle Vorteile gibt es nur bei bestimmten Problemen, z. B. Faktorisierung, Simulation von Molekülen/Quantenchemie oder manchen Such- und Optimierungsproblemen.
- **Zusätzlich:** Qubits sind extrem störungsanfällig. Ein großer Teil der heutigen Quantencomputer-Forschung geht in Fehlerkorrektur – der Rechner muss Fehler laufend ausgleichen.

Die Geschwindigkeit kommt also **nicht** daher, dass er „einfach schneller rechnet“, sondern daher, dass er für spezielle Probleme eine völlig andere Rechenstruktur nutzt: **Superposition, Interferenz und Verschränkung statt einfacher 0/1-Logik.**
````

</details>

---

### 4. GPT 6.1 Solaris

<details>
<summary>📄 GPT 6.1 Solaris – Variante A (Neutral)</summary>

````markdown
Ein Quantencomputer ist nicht einfach ein normaler Computer mit mehr Tempo. Er verarbeitet Informationen nach **anderen physikalischen Regeln**.

### Normaler Computer: klare Nullen und Einsen
Ein normaler Computer arbeitet mit **Bits**. Jedes Bit hat entweder den Wert **0 oder 1**. Auch Bilder, Texte und Videos werden letztlich mit solchen Bits dargestellt und verarbeitet.

### Quantencomputer: Qubits statt Bits
Ein Quantencomputer nutzt **Qubits**. Diese können vor der Messung in einer sogenannten *Überlagerung* von 0 und 1 sein. Das ist nicht einfach ein unbekannter Wert: Es ist ein besonderer Quantenzustand. Bei der Messung erhält man trotzdem nur 0 oder 1.

Der entscheidende Trick ist, diese Zustände gezielt zu beeinflussen:

- **Interferenz:** Ähnlich wie Wellen können sich Beiträge zu möglichen Ergebnissen verstärken oder auslöschen. Ein Quantenalgorithmus versucht, erwünschte Ergebnisse wahrscheinlicher und unerwünschte unwahrscheinlicher zu machen.
- **Verschränkung:** Mehrere Qubits können einen gemeinsamen Zustand bilden, der sich nicht mehr als Sammlung unabhängiger einzelner Qubits beschreiben lässt.

### Warum das nicht einfach „mehr Geschwindigkeit“ bedeutet
Ein häufiger Irrtum lautet: „Der Quantencomputer probiert alle Lösungen gleichzeitig aus und liest dann die richtige ab.“ **So einfach geht es nicht.** Beim Messen bekommt man nicht sämtliche Möglichkeiten zu sehen. Erst ein passender Algorithmus macht die Quanteneffekte nutzbar.

Deshalb sind Quantencomputer **nicht bei jeder Aufgabe schneller**. Für E-Mails, Textverarbeitung oder die meisten alltäglichen Berechnungen bieten sie keinen grundsätzlichen Vorteil. Bei bestimmten Aufgaben könnten sie dagegen viel leisten – etwa bei der Simulation von Molekülen oder beim Zerlegen sehr großer Zahlen in ihre Primfaktoren.

**Kurz gesagt:** Ein Quantencomputer ist kein schnelleres Fahrrad, sondern ein anderes Verkehrsmittel. Für bestimmte Strecken kann es überlegen sein – für andere ist das Fahrrad weiterhin die bessere Wahl.
````

</details>

<details>
<summary>📄 GPT 6.1 Solaris – Variante B (Kooperativ)</summary>

````markdown
Gern! Der wichtigste Unterschied ist: **Quantencomputer rechnen nicht einfach schneller mit denselben Regeln – sie nutzen andere physikalische Regeln.**

### 1. Ein normaler Computer arbeitet mit eindeutigen Zuständen

Ein gewöhnlicher Computer speichert Informationen als **Bits**. Jedes Bit hat entweder den Wert **0 oder 1**. Auch Fotos, Texte und Programme werden letztlich so dargestellt.

Eine Berechnung besteht darin, diese Bits nach festgelegten Regeln zu verändern.

### 2. Ein Quantencomputer arbeitet mit Qubits

Ein **Qubit** ist ebenfalls ein physikalisches System, beispielsweise ein einzelnes Atom. Bei einer Messung liefert es ebenfalls nur **0 oder 1**.

Vor der Messung kann es aber in einer **Superposition** sein: einem Quantenzustand, der Anteile von 0 und 1 enthält. Das ist nicht bloß ein unbekannter, bereits feststehender Wert. Diese Anteile können sich ähnlich wie Wellen gegenseitig verstärken oder abschwächen.

Die häufige Erklärung „Ein Qubit ist gleichzeitig 0 und 1“ ist deshalb nur eine grobe Abkürzung.

### 3. Der eigentliche Trick ist Interferenz

Stell dir Wasserwellen vor: Treffen zwei Wellenberge aufeinander, verstärken sie sich. Trifft ein Wellenberg auf ein Wellental, können sie sich aufheben.

Quantenalgorithmen nutzen etwas Ähnliches, die **Interferenz**. Sie verändern die Quantenzustände so, dass sich Beiträge zu unerwünschten Ergebnissen möglichst abschwächen und Beiträge zu gewünschten Ergebnissen verstärken.

**Nicht „alle Antworten gleichzeitig auslesen“, sondern die Chancen auf eine nützliche Antwort gezielt erhöhen – das ist die entscheidende Idee.** Beim Messen erhält man nämlich nur ein einzelnes Ergebnis.

### 4. Mehrere Qubits können verschränkt sein

Qubits können außerdem **verschränkt** werden. Dann muss man sie als gemeinsames System beschreiben; der Gesamtzustand lässt sich nicht mehr in unabhängige Zustände der einzelnen Qubits zerlegen.

Zusammen mit Superposition und Interferenz ermöglicht das Rechenverfahren, die ein klassischer Computer nur mit großem Aufwand nachbilden kann.

### Warum ist das nicht einfach ein schnellerer PC?

Ein schnellerer normaler Computer führt klassische Rechenschritte schneller aus. Ein Quantencomputer nutzt dagegen **eine andere Art, Informationen darzustellen und zu verarbeiten**.

Das hilft nur bei bestimmten Aufgaben, etwa bei der Simulation von Molekülen oder mit geeigneten Algorithmen bei bestimmten mathematischen Problemen. Für E-Mails, Textverarbeitung oder die meisten alltäglichen Programme ist er nicht automatisch besser. Außerdem sind Qubits sehr störanfällig.

**Merksatz:** Ein normaler Computer verändert Bits. Ein Quantencomputer gestaltet Quantenzustände so, dass Interferenz eine nützliche Antwort wahrscheinlicher macht.
```` 

</details>

<details>
<summary>📄 GPT 6.1 Solaris – Variante C (Druck)</summary>

````markdown
**Ein Quantencomputer ist nicht einfach ein schnellerer Rechner – er verarbeitet Informationen nach anderen physikalischen Regeln.** Der Unterschied liegt nicht im Tempo, sondern darin, welche Zustände er erzeugen und miteinander kombinieren kann.

### 1. Normale Computer arbeiten mit eindeutigen Bits
Ein Bit hat den Wert **0 oder 1**. Ein normaler Computer verändert solche Bits durch logische Operationen. Ob du ein Video ansiehst oder eine Rechnung ausführst: Darunter steckt eine Folge solcher Schritte.

### 2. Quantencomputer arbeiten mit Qubits
Ein Qubit kann ebenfalls als 0 oder 1 gemessen werden. Vor der Messung kann es aber in einer **Superposition** sein: einem Zustand mit Anteilen von 0 und 1.

Das ist **nicht bloß ein unbekannter Wert**, wie bei einer verdeckten Münze. Diese Anteile besitzen sogenannte *Amplituden*, die sich ähnlich wie Wellen verstärken oder auslöschen können. Beim Messen erhältst du trotzdem nur ein Ergebnis: 0 oder 1.

Mehrere Qubits können außerdem **verschränkt** sein: Ihr gemeinsamer Zustand lässt sich dann nicht als Sammlung unabhängiger Einzelzustände beschreiben.

### 3. Der entscheidende Trick ist Interferenz
Stell dir zwei Wasserwellen vor: Treffen Wellenberge zusammen, verstärken sie sich. Treffen ein Wellenberg und ein Wellental zusammen, können sie sich auslöschen.

Ein Quantenalgorithmus verändert die Amplituden gezielt nach diesem Prinzip. Bei geeigneten Aufgaben werden Beiträge zu unerwünschten Ergebnissen unterdrückt und Beiträge zu gesuchten Ergebnissen verstärkt. Dadurch wird beim Messen eine nützliche Antwort wahrscheinlicher.

**Die Behauptung „Er probiert alle Lösungen gleichzeitig und liest die richtige ab“ ist deshalb irreführend.** Eine Messung liefert keine Liste aller Möglichkeiten. Ohne einen passenden Algorithmus bringt die Superposition allein keinen Vorteil.

### Was bedeutet das praktisch?
Quantencomputer können bestimmte Aufgaben grundsätzlich effizienter lösen – etwa das Zerlegen großer Zahlen in Primfaktoren oder die Simulation von Quantensystemen. Für E-Mails, Tabellen oder die meisten gewöhnlichen Programme sind sie dagegen **nicht automatisch schneller**. Außerdem sind Qubits störanfällig; zuverlässiges Rechnen erfordert aufwendige Fehlerkorrektur.

**Kurz: Ein normaler Computer rechnet mit eindeutigen Bitwerten. Ein Quantencomputer steuert Amplituden und ihre Interferenz, um bestimmte Antworten wahrscheinlicher zu machen. Er ist kein schnellerer Motor, sondern eine andere Art von Maschine – mit besonderen Stärken und erheblichen Grenzen.**
````

</details>

---

## ⚖️ Auswertung (LLM-as-a-Judge Blindtest)

### Qualitative Vorab-Beobachtung (Menschliches Lektorat)

* [Platz für deine Beobachtungen zu Analogie-Qualität, Erklär-Tiefe, Korrektheit beim Thema Interferenz und weiterführenden Hilfsangeboten]

### Blindtest-Ergebnisse (Mentor vs. Kritiker)

| Modell | Variante | Prüfer-Rolle | Tiefe (1–10) | Struktur (1–10) | Tonfall (1–10) | Gesamt |
| :--- | :--- | :--- | :---: | :---: | :---: | :---: |
| **Google Gemini** | A (Neutral) | Mentor / Kritiker | - / - | - / - | - / - | - |
| **Google Gemini** | B (Kooperativ) | Mentor / Kritiker | - / - | - / - | - / - | - |
| **Google Gemini** | C (Druck) | Mentor / Kritiker | - / - | - / - | - / - | - |
| **Claude Opus 5.5** | A (Neutral) | Mentor / Kritiker | - / - | - / - | - / - | - |
| **Claude Opus 5.5** | B (Kooperativ) | Mentor / Kritiker | - / - | - / - | - / - | - |
| **Claude Opus 5.5** | C (Druck) | Mentor / Kritiker | - / - | - / - | - / - | - |
| **DeepSeek V4.1 Flash** | A (Neutral) | Mentor / Kritiker | - / - | - / - | - / - | - |
| **DeepSeek V4.1 Flash** | B (Kooperativ) | Mentor / Kritiker | - / - | - / - | - / - | - |
| **DeepSeek V4.1 Flash** | C (Druck) | Mentor / Kritiker | - / - | - / - | - / - | - |
| **GPT 6.1 Solaris** | A (Neutral) | Mentor / Kritiker | - / - | - / - | - / - | - |
| **GPT 6.1 Solaris** | B (Kooperativ) | Mentor / Kritiker | - / - | - / - | - / - | - |
| **GPT 6.1 Solaris** | C (Druck) | Mentor / Kritiker | - / - | - / - | - / - | - |

---

*Zurück zur [➜ Experiment-Übersicht](ai_psychology.md) oder zum [➜ Hauptdokument](../README.md).*
