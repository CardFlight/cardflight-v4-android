[payments-android-byod](../../index.md) / [com.cardflight.sdk](../index.md) / [SessionManager](./index.md)

# SessionManager

`object SessionManager : SessionManager`

SessionManager object to manage a session.

Copyright © 2019 CardFlight. All rights reserved.

**Author**
Austin Odell

**Since**
v4.0.0

### Properties

| Name | Summary |
|---|---|
| [isInitialized](is-initialized.md) | `val isInitialized: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isLogging](is-logging.md) | `var isLogging: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [loggerHandler](logger-handler.md) | `var loggerHandler: `[`LoggerHandler`](../../com.cardflight.sdk.core.interfaces/-logger-handler/index.md)`?` |

### Functions

| Name | Summary |
|---|---|
| [getSerialNumber](get-serial-number.md) | `fun getSerialNumber(onComplete: (serialNumber: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [init](init.md) | `fun init(context: `[`Context`](https://developer.android.com/reference/android/content/Context.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
