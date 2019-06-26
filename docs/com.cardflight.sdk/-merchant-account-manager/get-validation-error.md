[payments-android-byod](../../index.md) / [com.cardflight.sdk](../index.md) / [MerchantAccountManager](index.md) / [getValidationError](./get-validation-error.md)

# getValidationError

`fun getValidationError(merchantAccount: `[`MerchantAccount`](../../com.cardflight.sdk.core/-merchant-account/index.md)`, onComplete: (`[`Error`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-error/index.html)`?) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Gives any errors with the MerchantAccount object.

### Exceptions

`IllegalArgumentException` - if you pass a merchant account not created using MerchantAccountManager.

### Parameters

`merchantAccount` - MerchantAccount object to get validation error for.

`onComplete` - Block run when error is retrieved.