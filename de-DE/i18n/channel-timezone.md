---
description: Der Kanal-Zeitzone bestimmt die Zeitzone, die von allen Benutzern im Kanal verwendet wird, wenn sie mit Roll Bot interagieren
---

# Kanal-Zeitzone

> Die Verschiebung ist der Unterschied zwischen der Zeitzone und der UTC-Standardzeit, im Format +Stunden:Minuten:Sekunden oder -Stunden:Minuten:Sekunden
>
> Zum Beispiel `+5` oder `-9:30`

```
/roll time -c [Verschiebung]
```

Die Verschiebung ist optional und wenn sie leer gelassen wird, wird die aktuelle Verschiebung des Kanals zurückgegeben

## Priorität

[channel-timezone.md](channel-timezone.md "Erwähnung") > [user-timezone.md](user-timezone.md "Erwähnung") > [Standardzeitzone](../configuration/basic.md#defaulttimeoffset)

Sie können den `i18n.output`-Parameter in den Einstellungen ändern, um diese Reihenfolge anzupassen

## Berechtigung

Um die Kanal-Zeitzone zu ändern, müssen Sie [bot-admin.md](../permission/bot-admin.md "Erwähnung") oder [channel-admin.md](../permission/channel-admin.md "Erwähnung") sein

## Lokalisierung & Alias

Dieser Befehl kann auch wie folgt ausgelöst werden

```
/r time -c [Verschiebung]

/Zeitzone -c [Verschiebung]
```
