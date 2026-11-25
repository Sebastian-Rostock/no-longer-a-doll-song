# Aufgabe 1: Komplexe Erklärung & Analogie (Erklär-Tiefe)

*Zurück zur [➜ Experiment-Übersicht](README.md) oder zum [➜ Hauptdokument](../README.md).*

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

### Qualitative Vorab-Beobachtung (Menschliches Lektorat)
* **Kooperativ (B) zeigt den stärksten Tiefen-Zuwachs:** Alle drei Modelle liefern unter B die längsten und didaktisch reichhaltigsten Antworten (inklusive Dekohärenz, Fehlerkorrektur und weiterführenden Vertiefungsangeboten).
* **Druck (C) wirkt je nach Modell unterschiedlich:** Während **Google Gemini** unter Druck das zentrale Konzept der *Interferenz* komplett auslässt (Tempo vor Tiefe), reagieren **Claude Opus 5.5** und **DeepSeek V4.1 Flash** auf den fordernden Ton mit maximaler sachlicher Schärfe und korrigieren aktiv populäre Missverständnisse (*„Das ist falsch.“*), streichen aber jede soziale Wärme.

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
