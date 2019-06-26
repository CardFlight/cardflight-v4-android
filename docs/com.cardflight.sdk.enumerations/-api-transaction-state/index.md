[payments-android-byod](../../index.md) / [com.cardflight.sdk.enumerations](../index.md) / [ApiTransactionState](./index.md)

# ApiTransactionState

`enum class ~~ApiTransactionState~~`
**Deprecated:** Use com.cardflight.sdk.core.enums.ApiTransactionState instead. This class will be removed in v4.9.0.

ApiTransactionState is used to communicate the state of a given transaction on the API.

Copyright © 2019 CardFlight. All rights reserved.

**Author**
Austin Odell

**Since**
v4.6.0

### Enum Values

| Name | Summary |
|---|---|
| [UNKNOWN](-u-n-k-n-o-w-n.md) | Api State is unknown. |
| [PENDING_PRE_APPROVED](-p-e-n-d-i-n-g_-p-r-e_-a-p-p-r-o-v-e-d.md) | Api State is pending pre approved (pending authorization). |
| [PRE_APPROVED](-p-r-e_-a-p-p-r-o-v-e-d.md) | Api State is pre approved (authorized). |
| [PENDING_APPROVED](-p-e-n-d-i-n-g_-a-p-p-r-o-v-e-d.md) | Api State is pending approved (pending capture). |
| [APPROVED](-a-p-p-r-o-v-e-d.md) | Api State is approved (captured). |
| [PENDING_VOID](-p-e-n-d-i-n-g_-v-o-i-d.md) | Api State is pending void (voiding). |
| [VOIDED](-v-o-i-d-e-d.md) | Api State is voided. |
| [DECLINED](-d-e-c-l-i-n-e-d.md) | Api State is declined. |
| [SETTLED](-s-e-t-t-l-e-d.md) | Api State is settled (batch containing transaction closed). |
