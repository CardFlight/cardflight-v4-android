[payments-android-byod](../../index.md) / [com.cardflight.sdk.core.enums](../index.md) / [CardBrand](./index.md)

# CardBrand

`enum class CardBrand`

All card brands recognized by the SDK. Not all recognized cards are supported for running
transactions. Credit card numbers starting within the specified range are considered part of that
card brand

Copyright © 2019 CardFlight. All rights reserved.

**Author**
Austin Odell

**Since**
v1.0.0

### Enum Values

| Name | Summary |
|---|---|
| [UNKNOWN](-u-n-k-n-o-w-n.md) | Unknown |
| [AMERICAN_EXPRESS](-a-m-e-r-i-c-a-n_-e-x-p-r-e-s-s.md) | American Express |
| [CHINA_UNIONPAY](-c-h-i-n-a_-u-n-i-o-n-p-a-y.md) | China UnionPay |
| [DINERS_CLUB_CARTE_BLANCHE](-d-i-n-e-r-s_-c-l-u-b_-c-a-r-t-e_-b-l-a-n-c-h-e.md) | Diners Club Carte Blanche |
| [DINERS_CLUB_INTERNATIONAL](-d-i-n-e-r-s_-c-l-u-b_-i-n-t-e-r-n-a-t-i-o-n-a-l.md) | Diners Club International |
| [DINERS_CLUB](-d-i-n-e-r-s_-c-l-u-b.md) | Diners Club |
| [DISCOVER_CARD](-d-i-s-c-o-v-e-r_-c-a-r-d.md) | Discover Card |
| [INTERPAYMENT](-i-n-t-e-r-p-a-y-m-e-n-t.md) | InterPayment |
| [INSTAPAYMENT](-i-n-s-t-a-p-a-y-m-e-n-t.md) | InstaPayment |
| [JCB](-j-c-b.md) | JCB |
| [MAESTRO](-m-a-e-s-t-r-o.md) | Maestro |
| [DANKORT](-d-a-n-k-o-r-t.md) | Dankort |
| [MASTERCARD](-m-a-s-t-e-r-c-a-r-d.md) | Mastercard |
| [VISA](-v-i-s-a.md) | Visa |
| [UATP](-u-a-t-p.md) | Universal Air Travel Plan |
| [CARDGUARD](-c-a-r-d-g-u-a-r-d.md) | CardGuard |

### Properties

| Name | Summary |
|---|---|
| [cardBrandAbbreviation](card-brand-abbreviation.md) | `val cardBrandAbbreviation: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>The abbreviated name of the card brand. *Note: Not all card brands have an abbreviation.* |
| [cardBrandName](card-brand-name.md) | `val cardBrandName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>The name of the card brand |
