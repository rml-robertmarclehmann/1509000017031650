# AGENTS.md (Arbeits- und Strukturregeln)

Dieses Dokument definiert die Struktur, Benennung und den Workflow für diese Projektakte.

## 1) Grundprinzipien

- **Trennung von Fakten und Interpretation**
  - Fakten/Belege: reproduzierbar, prüfbar, mit Quelle/Dateiverweis.
  - Interpretation/These: als Hypothese markieren.
- **Ketten der Nachweise (Chain of Custody)**
  - Originaldateien nicht verändern.
  - Wenn Bearbeitung nötig ist, dann als Kopie in einem Unterordner `working/`.
- **Minimierung von Risiken**
  - Keine Veröffentlichung von Zugangsdaten, Tokens, privaten Adressen, Telefonnummern.
  - Personenbezogene Daten, sofern nicht zwingend: schwärzen/anonymisieren.

## 2) Ordnerkonventionen

### Themen
- Pfad: `themen/<thema_slug>/`
- Muss enthalten:
  - `README.md` (Langform)
  - `index.html` (Kurzform + Links)

### Belege
- Pfad: `belege/<thema_slug>/`
- Dateinamen-Schema (empfohlen):
  - `YYYY-MM-DD__kurztitel__quelle__hashhint.ext`

### Indizien
- Pfad: `indizien/<thema_slug>/`
- Inhalte: offene Punkte, Beobachtungen, Hypothesen, Querverweise.

### Timeline
- Pfad: `timeline/`
- Zentrale Datei:
  - `timeline/README.md`

### Links
- Pfad: `links/<thema_slug>/README.md`
- Externe Referenzen mit Datum des Abrufs.

## 3) Markdown-Template (für Vorfälle)

In Themen-READMEs bitte bevorzugt dieses Format nutzen:

- **Datum/Uhrzeit**: 
- **Ort/Kanal** (z.B. Plattform, Gerät, Netzwerk): 
- **Kurzbeschreibung**: 
- **Details**: 
- **Betroffene Systeme/Konten**: 
- **Vermutete Vorgehensweise** (als Hypothese markieren): 
- **Belege** (Dateiverweise): 
- **Indizien** (Dateiverweise): 
- **Offene Fragen / Nächste Schritte**: 

## 4) HTML-Seiten

- Root: `index.html` ist die Übersicht.
- Pro Thema: `themen/<thema_slug>/index.html`
- Jede Themenseite enthält:
  - Kurzüberblick
  - Links (intern/extern)
  - Verweise auf Belege/Indizien-Ordner
