[payments-android-byod](../../index.md) / [com.cardflight.sdk](../index.md) / [TransactionManager](index.md) / [resumeDeferredTransaction](./resume-deferred-transaction.md)

# resumeDeferredTransaction

`fun resumeDeferredTransaction(context: `[`Context`](https://developer.android.com/reference/android/content/Context.html)`, data: `[`ByteArray`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)`, handler: `[`TransactionHandler`](../../com.cardflight.sdk.core.interfaces/-transaction-handler/index.md)`, onComplete: (transaction: `[`Transaction`](../../com.cardflight.sdk.core/-transaction/index.md)`?, `[`Error`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-error/index.html)`?) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Resumes a previously deferred [Transaction](../../com.cardflight.sdk.core/-transaction/index.md).

### Parameters

`context` - Android context object.

`data` - Byte array representing transaction.

`handler` - TransactionHandler to attach to transaction.

`onComplete` - Block run when the transaction has been resumed or if an error occured.