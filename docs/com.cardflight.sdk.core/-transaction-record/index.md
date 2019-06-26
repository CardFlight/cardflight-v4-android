[payments-android-byod](../../index.md) / [com.cardflight.sdk.core](../index.md) / [TransactionRecord](./index.md)

# TransactionRecord

`interface TransactionRecord`

TransactionRecord provides information about a processed transaction.

Copyright © 2019 CardFlight. All rights reserved.

**Author**
Austin Odell

**Since**
v1.0.0

### Properties

| Name | Summary |
|---|---|
| [amount](amount.md) | `abstract val amount: `[`Amount`](../-amount/index.md)<br>Amount to run transaction for. |
| [apiTransactionState](api-transaction-state.md) | `abstract val apiTransactionState: `[`ApiTransactionState`](../../com.cardflight.sdk.core.enums/-api-transaction-state/index.md)`?`<br>State of the transaction on the CardFlight API. |
| [authCodes](auth-codes.md) | `abstract val authCodes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>?`<br>List of auth codes provided by the processor. |
| [avsResponse](avs-response.md) | `abstract val avsResponse: `[`AvsResponse`](../-avs-response/index.md)`?`<br>Address verification service response of the transaction. This is only used for [keyed](../../com.cardflight.sdk.core.enums/-card-input-method/index.md) transactions. |
| [callbackUrl](callback-url.md) | `abstract val callbackUrl: `[`URL`](https://developer.android.com/reference/java/net/URL.html)`?`<br>Callback URL transaction information was reported to. |
| [cardInfo](card-info.md) | `abstract val cardInfo: `[`CardInfo`](../-card-info/index.md)`?`<br>Card used to process the transaction. |
| [cardReaderInfo](card-reader-info.md) | `abstract val cardReaderInfo: `[`CardReaderInfo`](../-card-reader-info/index.md)`?`<br>Card reader used to process the transaction. Can be null if no card reader was involved. |
| [cardToken](card-token.md) | `abstract val cardToken: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>ID of the card used during the transaction. |
| [createdAt](created-at.md) | `abstract val createdAt: `[`Date`](https://developer.android.com/reference/java/util/Date.html)`?`<br>Date of when the transaction was created. |
| [merchantAccount](merchant-account.md) | `abstract val merchantAccount: `[`MerchantAccount`](../-merchant-account/index.md)<br>Merchant account to be used by transaction. |
| [message](message.md) | `abstract val message: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>Message explaining the [result](result.md) of the transaction. Can be null. |
| [metadata](metadata.md) | `abstract val metadata: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`?>?`<br>Any additional information saved by the client along with the transaction. |
| [referenceId](reference-id.md) | `abstract val referenceId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>Reference ID of the transaction. This is only used by certain processors. |
| [result](result.md) | `abstract val result: `[`TransactionResult`](../../com.cardflight.sdk.core.enums/-transaction-result/index.md)`?`<br>Result of the transaction. |
| [sdkData](sdk-data.md) | `abstract val sdkData: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`?>?`<br>SDK-generated data from the original transaction. |
| [signatureUrl](signature-url.md) | `abstract val signatureUrl: `[`URL`](https://developer.android.com/reference/java/net/URL.html)`?`<br>URL of the signature for the transaction. Can be null if no signature was provided. |
| [transactedAt](transacted-at.md) | `abstract val transactedAt: `[`Date`](https://developer.android.com/reference/java/util/Date.html)`?`<br>Date of when the transaction was processed. |
| [transactionId](transaction-id.md) | `abstract val transactionId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>Unique identifier of the transaction on the CardFlight API. |
| [transactionType](transaction-type.md) | `abstract val transactionType: `[`TransactionType`](../../com.cardflight.sdk.core.enums/-transaction-type/index.md)`?`<br>Type of transaction. |
