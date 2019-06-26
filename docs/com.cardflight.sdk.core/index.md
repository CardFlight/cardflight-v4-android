[payments-android-byod](../index.md) / [com.cardflight.sdk.core](./index.md)

## Package com.cardflight.sdk.core

### Types

| Name | Summary |
|---|---|
| [Adjustment](-adjustment/index.md) | `interface Adjustment`<br>Adjustment is used to provide a [transaction](-transaction/index.md) with optional tip and optional signature if requested by [onRequestAdjustment](../com.cardflight.sdk.core.interfaces/-transaction-handler/on-request-adjustment.md). |
| [Amount](-amount/index.md) | `interface Amount`<br>Amount represents a USD amount of money to be processed or that has been processed. |
| [AvsResponse](-avs-response/index.md) | `interface AvsResponse`<br>AvsResponse class returns AVS information about a [TransactionRecord](-transaction-record/index.md). |
| [CardAID](-card-a-i-d/index.md) | `interface CardAID`<br>CardAID (Card Application Identifier) is used to give information about a specific application available on a card. |
| [CardInfo](-card-info/index.md) | `interface CardInfo`<br>CardInfo class is used to give all necessary information from a physical card. |
| [CardReaderInfo](-card-reader-info/index.md) | `interface CardReaderInfo`<br>CardReaderInfo is used to provide information about a card reader. |
| [EmvDetails](-emv-details/index.md) | `interface EmvDetails`<br>EmvDetails class is used to provide all details required to be printed on a receipt according to EMV specification. |
| [KeyedEntryContainer](-keyed-entry-container/index.md) | `interface KeyedEntryContainer`<br>Container for the AVS-enabled card and address entry views. |
| [MerchantAccount](-merchant-account/index.md) | `interface MerchantAccount`<br>Interface is used to define the features of a MerchantAccount object. |
| [Message](-message/index.md) | `interface Message`<br>Message is used to give messages to be displayed to the customer during a transaction. |
| [Transaction](-transaction/index.md) | `interface Transaction`<br>Interface defining a class used to create and manage a transaction. |
| [TransactionRecord](-transaction-record/index.md) | `interface TransactionRecord`<br>TransactionRecord provides information about a processed transaction. |
