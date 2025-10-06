# Contributing to Trustup24 Platform

Vielen Dank für Ihr Interesse, zur Trustup24 Platform beizutragen! Diese Anleitung hilft Ihnen dabei, effektiv zum Projekt beizutragen.

## 🚀 Erste Schritte

### Voraussetzungen
- Node.js (v16 oder höher)
- npm oder yarn
- Git
- GitHub Account

### Repository Setup
```bash
# Repository forken und klonen
git clone https://github.com/IHR_USERNAME/trustup24-platform.git
cd trustup24-platform

# Dependencies installieren
npm install

# Entwicklungsserver starten
npm run dev
```

## 📋 Entwicklungsrichtlinien

### Code Style
- Verwenden Sie ESLint und Prettier für Code-Formatierung
- Folgen Sie den JavaScript/Node.js Best Practices
- Schreiben Sie aussagekräftige Commit-Messages
- Dokumentieren Sie neue Features

### Commit-Nachrichten
Verwenden Sie das folgende Format:
```
type(scope): description

[optional body]

[optional footer]
```

**Typen:**
- `feat`: Neue Features
- `fix`: Bug-Fixes
- `docs`: Dokumentation
- `style`: Code-Formatierung
- `refactor`: Code-Refactoring
- `test`: Tests
- `chore`: Wartungsarbeiten

**Beispiele:**
```
feat(providers): add new provider category filter
fix(auth): resolve login session timeout issue
docs(readme): update installation instructions
```

## 🔄 Contribution Workflow

### 1. Issue erstellen
- Überprüfen Sie bestehende Issues
- Erstellen Sie ein neues Issue für Bugs oder Feature-Requests
- Verwenden Sie die bereitgestellten Templates

### 2. Branch erstellen
```bash
# Neuen Feature-Branch erstellen
git checkout -b feature/your-feature-name

# Oder Bug-Fix-Branch
git checkout -b fix/bug-description
```

### 3. Entwicklung
- Implementieren Sie Ihre Änderungen
- Schreiben Sie Tests für neue Features
- Stellen Sie sicher, dass alle Tests bestehen
- Aktualisieren Sie die Dokumentation

### 4. Testing
```bash
# Tests ausführen
npm test

# Linting prüfen
npm run lint

# Build testen
npm run build
```

### 5. Pull Request erstellen
- Pushen Sie Ihren Branch zu GitHub
- Erstellen Sie einen Pull Request
- Füllen Sie die PR-Template aus
- Verlinken Sie relevante Issues

## 🧪 Testing

### Test-Struktur
```
tests/
├── unit/           # Unit Tests
├── integration/    # Integration Tests
├── e2e/           # End-to-End Tests
└── fixtures/      # Test-Daten
```

### Test-Befehle
```bash
# Alle Tests
npm test

# Tests mit Coverage
npm run test:coverage

# Tests im Watch-Mode
npm run test:watch

# E2E Tests
npm run test:e2e
```

## 📚 Dokumentation

### Code-Dokumentation
- Verwenden Sie JSDoc für Funktionen und Klassen
- Kommentieren Sie komplexe Logik
- Aktualisieren Sie README.md bei Änderungen

### API-Dokumentation
- Dokumentieren Sie neue API-Endpoints
- Verwenden Sie OpenAPI/Swagger-Spezifikationen
- Fügen Sie Beispiele hinzu

## 🐛 Bug Reports

### Bug-Report Template
```markdown
**Beschreibung:**
Kurze Beschreibung des Bugs

**Schritte zur Reproduktion:**
1. Gehen Sie zu '...'
2. Klicken Sie auf '...'
3. Scrollen Sie nach unten zu '...'
4. Sehen Sie den Fehler

**Erwartetes Verhalten:**
Was sollte passieren

**Screenshots:**
Falls zutreffend, fügen Sie Screenshots hinzu

**Umgebung:**
- OS: [z.B. iOS]
- Browser: [z.B. chrome, safari]
- Version: [z.B. 22]
```

## ✨ Feature Requests

### Feature-Request Template
```markdown
**Feature-Beschreibung:**
Klare Beschreibung des gewünschten Features

**Problem:**
Welches Problem löst dieses Feature?

**Lösung:**
Beschreibung der vorgeschlagenen Lösung

**Alternativen:**
Alternative Lösungsansätze

**Zusätzlicher Kontext:**
Screenshots, Mockups, etc.
```

## 🔒 Sicherheit

### Sicherheitsrichtlinien
- Niemals Passwörter oder API-Keys committen
- Verwenden Sie Umgebungsvariablen für sensible Daten
- Folgen Sie OWASP-Sicherheitsrichtlinien
- Melden Sie Sicherheitslücken privat

### Sicherheitslücken melden
Senden Sie eine E-Mail an: security@mindhaus-consulting.ae

## 📞 Hilfe und Support

### Community
- **GitHub Discussions:** Für allgemeine Fragen
- **Issues:** Für Bugs und Feature-Requests
- **Email:** info@mindhaus-consulting.ae

### Entwickler-Ressourcen
- **Dokumentation:** `/docs` Ordner
- **API-Referenz:** `/docs/api.md`
- **Architektur:** `/docs/architecture.md`

## 🏆 Anerkennung

Alle Beiträge werden in der [CONTRIBUTORS.md](CONTRIBUTORS.md) Datei anerkannt.

### Arten von Beiträgen
- 💻 Code
- 📖 Dokumentation
- 🐛 Bug-Reports
- 💡 Ideen
- 🎨 Design
- 🔧 Tools
- 🌍 Übersetzungen

## 📄 Lizenz

Durch Ihre Beiträge stimmen Sie zu, dass Ihre Arbeit unter der [MIT-Lizenz](LICENSE) lizenziert wird.

---

**Vielen Dank für Ihren Beitrag zur Trustup24 Platform! 🚀**
