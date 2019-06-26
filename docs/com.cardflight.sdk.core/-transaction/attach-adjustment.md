[payments-android-byod](../../index.md) / [com.cardflight.sdk.core](../index.md) / [Transaction](index.md) / [attachAdjustment](./attach-adjustment.md)

# attachAdjustment

`abstract fun attachAdjustment(context: `[`Context`](https://developer.android.com/reference/android/content/Context.html)`, adjustment: `[`Adjustment`](../-adjustment/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Attach an adjustment to the transaction. This should only be called after receiving the
[onRequestAdjustment](../../com.cardflight.sdk.core.interfaces/-transaction-handler/on-request-adjustment.md) callback.

### Parameters

`context` - Android context object.

`adjustment` - Adjustment containing all adjustment information for the transaction.