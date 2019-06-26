[payments-android-byod](../../index.md) / [com.cardflight.sdk.core.interfaces](../index.md) / [ReaderUtilitiesHandler](index.md) / [onReceiveCardReaderEvent](./on-receive-card-reader-event.md)

# onReceiveCardReaderEvent

`abstract fun onReceiveCardReaderEvent(cardReaderInfo: `[`CardReaderInfo`](../../com.cardflight.sdk.core/-card-reader-info/index.md)`?, cardReaderEvent: `[`CardReaderEvent`](../../com.cardflight.sdk.core.enums/-card-reader-event/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

A card reader event occurred.

### Parameters

`cardReaderInfo` - Card reader the event occurred with. Can be null if event occurred before successful connection.

`cardReaderEvent` - Event that occurred.