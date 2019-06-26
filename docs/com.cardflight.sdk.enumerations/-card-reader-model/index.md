[payments-android-byod](../../index.md) / [com.cardflight.sdk.enumerations](../index.md) / [CardReaderModel](./index.md)

# CardReaderModel

`enum class ~~CardReaderModel~~`
**Deprecated:** Use com.cardflight.sdk.core.enums.CardReaderModel instead. This class will be removed in v4.9.0.

All compatible card readers, with their interface and supported card input methods

Copyright © 2019 CardFlight. All rights reserved.

### Parameters

`cardInputMethodArray` - Array of supported [card input methods](../../com.cardflight.sdk.core.enums/-card-input-method/index.md) for the card reader model.

**Author**
Austin Odell

**Since**
v4.0.0

### Enum Values

| Name | Summary |
|---|---|
| [UNKNOWN](-u-n-k-n-o-w-n.md) | Unknown reader model |
| [SHUTTLE](-s-h-u-t-t-l-e.md) | Shuttle: Audio jack, swipe only |
| [BTMAG](-b-t-m-a-g.md) | BTMag: Bluetooth, swipe only |
| [A100](-a100.md) | A100: Audio jack, swipe only |
| [A200](-a200.md) | A200: Audio jack, swipe and dip |
| [B550](-b550.md) | B550: Bluetooth, swipe, dip, and tap |
| [B500](-b500.md) | B500: Bluetooth, swipe and dip |
| [A250](-a250.md) | A250: Audio jack, swipe, dip, and tap |
| [B200](-b200.md) | B200: Bluetooth, swipe and dip |
| [B250](-b250.md) | B250: Bluetooth, swipe, dip, and tap |

### Properties

| Name | Summary |
|---|---|
| [cardInputMethodArray](card-input-method-array.md) | `val cardInputMethodArray: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<`[`CardInputMethod`](../../com.cardflight.sdk.core.enums/-card-input-method/index.md)`>`<br>Array of supported [card input methods](../../com.cardflight.sdk.core.enums/-card-input-method/index.md) for the card reader model. |

### Functions

| Name | Summary |
|---|---|
| [getName](get-name.md) | `fun getName(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
