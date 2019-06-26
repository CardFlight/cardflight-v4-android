[payments-android-byod](../../index.md) / [com.cardflight.sdk.core.interfaces](../index.md) / [TransactionHandler](index.md) / [onTransactionStateUpdate](./on-transaction-state-update.md)

# onTransactionStateUpdate

`abstract fun onTransactionStateUpdate(transaction: `[`Transaction`](../../com.cardflight.sdk.core/-transaction/index.md)`, transactionState: `[`TransactionState`](../../com.cardflight.sdk.core.enums/-transaction-state/index.md)`, error: `[`Error`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-error/index.html)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Transaction state was updated or errored.

### Parameters

`transaction` - Transaction this method was called from.

`transactionState` - State of the transaction. Can be the same as previously reported if an error occurred.

`error` - Any error that may have occurred.