[payments-android-byod](../../index.md) / [com.cardflight.sdk](../index.md) / [TransactionManager](index.md) / [captureAuth](./capture-auth.md)

# captureAuth

`fun captureAuth(amount: `[`Amount`](../../com.cardflight.sdk.core/-amount/index.md)`, transactionRecord: `[`TransactionRecord`](../../com.cardflight.sdk.core/-transaction-record/index.md)`, handler: `[`TransactionHandler`](../../com.cardflight.sdk.core.interfaces/-transaction-handler/index.md)`, onComplete: (transaction: `[`Transaction`](../../com.cardflight.sdk.core/-transaction/index.md)`?, `[`Error`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-error/index.html)`?) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Captures a [Transaction](../../com.cardflight.sdk.core/-transaction/index.md) with transaction type
[authorization](../../com.cardflight.sdk.core.enums/-transaction-type/-a-u-t-h-o-r-i-z-a-t-i-o-n.md).

An exception will always be thrown as this method is not supported.

### Parameters

`transactionRecord` - TransactionRecord object to use.

`handler` - TransactionHandler to listen to transaction events.

`onComplete` - Block executed when a transaction has been created or if an error has occurred.