---
description: Benutzerpräferenzsprache bestimmt die Sprache, die der Benutzer bei der Interaktion mit Roll Bot verwendet
---

# Benutzerpräferenzsprache

> Roll Bot unterstützt derzeit die folgenden Sprachen: `zh-CN` `en-US` de-DE

```
/roll locale [Benutzerpräferenzsprache]
```

Die Benutzerpräferenzsprache ist optional; wenn sie leer gelassen wird, wird Ihre aktuelle Einstellung zurückgegeben

## Priorität

[channel-language-prefer.md](channel-language-prefer.md "Erwähnung") > [user-language-prefer.md](user-language-prefer.md "Erwähnung") > Standard-Sprachpräferenz

Sie können den `i18n.output`-Parameter in den Einstellungen ändern, um diese Reihenfolge anzupassen

## Zurücksetzen der Benutzervorlieben für Sprache

Sie können Ihre Sprachvorlieben mit dem `-d` -Parameter in Befehlen zurücksetzen:

```
/roll locale -d
```

## Lokalisierung & Alias

Dieser Befehl kann auch wie folgt ausgelöst werden

```
/r locale [Benutzerpräferenzsprache]

/Sprache [Benutzerpräferenzsprache]
```
