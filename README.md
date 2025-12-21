# 🎙️ StVO Teleprompter - Fahrlehrer Inside

**Version 5.0** - Listenansicht | Auswahl-System | Dunkles Design

---

## ✨ Features

### 📝 **Editor mit Listenansicht**
- Alle Paragraphen **dauerhaft sichtbar** in einer Liste
- Status-Icons zeigen was befüllt ist (🔵 StVO | 🟢 VwV | 🟡 Erläuterung | 🟠 Moderationstext)
- Einzeln bearbeiten → öffnet 4-Spalten-Editor
- **Bleibt gespeichert** auch wenn nur 1 Spalte befüllt ist

### 🔄 **GitHub Auto-Sync (NEU!)**
- Beim ersten Öffnen: **Popup für Token-Eingabe**
- Token wird **sicher im Browser** gespeichert
- **Nicht im Code** → Keine GitHub-Warnung!
- Button "🔄 GitHub Sync" zum Speichern
- Perfekt für Team-Zusammenarbeit

### 🎯 **Auswahl-System**
- Checkboxen: Wähle welche Paragraphen in den Teleprompter sollen
- Reihenfolge ändern mit [▲] [▼] Buttons
- Nur ausgewählte Paragraphen werden im Teleprompter angezeigt

### 🎬 **Teleprompter**
- Zeigt **nur ausgewählte** Paragraphen
- In **gewählter Reihenfolge**
- **Alle befüllten Spalten** werden nacheinander angezeigt
- Auto-Scroll, Schriftgröße, Vollbild

### 💾 **Speicherung**
- Automatisch alle 30 Sekunden
- JSON Export/Import für Multi-PC-Nutzung
- **PDF Export** mit Footer auf jeder Seite
- Strg+S zum manuellen Speichern

---

## 🚀 Quick Start

### 🔄 **GitHub Auto-Sync**

**Beim ersten Öffnen erscheint ein Popup:**
```
1. GitHub Token erstellen:
   → https://github.com/settings/tokens
   → "Generate new token (classic)"
   → Scope: ✅ repo
   → Token kopieren

2. Im Popup einfügen:
   → Token eingeben
   → "💾 Speichern & Verbinden"

3. Fertig!
   → Token wird sicher im Browser gespeichert
   → "🔄 GitHub Sync" speichert auf GitHub
   → Alle im Team haben die neuesten Daten!
```

### 1️⃣ **Tool öffnen**
```
https://710deckel.github.io/stvo-teleprompter/
```

### 2️⃣ **Paragraph erstellen**
```
Tab "📝 Editor"
→ Klicke "➕ Neuer Paragraph"
→ Paragraph erscheint in der Liste
```

### 3️⃣ **Bearbeiten**
```
→ Klicke [📝 Bearbeiten] bei einem Paragraph
→ 4-Spalten-Editor öffnet sich
→ Fülle Spalten nach und nach:
  🔵 Erst nur StVO → Speichern
  🟢 Später VwV hinzufügen → Speichern
  🟡 Später Erläuterung → Speichern
  🟠 Später Moderationstext → Speichern
→ Alles bleibt gespeichert!
```

### 4️⃣ **Für Podcast auswählen**
```
Tab "🎯 Auswahl"
→ ☑ Paragraphen anklicken die du vorlesen willst
→ [▲][▼] für Reihenfolge
→ "🎬 Zum Teleprompter"
```

### 5️⃣ **Aufnehmen**
```
Tab "🎬 Teleprompter"
→ Geschwindigkeit einstellen
→ ▶️ Start (oder Leertaste)
→ Ablesen & aufnehmen!
```

### 6️⃣ **PDF exportieren**
```
Tab "📝 Editor"
→ "📄 Als PDF exportieren"
→ PDF wird heruntergeladen
→ Ausdrucken fertig!
   (Footer: FL-BE_07/25_Justin_Lee_Probis)
```

---

## 📖 Detaillierte Anleitung

### **Editor-Tab (📝)**

**Liste der Paragraphen:**
```
┌──────────────────────────────────────────┐
│ § 1 Grundregeln                          │
│ 🔵StVO 🟢VwV 🟡Erl 🟠Mod  [📝 Bearbeiten]│
│                                          │
│ § 2 Straßenbenutzung                     │
│ 🔵StVO ⚫VwV ⚫Erl ⚫Mod  [📝 Bearbeiten]│
└──────────────────────────────────────────┘
```

**Status-Icons:**
- **Farbig** = Spalte ist befüllt
- **Grau** = Spalte ist leer

**Bearbeiten:**
1. Klick auf [📝 Bearbeiten]
2. Modal öffnet sich mit 4 Spalten
3. Fülle beliebige Spalten
4. Klick "💾 Speichern & Schließen"
5. Paragraph bleibt in Liste

---

### **Auswahl-Tab (🎯)**

**Für Teleprompter auswählen:**
```
☑ § 1 Grundregeln          [▲] [▼]
☑ § 2 Straßenbenutzung     [▲] [▼]
☐ § 5 Vorfahrt             [▲] [▼]
```

**Funktionen:**
- **☑ Checkbox** = Paragraph kommt in Teleprompter
- **[▲]** = Nach oben verschieben
- **[▼]** = Nach unten verschieben
- **"🎬 Zum Teleprompter"** = Wechselt direkt zum Teleprompter

---

### **Teleprompter-Tab (🎬)**

**Anzeige:**
```
§ 1 GRUNDREGELN

🟠 MODERATIONSTEXT
(falls befüllt)

🔵 STVO ORIGINAL
(falls befüllt)

🟢 VWV-STVO
(falls befüllt)

🟡 ERLÄUTERUNG
(falls befüllt)

────────────────

§ 2 STRASSENBENUTZUNG
...
```

**Steuerung:**
- **Geschwindigkeit:** 1-10 (empfohlen: 3-5)
- **Schriftgröße:** 18-48px (empfohlen: 24-32)
- **▶️ Start / ⏸️ Pause** (oder Leertaste)
- **⏮️ Zurücksetzen** → scrollt an den Anfang
- **🖥️ Vollbild** → für Aufnahmen

---

## 💡 Workflow-Beispiele

### **Schrittweise Befüllung**

**Tag 1:**
```
1. § 1 erstellen
2. Nur StVO-Text einfügen
3. Speichern
→ Paragraph bleibt mit StVO in Liste
```

**Tag 2:**
```
1. § 1 bearbeiten
2. VwV hinzufügen
3. Speichern
→ Paragraph jetzt mit StVO + VwV
```

**Tag 3:**
```
1. § 1 bearbeiten
2. Erläuterung schreiben
3. Speichern
→ Paragraph jetzt mit StVO + VwV + Erläuterung
```

**Tag 4:**
```
1. § 1 bearbeiten
2. Moderationstext schreiben
3. Speichern
→ Paragraph vollständig!
```

---

### **Podcast-Aufnahme**

**Vorbereitung:**
```
1. Alle Paragraphen in Editor erstellt
2. Tab "🎯 Auswahl"
3. § 1, § 2, § 5 auswählen (☑)
4. Reihenfolge: § 1 → § 5 → § 2 (mit [▲][▼])
```

**Aufnahme:**
```
1. "🎬 Zum Teleprompter"
2. Vollbild aktivieren
3. RØDE Mikrofon verbinden
4. ▶️ Start
5. Ablesen:
   - § 1 komplett
   - § 5 komplett
   - § 2 komplett
```

---

## 💾 Multi-PC-Nutzung

### **PC 1 (Zu Hause):**
```
1. Paragraphen erstellen & bearbeiten
2. "📥 Export JSON"
3. JSON-Datei in GitHub Repo hochladen
```

### **PC 2 (Fahrschule):**
```
1. JSON-Datei von GitHub herunterladen
2. "📤 Import JSON"
3. Weiterarbeiten
4. Wieder exportieren & hochladen
```

**Tipp:** Nutze GitHub als "Cloud-Speicher" für deine JSON-Backups!

---

## ⚡ Keyboard Shortcuts

- **Strg+S** → Speichern
- **Leertaste** → Play/Pause (im Teleprompter)
- **ESC** → Bearbeiten-Modal schließen

---

## 📊 Beispiel-Struktur

### **Editor-Liste:**
```
§ 1 Grundregeln           → 🔵🟢🟡🟠 (alles befüllt)
§ 2 Straßenbenutzung      → 🔵⚫⚫⚫ (nur StVO)
§ 5 Vorfahrt              → 🔵🟢⚫⚫ (StVO + VwV)
§ 10 Einbahnstraße        → ⚫⚫⚫🟠 (nur Moderationstext)
```

### **Auswahl für Teleprompter:**
```
☑ § 1 Grundregeln         (komplett → alle 4 Spalten)
☑ § 5 Vorfahrt            (nur StVO + VwV → 2 Spalten)
☐ § 2 Straßenbenutzung    (nicht ausgewählt)
☐ § 10 Einbahnstraße      (nicht ausgewählt)
```

### **Teleprompter zeigt:**
```
§ 1 GRUNDREGELN
🟠 MODERATIONSTEXT
🔵 STVO ORIGINAL
🟢 VWV-STVO
🟡 ERLÄUTERUNG

§ 5 VORFAHRT
🔵 STVO ORIGINAL
🟢 VWV-STVO
```

---

## ⚖️ Copyright

### ✅ **Darfst du vorlesen:**
- StVO-Paragraphen (amtlich)
- VwV-StVO (amtlich)
- Gerichtsurteile (mit Quelle)
- Eigene Erläuterungen

### ❌ **NICHT wörtlich übernehmen:**
- Bouska/Leue/Heltzel Kommentare → **sinngemäß umschreiben!**
- Lehrbücher
- Fremde Podcasts

---

## 🔧 Technisch

- **Browser:** Chrome/Edge (empfohlen), Firefox, Safari
- **Speicherung:** localStorage (Browser) + JSON Export
- **Auto-Save:** Alle 30 Sekunden
- **Responsive:** Funktioniert auf Desktop, Tablet, Smartphone

---

## 🆘 Troubleshooting

### **Daten gehen verloren?**
→ Regelmäßig JSON exportieren!

### **Paragraph erscheint nicht in Auswahl?**
→ Zurück zum Editor, prüfe ob er in der Liste ist

### **Teleprompter leer?**
→ Im Tab "🎯 Auswahl" Checkboxen aktivieren

### **Reihenfolge nicht änderbar?**
→ Paragraph muss ausgewählt (☑) sein

---

## 📝 Changelog

### **v5.2 (2025-12-21) - CURRENT**
- ✨ **GitHub Auto-Sync** - Automatische Synchronisation mit GitHub!
- ✨ Daten von überall abrufbar
- ✨ Status-Anzeige oben rechts (verbunden/speichert/fehler)
- ✨ Einmalige Einrichtung mit GitHub Token
- ✨ Export/Import weiterhin verfügbar

### **v5.1 (2025-12-21)**
- ✨ PDF-Export hinzugefügt
- ✨ Footer auf jeder PDF-Seite: FL-BE_07/25_Justin_Lee_Probis
- ✨ Schön formatiertes PDF zum Ausdrucken

### **v5.0 (2025-12-21)**
- ✨ Listenansicht für alle Paragraphen
- ✨ Einzeln bearbeiten per Modal
- ✨ Checkbox-Auswahl für Teleprompter
- ✨ Reihenfolge ändern mit [▲][▼]
- ✨ Status-Icons zeigen Befüllung
- ✨ Teleprompter zeigt nur ausgewählte Paragraphen

### **v4.0**
- 4-Spalten direkt sichtbar (zu unübersichtlich)

### **v1.0-v3.0**
- Frühere Versionen

---

## 💡 Tipps & Tricks

### **Effizientes Arbeiten:**
1. Erstelle ALLE Paragraphen zuerst (nur Titel)
2. Fülle StVO-Texte in einem Durchgang
3. Fülle VwV-Texte in einem Durchgang
4. Schreibe Erläuterungen in einem Durchgang
5. Schreibe Moderationstexte zuletzt

### **Podcast-Produktion:**
1. Wähle 3-5 Paragraphen pro Folge
2. Reihenfolge: Logisch aufeinander aufbauend
3. Füge Moderationstexte für Übergänge hinzu
4. Teste Teleprompter-Geschwindigkeit vorher

### **Backup-Strategie:**
1. Täglich JSON exportieren
2. Dateinamen mit Datum: `stvo-backup-2025-12-21.json`
3. In GitHub Repo hochladen
4. Oder in Cloud-Speicher (Google Drive, Dropbox)

---

**StVO Teleprompter v5.0**

Live: https://710deckel.github.io/stvo-teleprompter/
