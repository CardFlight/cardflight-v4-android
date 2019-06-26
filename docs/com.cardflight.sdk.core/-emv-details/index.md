[payments-android-byod](../../index.md) / [com.cardflight.sdk.core](../index.md) / [EmvDetails](./index.md)

# EmvDetails

`interface EmvDetails`

EmvDetails class is used to provide all details required to be printed on a receipt according to
EMV specification.

Copyright © 2019 CardFlight. All rights reserved.

**Author**
Austin Odell

**Since**
v1.0.0

### Properties

| Name | Summary |
|---|---|
| [applicationCryptogram](application-cryptogram.md) | `abstract val applicationCryptogram: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>Application Cryptogram of the EmvDetails. |
| [applicationId](application-id.md) | `abstract val applicationId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>Application Identifier of the EmvDetails. |
| [applicationLabel](application-label.md) | `abstract val applicationLabel: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>Application Label of the EmvDetails. |
| [applicationPreferredName](application-preferred-name.md) | `abstract val applicationPreferredName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>Application Preferred Name of the EmvDetails. |
| [applicationResponseCode](application-response-code.md) | `abstract val applicationResponseCode: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>Application Response Code of the EmvDetails. |
| [applicationTransactionCounter](application-transaction-counter.md) | `abstract val applicationTransactionCounter: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>Application Transaction Counter of the EmvDetails. |
| [cardholderVerificationMethod](cardholder-verification-method.md) | `abstract val cardholderVerificationMethod: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>Cardholder Verification Method of the EmvDetails. |
| [entryMode](entry-mode.md) | `abstract val entryMode: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>Entry Mode of the EmvDetails. |
| [issuerActionCodeDefault](issuer-action-code-default.md) | `abstract val issuerActionCodeDefault: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>Issuer Action Code Default of the EmvDetails. |
| [issuerActionCodeDenial](issuer-action-code-denial.md) | `abstract val issuerActionCodeDenial: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>Issuer Action Code Denial of the EmvDetails. |
| [issuerActionCodeOnline](issuer-action-code-online.md) | `abstract val issuerActionCodeOnline: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>Issuer Action Code Online of the EmvDetails. |
| [panSequenceNumber](pan-sequence-number.md) | `abstract val panSequenceNumber: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>Pan Sequence Number of the EmvDetails. |
| [transactionStatusIndicator](transaction-status-indicator.md) | `abstract val transactionStatusIndicator: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>Transaction Status Indicator of the EmvDetails. |

### Functions

| Name | Summary |
|---|---|
| [toMap](to-map.md) | `open fun toMap(): `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?>`<br>Outputs all information in a receipt-ready format. |
