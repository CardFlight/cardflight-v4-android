[payments-android-byod](../../index.md) / [com.cardflight.sdk.enumerations](../index.md) / [CardInputMethod](./index.md)

# CardInputMethod

`enum class ~~CardInputMethod~~`
**Deprecated:** Use com.cardflight.sdk.core.enums.CardInputMethod instead. This class will be removed in v4.9.0.

Specifies the method by which card info was generated

Copyright © 2019 CardFlight. All rights reserved.

**Author**
Austin Odell

**Since**
v4.0.0

### Enum Values

| Name | Summary |
|---|---|
| [UNKNOWN](-u-n-k-n-o-w-n.md) | Unknown method, should not occur in normal operation |
| [KEY](-k-e-y.md) | Card info generated from key entry |
| [SWIPE](-s-w-i-p-e.md) | Card info generated from swipe data |
| [SWIPE_FALLBACK](-s-w-i-p-e_-f-a-l-l-b-a-c-k.md) | Card info generated from swipe data (fallback from [DIP](-d-i-p.md)) |
| [DIP](-d-i-p.md) | Card info generated from dipped data |
| [TAP](-t-a-p.md) | Card info generated from NFC tapped data |
| [QUICK_CHIP](-q-u-i-c-k_-c-h-i-p.md) | Card info generated from dipped (quick chip) data |
