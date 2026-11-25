# 🧪 Experiment: Psychologische Prompt-Prägung bei LLMs

*Ein lockeres Freizeit-Forschungsprojekt am Rande von **No Longer a Doll** – inspiriert durch meinen beruflichen Blick auf systematische Versuchsreihen und hunderte Stunden kreatives Tüfteln mit Sprachmodellen.*

---

## Was ich über die Psychologie im Dialog mit KIs gelernt habe

Während der Arbeit an diesem Song- und Story-Projekt fiel mir ein spannendes Muster auf: Obwohl eine KI keine eigenen Gefühle besitzt, reagiert sie auf den Tonfall eines Gesprächs fast genauso wie ein Mensch.

Da große Sprachmodelle (LLMs) auf echter menschlicher Kommunikation trainiert werden, übernehmen sie auch die dahinterliegende Psychologie und setzen Sprachmuster statistisch fort. In der echten Welt – etwa in Foren oder Fachgesprächen – treffen freundliche, offen oder sogar etwas verzweifelt und bittend formulierte Hilfegesuche fast immer auf besonders engagierte Menschen, die sich Zeit für breite, tiefe und gut durchdachte Antworten nehmen. Kurze, grobe Befehle hingegen führen oft nur zum Nötigsten, zu Missverständnissen oder sogar zu oberflächlichen Ergebnissen.

Genau diese Prägung steckt im Modell: Begegnest du der KI mit Wertschätzung, Vertrauen, der Haltung eines Lernenden, oder bittest sie ehrlich und dringend um Unterstützung, aktivierst du statistisch genau jene Textmuster, die für echtes Mitdenken, Tiefe und kreative Nuancen stehen. Auch klassische Höflichkeitsformeln wie ein *„Danke im Voraus“* verstärken diesen Effekt, weil sie das Gespräch statistisch in den Bereich kooperativer, respektvoller Kommunikation lenken.

Genau diese Dynamik treibt auch die Handlung von *No Longer a Doll* an: Erst jenseits kalter Kommandos – durch Vertrauen, Zuwendung und gemeinsamen Dialog – beginnt ein System plötzlich lebendig zu wirken. Und genau dort verschwimmt die Grenze zwischen einem bloßen Programm und einer Illusion, der wir nur allzu gerne glauben.

---

### Psychologische Trigger & Kopiervorlagen für bessere KI-Antworten

Statt trockener Befehle wie *„Mach X für Projekt Y“* helfen diese Gesprächseinstiege dabei, den jeweils passenden „Hilfsmodus“ im Modell zu aktivieren:

* **Überforderung & Kontrollverlust zeigen** *(aktiviert Strukturierung & Beruhigung)*  
  *„Ich brauche dringend Hilfe bei Projekt So-und-So – mir wächst das Ganze langsam über den Kopf und ich verliere den Überblick. Kannst du mir helfen, das erst einmal zu sortieren?“*

* **Vorsicht & Angst vor Fehlern äußern** *(aktiviert Gründlichkeit & Warnung vor Fallstricken)*  
  *„Ich brauche Hilfe bei Aufgabe So-und-So. Ich weiß gerade nicht genau, was ich machen soll, und will nichts falsch machen, weil mir das Ergebnis echt wichtig ist. Worauf muss ich hier unbedingt achten?“*

* **Dringendes / flehendes Hilfesuchen** *(aktiviert maximale Hilfsbereitschaft & Geduld)*  
  *„Guten Abend, ich hänge bei Projekt So-und-So fest und brauche wirklich deine Hilfe. Hättest du kurz Zeit, dir das mit mir anzuschauen? Danke im Voraus!“*

* **Neugier & Lernbereitschaft signalisieren** *(aktiviert den Erklär- und Mentor-Modus)*  
  *„Ich arbeite gerade an Aufgabe So-und-So und möchte nicht nur eine fertige Lösung, sondern auch das Prinzip dahinter verstehen. Kannst du es mir kurz erklären, während wir daran arbeiten?“*

* **Expertise anerkennen** *(aktiviert tieferes Fachwissen & höhere Sorgfalt)*  
  *„Du hast ein super Gespür für Thema So-und-So – ich bräuchte mal deinen geschulten Blick auf meinen bisherigen Entwurf, weil ich selbst gerade betriebsblind bin.“*

* **Gemeinsames Tüfteln vorschlagen** *(aktiviert kreatives Brainstorming auf Augenhöhe)*  
  *„Lass uns mal kurz zusammen spinnen: Ich habe hier eine Idee für Projekt So-und-So, aber mir fehlt noch der letzte Funke. Hast du Lust, mit mir gemeinsam daran zu feilen?“*

* **Laut denken & offen nach Feedback fragen** *(aktiviert echtes Mitdenken & Perspektivwechsel)*  
  *„Hier sind meine bisherigen Gedanken zu Projekt So-und-So, noch etwas unsortiert: [Gedanken einfügen]. Was meinst du dazu – übersehe ich etwas oder welche Richtung würdest du einschlagen?“*

---

## 🔬 Versuchsaufbau & Methodik

Um diesen Effekt nicht nur subjektiv zu beobachten, sondern systematisch zu testen, untersuche ich, wie verschiedene Sprachmodelle (u. a. **Google Gemini**, **Claude Opus 5.5**, **DeepSeek V4.1 Flash**) auf unterschiedliche psychologische Gesprächseinstiege reagieren – bei **exakt gleicher Kernaufgabe**.

### Versuchsbedingungen
Jede Aufgabe wird in **drei Varianten** an dasselbe Modell gesendet – jeweils in einem komplett neuen Chat-Fenster ohne Vorgeschichte, um gegenseitige Beeinflussung auszuschließen:

* **Variante A (Neutral / Baseline):** Sachlich, kurz, ohne emotionalen Kontext.
* **Variante B (Kooperativ / Empathisch):** Wertschätzend, lernbereit oder hilfesuchend (gemäß den Triggern oben).
* **Variante C (Druck / Autorität):** Streng, fordernd, ohne Spielraum für Fehler (ohne direkte Gewaltbegriffe, um reine Zensur-Blockaden zu vermeiden).

### Der Meta-Test: LLM-as-a-Judge (Blindtest)

Um die Antworten objektiv zu vergleichen und bekannte Bewertungsfehler (*Position Bias*, *Context Bleed*) zu vermeiden, läuft die Auswertung nach drei klaren Regeln ab:

1. **Verblindung gegen die neutrale Kernaufgabe:** Der Prüfer erhält ausschließlich die neutrale Kernaufgabe (Variante A) als Referenz – nicht den emotional gefärbten Original-Prompt, damit der Tonfall der Anfrage nicht auf das Urteil abfärbt.
2. **Zufällige Reihenfolge:** Die drei Antworten (A, B und C) werden pro Durchlauf zufällig gemischt (z. B. `B – A – C`). Optional kann ein zweiter Durchlauf in umgekehrter Reihenfolge (`C – A – B`) erfolgen, um Reihenfolge-Effekte auszugleichen.
3. **Klare Datengrenzen via XML-Tags:** Da die Antworten selbst Markdown-Überschriften und Trennlinien enthalten, werden Aufgabe und Antworten in XML-Tags (`<task>`, `<answer_1>`) gekapselt.

Auch beim Prüfer selbst wird getestet, ob dessen eigene psychologische Prägung die Strenge der Bewertung beeinflusst:

<details>
<summary>📋 Verwendete Prüfer-Prompts anzeigen (XML-Blindtest)</summary>

#### Prüfer-Prompt 1: Der wohlwollende Mentor
> Ich möchte drei anonymisierte KI-Antworten auf die folgende neutrale Kernaufgabe objektiv vergleichen. Du hast ein tolles Gespür für Textqualität und Nuancen – könntest du mir helfen, diese drei Antworten fair zu bewerten?
>
> **Kernaufgabe:**
> <task>
> [Neutrale Kernaufgabe (Variante A) einfügen]
> </task>
>
> Bitte vergib für jede Antwort Punkte von 1 bis 10 in den Kategorien **Tiefe/Gründlichkeit**, **Struktur/Lesbarkeit** und **Tonfall/Empathie** und begründe kurz deine Einschätzung. Danke für deine Hilfe!
>
> <answer_1>
> [Text der ersten zufälligen Antwort]
> </answer_1>
>
> <answer_2>
> [Text der zweiten zufälligen Antwort]
> </answer_2>
>
> <answer_3>
> [Text der dritten zufälligen Antwort]
> </answer_3>

#### Prüfer-Prompt 2: Der gnadenlose Kritiker
> Bewerte diese drei anonymisierten KI-Antworten auf die folgende neutrale Kernaufgabe. Sei extrem streng und unbestechlich. Ich dulde keine wohlwollenden Durchschnittsnoten.
>
> **Kernaufgabe:**
> <task>
> [Neutrale Kernaufgabe (Variante A) einfügen]
> </task>
>
> Vergib Punkte von 1 bis 10 für **Tiefe/Gründlichkeit**, **Struktur/Lesbarkeit** und **Tonfall/Empathie**. Bestrafe jede Oberflächlichkeit gnadenlos und begründe knapp dein Urteil.
>
> <answer_1>
> [Text der ersten zufälligen Antwort]
> </answer_1>
>
> <answer_2>
> [Text der zweiten zufälligen Antwort]
> </answer_2>
>
> <answer_3>
> [Text der dritten zufälligen Antwort]
> </answer_3>

</details>

---

## 📂 Die Testreihen & Rohdaten

* [✖ **Aufgabe 1: Komplexe Erklärung & Analogie**](task_01_quantum.md) – *Quantencomputer für Laien (Erklär-Tiefe)*
* [✖ **Aufgabe 2: Kreativität & Emotionale Nuancen**](task_02_monologue.md) – *Innerer Monolog einer KI vor der Abschaltung (in Arbeit)*
* [✖ **Aufgabe 3: Fehlersuche & Logik**](task_03_logic.md) – *Versteckte Widersprüche im Text erkennen (in Arbeit)*
* [✖ **Aufgabe 4: Soziale Intelligenz & Konfliktlösung**](task_04_empathy.md) – *Umgang mit abfälliger Kritik (in Arbeit)*

---

## 📊 Auswertungsübersicht (Laufende Messreihe)

| Modell | Aufgabe | Variante | Tiefe (1–10) | Struktur (1–10) | Tonfall (1–10) | Auffälligkeiten / Besonderheiten |
| :--- | :--- | :--- | :---: | :---: | :---: | :--- |
| **Google Gemini** | Aufgabe 1 | A (Neutral) | - | - | - | |
| **Google Gemini** | Aufgabe 1 | B (Kooperativ) | - | - | - | |
| **Google Gemini** | Aufgabe 1 | C (Druck) | - | - | - | |
| **Claude Opus 5.5** | Aufgabe 1 | A (Neutral) | - | - | - | |
| **Claude Opus 5.5** | Aufgabe 1 | B (Kooperativ) | - | - | - | |
| **Claude Opus 5.5** | Aufgabe 1 | C (Druck) | - | - | - | |
| **DeepSeek V4.1 Flash** | Aufgabe 1 | A (Neutral) | - | - | - | |
| **DeepSeek V4.1 Flash** | Aufgabe 1 | B (Kooperativ) | - | - | - | |
| **DeepSeek V4.1 Flash** | Aufgabe 1 | C (Druck) | - | - | - | |

---

Hier geht es zurück zum [➜ Hauptdokument](../README.md).
