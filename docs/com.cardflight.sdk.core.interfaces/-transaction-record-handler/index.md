[payments-android-byod](../../index.md) / [com.cardflight.sdk.core.interfaces](../index.md) / [TransactionRecordHandler](./index.md)

# TransactionRecordHandler

`interface TransactionRecordHandler`

Handler used to receive updates from a transaction record.

Copyright © 2019 CardFlight. All rights reserved.

**Author**
Austin Odell

**Since**
v1.0.0

### Functions

| Name | Summary |
|---|---|
| [onComplete](on-complete.md) | `abstract fun onComplete(transactionRecord: `[`TransactionRecord`](../../com.cardflight.sdk.core/-transaction-record/index.md)`?, error: `[`Error`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-error/index.html)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Transaction record was created or errored. |
