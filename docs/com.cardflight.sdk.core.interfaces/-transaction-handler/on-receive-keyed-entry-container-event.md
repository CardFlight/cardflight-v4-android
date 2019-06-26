[payments-android-byod](../../index.md) / [com.cardflight.sdk.core.interfaces](../index.md) / [TransactionHandler](index.md) / [onReceiveKeyedEntryContainerEvent](./on-receive-keyed-entry-container-event.md)

# onReceiveKeyedEntryContainerEvent

`abstract fun onReceiveKeyedEntryContainerEvent(transaction: `[`Transaction`](../../com.cardflight.sdk.core/-transaction/index.md)`, keyedEntryContainerEvent: `[`KeyedEntryContainerEvent`](../../com.cardflight.sdk.core.enums/-keyed-entry-container-event/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

A keyed entry event occurred.

### Parameters

`transaction` - Transaction this method was called from.

`keyedEntryContainerEvent` - Event that occurred while interacting with the KeyedEntryContainer.