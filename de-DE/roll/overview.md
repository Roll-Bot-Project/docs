---
description: Roll Bot Hauptfunktionen
---

# Einführung

**Verlosung** ist eine Hauptfunktion von Roll Bot und umfasst Folgendes:

- Titel
- Detaillierte Beschreibung&#x20
- Preise
- Automatische Gewinnziehung
- Füge ein Passwort hinzu
- Öffnungsbereich
- Verwendete Erinnerung

Du kannst mit dem Befehl [add.md](add.md "mention") eine neue Verlosung erstellen und diese anschließend mit dem Befehl [edit-roll.md](../advanced/edit-roll.md "mention") bearbeiten.

## Beitrittscode zur Verlosung

Wenn für die Verlosung ein Beitrittscode festgelegt ist, können Benutzer diesen bequem im Kanal eingeben, um an der Verlosung teilzunehmen.Durch Eingabe des Beitrittscodes können Benutzer schnell an der Verlosung teilnehmen, ohne weitere Anweisungen lesen zu müssen.

## Bereich der Verlosungsteilnahme

Verlosungen sind standardmäßig nur für den aktuellen Kanal geöffnet.在创建后，你可以通过 [edit-roll.md](../advanced/edit-roll.md "mention") 指令来编辑抽奖的开放范围。这可以使多个频道的用户均可以参与抽奖。同一平台的同一用户只能参与一次。在跨平台环境下使用时，如果用户未使用 `bind` 指令绑定其不同平台的用户，则他将被视为不同的用户。

Private Nachrichten werden als Kanal mit nur dir und Roll Bot betrachtet, was bedeutet, dass du in privaten Nachrichten eine Verlosung erstellen und anschließend den Teilnahmebereich bearbeiten kannst.使用此方法可以隐藏创建抽奖的过程，避免刷屏。
