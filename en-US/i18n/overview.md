---
description: Internationalization
---

# Introduction

Roll Bot supports different time zones and languages.

## Timezone

Roll Bot uses [offset](https://en.wikipedia.org/wiki/UTC_offset) to record time zones, and utilizes it when parsing and sending times.

Since the offset is a fixed value, users using daylight time may need to adjust their offsets several times.

## Language preferences

Roll Bot uses [IETF language tag](https://en.wikipedia.org/wiki/IETF_language_tag) to record language preferences, and uses it when sending content.

Language currently supported by Roll Bot includes `en-US` `de-DE`

## Priority

Use the following priority： when Roll Bot processes time zone and language preferences

**Channel Settings > User Settings > Default Setting**

You can adjust the `i18n.output` entry in the settings to change this order
