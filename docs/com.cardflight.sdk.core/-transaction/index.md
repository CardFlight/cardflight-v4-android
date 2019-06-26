[payments-android-byod](../../index.md) / [com.cardflight.sdk.core](../index.md) / [Transaction](./index.md)

# Transaction

`interface Transaction`

Interface defining a class used to create and manage a transaction.

Copyright © 2019 CardFlight. All rights reserved.

**Author**
Austin Odell

**Since**
v1.0.0

### Properties

| Name | Summary |
|---|---|
| [merchantAccount](merchant-account.md) | `abstract val merchantAccount: `[`MerchantAccount`](../-merchant-account/index.md)`?`<br>Merchant account used for the transaction. |
| [reachability](reachability.md) | `abstract var reachability: `[`Reachability`](../../com.cardflight.sdk.core.enums/-reachability/index.md)<br>Network reachability to be assumed during the transaction. |
| [uuid](uuid.md) | `abstract val uuid: `[`UUID`](https://developer.android.com/reference/java/util/UUID.html)<br>Unique identifier for a transaction. |

### Functions

| Name | Summary |
|---|---|
| [attachAdjustment](attach-adjustment.md) | `abstract fun attachAdjustment(context: `[`Context`](https://developer.android.com/reference/android/content/Context.html)`, adjustment: `[`Adjustment`](../-adjustment/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Attach an adjustment to the transaction. This should only be called after receiving the [onRequestAdjustment](../../com.cardflight.sdk.core.interfaces/-transaction-handler/on-request-adjustment.md) callback. |
| [attachSignature](attach-signature.md) | `abstract fun attachSignature(bitmap: `[`Bitmap`](https://developer.android.com/reference/android/graphics/Bitmap.html)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Attach a signature to the transaction. This should only be called after receiving the [onRequestCvm](../../com.cardflight.sdk.core.interfaces/-transaction-handler/on-request-cvm.md) callback. |
| [close](close.md) | `abstract fun close(context: `[`Context`](https://developer.android.com/reference/android/content/Context.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Closes the transaction. This should be called at the end of every transaction. |
| [getKeyedEntryContainer](get-keyed-entry-container.md) | `abstract fun getKeyedEntryContainer(context: `[`Context`](https://developer.android.com/reference/android/content/Context.html)`): `[`KeyedEntryContainer`](../-keyed-entry-container/index.md)`?`<br>Container class for accessing view elements for [keyed](#) card input. |
| [scanBluetoothCardReaders](scan-bluetooth-card-readers.md) | `abstract fun scanBluetoothCardReaders(context: `[`Context`](https://developer.android.com/reference/android/content/Context.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Scan for bluetooth card readers to connect to. |
| [selectCardAid](select-card-aid.md) | `abstract fun selectCardAid(cardAid: `[`CardAID`](../-card-a-i-d/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Select which card application to use on a card. This should only be called after receiving the [onRequestCardAidSelection](../../com.cardflight.sdk.core.interfaces/-transaction-handler/on-request-card-aid-selection.md) callback. |
| [selectCardReader](select-card-reader.md) | `abstract fun selectCardReader(context: `[`Context`](https://developer.android.com/reference/android/content/Context.html)`, cardReaderInfo: `[`CardReaderInfo`](../-card-reader-info/index.md)`?, cardReaderModel: `[`CardReaderModel`](../../com.cardflight.sdk.core.enums/-card-reader-model/index.md)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Select a card reader to attempt to connect to. |
| [selectProcessOption](select-process-option.md) | `abstract fun selectProcessOption(processOption: `[`ProcessOption`](../../com.cardflight.sdk.core.enums/-process-option/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Select which [process option](../../com.cardflight.sdk.core.enums/-process-option/index.md) to use. This should only be called after receiving the [onRequestProcessOption](../../com.cardflight.sdk.core.interfaces/-transaction-handler/on-request-process-option.md) callback. |
| [useKeyedCardInfo](use-keyed-card-info.md) | `abstract fun useKeyedCardInfo(context: `[`Context`](https://developer.android.com/reference/android/content/Context.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Use keyed card info obtained from the [keyedEntryContainer](#). |
