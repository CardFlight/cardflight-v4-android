[payments-android-byod](../../index.md) / [com.cardflight.sdk.core.interfaces](../index.md) / [TransactionHandler](index.md) / [onReceiveCardReaderEvent](./on-receive-card-reader-event.md)

# onReceiveCardReaderEvent

`abstract fun onReceiveCardReaderEvent(transaction: `[`Transaction`](../../com.cardflight.sdk.core/-transaction/index.md)`, cardReaderInfo: `[`CardReaderInfo`](../../com.cardflight.sdk.core/-card-reader-info/index.md)`?, cardReaderEvent: `[`CardReaderEvent`](../../com.cardflight.sdk.core.enums/-card-reader-event/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

A card reader event occurred.

### Parameters

`transaction` - Transaction this method was called from.

`cardReaderInfo` - Card reader event occurred with. Can be null if the event occurred before successful connection.

`cardReaderEvent` - Event that occurred while interacting with a card reader.