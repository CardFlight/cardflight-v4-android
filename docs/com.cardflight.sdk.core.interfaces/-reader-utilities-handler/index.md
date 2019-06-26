[payments-android-byod](../../index.md) / [com.cardflight.sdk.core.interfaces](../index.md) / [ReaderUtilitiesHandler](./index.md)

# ReaderUtilitiesHandler

`interface ReaderUtilitiesHandler`

ReaderUtilitiesHandler is used to communicate updates from the ReaderUtilities object.

Copyright © 2019 CardFlight. All rights reserved.

**Author**
Austin Odell

**Since**
v1.0.0

### Functions

| Name | Summary |
|---|---|
| [onReceiveCardReaderEvent](on-receive-card-reader-event.md) | `abstract fun onReceiveCardReaderEvent(cardReaderInfo: `[`CardReaderInfo`](../../com.cardflight.sdk.core/-card-reader-info/index.md)`?, cardReaderEvent: `[`CardReaderEvent`](../../com.cardflight.sdk.core.enums/-card-reader-event/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>A card reader event occurred. |
| [onSessionStateUpdate](on-session-state-update.md) | `abstract fun onSessionStateUpdate(state: `[`ReaderUtilitiesState`](../../com.cardflight.sdk.core.enums/-reader-utilities-state/index.md)`, error: `[`Error`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-error/index.html)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Session state was updated or errored. |
| [onUpdateCardReaderCompatibility](on-update-card-reader-compatibility.md) | `abstract fun onUpdateCardReaderCompatibility(cardReaderInfo: `[`CardReaderInfo`](../../com.cardflight.sdk.core/-card-reader-info/index.md)`?, cardReaderCompatibility: `[`CardReaderCompatibility`](../../com.cardflight.sdk.core.enums/-card-reader-compatibility/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Card reader compatibility was updated. |
| [onUpdateCardReaders](on-update-card-readers.md) | `abstract fun onUpdateCardReaders(cardReaderInfoArray: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<`[`CardReaderInfo`](../../com.cardflight.sdk.core/-card-reader-info/index.md)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Card readers available was updated. |
