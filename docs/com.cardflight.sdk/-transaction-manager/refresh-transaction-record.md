[payments-android-byod](../../index.md) / [com.cardflight.sdk](../index.md) / [TransactionManager](index.md) / [refreshTransactionRecord](./refresh-transaction-record.md)

# refreshTransactionRecord

`fun refreshTransactionRecord(transactionRecord: `[`TransactionRecord`](../../com.cardflight.sdk.core/-transaction-record/index.md)`, onComplete: (isSuccess: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`, `[`Error`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-error/index.html)`?) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Refresh a [TransactionRecord](../../com.cardflight.sdk.core/-transaction-record/index.md) from the API.

### Parameters

`transactionRecord` - TransactionRecord to refresh.

`onComplete` - Block run when TransactionRecord refreshing has completed.