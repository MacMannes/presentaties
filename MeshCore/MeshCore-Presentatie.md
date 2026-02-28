---
theme:
  name: gruvbox-dark
---

<!-- alignment: center -->
<!-- newlines: 8 -->

![MeshCore](meshcore-logo.png)

<span style="color: blue">Door: André Mathlener</span>

<!-- end_slide -->

# Wat is MeshCore?

- Off-Grid berichten platform
- Gedecentraliseerd, geen internet nodig
- Alle berichten zijn _versleuteld_
  - Kanalen
    - Public
    - #grunn, #stad, #testnoord
    - Privé Kanalen _(Private key nodig)_
  - Direct Messaging
    - Zender en ontvanger moeten elkaar in het adresboek hebben

<!-- end_slide -->

# Hoe werkt het?

- Werkt met LoRa
  - In NL gebruiken we `EU/UK Narrow` preset
    - Frequency: **`869.618 MHz`**
    - Bandwidth: **`62.5 kHz`**
    - Spreading Factor: **`8`** _(snelheid)_
    - Coding Rate: **`8`** _(foutcorrectie)_

- Verschillende nodes maken samen een netwerk
  - Repeaters sturen alleen signalen door
  - Companions sturen direct naar elkaar of via repeaters

<!-- end_slide -->

# Verschil met Meshtastic

<!-- column_layout: [1, 1] -->

<!-- column: 0 -->

## MeshCore

- Slimmere routering _(Path discovery)_
  - Zoekt en onthoudt de beste route voor elk bericht
- Schaalbaar
  - Werkt beter in grotere netwerken
- Betere betrouwbaarheid
  - Berichten komen vaker aan
- Companions _repeaten_ niet
  - Lager batterij verbruik

<!-- column: 1 -->

## Meshtastic

- Flood routing
  - Berichten worden overal heen gestuurd
- Schalingsproblemen
  - Wordt langzaam bij veel gebruikers
- Minder betrouwbaar
  - Berichten kunnen verdwalen in drukke netwerken
- Cpmpanions _repeaten_ wel
  - Hoger batterij verbruik

<!-- reset_layout -->

> Doordat bij MeshCore steeds minder berichten aankwamen, zijn de meeste Meshtastic gebruikers overgestapt naar MeshCore.
