# Tauschplatz - Rechtliche Dokumentation

Diese Dokumentation enthält die rechtlichen Informationen für die Tauschplatz Android-App.

## Dateien

- **index.html** - Startseite mit Links zu allen rechtlichen Dokumenten
- **datenschutz.html** - Datenschutzerklärung gemäß DSGVO
- **impressum.html** - Impressum gemäß § 5 TMG

## GitHub Pages Setup

Um diese Seiten auf GitHub Pages zu veröffentlichen:

1. **Option 1: Docs-Ordner verwenden (empfohlen)**
   - Diese Dateien sind bereits im `docs/` Ordner
   - Gehen Sie zu: Repository → Settings → Pages
   - Unter "Source" wählen Sie: "Deploy from a branch" → "main" → "/docs"
   - Die Seiten sind dann unter: `https://[username].github.io/[repository-name]/` verfügbar

2. **Option 2: Separates Repository**
   - Erstellen Sie ein neues Repository (z.B. `tauschplatz-privacy`)
   - Kopieren Sie die HTML-Dateien dorthin
   - Aktivieren Sie GitHub Pages für dieses Repository
   - Die Seiten sind dann unter: `https://[username].github.io/tauschplatz-privacy/` verfügbar

## Verwendung in der App

In Ihrer Android-App können Sie die Datenschutzerklärung so verlinken:

```kotlin
val privacyPolicyUrl = "https://[username].github.io/[repository-name]/datenschutz.html"
```

Oder wenn Sie ein separates Repository verwenden:

```kotlin
val privacyPolicyUrl = "https://[username].github.io/tauschplatz-privacy/datenschutz.html"
```

## Wichtige Hinweise

⚠️ **Bitte aktualisieren Sie vor der Veröffentlichung:**

1. **Impressum (impressum.html):**
   - Ersetzen Sie `[Ihr Name]` mit Ihrem tatsächlichen Namen
   - Ersetzen Sie `[Ihre Adresse]` mit Ihrer vollständigen Adresse
   - Aktualisieren Sie die E-Mail-Adressen

2. **Datenschutzerklärung (datenschutz.html):**
   - Überprüfen Sie alle Angaben auf Richtigkeit
   - Passen Sie die Kontaktdaten an
   - Stellen Sie sicher, dass alle genannten Dienstleister korrekt sind

3. **GitHub Pages URL:**
   - Aktualisieren Sie alle Links in der App mit der tatsächlichen GitHub Pages URL

## Rechtliche Beratung

Diese Dokumente sind Vorlagen und sollten von einem Rechtsanwalt überprüft werden, 
bevor sie veröffentlicht werden, insbesondere wenn Sie:
- Eine kommerzielle App betreiben
- Daten von Nutzern in der EU sammeln
- Eine Firma oder ein Unternehmen sind
