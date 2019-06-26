[payments-android-byod](../../index.md) / [com.cardflight.sdk.core](../index.md) / [CardInfo](./index.md)

# CardInfo

`interface CardInfo`

CardInfo class is used to give all necessary information from a physical card.

Copyright © 2019 CardFlight. All rights reserved.

**Author**
Austin Odell

**Since**
v1.0.0

### Properties

| Name | Summary |
|---|---|
| [applicationId](application-id.md) | `abstract val applicationId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>Application Identifier of the card. |
| [applicationPreferredName](application-preferred-name.md) | `abstract val applicationPreferredName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>Application Preferred Name of the card. |
| [cardBrand](card-brand.md) | `abstract val cardBrand: `[`CardBrand`](../../com.cardflight.sdk.core.enums/-card-brand/index.md)`?`<br>Brand of the card. |
| [cardId](card-id.md) | `abstract val cardId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>Unique identifier for the card. |
| [cardInputMethod](card-input-method.md) | `abstract val cardInputMethod: `[`CardInputMethod`](../../com.cardflight.sdk.core.enums/-card-input-method/index.md)`?`<br>Card input method representing the way the card information was captured. |
| [cardReaderModel](card-reader-model.md) | `abstract val cardReaderModel: `[`CardReaderModel`](../../com.cardflight.sdk.core.enums/-card-reader-model/index.md)`?`<br>Model of the card reader used to capture the card. This will not be populated if the card input method is [keyed](../../com.cardflight.sdk.core.enums/-card-input-method/-k-e-y.md). |
| [cardholderName](cardholder-name.md) | `abstract val cardholderName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>Name of the cardholder. |
| [emvDetails](emv-details.md) | `abstract val emvDetails: `[`EmvDetails`](../-emv-details/index.md)`?`<br>Additional EMV details required to be printed on a receipt. |
| [expirationMonth](expiration-month.md) | `abstract val expirationMonth: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>Expiration month of the card as a two digit representation. |
| [expirationYear](expiration-year.md) | `abstract val expirationYear: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>Expiration year of the card as a two digit representation. |
| [firstSix](first-six.md) | `abstract val firstSix: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>First six digits of the card number. |
| [lastFour](last-four.md) | `abstract val lastFour: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?`<br>Last four digits of the card number. |
