[payments-android-byod](../../index.md) / [com.cardflight.sdk.core](../index.md) / [Adjustment](./index.md)

# Adjustment

`interface Adjustment`

Adjustment is used to provide a [transaction](../-transaction/index.md) with optional tip and optional
signature if requested by
[onRequestAdjustment](../../com.cardflight.sdk.core.interfaces/-transaction-handler/on-request-adjustment.md).

Copyright © 2019 CardFlight. All rights reserved.

**Author**
Austin Odell

**Since**
v1.0.4

### Properties

| Name | Summary |
|---|---|
| [metadata](metadata.md) | `abstract val metadata: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`?>?`<br>Any additional information saved by the client along with the transaction. |
| [signature](signature.md) | `abstract val signature: `[`Bitmap`](https://developer.android.com/reference/android/graphics/Bitmap.html)`?`<br>Signature to provide to transaction. |
| [tipAmount](tip-amount.md) | `abstract val tipAmount: `[`Amount`](../-amount/index.md)`?`<br>Amount to tip on top of original transaction amount. |

### Inheritors

| Name | Summary |
|---|---|
| [BaseAdjustment](../../com.cardflight.sdk.core.base/-base-adjustment/index.md) | `class BaseAdjustment : `[`Adjustment`](./index.md)<br>BaseAdjustment is used to easily create an [Adjustment](./index.md) object to provide to a [Transaction](../-transaction/index.md). |
