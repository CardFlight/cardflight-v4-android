[payments-android-byod](../../index.md) / [com.cardflight.sdk.enumerations](../index.md) / [TransactionEvent](./index.md)

# TransactionEvent

`enum class ~~TransactionEvent~~`
**Deprecated:** Use com.cardflight.sdk.core.enums.TransactionEvent instead. This class will be removed in v4.9.0.

Copyright © 2019 CardFlight. All rights reserved.

**Author**
Austin Odell

**Since**
v4.0.0

### Enum Values

| Name | Summary |
|---|---|
| [UNKNOWN](-u-n-k-n-o-w-n.md) |  |
| [USER_CREATE_TRANSACTION](-u-s-e-r_-c-r-e-a-t-e_-t-r-a-n-s-a-c-t-i-o-n.md) |  |
| [USER_REQUEST_BEGIN_TRANSACTION](-u-s-e-r_-r-e-q-u-e-s-t_-b-e-g-i-n_-t-r-a-n-s-a-c-t-i-o-n.md) |  |
| [USER_ATTACH_KEYED_CARD_INFO_ENCRYPTED](-u-s-e-r_-a-t-t-a-c-h_-k-e-y-e-d_-c-a-r-d_-i-n-f-o_-e-n-c-r-y-p-t-e-d.md) |  |
| [USER_ATTACH_KEYED_CARD_INFO_UNENCRYPTED](-u-s-e-r_-a-t-t-a-c-h_-k-e-y-e-d_-c-a-r-d_-i-n-f-o_-u-n-e-n-c-r-y-p-t-e-d.md) |  |
| [READER_ATTACH_SWIPE_CARD_INFO](-r-e-a-d-e-r_-a-t-t-a-c-h_-s-w-i-p-e_-c-a-r-d_-i-n-f-o.md) |  |
| [READER_ATTACH_DIP_CARD_INFO](-r-e-a-d-e-r_-a-t-t-a-c-h_-d-i-p_-c-a-r-d_-i-n-f-o.md) |  |
| [READER_ATTACH_TAP_CARD_INFO](-r-e-a-d-e-r_-a-t-t-a-c-h_-t-a-p_-c-a-r-d_-i-n-f-o.md) |  |
| [READER_ATTACH_QUICK_CHIP_CARD_INFO](-r-e-a-d-e-r_-a-t-t-a-c-h_-q-u-i-c-k_-c-h-i-p_-c-a-r-d_-i-n-f-o.md) |  |
| [USER_REQUEST_RESUME_DEFER](-u-s-e-r_-r-e-q-u-e-s-t_-r-e-s-u-m-e_-d-e-f-e-r.md) |  |
| [USER_REQUEST_PROCESS_WITH_VALID_CREDENTIALS](-u-s-e-r_-r-e-q-u-e-s-t_-p-r-o-c-e-s-s_-w-i-t-h_-v-a-l-i-d_-c-r-e-d-e-n-t-i-a-l-s.md) |  |
| [USER_REQUEST_PROCESS_WITH_INVALID_CREDENTIALS](-u-s-e-r_-r-e-q-u-e-s-t_-p-r-o-c-e-s-s_-w-i-t-h_-i-n-v-a-l-i-d_-c-r-e-d-e-n-t-i-a-l-s.md) |  |
| [USER_REQUEST_DEFER](-u-s-e-r_-r-e-q-u-e-s-t_-d-e-f-e-r.md) |  |
| [USER_REQUEST_ABORT](-u-s-e-r_-r-e-q-u-e-s-t_-a-b-o-r-t.md) |  |
| [API_APPROVAL](-a-p-i_-a-p-p-r-o-v-a-l.md) |  |
| [API_DECLINE](-a-p-i_-d-e-c-l-i-n-e.md) |  |
| [API_ERROR](-a-p-i_-e-r-r-o-r.md) |  |
| [READER_REQUEST_CONFIRMATION](-r-e-a-d-e-r_-r-e-q-u-e-s-t_-c-o-n-f-i-r-m-a-t-i-o-n.md) |  |
| [READER_REQUEST_REVERSE](-r-e-a-d-e-r_-r-e-q-u-e-s-t_-r-e-v-e-r-s-e.md) |  |
| [API_CONFIRMATION_SUCCESS](-a-p-i_-c-o-n-f-i-r-m-a-t-i-o-n_-s-u-c-c-e-s-s.md) |  |
| [API_CONFIRMATION_FAIL](-a-p-i_-c-o-n-f-i-r-m-a-t-i-o-n_-f-a-i-l.md) |  |
| [READER_COMPLETE](-r-e-a-d-e-r_-c-o-m-p-l-e-t-e.md) |  |
| [API_REQUEST_NO_CVM](-a-p-i_-r-e-q-u-e-s-t_-n-o_-c-v-m.md) |  |
| [USER_ATTACH_CVM](-u-s-e-r_-a-t-t-a-c-h_-c-v-m.md) |  |
| [READER_DISCONNECT](-r-e-a-d-e-r_-d-i-s-c-o-n-n-e-c-t.md) |  |
| [USER_REMOVE_CARD](-u-s-e-r_-r-e-m-o-v-e_-c-a-r-d.md) |  |
| [MANAGER_REPORT_UNKNOWN](-m-a-n-a-g-e-r_-r-e-p-o-r-t_-u-n-k-n-o-w-n.md) |  |
| [MANAGER_REPORT_PENDING_TRANSACTION_PARAMETERS](-m-a-n-a-g-e-r_-r-e-p-o-r-t_-p-e-n-d-i-n-g_-t-r-a-n-s-a-c-t-i-o-n_-p-a-r-a-m-e-t-e-r-s.md) |  |
| [MANAGER_REPORT_PENDING_CARD_INPUT](-m-a-n-a-g-e-r_-r-e-p-o-r-t_-p-e-n-d-i-n-g_-c-a-r-d_-i-n-p-u-t.md) |  |
| [MANAGER_REPORT_PENDING_PROCESS_OPTION_KEYED_ENCRYPTED](-m-a-n-a-g-e-r_-r-e-p-o-r-t_-p-e-n-d-i-n-g_-p-r-o-c-e-s-s_-o-p-t-i-o-n_-k-e-y-e-d_-e-n-c-r-y-p-t-e-d.md) |  |
| [MANAGER_REPORT_PENDING_PROCESS_OPTION_KEYED_UNENCRYPTED](-m-a-n-a-g-e-r_-r-e-p-o-r-t_-p-e-n-d-i-n-g_-p-r-o-c-e-s-s_-o-p-t-i-o-n_-k-e-y-e-d_-u-n-e-n-c-r-y-p-t-e-d.md) |  |
| [MANAGER_REPORT_PENDING_PROCESS_OPTION_SWIPE](-m-a-n-a-g-e-r_-r-e-p-o-r-t_-p-e-n-d-i-n-g_-p-r-o-c-e-s-s_-o-p-t-i-o-n_-s-w-i-p-e.md) |  |
| [MANAGER_REPORT_PENDING_PROCESS_OPTION_DIP](-m-a-n-a-g-e-r_-r-e-p-o-r-t_-p-e-n-d-i-n-g_-p-r-o-c-e-s-s_-o-p-t-i-o-n_-d-i-p.md) |  |
| [MANAGER_REPORT_PENDING_PROCESS_OPTION_TAP](-m-a-n-a-g-e-r_-r-e-p-o-r-t_-p-e-n-d-i-n-g_-p-r-o-c-e-s-s_-o-p-t-i-o-n_-t-a-p.md) |  |
| [MANAGER_REPORT_PENDING_PROCESS_OPTION_QUICK_CHIP](-m-a-n-a-g-e-r_-r-e-p-o-r-t_-p-e-n-d-i-n-g_-p-r-o-c-e-s-s_-o-p-t-i-o-n_-q-u-i-c-k_-c-h-i-p.md) |  |
| [MANAGER_REPORT_PROCESSING](-m-a-n-a-g-e-r_-r-e-p-o-r-t_-p-r-o-c-e-s-s-i-n-g.md) |  |
| [MANAGER_REPORT_CONFIRMING](-m-a-n-a-g-e-r_-r-e-p-o-r-t_-c-o-n-f-i-r-m-i-n-g.md) |  |
| [MANAGER_REPORT_PENDING_CVM](-m-a-n-a-g-e-r_-r-e-p-o-r-t_-p-e-n-d-i-n-g_-c-v-m.md) |  |
| [MANAGER_REPORT_COMPLETED](-m-a-n-a-g-e-r_-r-e-p-o-r-t_-c-o-m-p-l-e-t-e-d.md) |  |
| [MANAGER_REPORT_DEFERRED_KEYED](-m-a-n-a-g-e-r_-r-e-p-o-r-t_-d-e-f-e-r-r-e-d_-k-e-y-e-d.md) |  |
| [MANAGER_REPORT_DEFERRED_SWIPED](-m-a-n-a-g-e-r_-r-e-p-o-r-t_-d-e-f-e-r-r-e-d_-s-w-i-p-e-d.md) |  |
| [READER_ERROR](-r-e-a-d-e-r_-e-r-r-o-r.md) |  |
