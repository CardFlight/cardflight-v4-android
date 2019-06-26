[payments-android-byod](../../index.md) / [com.cardflight.sdk](../index.md) / [MerchantAccountManager](index.md) / [serialize](./serialize.md)

# serialize

`fun serialize(merchantAccount: `[`MerchantAccount`](../../com.cardflight.sdk.core/-merchant-account/index.md)`): `[`ByteArray`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)`?`

Serializes a merchant account for storage.

### Exceptions

`IllegalArgumentException` - if you pass a merchant account not created using MerchantAccountManager.

### Parameters

`merchantAccount` - MerchantAccount object to serialize.

**Return**
A representation of the MerchantAccount object as byte array.

**See Also**

[MerchantAccountManager.deserialize](deserialize.md)

