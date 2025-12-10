# 🎓 Lern-Apps Portfolio

Eine Sammlung professioneller HTML-Lern-Anwendungen für Persisch und Deutsch – entwickelt mit Claude AI für modernen, effektiven Sprachunterricht.

[![Powered by Claude AI](https://img.shields.io/badge/Powered%20by-Claude%20AI-6366f1?style=for-the-badge)](https://www.anthropic.com/claude)
[![GitHub Pages](https://img.shields.io/badge/GitHub-Pages-222?style=for-the-badge&logo=github)](https://pages.github.com/)

## 🌟 Live Demo

**Haupt-Portfolio:** `https://[dein-username].github.io/[repo-name]/`

## 📱 Features

- ✅ **OLAT & LMS Integration** – Nahtlos integrierbar in Learning Management Systeme
- 📤 **Automatisierte Hausaufgaben-Abgabe** – Kein manuelles Einsammeln mehr
- 🔁 **Beliebige Wiederholung** – Lernende können Übungen so oft wiederholen wie nötig
- 📱 **Mobiles Lernen** – Optimiert für Smartphones und Tablets
- 📊 **Progress-Tracking** – Fortschritt wird automatisch gespeichert
- 🎓 **Self-Paced Learning** – Jeder lernt in seinem eigenen Tempo
- 🎮 **Gamification** – Liga-Systeme, Zertifikate, Achievements
- ⚡ **Sofortiges Feedback** – Unmittelbare Rückmeldung zu Antworten
- 🌐 **Offline-Fähig** – Funktioniert ohne Internetverbindung

## 📚 Enthaltene Apps

### 🇮🇷 Persisch Lernen

| App | Level | Beschreibung |
|-----|-------|--------------|
| 💼 **Berufliche Vorstellung** | B1-B2 | Umfassende Lern-App für berufliche Vorstellungen |
| 🏢 **Bita - دنیای کاری** | B1-B2 | Fortgeschrittene Arbeitswelt-Vokabeln mit Flashcards |
| 🎵 **Googoosh - کمکم کن** | A2-B1 | Lernen durch das berühmte Lied von Googoosh |
| 📝 **Persischer Imperativ** | A2-B1 | Meistern Sie die Befehlsformen im Persischen |
| ⏮️ **Präteritum-Camp** | A1 | Intensives Training für Vergangenheitsformen |
| 📅 **Was habe ich gestern gemacht** | A1 | Alltags-Vokabular in der Vergangenheit |
| 💬 **Goftogooye Sina & Tarane** | A1 | Interaktive Dialog-Lektion mit Alltagskonversation |

### 🇩🇪 Deutsch Lernen

| App | Level | Beschreibung |
|-----|-------|--------------|
| 🍳 **Küchen-Vokabeln** | A1-A2 | Spielerisches Matching-Game für Küchen-Vokabular |

## 🚀 Installation & Deployment

### Schritt 1: Repository erstellen

1. Gehe zu [GitHub](https://github.com) und erstelle ein neues Repository
2. Name: z.B. `lern-apps` oder `sprachlern-portfolio`
3. ✅ Public Repository (für GitHub Pages)
4. ❌ Kein README initialisieren (du hast bereits eins!)

### Schritt 2: Dateien hochladen

**Option A: Via GitHub Web Interface**
1. Klicke auf "uploading an existing file"
2. Ziehe alle Dateien aus diesem Ordner in den Upload-Bereich
3. Commit message: "Initial commit - Lern-Apps Portfolio"
4. Klicke auf "Commit changes"

**Option B: Via Git Command Line**
```bash
git init
git add .
git commit -m "Initial commit - Lern-Apps Portfolio"
git branch -M main
git remote add origin https://github.com/[dein-username]/[repo-name].git
git push -u origin main
```

### Schritt 3: GitHub Pages aktivieren

1. Gehe zu **Settings** → **Pages**
2. Source: **Deploy from a branch**
3. Branch: **main** / Folder: **/ (root)**
4. Klicke auf **Save**
5. Nach ~2 Minuten ist deine Seite live! 🎉

## 🔗 URL-Struktur

Nach dem Deployment sind deine Apps unter folgenden URLs erreichbar:

```
https://[dein-username].github.io/[repo-name]/                    ← Haupt-Portfolio
https://[dein-username].github.io/[repo-name]/persian-beruf-komplett.html
https://[dein-username].github.io/[repo-name]/bita-arbeitswelt-2.html
https://[dein-username].github.io/[repo-name]/googoosh_app.html
https://[dein-username].github.io/[repo-name]/persischer_imperativ.html
https://[dein-username].github.io/[repo-name]/praeteritum-camp-3.html
https://[dein-username].github.io/[repo-name]/was_habe_ich_gestern_gemacht.html
https://[dein-username].github.io/[repo-name]/goftoguye_sina_va_taraneh_lms.html
https://[dein-username].github.io/[repo-name]/kuechen_vokabel_spiel.html
```

## 🎯 OLAT & LMS Integration

### In OLAT einbinden

**Methode 1: Als externe Seite**
1. OLAT-Kurs öffnen
2. **Kurseditor** → **Kursbaustein einfügen** → **Externe Seite**
3. URL einfügen: `https://[dein-username].github.io/[repo-name]/[app-name].html`
4. Speichern & publizieren

**Methode 2: Als HTML-Seite hochladen**
1. OLAT-Kurs öffnen
2. **Ablageordner** öffnen
3. HTML-Datei hochladen
4. **Kursbaustein** → **Einzelne Seite** → Datei auswählen

**Methode 3: Per iframe einbetten**
```html
<iframe 
    src="https://[dein-username].github.io/[repo-name]/[app-name].html" 
    width="100%" 
    height="800px" 
    frameborder="0">
</iframe>
```

### In Moodle einbinden

1. **Bearbeiten einschalten**
2. **Material oder Aktivität anlegen** → **URL** oder **Seite**
3. URL der App einfügen
4. Speichern

## 📊 Analytics

Alle Apps haben **Goatcounter Analytics** integriert:
- URL: `https://aguitoo.goatcounter.com`
- Tracking von Seitenaufrufen, Nutzung und Engagement
- Datenschutzfreundlich & DSGVO-konform

## 🎨 Anpassungen

### Farben ändern

Die Farbvariablen findest du am Anfang jeder HTML-Datei im `<style>`-Bereich:

```css
:root {
    --primary: #667eea;    /* Hauptfarbe */
    --secondary: #764ba2;  /* Sekundärfarbe */
    --accent: #f093fb;     /* Akzentfarbe */
    --success: #2ecc71;    /* Erfolgsfarbe */
    /* ... weitere Farben */
}
```

### Inhalte bearbeiten

Alle Inhalte sind direkt in den HTML-Dateien als JavaScript-Arrays definiert:

```javascript
const questions = [
    {
        question: "Deine Frage hier",
        correct: "Richtige Antwort",
        options: ["Option 1", "Option 2", "Option 3", "Option 4"]
    },
    // ... weitere Fragen
];
```

## 🛠️ Technologie-Stack

- **HTML5** – Struktur
- **CSS3** – Design & Animationen
- **Vanilla JavaScript** – Interaktivität
- **Google Fonts** – Vazirmatn (Persisch), Calibri/Segoe UI (Deutsch)
- **Goatcounter** – Analytics
- **GitHub Pages** – Hosting

## 📝 Dateiübersicht

```
lern-apps/
├── index.html                           # Haupt-Portfolio-Seite
├── README.md                            # Diese Datei
├── persian-beruf-komplett.html          # Berufliche Vorstellung (B1-B2)
├── bita-arbeitswelt-2.html              # Bita Arbeitswelt (B1-B2)
├── googoosh_app.html                    # Googoosh Lied (A2-B1)
├── persischer_imperativ.html            # Imperativ-Training (A2-B1)
├── praeteritum-camp-3.html              # Präteritum-Camp (A1)
├── was_habe_ich_gestern_gemacht.html    # Gestern-Aktivitäten (A1)
├── goftoguye_sina_va_taraneh_lms.html   # Sina & Tarane Dialog (A1)
└── kuechen_vokabel_spiel.html           # Küchen-Vokabeln (A1-A2)
```

## 💡 Highlights Tour

Die Portfolio-Seite enthält eine **interaktive Highlights-Tour** mit 8 Stationen:

1. 🎯 **OLAT & LMS Integration**
2. 📱 **Mobiles Lernen überall**
3. 🔄 **Endless-Stack Mechanik**
4. 🎮 **Gamification & Motivation**
5. ⚡ **Sofortiges Feedback**
6. 🎓 **Self-Paced Learning**
7. ✏️ **Flexible Eingabe-Toleranz**
8. 🤖 **Mit Claude AI entwickelt**

Klicke auf den **"✨ Highlights Tour"** Button auf der Hauptseite!

## 🤝 Entwickelt mit Claude AI

Alle Apps wurden in Zusammenarbeit mit **Claude AI von Anthropic** entwickelt:
- ⚡ **Entwicklungszeit:** 10-30 Minuten pro App
- 🎨 **Professionelles Design:** Out-of-the-box
- 🔧 **Keine Programmierkenntnisse:** Erforderlich
- 💡 **Leicht anpassbar:** Für individuelle Bedürfnisse

## 📧 Kontakt

**Entwickelt von:** Arash Guitoo  
**Powered by:** [Claude AI (Anthropic)](https://www.anthropic.com/claude)

## 📜 Lizenz

Diese Apps sind Open Source und können frei verwendet, angepasst und weitergegeben werden.

---

⭐ **Gefällt dir dieses Projekt?** Gib dem Repository einen Stern auf GitHub!

🐛 **Fehler gefunden?** Erstelle ein Issue oder Pull Request!

💬 **Fragen?** Öffne eine Discussion im Repository!

---

**Made with ❤️ and 🤖 Claude AI | © 2025**
