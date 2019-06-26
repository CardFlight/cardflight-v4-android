[payments-android-byod](../../index.md) / [com.cardflight.sdk.enumerations](../index.md) / [BatteryStatus](./index.md)

# BatteryStatus

`enum class ~~BatteryStatus~~`
**Deprecated:** Use com.cardflight.sdk.core.enums.BatteryStatus instead. This class will be removed in v4.9.0.

Status of battery in card readers that contain a rechargeable battery

Copyright © 2019 CardFlight. All rights reserved.

**Author**
Austin Odell

**Since**
v4.0.0

**See Also**

[com.cardflight.sdk.core.enums.BatteryStatus](../../com.cardflight.sdk.core.enums/-battery-status/index.md)

### Enum Values

| Name | Summary |
|---|---|
| [UNKNOWN](-u-n-k-n-o-w-n.md) | Unknown battery status |
| [LOW](-l-o-w.md) | Low battery, charge immediately |
| [NOMINAL](-n-o-m-i-n-a-l.md) | Sufficient battery to run transactions |
| [PLUGGED_IN](-p-l-u-g-g-e-d_-i-n.md) | Card reader running off AC power |

### Companion Object Functions

| Name | Summary |
|---|---|
| [getBatteryStatusFromPercentage](get-battery-status-from-percentage.md) | `fun getBatteryStatusFromPercentage(percentage: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`BatteryStatus`](./index.md) |
