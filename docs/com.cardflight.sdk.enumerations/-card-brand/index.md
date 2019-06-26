[payments-android-byod](../../index.md) / [com.cardflight.sdk.enumerations](../index.md) / [CardBrand](./index.md)

# CardBrand

`enum class ~~CardBrand~~`
**Deprecated:** Use com.cardflight.sdk.core.enums.CardBrand instead. This class will be removed in v4.9.0.

All card brands recognized by the SDK. Not all recognized cards are supported for running
transactions. Credit card numbers starting within the specified range are considered part of that
card brand

Copyright © 2019 CardFlight. All rights reserved.

**Author**
Austin Odell

**Since**
v4.0.0

**See Also**

[com.cardflight.sdk.core.enums.CardBrand](../../com.cardflight.sdk.core.enums/-card-brand/index.md)

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

### Functions

| Name | Summary |
|---|---|
| [getName](get-name.md) | `fun getName(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Returns the name of the CardBrand. |
| [getShortName](get-short-name.md) | `fun getShortName(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>Returns the short name of the CardBrand if one exists, otherwise it returns the full name. |
