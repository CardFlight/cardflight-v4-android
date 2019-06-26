[payments-android-byod](../../index.md) / [com.cardflight.sdk.core](../index.md) / [KeyedEntryContainer](./index.md)

# KeyedEntryContainer

`interface KeyedEntryContainer`

Container for the AVS-enabled card and address entry views.

Copyright © 2019 CardFlight. All rights reserved.

**Author**
Austin Odell

**Since**
v1.0.0

### Properties

| Name | Summary |
|---|---|
| [addressEntryView](address-entry-view.md) | `abstract val addressEntryView: `[`View`](https://developer.android.com/reference/android/view/View.html)`?`<br>View for address entry. |
| [cardEntryView](card-entry-view.md) | `abstract val cardEntryView: `[`View`](https://developer.android.com/reference/android/view/View.html)<br>View for card entry. |

### Functions

| Name | Summary |
|---|---|
| [clearAddressEntryView](clear-address-entry-view.md) | `abstract fun clearAddressEntryView(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Clears all input fields on address entry view. |
| [clearCardEntryView](clear-card-entry-view.md) | `abstract fun clearCardEntryView(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Clears all input fields on card entry view. |
