[payments-android-byod](../../index.md) / [com.cardflight.sdk.core.enums](../index.md) / [CardReaderModel](./index.md)

# CardReaderModel

`enum class CardReaderModel`

All compatible card readers, with their interface and supported card input methods

Copyright © 2019 CardFlight. All rights reserved.

**Author**
Austin Odell

**Since**
v1.0.0

### Enum Values

| Name | Summary |
|---|---|
| [UNKNOWN](-u-n-k-n-o-w-n.md) | Unknown reader model. |
| [SHUTTLE](-s-h-u-t-t-l-e.md) | Shuttle: Audio jack, swipe only. |
| [BTMAG](-b-t-m-a-g.md) | BTMag: Bluetooth, swipe only. |
| [A100](-a100.md) | A100: Audio jack, swipe only. |
| [A200](-a200.md) | A200: Audio jack, swipe and dip. |
| [B550](-b550.md) | B550: Bluetooth, swipe, dip, and tap. |
| [B500](-b500.md) | B500: Bluetooth, swipe and dip. |
| [A250](-a250.md) | A250: Audio jack, swipe, dip, and tap. |
| [B200](-b200.md) | B200: Bluetooth, swipe and dip. |
| [B250](-b250.md) | B250: Bluetooth, swipe, dip, and tap. |
| [PAX_A920](-p-a-x_-a920.md) | PAX A920: Built In, swipe, dip, and tap. |

### Properties

| Name | Summary |
|---|---|
| [cardReaderModelName](card-reader-model-name.md) | `val cardReaderModelName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Name of card reader model. |
| [cardReaderType](card-reader-type.md) | `val cardReaderType: `[`CardReaderType`](../-card-reader-type/index.md)<br>[CardReaderType](../-card-reader-type/index.md) for card reader model. |
| [number](number.md) | `val number: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Get the name prefix for the specified card reader |
| [supportedCardInputMethods](supported-card-input-methods.md) | `val supportedCardInputMethods: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`CardInputMethod`](../-card-input-method/index.md)`>`<br>List of supported [card input methods](../-card-input-method/index.md) for the card reader model. |

### Functions

| Name | Summary |
|---|---|
| [getName](get-name.md) | `fun ~~getName~~(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
