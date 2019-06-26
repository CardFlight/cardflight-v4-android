[payments-android-byod](../../index.md) / [com.cardflight.sdk.core.interfaces](../index.md) / [TransactionHandler](index.md) / [onRequestCardAidSelection](./on-request-card-aid-selection.md)

# onRequestCardAidSelection

`abstract fun onRequestCardAidSelection(transaction: `[`Transaction`](../../com.cardflight.sdk.core/-transaction/index.md)`, cardAidArray: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<`[`CardAID`](../../com.cardflight.sdk.core/-card-a-i-d/index.md)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Card Application selection requested as the result of multiple application being available on the presented card.

### Parameters

`transaction` - Transaction this method was called from.

`cardAidArray` - Card AIDs available for the user to select from.