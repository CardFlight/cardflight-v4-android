[payments-android-byod](../../index.md) / [com.cardflight.sdk.core](../index.md) / [Transaction](index.md) / [attachSignature](./attach-signature.md)

# attachSignature

`abstract fun attachSignature(bitmap: `[`Bitmap`](https://developer.android.com/reference/android/graphics/Bitmap.html)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Attach a signature to the transaction. This should only be called after receiving the
[onRequestCvm](../../com.cardflight.sdk.core.interfaces/-transaction-handler/on-request-cvm.md) callback.

### Parameters

`bitmap` - Bitmap representation of the customer signature. Null is allowed.