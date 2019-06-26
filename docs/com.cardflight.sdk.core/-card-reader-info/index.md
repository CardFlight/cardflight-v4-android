[payments-android-byod](../../index.md) / [com.cardflight.sdk.core](../index.md) / [CardReaderInfo](./index.md)

# CardReaderInfo

`interface CardReaderInfo`

CardReaderInfo is used to provide information about a card reader.

Copyright © 2019 CardFlight. All rights reserved.

**Author**
Austin Odell

**Since**
v1.0.0

### Properties

| Name | Summary |
|---|---|
| [batteryStatus](battery-status.md) | `abstract val batteryStatus: `[`BatteryStatus`](../../com.cardflight.sdk.core.enums/-battery-status/index.md)`?`<br>Battery status of card reader. |
| [bluetoothDevice](bluetooth-device.md) | `abstract val bluetoothDevice: `[`BluetoothDevice`](https://developer.android.com/reference/android/bluetooth/BluetoothDevice.html)`?`<br>Bluetooth device supported on card reader. |
| [cardReaderModel](card-reader-model.md) | `abstract val cardReaderModel: `[`CardReaderModel`](../../com.cardflight.sdk.core.enums/-card-reader-model/index.md)`?`<br>Model of card reader. |
| [cardReaderType](card-reader-type.md) | `abstract val cardReaderType: `[`CardReaderType`](../../com.cardflight.sdk.core.enums/-card-reader-type/index.md)`?`<br>Type of card reader. |
| [metadata](metadata.md) | `abstract val metadata: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?>?`<br>Additional information about the card reader. |
| [name](name.md) | `abstract val name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>String representation of the card reader. |
