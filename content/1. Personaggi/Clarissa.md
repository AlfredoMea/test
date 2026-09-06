---
publish: true
created: 2026-09-06T15:18:04.416Z
modified: 2026-09-06T15:18:28.477Z
tags:
  - npc
  - fazione/bambini
  - fazione/adulti
  - fazione/loggia
  - antagonista
  - alleato
---

# 👤

> **Fazione:**  | **Residenza:**  | **Ruolo:**

---

## 📌 1. Panoramica & Personalità

- **Descrizione fisica:**
- **Personalità & Modus Operandi:**
- **Obiettivo nel Loop:**
- **Importanza Narrativa:**

---

## ⚖️ 2. Meccaniche Trust & Suspicion

### 🎁 Meccanica `GIVE` (Oggetti)

| Oggetto | Variazione Trust | Reazione / Risposta | Note / Conseguenze |
| :--- | :---: | :--- | :--- |
| `[[Oggetto A]]` | +1 | _"Ah, lo cercavo da tempo..."_ | Sblocca il dialogo sulla Loggia |
| `[[Oggetto B]]` | -1 (Trappola) | _"Perché hai questo? Mi spii?"_ | Incrementa la **Suspicion** |

### 💬 Meccanica `SAY` (Parole Chiave)

- **Parole Chiave Efficaci (`+Trust`):**
  - **`"Parola1"`**: (Condizione: Trust >= 2) — Rivelazione su `[[Luogo]]`.
- **Parole Chiave Pericolose (`+Suspicion` / Trappola):**
  - **`"Parola2"`**: Reagisce in modo ostile, sospetta un complotto.

### 🚨 Indicatori di Sospetto (Suspicion Checks)

- **Cosa fa salire il Sospetto:**
  - Incontrarlo in luoghi riservati senza giustificazione.
  - Sbagliare risposte nei dialoghi chiave.
- **Conseguenze al raggiungimento della Soglia (3):**
  - L'NPC cambia la sua routine (es. si chiude a chiave, avvisa `[[Cop Tucker]]`).

---

## ⏰ 3. Routine nei 3 Giorni (Time Loop)

> [!TIP]
> Questa tabella permette a Dataview e ai plugin Timeline di tracciare la posizione dell'NPC orario per orario.

### 📅 Giorno 1

| Ora | Luogo | Azione / Comportamento | Opportunità per Noah |
| :---: | :--- | :--- | :--- |
| **08:00** | `[[Mappa - Mercato\|Mercato]]` | Compra provviste da `[[Walter]]` | Possibile borseggio della chiave |
| **12:00** | `[[Mappa - Casa\|Casa]]` | Pranzo a porte chiuse | Nessuna interazione visiva |
| **18:00** | `[[Mappa - Chiesa\|Chiesa]]` | Partecipa alla Messa d'Emergenza | Lascia la casa incustodita |

### 📅 Giorno 2

| Ora | Luogo | Azione / Comportamento | Opportunità per Noah |
| :---: | :--- | :--- | :--- |
| **09:00** | `[[Mappa - Scuola\|Scuola]]` | Cerca indizi nell'archivio | Intercettare conversazione |
| **20:00** | `[[Mappa - Bosco\|Bosco]]` | Incontro segreto | Rischio di ingaggio con Nephilim |

### 📅 Giorno 3

| Ora | Luogo | Azione / Comportamento | Opportunità per Noah |
| :---: | :--- | :--- | :--- |
| **11:00** | `[[Mappa - Municipio\|Municipio]]` | Confronto con `[[Sindaco Ermes]]` | Momento chiave prima del reset |

---

## 🗺️ 4. Enigmi e Quest Correlati

- **Quest associata:** `[[Quest - Titolo Quest]]`
- **Enigma chiave:** `[[Enigma - Titolo Enigma]]` (Layer: )
- **Indizio per il Diario di Noah:**

---

## 🔗 5. Relazioni & Rete di Contatti

- `[[NPC 1]]`: Alleato segreto / Scambio di informazioni.
- `[[NPC 2]]`: Nemico / Rivalità nella Loggia.

---

## 📑 6. Dataview Query (Auto-richiamo dati)

### Oggetti correlati a questo NPC

| File | tipo | slot\_inventario |
| ---- | ---- | --------------- |
