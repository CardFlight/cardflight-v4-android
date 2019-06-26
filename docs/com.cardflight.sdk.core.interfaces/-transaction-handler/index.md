[payments-android-byod](../../index.md) / [com.cardflight.sdk.core.interfaces](../index.md) / [TransactionHandler](./index.md)

# TransactionHandler

`interface TransactionHandler`

Handler used to interact with and receive updates from the transaction.

Copyright © 2019 CardFlight. All rights reserved.

**Author**
Austin Odell

**Since**
v1.0.0

### Functions

| Name | Summary |
|---|---|
| [onComplete](on-complete.md) | `abstract fun onComplete(transaction: `[`Transaction`](../../com.cardflight.sdk.core/-transaction/index.md)`, transactionRecord: `[`TransactionRecord`](../../com.cardflight.sdk.core/-transaction-record/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Transaction has completed. |
| [onReceiveCardReaderEvent](on-receive-card-reader-event.md) | `abstract fun onReceiveCardReaderEvent(transaction: `[`Transaction`](../../com.cardflight.sdk.core/-transaction/index.md)`, cardReaderInfo: `[`CardReaderInfo`](../../com.cardflight.sdk.core/-card-reader-info/index.md)`?, cardReaderEvent: `[`CardReaderEvent`](../../com.cardflight.sdk.core.enums/-card-reader-event/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>A card reader event occurred. |
| [onReceiveKeyedEntryContainerEvent](on-receive-keyed-entry-container-event.md) | `abstract fun onReceiveKeyedEntryContainerEvent(transaction: `[`Transaction`](../../com.cardflight.sdk.core/-transaction/index.md)`, keyedEntryContainerEvent: `[`KeyedEntryContainerEvent`](../../com.cardflight.sdk.core.enums/-keyed-entry-container-event/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>A keyed entry event occurred. |
| [onRequestAdjustment](on-request-adjustment.md) | `abstract fun onRequestAdjustment(transaction: `[`Transaction`](../../com.cardflight.sdk.core/-transaction/index.md)`, cvm: `[`CVM`](../../com.cardflight.sdk.core.enums/-c-v-m/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Adjustment requested. |
| [onRequestCardAidSelection](on-request-card-aid-selection.md) | `abstract fun onRequestCardAidSelection(transaction: `[`Transaction`](../../com.cardflight.sdk.core/-transaction/index.md)`, cardAidArray: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<`[`CardAID`](../../com.cardflight.sdk.core/-card-a-i-d/index.md)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Card Application selection requested as the result of multiple application being available on the presented card. |
| [onRequestCvm](on-request-cvm.md) | `abstract fun onRequestCvm(transaction: `[`Transaction`](../../com.cardflight.sdk.core/-transaction/index.md)`, cvm: `[`CVM`](../../com.cardflight.sdk.core.enums/-c-v-m/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Cardholder verification requested. |
| [onRequestDisplayMessage](on-request-display-message.md) | `abstract fun onRequestDisplayMessage(transaction: `[`Transaction`](../../com.cardflight.sdk.core/-transaction/index.md)`, message: `[`Message`](../../com.cardflight.sdk.core/-message/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>A display message is requested. |
| [onRequestProcessOption](on-request-process-option.md) | `abstract fun onRequestProcessOption(transaction: `[`Transaction`](../../com.cardflight.sdk.core/-transaction/index.md)`, cardInfo: `[`CardInfo`](../../com.cardflight.sdk.core/-card-info/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Process option requested. |
| [onTransactionDeferred](on-transaction-deferred.md) | `abstract fun onTransactionDeferred(transaction: `[`Transaction`](../../com.cardflight.sdk.core/-transaction/index.md)`, transactionData: `[`ByteArray`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Transaction was deferred. |
| [onTransactionStateUpdate](on-transaction-state-update.md) | `abstract fun onTransactionStateUpdate(transaction: `[`Transaction`](../../com.cardflight.sdk.core/-transaction/index.md)`, transactionState: `[`TransactionState`](../../com.cardflight.sdk.core.enums/-transaction-state/index.md)`, error: `[`Error`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-error/index.html)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Transaction state was updated or errored. |
| [onUpdateCardInputMethods](on-update-card-input-methods.md) | `abstract fun onUpdateCardInputMethods(transaction: `[`Transaction`](../../com.cardflight.sdk.core/-transaction/index.md)`, cardInputMethodArray: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<`[`CardInputMethod`](../../com.cardflight.sdk.core.enums/-card-input-method/index.md)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Card input methods available was updated. |
| [onUpdateCardReaders](on-update-card-readers.md) | `abstract fun onUpdateCardReaders(transaction: `[`Transaction`](../../com.cardflight.sdk.core/-transaction/index.md)`, cardReaderInfoArray: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<`[`CardReaderInfo`](../../com.cardflight.sdk.core/-card-reader-info/index.md)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Card readers available was updated. |
