[payments-android-byod](../../index.md) / [com.cardflight.sdk.core.interfaces](../index.md) / [TransactionHandler](index.md) / [onRequestAdjustment](./on-request-adjustment.md)

# onRequestAdjustment

`abstract fun onRequestAdjustment(transaction: `[`Transaction`](../../com.cardflight.sdk.core/-transaction/index.md)`, cvm: `[`CVM`](../../com.cardflight.sdk.core.enums/-c-v-m/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Adjustment requested.

### Parameters

`transaction` - Transaction this method was called from.

`cvm` - Cardholder verification method to request from the user.