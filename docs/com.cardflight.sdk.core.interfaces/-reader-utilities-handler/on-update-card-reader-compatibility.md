[payments-android-byod](../../index.md) / [com.cardflight.sdk.core.interfaces](../index.md) / [ReaderUtilitiesHandler](index.md) / [onUpdateCardReaderCompatibility](./on-update-card-reader-compatibility.md)

# onUpdateCardReaderCompatibility

`abstract fun onUpdateCardReaderCompatibility(cardReaderInfo: `[`CardReaderInfo`](../../com.cardflight.sdk.core/-card-reader-info/index.md)`?, cardReaderCompatibility: `[`CardReaderCompatibility`](../../com.cardflight.sdk.core.enums/-card-reader-compatibility/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Card reader compatibility was updated.

### Parameters

`cardReaderInfo` - Card reader the compatibility is being reported on. Can be null if attempt was not successful.

`cardReaderCompatibility` - Compatibility of the attached card reader.