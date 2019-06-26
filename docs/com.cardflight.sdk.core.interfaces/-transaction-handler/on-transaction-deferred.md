[payments-android-byod](../../index.md) / [com.cardflight.sdk.core.interfaces](../index.md) / [TransactionHandler](index.md) / [onTransactionDeferred](./on-transaction-deferred.md)

# onTransactionDeferred

`abstract fun onTransactionDeferred(transaction: `[`Transaction`](../../com.cardflight.sdk.core/-transaction/index.md)`, transactionData: `[`ByteArray`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Transaction was deferred.

### Parameters

`transaction` - Transaction this method was called from.

`transactionData` - Byte array representing the serialized transaction.