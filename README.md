# Yuniqx Twitch Bot


> [!CAUTION]
> ⚠️ **Hinweis zur frühen Zugriffsphase** ⚠️
> Yuniqx Bot befindet sich derzeit in der frühen Zugriffsphase. Funktionen können hinzugefügt, geändert oder entfernt werden, während die Entwicklung voranschreitet. Wir schätzen Ihre Unterstützung und Ihr Feedback in dieser Phase sehr!

Yuniqx ist ein vielseitiger Twitch-Bot, der entwickelt wurde, um die Kanalmoderationund das Nutzerengagement zu verbessern. Basierend auf Python und der TwitchIO-Bibliothek bietet dieser Bot eine Reihe von Funktionen zur Verbesserung des Streaming-Erlebnisses.

## Funktionen

- **Slowmode-Verwaltung**: Moderatoren können den Slowmode im Chat aktivieren oder deaktivieren.
- **Benutzerdefinierte Befehle**: Enthält Befehle wie !discord, !party und mehr für das Nutzerengagement.
- **Nachrichtenzählung**: Verfolgt die Gesamtzahl der Chat-Nachrichten.
- **Automatische Antworten**: Reagiert auf bestimmte Schlüsselwörter im Chat.
- **Befehlsliste**: Benutzer können verfügbare Befehle mit !cm anzeigen.

- **URL-Überprüfung und Virenscan**:
  - Automatische Erkennung von URLs in Chat-Nachrichten.
  - Integration mit der VirusTotal API für umfassende Sicherheitsüberprüfungen.
  - Scannt URLs auf Malware, Phishing-Seiten und andere potenzielle Bedrohungen.
  - Benachrichtigt Moderatoren über verdächtige Links.
  - Optionale automatische Entfernung von als gefährlich eingestuften URLs.
  - Konfigurierbare Schwellenwerte für Bedrohungseinstufungen.

- **Erweiterter Spam-Filter**:
  - Dynamische Spam-Erkennung basierend auf konfigurierbaren Mustern und Regeln.
  - Erkennung von wiederholten Nachrichten, übermäßiger Großschreibung und unerwünschten Zeichenfolgen.
  - Automatische Zeitstrafen für Benutzer, die Spam-Regeln verletzen.
  - Eskalationssystem für wiederholte Verstöße (Warnung → Timeout → Ban).
  - Whitelist-Funktion für vertrauenswürdige Benutzer oder bestimmte Nachrichtentypen.
  - Echtzeit-Aktualisierung der Spam-Regeln durch Moderatoren über Chat-Befehle.
  - Logging von Spam-Vorfällen für spätere Analyse und Berichterstattung.

## Befehle

- `!slowmode <Sekunden>`: Stellt den Slowmode ein (0-1800 Sekunden, nur für Moderatoren).
- `!discord` oder `!dc`: Teilt den Discord-Einladungslink.
- `!ms`: Zeigt die Gesamtzahl der Nachrichten an.
- `!party`: Löst einen Party-Modus mit Emotes aus.
- `!cm`: Listet alle verfügbaren Befehle auf.
- `!addspam <Muster>`: Fügt ein Spam-Muster zum Filter hinzu (nur für Moderatoren).
- `!removespam <Muster>`: Entfernt ein Spam-Muster aus dem Filter (nur für Moderatoren).
- `!listspam`: Zeigt die aktuelle Liste der Spam-Filtermuster an.
- `!status`: Zeigt den aktuellen Status des Bots an.

## ⚠️ Informationen zur frühen Zugriffsphase ⚠️

Da sich Yuniqx Bot in der frühen Zugriffsphase befindet:

- Können einige Funktionen experimentell sein und sich ändern.
- Können Sie auf Fehler oder unerwartetes Verhalten stoßen.
- Schätzen wir Ihr Feedback und Ihre Fehlerberichte sehr.
- Werden regelmäßig neue Funktionen und Verbesserungen hinzugefügt.

Um den aktuellen Status des Bots zu erfahren, verwenden Sie den Befehl `!status` im Chat.

Ihr Input ist wertvoll für die Gestaltung der Zukunft des Yuniqx Bots!

## Mitwirken

Beiträge, Issues und Feature-Anfragen sind willkommen! Schauen Sie gerne auf der [Issues-Seite](https://github.com/Mou67/YuniBot/issues) vorbei.

## Lizenz

[MIT](https://choosealicense.com/licenses/mit/)

## Author

 - Mou67
