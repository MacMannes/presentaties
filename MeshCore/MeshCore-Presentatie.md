---
theme:
  name: gruvbox-dark
options:
  implicit_slide_ends: false
  h1_slide_titles: true
  end_slide_shorthand: true
---

<!-- alignment: center -->
<!-- newlines: 8 -->

![MeshCore](meshcore-logo.png)

<span style="color: blue">Door: André Mathlener</span>

---

# Wat is MeshCore?

<!-- column_layout: [2, 1] -->

<!-- column: 0 -->

## Algemeen

- Off-Grid berichten platform
- Gedecentraliseerd, geen internet nodig
- _Kan_ gebruikt worden als nood-communicatie
- Laagdrempelig, geen licentie nodig
- Alle berichten zijn _versleuteld_

## Manieren om te communiceren

- Kanalen
  - Public
  - #grunn, #stad, #testnoord
  - Privé Kanalen _(Private key nodig)_
- Direct Messaging
  - Zender en ontvanger moeten elkaar in het adresboek hebben

<!--column: 1 -->

<!-- newlines: 3 -->

![MeshCore](meshcore-mountains.jpg)

---

# Hoe werkt het?

<!-- column_layout: [1, 1] -->

<!-- column: 0 -->

- Werkt met LoRa
  - In NL gebruiken we `EU/UK Narrow` preset
    - Frequency: **`869.618 MHz`**
    - Bandwidth: **`62.5 kHz`**
    - Spreading Factor: **`8`** _(snelheid)_
    - Coding Rate: **`8`** _(foutcorrectie)_

- Verschillende nodes maken samen een netwerk
  - Repeaters sturen alleen signalen door
  - Companions sturen direct naar elkaar of via repeaters

<!-- column: 1 -->

![Netwerk](meshcore-netwerk.png)

---

# Verschil met Meshtastic

<!-- column_layout: [1, 1] -->

<!-- column: 0 -->

## MeshCore

- Slimmere routering _(Path discovery)_
  - Zoekt en onthoudt de beste route voor elk bericht
- Betere betrouwbaarheid
  - Berichten komen vaker aan
- Companions _repeaten_ niet
  - Lager batterij verbruik

<!-- column: 1 -->

## Meshtastic

- Flood routing
  - Berichten worden overal heen gestuurd
- Minder betrouwbaar
  - Berichten kunnen verdwalen in drukke netwerken
- Cpmpanions _repeaten_ wel
  - Hoger batterij verbruik

<!-- reset_layout -->

> Doordat bij MeshCore steeds minder berichten aankwamen, zijn heel veel
> Meshtastic gebruikers overgestapt naar MeshCore.

---

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

![Heltec V4](heltec-v4.jpg)
![t-echo](t-echo.jpg)

---

# Welke Hardware?

<!-- column_layout: [1, 1] -->

<!-- column: 0 -->

## Telefoon

- Een iOS of Android telefoon met de MeshCore app is nodig om te communiceren met de Companions.
- De telefoon communiceert via **Bluetooth** met de Companion.

<!-- column: 1 -->

![MeshCore App](meshcore-app.png)

---

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

![SenseCAP P1 Pro](seeed-sensecap-p1.png)

---

# Is alles perfect?
