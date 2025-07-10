# 🤖 N8N Agent Workflow Builder

Ein intelligenter KI-Agent, der automatisch N8N-Workflows basierend auf natürlichen Chat-Nachrichten erstellt. Einfach beschreiben was du brauchst und der Agent baut den kompletten Workflow für dich!

## 🚀 Features

- **Chat-basierte Workflow-Erstellung**: Beschreibe einfach in natürlicher Sprache was du automatisieren möchtest
- **Blitzschnell**: Erstellt funktionsfähige Workflows in unter 60 Sekunden
- **Multi-LLM Support**: Nutzt Claude Sonnet 4, GPT-4 oder andere OpenRouter-Modelle
- **Automatische Dokumentation**: Erstellt Anleitungen und Setup-Guides für jeden Workflow
- **Sofort einsatzbereit**: Generierte Workflows sind direkt importierbar und funktionsfähig
- **Deutsche und englische Eingaben**: Funktioniert in beiden Sprachen

## 📺 Demo Video

Sieh dir das komplette Tutorial an: [YouTube Video](https://www.youtube.com/watch?v=9XTJK9_KyEE)

**Inspiriert von:** [Nate Herk](https://www.youtube.com/@nateherk)

## 🛠️ Schnellstart

### Voraussetzungen

- N8N Installation (selbst gehostet oder Cloud)
- API-Schlüssel für:
  - [OpenRouter](https://openrouter.ai/) (empfohlen)
  - [Anthropic](https://console.anthropic.com/) (optional für Claude)
  - Google Drive (für Dokumentation)

### Installation

1. **Repository klonen**
   ```bash
   git clone https://github.com/yourusername/n8n-agent-workflow-builder.git
   ```

2. **Workflow importieren**
   - Öffne deine N8N-Instanz
   - Gehe zu "Workflows" > "Import from file"
   - Wähle die `Agent Workflow builder.json` Datei

3. **Credentials konfigurieren**
   - OpenRouter API-Schlüssel hinzufügen
   - N8N API-Anmeldeinformationen erstellen
   - Google Drive Zugang konfigurieren (optional)

### Konfiguration

#### ✅ Schritt 1: OpenRouter API-Schlüssel
- Registriere dich bei [OpenRouter](https://openrouter.ai/)
- Erstelle einen API-Schlüssel
- Füge ihn in den Credentials-Bereich ein

#### ✅ Schritt 2: N8N API-Schlüssel
- Gehe zu deinen N8N-Einstellungen
- Erstelle einen neuen API-Schlüssel
- Konfiguriere die N8N-Credentials im Workflow

#### ✅ Schritt 3: Google Drive (Optional)
- Kopiere das [Dokumentations-Template](https://docs.google.com/document/d/1TiRusVo4DbbANwAr7I0GUGDZY3pmEmHZy3k66mRxLCg/edit?usp=sharing)
- Verbinde deine Google Drive Credentials
- Aktualisiere die Dokument-ID im Workflow

#### ✅ Schritt 4: Claude (Optional)
- Für erweiterte Funktionen mit Thinking Mode
- Füge deinen [Anthropic API-Schlüssel](https://console.anthropic.com/) hinzu

## 📖 Verwendung

### Einfaches Beispiel
```
Erstelle mir einen Telegram Bot, der auf Nachrichten mit KI antwortet
```

### Erweiterte Beispiele
```
Baue einen Workflow der:
- E-Mails von Gmail überwacht
- Wichtige E-Mails an Slack weiterleitet
- Eine Zusammenfassung mit GPT erstellt
```

### Workflow starten
1. Öffne den Chat-Trigger
2. Beschreibe deinen gewünschten Workflow
3. Warte 30-60 Sekunden
4. Erhalte einen Link zu deinem fertigen Workflow

## 🏗️ Workflow-Architektur

### Hauptkomponenten:

- **Chat Trigger**: Empfängt deine Anfragen
- **N8N Developer Agent**: Koordiniert den Erstellungsprozess
- **Documentation Loader**: Lädt N8N-Beispiele und Best Practices
- **N8N Builder**: Erstellt den eigentlichen Workflow-Code
- **Workflow Creator**: Importiert den fertigen Workflow

### Unterstützte LLM-Modelle:
- Claude Sonnet 4 (OpenRouter)
- Claude Opus 4 (Anthropic - mit Thinking Mode)
- GPT-4 (OpenRouter)
- Weitere OpenRouter-Modelle

## 🔧 Anpassungen

### Eigene Dokumentation hinzufügen
1. Bearbeite das Google Doc mit deinen eigenen N8N-Beispielen
2. Füge spezifische Use Cases für deine Branche hinzu
3. Der Agent lernt automatisch von deinen Beispielen

### Modell wechseln
- Standardmäßig: Claude Sonnet 4 (OpenRouter)
- Für bessere Qualität: Claude Opus 4 (Anthropic)
- Für Kosteneinsparung: GPT-4 Mini

## 📋 Beispiel-Workflows

Der Agent kann erstellen:
- **Telegram/Discord Bots** mit KI-Integration
- **E-Mail Automation** mit Gmail/Outlook
- **Social Media Management** für LinkedIn/Twitter
- **Datenverarbeitung** mit APIs und Webhooks
- **Monitoring & Alerts** für verschiedene Services
- **CRM-Integration** mit Salesforce/HubSpot

## 🐛 Troubleshooting

### Häufige Probleme:
1. **Workflow wird nicht erstellt**
   - Prüfe API-Schlüssel-Konfiguration
   - Stelle sicher, dass N8N-Credentials korrekt sind

2. **Leere Antworten**
   - Überprüfe Google Drive Zugriff
   - Kontrolliere Dokumentations-ID

3. **Fehlerhafte Workflows**
   - Teste mit einfacheren Anfragen
   - Prüfe ob alle Nodes verfügbar sind

### Debug-Modus:
- Aktiviere "Save Execution Data" für detaillierte Logs
- Überprüfe jeden Workflow-Schritt einzeln

## 🤝 Beitragen

Verbesserungen sind willkommen! 

1. Fork das Repository
2. Erstelle einen Feature Branch
3. Committe deine Änderungen
4. Erstelle einen Pull Request

### Verbesserungsideen:
- Zusätzliche LLM-Provider
- Erweiterte Workflow-Templates
- Bessere Error Handling
- UI-Verbesserungen

## 📄 Lizenz

MIT License - siehe [LICENSE](LICENSE) Datei für Details.

## 🙏 Credits

- **Inspiriert von:** [Nate Herk](https://www.youtube.com/@nateherk)
- **Erstellt von:** [Alexander Lutsyuk](https://www.youtube.com/@Digi-Wissen-algoran)
- **Community:** Danke an alle N8N-Enthusiasten für Feedback und Verbesserungen

## 📞 Support

- 🎥 [YouTube Tutorial](https://www.youtube.com/watch?v=9XTJK9_KyEE)
- 🐛 [GitHub Issues](https://github.com/yourusername/n8n-agent-workflow-builder/issues)
- 💬 [Community Discord](https://discord.gg/n8n)

---

**⭐ Wenn dir dieses Projekt gefällt, gib ihm einen Stern auf GitHub!**
