[payments-android-byod](../../index.md) / [com.cardflight.sdk](../index.md) / [TransactionManager](index.md) / [createRefund](./create-refund.md)

# createRefund

`fun createRefund(amount: `[`Amount`](../../com.cardflight.sdk.core/-amount/index.md)`, callbackUrl: `[`URL`](https://developer.android.com/reference/java/net/URL.html)`?, metadata: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`?>?, transactionRecord: `[`TransactionRecord`](../../com.cardflight.sdk.core/-transaction-record/index.md)`, handler: `[`TransactionHandler`](../../com.cardflight.sdk.core.interfaces/-transaction-handler/index.md)`, onComplete: (transaction: `[`Transaction`](../../com.cardflight.sdk.core/-transaction/index.md)`?, `[`Error`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-error/index.html)`?) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Creates a new [Transaction](../../com.cardflight.sdk.core/-transaction/index.md) with transaction type
[refund](../../com.cardflight.sdk.core.enums/-transaction-type/-r-e-f-u-n-d.md).

An error will be returned in the following cases:

* The CardFlight API could not be reached.

Exception can be thrown in the following cases:

* There is already an active Transaction running.
* The Amount is not greater than $0.00.
* The TransactionRecord was not created by the CardFlight Payments SDK.
* The TransactionRecord's transactionId is blank.
* The MerchantAccount has a validation error.
* The MerchantAccount does not have the capability MerchantAccountCapability.MERCHANT_ACCOUNT_CAN_PROCESS_TRANSACTIONS.

### Parameters

`amount` - Amount object to use.

`callbackUrl` - Callback URL to use.

`metadata` - Metadata to use.

`transactionRecord` - TransactionRecord object to use.

`handler` - TransactionHandler to listen to transaction events.

`onComplete` - Block executed when a transaction has been created or if an error has occurred.