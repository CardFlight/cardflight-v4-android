[payments-android-byod](../../index.md) / [com.cardflight.sdk.core.interfaces](../index.md) / [TransactionRecordHandler](index.md) / [onComplete](./on-complete.md)

# onComplete

`abstract fun onComplete(transactionRecord: `[`TransactionRecord`](../../com.cardflight.sdk.core/-transaction-record/index.md)`?, error: `[`Error`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-error/index.html)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Transaction record was created or errored.

### Parameters

`transactionRecord` - Transaction record resulting from the interaction. Can be null if an error occurred.

`error` - Error that may have occurred.