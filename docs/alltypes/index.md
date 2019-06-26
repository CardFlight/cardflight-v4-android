

### All Types

| Name | Summary |
|---|---|
| [com.cardflight.sdk.core.Adjustment](../com.cardflight.sdk.core/-adjustment/index.md) | Adjustment is used to provide a [transaction](../com.cardflight.sdk.core/-transaction/index.md) with optional tip and optional signature if requested by [onRequestAdjustment](../com.cardflight.sdk.core.interfaces/-transaction-handler/on-request-adjustment.md). |
| [com.cardflight.sdk.core.Amount](../com.cardflight.sdk.core/-amount/index.md) | Amount represents a USD amount of money to be processed or that has been processed. |
| [com.cardflight.sdk.core.enums.ApiTransactionState](../com.cardflight.sdk.core.enums/-api-transaction-state/index.md) | ApiTransactionState is used to communicate the state of a given transaction on the API. |
| [com.cardflight.sdk.enumerations.ApiTransactionState](../com.cardflight.sdk.enumerations/-api-transaction-state/index.md) | ApiTransactionState is used to communicate the state of a given transaction on the API. |
| [com.cardflight.sdk.core.AvsResponse](../com.cardflight.sdk.core/-avs-response/index.md) | AvsResponse class returns AVS information about a [TransactionRecord](../com.cardflight.sdk.core/-transaction-record/index.md). |
| [com.cardflight.sdk.core.enums.AvsResult](../com.cardflight.sdk.core.enums/-avs-result/index.md) | AvsResult enum contains all possible values returned from the Address Verification Service. |
| [com.cardflight.sdk.enumerations.AvsResult](../com.cardflight.sdk.enumerations/-avs-result/index.md) | AvsResult enum contains all possible values returned from the Address Verification System |
| [com.cardflight.sdk.core.base.BaseAdjustment](../com.cardflight.sdk.core.base/-base-adjustment/index.md) | BaseAdjustment is used to easily create an [Adjustment](../com.cardflight.sdk.core/-adjustment/index.md) object to provide to a [Transaction](../com.cardflight.sdk.core/-transaction/index.md). |
| [com.cardflight.sdk.core.base.BaseAmount](../com.cardflight.sdk.core.base/-base-amount/index.md) | Amount represents a USD amount of money to be processed or that has been processed. |
| [com.cardflight.sdk.core.enums.BatteryStatus](../com.cardflight.sdk.core.enums/-battery-status/index.md) | Status of battery in card readers that contain a rechargeable battery. |
| [com.cardflight.sdk.enumerations.BatteryStatus](../com.cardflight.sdk.enumerations/-battery-status/index.md) | Status of battery in card readers that contain a rechargeable battery |
| [com.cardflight.sdk.core.enums.CVM](../com.cardflight.sdk.core.enums/-c-v-m/index.md) | Supported CVMs (a.k.a. Cardholder Verification Method). |
| [com.cardflight.sdk.enumerations.CVM](../com.cardflight.sdk.enumerations/-c-v-m/index.md) | Supported CVMs (a.k.a. Cardholder Verification Method). |
| [com.cardflight.sdk.core.CardAID](../com.cardflight.sdk.core/-card-a-i-d/index.md) | CardAID (Card Application Identifier) is used to give information about a specific application available on a card. |
| [com.cardflight.sdk.core.enums.CardBrand](../com.cardflight.sdk.core.enums/-card-brand/index.md) | All card brands recognized by the SDK. Not all recognized cards are supported for running transactions. Credit card numbers starting within the specified range are considered part of that card brand |
| [com.cardflight.sdk.enumerations.CardBrand](../com.cardflight.sdk.enumerations/-card-brand/index.md) | All card brands recognized by the SDK. Not all recognized cards are supported for running transactions. Credit card numbers starting within the specified range are considered part of that card brand |
| [com.cardflight.sdk.core.CardInfo](../com.cardflight.sdk.core/-card-info/index.md) | CardInfo class is used to give all necessary information from a physical card. |
| [com.cardflight.sdk.core.enums.CardInputMethod](../com.cardflight.sdk.core.enums/-card-input-method/index.md) | Specifies the method by which card info was generated. |
| [com.cardflight.sdk.enumerations.CardInputMethod](../com.cardflight.sdk.enumerations/-card-input-method/index.md) | Specifies the method by which card info was generated |
| [com.cardflight.sdk.core.enums.CardReaderCompatibility](../com.cardflight.sdk.core.enums/-card-reader-compatibility/index.md) | CardReaderCompatibility is used to communicate whether or not a card reader will work with a device. |
| [com.cardflight.sdk.enumerations.CardReaderCompatibility](../com.cardflight.sdk.enumerations/-card-reader-compatibility/index.md) | CardReaderCompatibility is used to communicate whether or not a card reader will work with a device. |
| [com.cardflight.sdk.core.enums.CardReaderEvent](../com.cardflight.sdk.core.enums/-card-reader-event/index.md) | CardReaderEvent is used to communicate what event occurred on a card reader. |
| [com.cardflight.sdk.enumerations.CardReaderEvent](../com.cardflight.sdk.enumerations/-card-reader-event/index.md) | CardReaderEvent is used to communicate what event occurred on a card reader. |
| [com.cardflight.sdk.core.CardReaderInfo](../com.cardflight.sdk.core/-card-reader-info/index.md) | CardReaderInfo is used to provide information about a card reader. |
| [com.cardflight.sdk.core.enums.CardReaderModel](../com.cardflight.sdk.core.enums/-card-reader-model/index.md) | All compatible card readers, with their interface and supported card input methods |
| [com.cardflight.sdk.enumerations.CardReaderModel](../com.cardflight.sdk.enumerations/-card-reader-model/index.md) | All compatible card readers, with their interface and supported card input methods |
| [com.cardflight.sdk.core.enums.CardReaderType](../com.cardflight.sdk.core.enums/-card-reader-type/index.md) | Card reader type |
| [com.cardflight.sdk.enumerations.CardReaderType](../com.cardflight.sdk.enumerations/-card-reader-type/index.md) | Card reader type |
| [com.cardflight.sdk.core.interfaces.CompletionHandler](../com.cardflight.sdk.core.interfaces/-completion-handler/index.md) | Handler used for various asynchronous calls in the SDK. |
| [com.cardflight.sdk.core.EmvDetails](../com.cardflight.sdk.core/-emv-details/index.md) | EmvDetails class is used to provide all details required to be printed on a receipt according to EMV specification. |
| [com.cardflight.sdk.core.KeyedEntryContainer](../com.cardflight.sdk.core/-keyed-entry-container/index.md) | Container for the AVS-enabled card and address entry views. |
| [com.cardflight.sdk.core.enums.KeyedEntryContainerEvent](../com.cardflight.sdk.core.enums/-keyed-entry-container-event/index.md) | KeyedEntryContainerEvent is used to communicate events occurring inside the KeyedEntryContainer. |
| [com.cardflight.sdk.enumerations.KeyedEntryContainerEvent](../com.cardflight.sdk.enumerations/-keyed-entry-container-event/index.md) | KeyedEntryContainerEvent is used to communicate events occurring inside the KeyedEntryContainer. |
| [com.cardflight.sdk.core.interfaces.LoggerHandler](../com.cardflight.sdk.core.interfaces/-logger-handler/index.md) | Handler to accept log messages. |
| [com.cardflight.sdk.core.enums.LoggerLevel](../com.cardflight.sdk.core.enums/-logger-level/index.md) | All level types for any log message coming from the SDK. |
| [com.cardflight.sdk.core.MerchantAccount](../com.cardflight.sdk.core/-merchant-account/index.md) | Interface is used to define the features of a MerchantAccount object. |
| [com.cardflight.sdk.core.enums.MerchantAccountCapability](../com.cardflight.sdk.core.enums/-merchant-account-capability/index.md) | Copyright © 2019 CardFlight. All rights reserved. |
| [com.cardflight.sdk.MerchantAccountManager](../com.cardflight.sdk/-merchant-account-manager/index.md) | Manager to create and modify [MerchantAccount](../com.cardflight.sdk.core/-merchant-account/index.md) objects. |
| [com.cardflight.sdk.core.Message](../com.cardflight.sdk.core/-message/index.md) | Message is used to give messages to be displayed to the customer during a transaction. |
| [com.cardflight.sdk.core.enums.ProcessOption](../com.cardflight.sdk.core.enums/-process-option/index.md) | Options for processing a transaction. |
| [com.cardflight.sdk.enumerations.ProcessOption](../com.cardflight.sdk.enumerations/-process-option/index.md) | Options for processing a transaction. |
| [com.cardflight.sdk.core.enums.Reachability](../com.cardflight.sdk.core.enums/-reachability/index.md) | Reachability is used to specify whether a network connection is available. |
| [com.cardflight.sdk.enumerations.Reachability](../com.cardflight.sdk.enumerations/-reachability/index.md) | Reachability is used to specify whether a network connection is available. |
| [com.cardflight.sdk.ReaderUtilities](../com.cardflight.sdk/-reader-utilities/index.md) | ReaderUtilities is a tool used to connect to a card reader before starting a transaction. |
| [com.cardflight.sdk.core.interfaces.ReaderUtilitiesHandler](../com.cardflight.sdk.core.interfaces/-reader-utilities-handler/index.md) | ReaderUtilitiesHandler is used to communicate updates from the ReaderUtilities object. |
| [com.cardflight.sdk.core.enums.ReaderUtilitiesState](../com.cardflight.sdk.core.enums/-reader-utilities-state/index.md) | Session State of the [ReaderUtilities](#) object |
| [com.cardflight.sdk.core.exceptions.RefundException](../com.cardflight.sdk.core.exceptions/-refund-exception/index.md) | RefundException is used to throw exceptions during a refund. |
| [com.cardflight.sdk.core.interfaces.RefundHandler](../com.cardflight.sdk.core.interfaces/-refund-handler/index.md) | Handler for receiving information from a refund attempt. |
| [com.cardflight.sdk.SessionManager](../com.cardflight.sdk/-session-manager/index.md) | SessionManager object to manage a session. |
| [com.cardflight.sdk.enumerations.SessionState](../com.cardflight.sdk.enumerations/-session-state/index.md) | Session State of the [ReaderUtilities](#) object |
| [com.cardflight.sdk.core.Transaction](../com.cardflight.sdk.core/-transaction/index.md) | Interface defining a class used to create and manage a transaction. |
| [com.cardflight.sdk.core.enums.TransactionCapability](../com.cardflight.sdk.core.enums/-transaction-capability/index.md) | Copyright © 2019 CardFlight. All rights reserved. |
| [com.cardflight.sdk.enumerations.TransactionEvent](../com.cardflight.sdk.enumerations/-transaction-event/index.md) | Copyright © 2019 CardFlight. All rights reserved. |
| [com.cardflight.sdk.core.interfaces.TransactionHandler](../com.cardflight.sdk.core.interfaces/-transaction-handler/index.md) | Handler used to interact with and receive updates from the transaction. |
| [com.cardflight.sdk.TransactionManager](../com.cardflight.sdk/-transaction-manager/index.md) | Copyright © 2019 CardFlight. All rights reserved. |
| [com.cardflight.sdk.core.TransactionRecord](../com.cardflight.sdk.core/-transaction-record/index.md) | TransactionRecord provides information about a processed transaction. |
| [com.cardflight.sdk.core.interfaces.TransactionRecordHandler](../com.cardflight.sdk.core.interfaces/-transaction-record-handler/index.md) | Handler used to receive updates from a transaction record. |
| [com.cardflight.sdk.core.enums.TransactionResult](../com.cardflight.sdk.core.enums/-transaction-result/index.md) | TransactionResult describes the outcome of a transaction. |
| [com.cardflight.sdk.enumerations.TransactionResult](../com.cardflight.sdk.enumerations/-transaction-result/index.md) | TransactionResult describes the outcome of a transaction. |
| [com.cardflight.sdk.core.enums.TransactionState](../com.cardflight.sdk.core.enums/-transaction-state/index.md) | Current state of a transaction. |
| [com.cardflight.sdk.enumerations.TransactionState](../com.cardflight.sdk.enumerations/-transaction-state/index.md) | Current state of a transaction. |
| [com.cardflight.sdk.core.enums.TransactionType](../com.cardflight.sdk.core.enums/-transaction-type/index.md) | The type of transaction being performed. |
| [com.cardflight.sdk.enumerations.TransactionType](../com.cardflight.sdk.enumerations/-transaction-type/index.md) | The type of transaction being performed. |
