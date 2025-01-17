---
editable: false
---
# Pricing for [!KEYREF speechkit-name]

[!INCLUDE [currency-choice](../_includes/pricing/currency-choice.md)]

## What goes into the cost of use for [!KEYREF speechkit-short-name] {#rules}

### Speech synthesis use {#rules-tts}

The cost of using the SpeechKit API for speech synthesis is calculated from the total number of characters sent to generate speech from text over a calendar month (the reporting period).

[!INCLUDE [pricing-symbol-count](../_includes/pricing-symbol-count.md)]

### Speech recognition use {#rules-stt}

The cost of using the SpeechKit API for speech recognition is calculated from the length of audio files successfully processed by the service during the reporting period. The length of each audio file is measured in 15-second segments and rounded up.

#### Examples {#rules-stt-examples}

- You send a 37-second fragment for speech recognition. Your request is split into three segments: two that are 15 seconds long, and one that is 7 seconds long. The length of the last segment is rounded up to 15 seconds. The final cost of the request is calculated for 45 seconds.
- You made two requests, for 5 and 8 seconds, respectively. The length of each request is rounded up to 15 seconds. The final cost of the request is calculated for 30 seconds.

## Pricing {#prices}

### Speech synthesis {#prices-tts}

---

**[!TAB Prices in USD]**

| Service | Rate for 1 million characters, without VAT |
| ----- | ----- |
| Speech synthesis | $2.346805 |

**[!TAB Prices in roubles]**

| Service | Rate per 1 million characters,<br/>with VAT |
| ----- | ----- |
| Speech synthesis | ₽183.0508 |

---

### Speech recognition {#prices-stt}

You are only charged for [recognition of short audio recordings](stt/request.md) and [data streaming recognition](stt/streaming.md).

[Recognition of long audio recordings](stt/transcribation.md) is free of charge during the [Preview stage](../overview/concepts/launch-stages).

---

**[!TAB Prices in USD]**

| Service | Rate for 15 sec segment, without VAT |
| ----- | ----- |
| Speech recognition | $0.001953 |

**[!TAB Prices in roubles]**

| Service | Rate for 15 sec segment, with VAT |
| ----- | ----- |
| Speech recognition | ₽0.1524 |

---