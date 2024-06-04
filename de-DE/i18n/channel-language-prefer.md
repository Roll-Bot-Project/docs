---
description: Der Kanalsprachpräferenz bestimmt die Sprache, die von allen Benutzern im Kanal bei der Interaktion mit Roll Bot verwendet wird
---

# Kanalsprachpräferenz

> Roll Bot unterstützt derzeit die folgenden Sprachen: `zh-CN` `en-US` de-DE

```
/roll lokal -c [Sprachpräferenz]
```

Die Sprachpräferenz ist optional. Wenn sie leer gelassen wird, wird die aktuelle Einstellung der Gruppe zurückgegeben

## Priorität

[channel-language-prefer.md](channel-language-prefer.md "Erwähnung") > [user-language-prefer.md](user-language-prefer.md "Erwähnung") > Standard-Sprachpräferenz

Sie können den `i18n.output`-Parameter in den Einstellungen ändern, um diese Reihenfolge anzupassen

## Reset Kanal Sprachpräferenzeinstellungen

Du kannst `-d` Parameter im Befehl verwenden, um die Sprachpräferenzeinstellungen des aktuellen Kanals zurückzusetzen:

```
/roll locale -c -d
```

## Berechtigung

Um die Kanalsprachpräferenz zu ändern, müssen Sie [bot-admin.md](../permission/bot-admin.md "Erwähnung") oder [channel-admin.md](../permission/channel-admin.md "Erwähnung") sein

## Lokalisierung & Alias

Dieser Befehl kann auch wie folgt ausgelöst werden

```
/r lokal -c [Sprachpräferenz]

/lingua -c [Sprachpräferenz]
```
