[payments-android-byod](../../index.md) / [com.cardflight.sdk.core](../index.md) / [Transaction](index.md) / [selectProcessOption](./select-process-option.md)

# selectProcessOption

`abstract fun selectProcessOption(processOption: `[`ProcessOption`](../../com.cardflight.sdk.core.enums/-process-option/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Select which [process option](../../com.cardflight.sdk.core.enums/-process-option/index.md) to use. This should only be called after receiving the
[onRequestProcessOption](../../com.cardflight.sdk.core.interfaces/-transaction-handler/on-request-process-option.md) callback.

### Parameters

`processOption` - ProcessOption to use.