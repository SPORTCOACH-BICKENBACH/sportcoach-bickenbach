# Sport in Bickenbach - Website

Moderne, mehrsprachige Website für den Sportcoach in Bickenbach.

## 🌟 Features

- **Modern & Responsive Design** - Funktioniert perfekt auf Desktop, Tablet und Smartphone
- **Mehrsprachig** - Deutsch, Englisch (weitere Sprachen können einfach hinzugefügt werden)
- **Schnell & Leichtgewichtig** - Keine schweren Frameworks, nur reines HTML/CSS/JS
- **SEO-optimiert** - Gute Sichtbarkeit in Suchmaschinen
- **Kostenlos hostbar** - GitHub Pages oder andere kostenlose Hosting-Dienste

## 📁 Dateien

```
sportcoach-website/
├── index.html          # Deutsche Startseite
├── english.html        # Englische Version
├── styles.css          # Alle Styling-Informationen
├── script.js           # Interaktive Funktionen
└── README.md          # Diese Datei
```

## 🚀 So hosten Sie die Website kostenlos

### Option 1: GitHub Pages (EMPFOHLEN - Komplett kostenlos!)

1. **GitHub Account erstellen** (falls noch nicht vorhanden)
   - Gehen Sie zu https://github.com
   - Klicken Sie auf "Sign up"

2. **Neues Repository erstellen**
   - Klicken Sie auf das "+" Symbol oben rechts
   - Wählen Sie "New repository"
   - Name: `sportcoach-bickenbach` (oder ein anderer Name)
   - Wählen Sie "Public"
   - Klicken Sie auf "Create repository"

3. **Dateien hochladen**
   - Klicken Sie auf "uploading an existing file"
   - Ziehen Sie alle Dateien (index.html, english.html, styles.css, script.js) in den Upload-Bereich
   - Klicken Sie auf "Commit changes"

4. **GitHub Pages aktivieren**
   - Gehen Sie zu "Settings" (im Repository)
   - Scrollen Sie zu "Pages" (links in der Seitenleiste)
   - Unter "Source" wählen Sie "main" branch
   - Klicken Sie auf "Save"
   - Ihre Website ist jetzt unter `https://IhrBenutzername.github.io/sportcoach-bickenbach/` verfügbar!

5. **Eigene Domain verbinden (optional)**
   - Kaufen Sie eine Domain (z.B. bei IONOS, Strato, oder Namecheap für ca. 10€/Jahr)
   - Folgen Sie dieser Anleitung: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site

### Option 2: Netlify (Ebenfalls kostenlos!)

1. Gehen Sie zu https://www.netlify.com
2. Klicken Sie auf "Sign up"
3. Ziehen Sie den gesamten Ordner in den Upload-Bereich
4. Ihre Website ist sofort online!

### Option 3: Vercel (Kostenlos für private Projekte)

1. Gehen Sie zu https://vercel.com
2. Melden Sie sich an
3. Klicken Sie auf "New Project"
4. Laden Sie die Dateien hoch
5. Fertig!

## 🎨 Website anpassen

### Farben ändern
Öffnen Sie `styles.css` und ändern Sie die Farben im `:root` Bereich (Zeilen 8-15):

```css
:root {
    --primary-color: #2563eb;      /* Hauptfarbe (Blau) */
    --secondary-color: #10b981;    /* Sekundärfarbe (Grün) */
    --accent-color: #f59e0b;       /* Akzentfarbe (Orange) */
}
```

### Inhalte ändern
Öffnen Sie `index.html` oder `english.html` mit einem Texteditor und bearbeiten Sie die Texte direkt.

### Bilder hinzufügen
1. Erstellen Sie einen Ordner `images` im Hauptverzeichnis
2. Laden Sie Ihre Bilder hoch
3. Ersetzen Sie die Bild-URLs in den HTML-Dateien

### Weitere Sprachen hinzufügen
1. Kopieren Sie `english.html`
2. Benennen Sie sie um (z.B. `turkish.html`)
3. Übersetzen Sie die Inhalte
4. Fügen Sie die Sprache zum Dropdown-Menü hinzu

## 📱 Testen der Website lokal

1. Öffnen Sie `index.html` einfach in Ihrem Browser (Doppelklick)
2. Oder nutzen Sie einen lokalen Server:
   - Installieren Sie die "Live Server" Extension in VS Code
   - Oder öffnen Sie ein Terminal und führen Sie aus:
     ```
     python -m http.server 8000
     ```
   - Dann öffnen Sie `http://localhost:8000` im Browser

## 🔧 Technische Details

- **HTML5** - Moderne semantische Struktur
- **CSS3** - Flexbox & Grid Layout, CSS Variables
- **Vanilla JavaScript** - Keine externen Abhängigkeiten
- **Responsive Design** - Mobile-First Ansatz
- **Accessibility** - Semantisches HTML, ARIA-Labels wo nötig

## 📊 SEO Optimierungen

Die Website ist bereits für Suchmaschinen optimiert:
- ✅ Semantisches HTML
- ✅ Meta-Tags
- ✅ Schnelle Ladezeiten
- ✅ Mobile-freundlich
- ✅ Strukturierte Daten-ready

## 🆘 Support & Kontakt

Bei Fragen oder Problemen:
- Erstellen Sie ein Issue auf GitHub
- Oder kontaktieren Sie: sportcoach.bickenbach@mail.de

## 📝 Lizenz

Diese Website wurde erstellt für Sport in Bickenbach und kann frei verwendet und angepasst werden.

---

**Viel Erfolg mit Ihrer neuen Website! 🎉**

## Nächste Schritte

1. ✅ Website lokal testen
2. ✅ Inhalte anpassen falls nötig
3. ✅ Auf GitHub Pages oder Netlify hochladen
4. ✅ Eigene Domain verbinden (optional)
5. ✅ In Suchmaschinen eintragen (Google Search Console)

### Empfohlene Domain-Namen
- `sportcoach-bickenbach.de`
- `sport-bickenbach.de`
- `integration-sport-bickenbach.de`
