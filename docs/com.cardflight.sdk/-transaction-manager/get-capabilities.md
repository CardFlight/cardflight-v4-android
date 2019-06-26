[payments-android-byod](../../index.md) / [com.cardflight.sdk](../index.md) / [TransactionManager](index.md) / [getCapabilities](./get-capabilities.md)

# getCapabilities

`fun getCapabilities(transactionRecord: `[`TransactionRecord`](../../com.cardflight.sdk.core/-transaction-record/index.md)`?, onComplete: (capabilities: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`TransactionCapability`](../../com.cardflight.sdk.core.enums/-transaction-capability/index.md)`>) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Gets the capabilities of a [TransactionRecord](../../com.cardflight.sdk.core/-transaction-record/index.md).

### Parameters

`transactionRecord` - TransactionRecord object to check capabilities for.

`onComplete` - Block run when capabilities are retrieved.