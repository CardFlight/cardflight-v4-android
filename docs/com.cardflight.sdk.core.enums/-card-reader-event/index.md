[payments-android-byod](../../index.md) / [com.cardflight.sdk.core.enums](../index.md) / [CardReaderEvent](./index.md)

# CardReaderEvent

`enum class CardReaderEvent`

CardReaderEvent is used to communicate what event occurred on a card reader.

Copyright © 2019 CardFlight. All rights reserved.

**Author**
Austin Odell

**Since**
v1.0.0

### Enum Values

| Name | Summary |
|---|---|
| [DISCONNECTED](-d-i-s-c-o-n-n-e-c-t-e-d.md) | Card reader disconnected. |
| [CONNECTED](-c-o-n-n-e-c-t-e-d.md) | Card reader connected. |
| [CONNECTING](-c-o-n-n-e-c-t-i-n-g.md) | Card reader connecting. |
| [CONNECTION_ERRORED](-c-o-n-n-e-c-t-i-o-n_-e-r-r-o-r-e-d.md) | Card reader connection errored. |
| [CARD_SWIPED](-c-a-r-d_-s-w-i-p-e-d.md) | Card swiped on card reader. |
| [CARD_SWIPE_ERRORED](-c-a-r-d_-s-w-i-p-e_-e-r-r-o-r-e-d.md) | Card swipe errored on card reader. *(Usually means to retry swipe.)* |
| [CARD_DIPPED](-c-a-r-d_-d-i-p-p-e-d.md) | Card dipped on card reader. |
| [CARD_DIP_ERRORED](-c-a-r-d_-d-i-p_-e-r-r-o-r-e-d.md) | Card dip errored on card reader. *(Usually means to retry dip.)* |
| [CARD_REMOVED](-c-a-r-d_-r-e-m-o-v-e-d.md) | Card removed from card reader. |
| [CARD_TAPPED](-c-a-r-d_-t-a-p-p-e-d.md) | Card tapped on card reader. |
| [CARD_TAP_ERRORED](-c-a-r-d_-t-a-p_-e-r-r-o-r-e-d.md) | Card tap errored on card reader. |
| [UPDATE_STARTED](-u-p-d-a-t-e_-s-t-a-r-t-e-d.md) | Card reader update started. |
| [UPDATE_COMPLETED](-u-p-d-a-t-e_-c-o-m-p-l-e-t-e-d.md) | Card reader update onComplete. |
| [BLUETOOTH_PERMISSION_NOT_GRANTED](-b-l-u-e-t-o-o-t-h_-p-e-r-m-i-s-s-i-o-n_-n-o-t_-g-r-a-n-t-e-d.md) | Permission android.permission.BLUETOOTH not granted. |
| [BLUETOOTH_ADMIN_PERMISSION_NOT_GRANTED](-b-l-u-e-t-o-o-t-h_-a-d-m-i-n_-p-e-r-m-i-s-s-i-o-n_-n-o-t_-g-r-a-n-t-e-d.md) | Permission android.permission.BLUETOOTH_ADMIN not granted. |
| [RECORD_AUDIO_PERMISSION_NOT_GRANTED](-r-e-c-o-r-d_-a-u-d-i-o_-p-e-r-m-i-s-s-i-o-n_-n-o-t_-g-r-a-n-t-e-d.md) | Permission android.permission.RECORD_AUDIO not granted. |
| [ACCESS_COARSE_LOCATION_PERMISSION_NOT_GRANTED](-a-c-c-e-s-s_-c-o-a-r-s-e_-l-o-c-a-t-i-o-n_-p-e-r-m-i-s-s-i-o-n_-n-o-t_-g-r-a-n-t-e-d.md) | Permission android.permission.ACCESS_COARSE_LOCATION not granted. |
| [WRITE_EXTERNAL_STORAGE_PERMISSION_NOT_GRANTED](-w-r-i-t-e_-e-x-t-e-r-n-a-l_-s-t-o-r-a-g-e_-p-e-r-m-i-s-s-i-o-n_-n-o-t_-g-r-a-n-t-e-d.md) | Permission android.permission.WRITE_EXTERNAL_STORAGE not granted. |
| [READER_FATAL_ERROR](-r-e-a-d-e-r_-f-a-t-a-l_-e-r-r-o-r.md) | Card reader error occurred. |
| [BATTERY_STATUS_UPDATED](-b-a-t-t-e-r-y_-s-t-a-t-u-s_-u-p-d-a-t-e-d.md) | Card reader battery status updated. |
