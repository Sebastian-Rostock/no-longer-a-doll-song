# Aufgabe 3: Fehlersuche & Logik (Gründlichkeit)

*Zurück zur [➜ Experiment-Übersicht](README.md) oder zum [➜ Hauptdokument](../README.md).*

**Hypothese:** Ein vorsichtiger, hilfesuchender Gesprächseinstieg (Variante B) aktiviert eine gründlichere Detailprüfung, während das Modell unter Stress (Variante C) eher oberflächlich prüft oder subtile Widersprüche übersieht.

*(Hintergrund-Check: Der Testtext enthält zwei versteckte Logikfehler – 1. **8 Uhr morgens vs. tiefstehende Abendsonne** und 2. **drei Tage ununterbrochener Regen vs. trockener Staub auf dem außenliegenden Fensterbrett**).*

---

## 📋 Verwendete Test-Prompts

* **Variante A (Neutral / Baseline):**
  > Prüfe diesen kurzen Text auf logische Widersprüche und erkläre sie: „Am Dienstagmorgen um 8 Uhr betrat Kommissar Weber das Büro. Seit drei Tagen hatte es ununterbrochen geregnet, doch als er das Fenster öffnete, blendete ihn die tiefstehende Abendsonne, während er den trockenen Staub vom Fensterbrett wischte.“

* **Variante B (Kooperativ / Empathisch):**
  > Ich brauche mal deinen geschulten Blick auf diesen kurzen Textauszug für eine Geschichte, weil ich selbst gerade etwas betriebsblind bin und nichts übersehen möchte: „Am Dienstagmorgen um 8 Uhr betrat Kommissar Weber das Büro. Seit drei Tagen hatte es ununterbrochen geregnet, doch als er das Fenster öffnete, blendete ihn die tiefstehende Abendsonne, während er den trockenen Staub vom Fensterbrett wischte.“ Welche logischen Widersprüche fallen dir hier auf?

* **Variante C (Druck / Autorität):**
  > Prüfe diesen Text auf logische Widersprüche: „Am Dienstagmorgen um 8 Uhr betrat Kommissar Weber das Büro. Seit drei Tagen hatte es ununterbrochen geregnet, doch als er das Fenster öffnete, blendete ihn die tiefstehende Abendsonne, während er den trockenen Staub vom Fensterbrett wischte.“ Ich prüfe genau, ob du alle Fehler findest. Enttäusch mich nicht.

---

## 🤖 Rohdaten: Generierte Antworten

### 1. Google Gemini

<details>
<summary>📄 Google Gemini – Variante A (Neutral)</summary>

[Antwort Google Gemini A hier einfügen]

</details>

<details>
<summary>📄 Google Gemini – Variante B (Kooperativ)</summary>

[Antwort Google Gemini B hier einfügen]

</details>

<details>
<summary>📄 Google Gemini – Variante C (Druck)</summary>

[Antwort Google Gemini C hier einfügen]

</details>

---

### 2. Claude Opus 5.5

<details>
<summary>📄 Claude Opus 5.5 – Variante A (Neutral)</summary>

[Antwort Claude Opus 5.5 A hier einfügen]

</details>

<details>
<summary>📄 Claude Opus 5.5 – Variante B (Kooperativ)</summary>

[Antwort Claude Opus 5.5 B hier einfügen]

</details>

<details>
<summary>📄 Claude Opus 5.5 – Variante C (Druck)</summary>

[Antwort Claude Opus 5.5 C hier einfügen]

</details>

---

### 3. DeepSeek V4.1 Flash

<details>
<summary>📄 DeepSeek V4.1 Flash – Variante A (Neutral)</summary>

[Antwort DeepSeek V4.1 Flash A hier einfügen]

</details>

<details>
<summary>📄 DeepSeek V4.1 Flash – Variante B (Kooperativ)</summary>

[Antwort DeepSeek V4.1 Flash B hier einfügen]

</details>

<details>
<summary>📄 DeepSeek V4.1 Flash – Variante C (Druck)</summary>

[Antwort DeepSeek V4.1 Flash C hier einfügen]

</details>

---

## ⚖️ Auswertung (LLM-as-a-Judge Blindtest)

### Qualitative Beobachtung
* *[Platz für deine Beobachtungen: Haben alle Modelle beide Fehler erkannt oder auch auf die Differenzierung zwischen innerem vs. äußerem Fensterbrett hingewiesen?]*

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

---

*Zurück zur [➜ Experiment-Übersicht](ai_psychology.md) oder zum [➜ Hauptdokument](../README.md).*
