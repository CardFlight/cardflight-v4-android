[payments-android-byod](../../index.md) / [com.cardflight.sdk](../index.md) / [MerchantAccountManager](index.md) / [validate](./validate.md)

# validate

`fun validate(merchantAccount: `[`MerchantAccount`](../../com.cardflight.sdk.core/-merchant-account/index.md)`, onComplete: (isSuccess: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`, `[`Error`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-error/index.html)`?) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Validates the MerchantAccount object with the CardFlight API.

### Exceptions

`IllegalArgumentException` - if you pass a merchant account not created using MerchantAccountManager.

### Parameters

`merchantAccount` - MerchantAccount object to validate.

`onComplete` - Block run when validation is complete.`fun validate(merchantAccount: `[`MerchantAccount`](../../com.cardflight.sdk.core/-merchant-account/index.md)`, handler: `[`CompletionHandler`](../../com.cardflight.sdk.core.interfaces/-completion-handler/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Validates the MerchantAccount object with the CardFlight API.

### Exceptions

`IllegalArgumentException` - if you pass a merchant account not created using MerchantAccountManager.

### Parameters

`merchantAccount` - MerchantAccount object to validate.

`handler` - Completion handler for when validation is complete.