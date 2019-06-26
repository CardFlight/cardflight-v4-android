[payments-android-byod](../../index.md) / [com.cardflight.sdk](../index.md) / [MerchantAccountManager](index.md) / [create](./create.md)

# create

`fun create(merchantAccountId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, apiKey: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`MerchantAccount`](../../com.cardflight.sdk.core/-merchant-account/index.md)

Creates a new MerchantAccount object with the given merchantAccountId and apiKey.

### Exceptions

`IllegalArgumentException` - if you pass an empty string for merchantAccountId or apiKey.

### Parameters

`merchantAccountId` - ID of merchant account.

`apiKey` - API Key of merchant account.