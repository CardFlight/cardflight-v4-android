[payments-android-byod](../../index.md) / [com.cardflight.sdk.core](../index.md) / [Transaction](index.md) / [selectCardReader](./select-card-reader.md)

# selectCardReader

`abstract fun selectCardReader(context: `[`Context`](https://developer.android.com/reference/android/content/Context.html)`, cardReaderInfo: `[`CardReaderInfo`](../-card-reader-info/index.md)`?, cardReaderModel: `[`CardReaderModel`](../../com.cardflight.sdk.core.enums/-card-reader-model/index.md)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Select a card reader to attempt to connect to.

### Parameters

`context` - Android context object.

`cardReaderInfo` - CardReaderInfo object to connect to.

`cardReaderModel` - CardReaderModel of the CardReaderInfo object. Only necessary for [audio jack](#) readers.