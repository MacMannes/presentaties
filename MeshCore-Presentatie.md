# MeshCore Presentatie

## Wat is MeshCore?

- Off-Grid berichten platform
  - Gedecentraliseerd, geen internet nodig
  - Kanalen
    - Public
    - #grunn, #stad, #testnoord
    - Privé Kanalen
      - Private key nodig
  - Direct Messaging
    - Zender en ontvanger moeten elkaar in het adresboek hebben
  - Alle berichten zijn _versleuteld_

## Hoe werkt het?

- Werkt met LoRa
  - In NL gebruiken we `EU/UK Narrow` preset
    - Frequency: **869.618 MHz**
    - Bandwidth: **62.5 kHz**
    - Spreading Factor: **8** _(snelheid)_
    - Coding Rate: **8** _(foutcorrectie)_
- Verschillende nodes maken samen een netwerk
  - Repeaters sturen de signalen door
  - Companions
