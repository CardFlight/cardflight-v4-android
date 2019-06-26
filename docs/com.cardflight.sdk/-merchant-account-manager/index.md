[payments-android-byod](../../index.md) / [com.cardflight.sdk](../index.md) / [MerchantAccountManager](./index.md)

# MerchantAccountManager

`object MerchantAccountManager : MerchantAccountManager`

Manager to create and modify [MerchantAccount](../../com.cardflight.sdk.core/-merchant-account/index.md) objects.

Copyright © 2019 CardFlight. All rights reserved.

**Author**
Austin Odell

**Since**
v4.8.0

### Functions

| Name | Summary |
|---|---|
| [create](create.md) | `fun create(merchantAccountId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, apiKey: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`MerchantAccount`](../../com.cardflight.sdk.core/-merchant-account/index.md)<br>Creates a new MerchantAccount object with the given merchantAccountId and apiKey. |
| [deserialize](deserialize.md) | `fun deserialize(data: `[`ByteArray`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)`): `[`MerchantAccount`](../../com.cardflight.sdk.core/-merchant-account/index.md)`?`<br>Deserializes a merchant account from storage. |
| [getCapabilities](get-capabilities.md) | `fun getCapabilities(merchantAccount: `[`MerchantAccount`](../../com.cardflight.sdk.core/-merchant-account/index.md)`, onComplete: (capabilities: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`MerchantAccountCapability`](../../com.cardflight.sdk.core.enums/-merchant-account-capability/index.md)`>) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Gets capabilities for a Merchant Account. |
| [getValidationError](get-validation-error.md) | `fun getValidationError(merchantAccount: `[`MerchantAccount`](../../com.cardflight.sdk.core/-merchant-account/index.md)`, onComplete: (`[`Error`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-error/index.html)`?) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Gives any errors with the MerchantAccount object. |
| [serialize](serialize.md) | `fun serialize(merchantAccount: `[`MerchantAccount`](../../com.cardflight.sdk.core/-merchant-account/index.md)`): `[`ByteArray`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-byte-array/index.html)`?`<br>Serializes a merchant account for storage. |
| [validate](validate.md) | `fun validate(merchantAccount: `[`MerchantAccount`](../../com.cardflight.sdk.core/-merchant-account/index.md)`, onComplete: (isSuccess: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`, `[`Error`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-error/index.html)`?) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>`fun validate(merchantAccount: `[`MerchantAccount`](../../com.cardflight.sdk.core/-merchant-account/index.md)`, handler: `[`CompletionHandler`](../../com.cardflight.sdk.core.interfaces/-completion-handler/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Validates the MerchantAccount object with the CardFlight API. |
