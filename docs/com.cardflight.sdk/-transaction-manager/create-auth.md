[payments-android-byod](../../index.md) / [com.cardflight.sdk](../index.md) / [TransactionManager](index.md) / [createAuth](./create-auth.md)

# createAuth

`fun createAuth(context: `[`Context`](https://developer.android.com/reference/android/content/Context.html)`, amount: `[`Amount`](../../com.cardflight.sdk.core/-amount/index.md)`, merchantAccount: `[`MerchantAccount`](../../com.cardflight.sdk.core/-merchant-account/index.md)`, callbackUrl: `[`URL`](https://developer.android.com/reference/java/net/URL.html)`?, metadata: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`?>?, isSignatureRequired: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`, isQuickChipEnabled: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`, handler: `[`TransactionHandler`](../../com.cardflight.sdk.core.interfaces/-transaction-handler/index.md)`, onComplete: (transaction: `[`Transaction`](../../com.cardflight.sdk.core/-transaction/index.md)`?, `[`Error`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-error/index.html)`?) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Creates a new [Transaction](../../com.cardflight.sdk.core/-transaction/index.md) with transaction type
[authorization](../../com.cardflight.sdk.core.enums/-transaction-type/-a-u-t-h-o-r-i-z-a-t-i-o-n.md).

An exception will always be thrown as this method is not supported.

### Parameters

`context` - Android context object.

`amount` - Amount to run transaction for.

`merchantAccount` - Merchant account to be used by transaction.

`callbackUrl` - Optional URL to report transaction information to.

`metadata` - Any additional information you want saved along with the transaction. It will be accessible from the [TransactionRecord](../../com.cardflight.sdk.core/-transaction-record/index.md).

`isSignatureRequired` - Whether or not you want signature requested on [KEY](../../com.cardflight.sdk.core.enums/-card-input-method/index.md) and [SWIPE](../../com.cardflight.sdk.core.enums/-card-input-method/index.md) transactions.

`isQuickChipEnabled` - Whether or not you want [QUICK_CHIP](../../com.cardflight.sdk.core.enums/-card-input-method/index.md) transactions enabled.

`handler` - TransactionHandler to listen to transaction events.

`onComplete` - Block executed when a transaction has been created or if an error has occurred.