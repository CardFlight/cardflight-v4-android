[payments-android-byod](../../index.md) / [com.cardflight.sdk](../index.md) / [TransactionManager](index.md) / [attemptVoid](./attempt-void.md)

# attemptVoid

`fun attemptVoid(transactionRecord: `[`TransactionRecord`](../../com.cardflight.sdk.core/-transaction-record/index.md)`, handler: `[`TransactionHandler`](../../com.cardflight.sdk.core.interfaces/-transaction-handler/index.md)`, onComplete: (transaction: `[`Transaction`](../../com.cardflight.sdk.core/-transaction/index.md)`?, `[`Error`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-error/index.html)`?) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Attempt to void a [Transaction](../../com.cardflight.sdk.core/-transaction/index.md).

*Will only succeed if transaction is in current open batch.*

An error will be returned in the following cases:

* The CardFlight API could not be reached.

Exception can be thrown in the following cases:

* There is already an active Transaction running.
* The TransactionRecord was not created by the CardFlight Payments SDK.
* The TransactionRecord's transactionId is blank.

### Parameters

`transactionRecord` - TransactionRecord object to use.

`handler` - TransactionHandler to listen to transaction events.

`onComplete` - Block executed when a transaction has been created or if an error has occurred.