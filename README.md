# Yuniqx Twitch Bot

![Yuniqx Bot Logo](Images/3fed6854-7464-421b-80b2-90512b6147ab-channel_offline_image-1920x1080.jpg)

> [!CAUTION]
> ⚠️ **Hinweis zur frühen Zugriffsphase** ⚠️
> Yuniqx Bot befindet sich derzeit in der frühen Zugriffsphase. Funktionen können hinzugefügt, geändert oder entfernt werden, während die Entwicklung voranschreitet. Wir schätzen Ihre Unterstützung und Ihr Feedback in dieser Phase sehr!

Yuniqx ist ein vielseitiger Twitch-Bot, der entwickelt wurde, um die Kanalmoderationund das Nutzerengagement zu verbessern. Basierend auf Python und der TwitchIO-Bibliothek bietet dieser Bot eine Reihe von Funktionen zur Verbesserung des Streaming-Erlebnisses.

## Funktionen

- **Slowmode-Verwaltung**: Moderatoren können den Slowmode im Chat aktivieren oder deaktivieren.
- **URL-Überprüfung**: Scannt automatisch gepostete URLs auf potenzielle Sicherheitsbedrohungen mit der VirusTotal API.
- **Benutzerdefinierte Befehle**: Enthält Befehle wie !discord, !party und mehr für das Nutzerengagement.
- **Nachrichtenzählung**: Verfolgt die Gesamtzahl der Chat-Nachrichten.
- **Automatische Antworten**: Reagiert auf bestimmte Schlüsselwörter im Chat.
- **Spam-Filterung**: Erkennt und entfernt automatisch häufige Spam-Nachrichten.
- **Befehlsliste**: Benutzer können verfügbare Befehle mit !cm anzeigen.
- **Yunimark-System**: Ein automatisches Währungssystem, das aktive Chatter belohnt.
- **Glücksspiel**: Benutzer können ihre Yunimarks einsetzen, um die Chance zu haben, mehr zu gewinnen.
- **Moderationstools**: Beinhaltet Spam-Erkennung und Zeitsperre-Funktionen für Benutzer.

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

 ## Yunimark-System

- Alle 60 Sekunden erhalten aktive Benutzer im Chat 100 Yunimarks.
- Benutzer können ihren Kontostand überprüfen, Glücksspiele machen und an anderen Yunimark-basierten Aktivitäten teilnehmen.
- Moderatoren können mit dem Befehl `!addyunimark` Yunimarks zum Kontostand von Benutzern hinzufügen.

## Moderationsfunktionen

- Automatische Spam-Erkennung und Zeitsperre für auffällige Benutzer.
- Möglichkeit, Bots zur Filterliste hinzuzufügen oder daraus zu entfernen.
- Anpassbare Spam-Muster für verbesserte Chat-Moderation.

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
- `!yunimark`: Überprüfe deinen aktuellen Yunimark-Kontostand.
- `!gamble <Betrag>`: Setze deine Yunimarks. Verwende 'all', um alle deine Yunimarks zu setzen.
- `!cooldown`: Überprüfe die verbleibende Zeit, bevor du wieder setzen kannst.
- `!addyunimark <Benutzername> <Betrag>`: (Nur für Moderatoren) Füge Yunimarks zum Kontostand eines Benutzers hinzu.
- `!balance [Benutzername]`: Überprüfe den Yunimark-Kontostand von dir selbst oder einem anderen Benutzer.
- `!info`: Zeige Informationen über den Bot und seinen aktuellen Status an.

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
