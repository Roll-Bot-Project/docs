---
description: Benutzerzeitzone entscheidet über die lokale Zeit, die beim Interagieren mit Roll Bot verwendet wird
---

# Benutzerzeitzone

> Die Verschiebung ist der Unterschied zwischen der Zeitzone und der UTC-Standardzeit, im Format +Stunden:Minuten:Sekunden oder -Stunden:Minuten:Sekunden
>
> zum Beispiel `+8` oder `-9:30 oder −00:25:21 (wenn Sie sich im Irland des Jahres 1880 befinden)`

```
/roll time [Versatz]
```

Der Versatz ist optional und wird leer gelassen, um Ihren aktuellen Versatz zurückzugeben

## Priorität

[channel-timezone.md](channel-timezone.md "Erwähnung") > [user-timezone.md](user-timezone.md "Erwähnung") > [Standardzeitzone](../configuration/basic.md#defaulttimeoffset)

Sie können den `i18n.output`-Parameter in den Einstellungen ändern, um diese Reihenfolge anzupassen

## Parameter zurücksetzen Nutzer Zeitzone Einstellungen

Du kannst `-d` Parameter zum Zurücksetzen deiner Zeitzone Einstellungen im Befehl verwenden:

```
/roll Zeit -d
```

## Lokalisierung & Alias

Dieser Befehl kann auch wie folgt ausgelöst werden

```
/r time [Versatz]

/Zeitzone [Versatz]
```
