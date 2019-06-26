[payments-android-byod](../../index.md) / [com.cardflight.sdk.core.enums](../index.md) / [TransactionState](./index.md)

# TransactionState

`enum class TransactionState`

Current state of a transaction.

Copyright © 2019 CardFlight. All rights reserved.

**Author**
Austin Odell

**Since**
v1.0.0

### Enum Values

| Name | Summary |
|---|---|
| [UNKNOWN](-u-n-k-n-o-w-n.md) | Transaction is in an unknown state. |
| [PENDING_TRANSACTION_PARAMETERS](-p-e-n-d-i-n-g_-t-r-a-n-s-a-c-t-i-o-n_-p-a-r-a-m-e-t-e-r-s.md) | Transaction is in the pending transaction parameters state, it requires a [TransactionParameters](#) object. |
| [PENDING_CARD_INPUT](-p-e-n-d-i-n-g_-c-a-r-d_-i-n-p-u-t.md) | Transaction is in the pending card input state, it requires card input. |
| [PENDING_PROCESS_OPTION](-p-e-n-d-i-n-g_-p-r-o-c-e-s-s_-o-p-t-i-o-n.md) | Transaction is in the pending process option state, it requires calling [selectProcessOption](#). |
| [PROCESSING](-p-r-o-c-e-s-s-i-n-g.md) | Transaction is in the processing state. |
| [COMPLETED](-c-o-m-p-l-e-t-e-d.md) | Transaction is in the onComplete state. |
| [DEFERRED](-d-e-f-e-r-r-e-d.md) | Transaction is in the deferred state, it requires calling [resumeTransaction](#). |
