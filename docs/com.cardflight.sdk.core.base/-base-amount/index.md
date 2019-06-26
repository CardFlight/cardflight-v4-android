[payments-android-byod](../../index.md) / [com.cardflight.sdk.core.base](../index.md) / [BaseAmount](./index.md)

# BaseAmount

`class BaseAmount : `[`Amount`](../../com.cardflight.sdk.core/-amount/index.md)

Amount represents a USD amount of money to be processed or that has been processed.

Copyright © 2019 CardFlight. All rights reserved.

### Parameters

`value` - BigDecimal representation of the amount.

**Author**
Austin Odell

**Since**
v1.0.0

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `BaseAmount(value: `[`BigDecimal`](https://developer.android.com/reference/java/math/BigDecimal.html)`)`<br>Initialize an Amount object with the BigDecimal value you want to process. Make sure the scale is set to 2 to prevent unintentional rounding. |

### Functions

| Name | Summary |
|---|---|
| [bigDecimalValue](big-decimal-value.md) | `fun bigDecimalValue(): `[`BigDecimal`](https://developer.android.com/reference/java/math/BigDecimal.html)<br>Returns the bigDecimal equivalent of the Amount. |
| [toString](to-string.md) | `fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Returns the USD formatted string representation of the Amount. |
