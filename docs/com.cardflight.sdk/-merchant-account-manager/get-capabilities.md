[payments-android-byod](../../index.md) / [com.cardflight.sdk](../index.md) / [MerchantAccountManager](index.md) / [getCapabilities](./get-capabilities.md)

# getCapabilities

`fun getCapabilities(merchantAccount: `[`MerchantAccount`](../../com.cardflight.sdk.core/-merchant-account/index.md)`, onComplete: (capabilities: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`MerchantAccountCapability`](../../com.cardflight.sdk.core.enums/-merchant-account-capability/index.md)`>) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Gets capabilities for a Merchant Account.

### Parameters

`merchantAccount` - MerchantAccount object to check capabilities for.

`onComplete` - Block run when capabilities are retrieved.