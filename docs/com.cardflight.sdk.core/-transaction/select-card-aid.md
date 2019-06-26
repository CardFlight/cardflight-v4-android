[payments-android-byod](../../index.md) / [com.cardflight.sdk.core](../index.md) / [Transaction](index.md) / [selectCardAid](./select-card-aid.md)

# selectCardAid

`abstract fun selectCardAid(cardAid: `[`CardAID`](../-card-a-i-d/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Select which card application to use on a card. This should only be called after receiving the
[onRequestCardAidSelection](../../com.cardflight.sdk.core.interfaces/-transaction-handler/on-request-card-aid-selection.md) callback.

### Parameters

`cardAid` - CardAID object to use.