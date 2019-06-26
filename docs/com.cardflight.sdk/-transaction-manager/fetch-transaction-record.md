[payments-android-byod](../../index.md) / [com.cardflight.sdk](../index.md) / [TransactionManager](index.md) / [fetchTransactionRecord](./fetch-transaction-record.md)

# fetchTransactionRecord

`fun fetchTransactionRecord(id: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, merchantAccount: `[`MerchantAccount`](../../com.cardflight.sdk.core/-merchant-account/index.md)`, onComplete: (transactionRecord: `[`TransactionRecord`](../../com.cardflight.sdk.core/-transaction-record/index.md)`?, `[`Error`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-error/index.html)`?) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Fetch a [TransactionRecord](../../com.cardflight.sdk.core/-transaction-record/index.md) from the API.

### Parameters

`id` - ID of the transaction.

`merchantAccount` - MerchantAccount owning the transaction.

`onComplete` - Block run when TransactionRecord fetching has completed.