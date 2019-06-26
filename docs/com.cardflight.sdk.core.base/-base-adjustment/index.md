[payments-android-byod](../../index.md) / [com.cardflight.sdk.core.base](../index.md) / [BaseAdjustment](./index.md)

# BaseAdjustment

`class BaseAdjustment : `[`Adjustment`](../../com.cardflight.sdk.core/-adjustment/index.md)

BaseAdjustment is used to easily create an [Adjustment](../../com.cardflight.sdk.core/-adjustment/index.md) object to provide to a
[Transaction](../../com.cardflight.sdk.core/-transaction/index.md).

Copyright © 2019 CardFlight. All rights reserved.

**Author**
Austin Odell

**Since**
v1.0.4

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `BaseAdjustment(metadata: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`?>? = null, signature: `[`Bitmap`](https://developer.android.com/reference/android/graphics/Bitmap.html)`? = null, tipAmount: `[`Amount`](../../com.cardflight.sdk.core/-amount/index.md)`? = null)`<br>BaseAdjustment is used to easily create an [Adjustment](../../com.cardflight.sdk.core/-adjustment/index.md) object to provide to a [Transaction](../../com.cardflight.sdk.core/-transaction/index.md). |

### Properties

| Name | Summary |
|---|---|
| [metadata](metadata.md) | `val metadata: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`?>?`<br>Any additional information saved by the client along with the transaction. |
| [signature](signature.md) | `val signature: `[`Bitmap`](https://developer.android.com/reference/android/graphics/Bitmap.html)`?`<br>Signature to provide to transaction. |
| [tipAmount](tip-amount.md) | `val tipAmount: `[`Amount`](../../com.cardflight.sdk.core/-amount/index.md)`?`<br>Amount to tip on top of original transaction amount. |
