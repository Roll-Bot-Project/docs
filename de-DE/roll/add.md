---
description: Interaktive Erstellung einer Verlosung
---

# Verlosung erstellen

```
/roll hinzufügen
```

> Sie können auch Parameter verwenden, um alle Informationen in einem Befehl einzugeben, siehe [add-by-option.md](../advanced/add-by-option.md "mention")

## Schnelle Erstellung

Sie können den Parameter `-n` verwenden, um alle möglichen Standardoptionen auszuwählen. Geben Sie einfach eine Liste von Preisen ein, um eine Verlosung zu erstellen

D. h.:

```
/roll hinzufügen -n
```

## Erstellungsgegenstand

### Titel

Name, der in der Abfrageliste angezeigt wird

Antworten Sie mit n, um den Standardinhalt zu verwenden: Verlosung von <Benutzername>

### Ausführliche Beschreibung

Detaillierte Beschreibung der Verlosung, die im Befehl [list.md](list.md "mention") angezeigt wird

Antworten Sie mit n, um den Standardinhalt zu verwenden: Verlosung von <Benutzername>

### Preise

Die Preise, die Sie gewinnen möchten, sind im Format <Preisname>\*[Anzahl (leer für 1)], jede Zeile wird als eigenständiger Preis betrachtet

Zum Beispiel:

{% code lineNumbers="true" %}

```
Bild*2     // Zwei Bilder
Kissen       // Ein Kissen

// 66 [Unterstützung Leerzeichen und* mehrfache* Multiplikationszeichen*2]
Unterstützung Leerzeichen und* mehrfache* Multiplikationszeichen*2*66
```

{% endcode %}

### Automatische Auslosung

Zeitpunkt der Verlosung, im Format Jahr-Monat-Tag-Stunde-Minute (Minute kann weggelassen werden)

Antworten Sie mit n, um die automatische Auslosung nicht zu verwenden

Zum Beispiel:

{% code lineNumbers="true" %}

```
2077-11-4-5-14    // 4. November 2077, 5:14 Uhr
2042-2-6-23       // 6. Februar 2042, 23:00 Uhr
```

{% endcode %}

### Verlosungstyp

Wählen Sie den Verlosungstyp für die automatische Auslosung aus, geben Sie einfach eine Zahl an

0：Gewinner kann sich wiederholen

1：Gewinner kann sich nicht wiederholen

Antworte n, um den Standardtyp zu verwenden: 1

### Füge ein Passwort hinzu

Erstelle ein Passwort, damit Benutzer das Passwort direkt senden können, um am Gewinnspiel teilzunehmen

Antworte n, um kein Passwort hinzuzufügen

## Berechtigung

Um ein Gewinnspiel zu erstellen, musst du [bot-admin.md](../permission/bot-admin.md "mention") oder [channel-admin.md](../permission/channel-admin.md "mention") sein

Wenn die Option `allowNormalUserAdd` in den Einstellungen aktiviert ist, können auch [channel-member.md](../permission/channel-member.md "mention") den Vorgang durchführen

## Lokalisierung & Alias

Dieser Befehl kann auch wie folgt ausgelöst werden

```
/r hinzufügen

/Erstelle Gewinnspiel
```
