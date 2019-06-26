[payments-android-byod](../../index.md) / [com.cardflight.sdk](../index.md) / [TransactionManager](index.md) / [createTokenization](./create-tokenization.md)

# createTokenization

`fun createTokenization(merchantAccount: `[`MerchantAccount`](../../com.cardflight.sdk.core/-merchant-account/index.md)`, customerId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?, handler: `[`TransactionHandler`](../../com.cardflight.sdk.core.interfaces/-transaction-handler/index.md)`, onComplete: (transaction: `[`Transaction`](../../com.cardflight.sdk.core/-transaction/index.md)`?, `[`Error`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-error/index.html)`?) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Creates a new [Transaction](../../com.cardflight.sdk.core/-transaction/index.md) with transaction type
[tokenization](../../com.cardflight.sdk.core.enums/-transaction-type/-t-o-k-e-n-i-z-a-t-i-o-n.md).

An exception will always be thrown as this method is not supported.

### Parameters

`merchantAccount` - Merchant account to associate to the card.

`customerId` - Customer ID to associate to card. If one is not specified, a new customer will be created.

`handler` - TransactionHandler to listen to transaction events.

`onComplete` - Block executed when a transaction has been created or if an error has occurred.