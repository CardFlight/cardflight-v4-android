[payments-android-byod](../../index.md) / [com.cardflight.sdk](../index.md) / [ReaderUtilities](./index.md)

# ReaderUtilities

`object ReaderUtilities : ReaderUtilities, CardReaderCommunicatorHandler`

ReaderUtilities is a tool used to connect to a card reader before starting a transaction.

Copyright © 2019 CardFlight. All rights reserved.

**Author**
Austin Odell

**Since**
v4.1.0

### Properties

| Name | Summary |
|---|---|
| [keepReaderConnectionAlive](keep-reader-connection-alive.md) | `var keepReaderConnectionAlive: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>Specify whether to stay connected to a reader after a transaction has been run. |
| [state](state.md) | `val state: `[`ReaderUtilitiesState`](../../com.cardflight.sdk.core.enums/-reader-utilities-state/index.md)<br>State of the ReaderUtilities object. |

### Functions

| Name | Summary |
|---|---|
| [closeSession](close-session.md) | `fun closeSession(context: `[`Context`](https://developer.android.com/reference/android/content/Context.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Closes the session. |
| [openSession](open-session.md) | `fun ~~openSession~~(context: `[`Context`](https://developer.android.com/reference/android/content/Context.html)`, handler: ReaderUtilitiesHandler): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>`fun openSession(context: `[`Context`](https://developer.android.com/reference/android/content/Context.html)`, handler: `[`ReaderUtilitiesHandler`](../../com.cardflight.sdk.core.interfaces/-reader-utilities-handler/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Opens a session to the ReaderUtilities. |
| [runAutoConfig](run-auto-config.md) | `fun ~~runAutoConfig~~(context: `[`Context`](https://developer.android.com/reference/android/content/Context.html)`, cardReaderInfo: CardReaderInfo?, cardReaderModel: `[`CardReaderModel`](../../com.cardflight.sdk.enumerations/-card-reader-model/index.md)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>`fun runAutoConfig(context: `[`Context`](https://developer.android.com/reference/android/content/Context.html)`, cardReaderInfo: `[`CardReaderInfo`](../../com.cardflight.sdk.core/-card-reader-info/index.md)`?, cardReaderModel: `[`CardReaderModel`](../../com.cardflight.sdk.core.enums/-card-reader-model/index.md)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Runs auto config to determine compatibility. |
| [scanBluetoothCardReaders](scan-bluetooth-card-readers.md) | `fun scanBluetoothCardReaders(context: `[`Context`](https://developer.android.com/reference/android/content/Context.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Scans for bluetooth card readers. |
| [selectCardReader](select-card-reader.md) | `fun ~~selectCardReader~~(context: `[`Context`](https://developer.android.com/reference/android/content/Context.html)`, cardReaderInfo: CardReaderInfo?, cardReaderModel: `[`CardReaderModel`](../../com.cardflight.sdk.enumerations/-card-reader-model/index.md)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>`fun selectCardReader(context: `[`Context`](https://developer.android.com/reference/android/content/Context.html)`, cardReaderInfo: `[`CardReaderInfo`](../../com.cardflight.sdk.core/-card-reader-info/index.md)`?, cardReaderModel: `[`CardReaderModel`](../../com.cardflight.sdk.core.enums/-card-reader-model/index.md)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Selects a card reader to connect to. |
