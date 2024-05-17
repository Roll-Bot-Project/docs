---
description: Internationalisierungsfunktion
---

# Einführung

Roll Bot bietet Unterstützung für verschiedene Zeitzonen und Sprachen.

## Zeitzone

Roll Bot verwendet den [Zeitunterschied (Offset)](https://zh.wikipedia.org/wiki/UTC%E5%81%8F%E7%A7%BB%E9%87%8F) zur Aufzeichnung der Zeitzone und zur Verwendung beim Analysieren und Senden von Zeitangaben.

Da der Offset ein fester Wert ist, müssen Benutzer, die die Sommerzeit verwenden, möglicherweise ihren Offset mehrmals anpassen.

## Sprachpräferenz

Roll Bot verwendet den [IETF-Sprachtag (IETF language tag)](https://zh.wikipedia.org/wiki/IETF%E8%AA%9E%E8%A8%80%E6%A8%99%E7%B1%A4) zur Aufzeichnung der Sprachpräferenz und zur Verwendung beim Senden von Inhalten.

Derzeit unterstützt Roll Bot Sprachpakete wie `zh-CN` `en-US` `de-DE`

## Priorität

Roll Bot priorisiert die Behandlung von Zeitzonen und Sprachpräferenzen wie folgt:

**Kanal Einstellungen > Benutzereinstellungen > Standard Einstellungen**

Sie können den `i18n.output`-Parameter in den Einstellungen ändern, um diese Reihenfolge anzupassen
