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

## Algemeen

- Off-Grid berichten platform
- Gedecentraliseerd, geen internet nodig
- Alle berichten zijn _versleuteld_

## Manieren om te communiceren

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

#### TODO: Plaatje van netwerk

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

> Doordat bij MeshCore steeds minder berichten aankwamen, zijn heel veel Meshtastic gebruikers overgestapt naar MeshCore.

<!--end_slide -->

# Welke Hardware?

<!-- column_layout: [1, 1] -->

<!-- column: 0 -->

## Companions

- **Heltec V3**
  - vanaf € 22,75
- **Heltec V4**
  - heeft een ingebouwde LNA
  - vanaf € 22,00
- **Heltec T114**
  - lager stroomverbruik
  - vanaf € 34,50
- LilyGo T-Echo
  - e-ink display, lager stroomverbruik
  - vanaf € 50,00
- **LilyGo T-Deck Plus**
  - geen telefoon nodig
- vanaf € 95,00

<!-- column: 1 -->

#### TODO: Plaatje

<!--end_slide -->

# Welke Hardware?

<!-- column_layout: [1, 1] -->

<!-- column: 0 -->

## Solar Repeaters

- **Seeed Studio SenseCAP P1 Pro**
  - De beste keuze voor outdoor MeshCore repeaters.
  - Vanaf € 90
- **WisMesh Solar Repeater**
  - Compacte solar repeater van RAK Wireless
  - Vanaf € 95
- Zelfbouw
  - XIAO nRF52840 & Wio-SX1262 Kit - € 12,00
  - Action Solar Schijnwerper: € 18,95
  - 6 dBi Antenne van kalkanstore.nl: € 27,50
    - Totaal: € 58,45

<!-- column: 1 -->

#### TODO: Plaatje

<!--end_slide -->
