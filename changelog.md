## 4.8.14
- Additions
  - `TransactionState.PENDING_ADJUSTMENT` and `TransactionState.PENDING_CVM`
- Fixes
  - Keyed Entry not always being available when it should
  - Various bug fixes and performance improvements


## 4.8.10
- Additions
  - TransactionManager to create transactions
  - MerchantAccountManager to create merchant accounts
- Changes
  - Credentials became MerchantAccount
  - HistoricalTransaction became TransactionRecord
  - Many classes deprecated and will be removed in v4.9.0
- Fixes
  - Various bug fixes and performance improvements


## 4.6.3
- Fixes
  - Various bug fixes and performance improvements


## 4.6.2
- Fixes
  - Don't require CVV for keyed transactions
  - Change process prompt for tokenization transactions
  - Various bug fixes and performance improvements


## 4.6.0
- Additions
  - Accept AVS details on keyed transactions

- Changes
  - Keyed transactions can be disabled


## 4.5.3
- Additions
  - Debug logging is now available in the LoggerHandler


## 4.5.2
- Additions
  - Card ID is now provided on the `CardInfo` object

- Fixes
  - Large transaction amounts can now be processed using more readers


## 4.5.1
- Fixes
  - Improved connectivity for Samsung Galaxy S7 devices


## 4.5.0
- Fixes
  - Dates on HistoricalTransaction objects


## 4.4.2
- Fixes
  - Improved reader connectivity for the B550


## 4.4.1
- Fixes
  - Various bug fixes and performance improvements


## 4.4.0
- Changes
  - CVV is now optional on the `KeyedEntryView`

- Fixes
  - Various bug fixes and performance improvements


## 4.3.2
- Fixes
  - Various bug fixes and performance improvements


## 4.3.0
- Additions
  - TokenizationParameters class to add a Customer ID to a tokenization

- Changes
  - beginTokenization now takes a TokenizationParameters object as the only parameter

- Fixes
  - Various bug fixes and performance improvements


## 4.2.0
- Additions
  - Ability to create Historical Transactions from charge IDs
  - Additional field to Historical Transactions
  - Utility class to allow reader connection outside of Transaction
  - Auto config support for improving connections with Audio Jack readers

- Fixes
  - Various bug fixes and performance improvements


## 4.1.0
- Additions
  - B550 NFC support
  - A100 support
  - `chargeId` saved to `HistoricalTransaction`
  - Resume/Defer a `Transaction`
  - Set `Reachability` of `Transaction`
  - `close` method added to `Transaction`
  - Reference Number saved to `HistoricalTransaction`
  - Quick Chip support
  - `BatteryStatus` updates reported
  - Tokenization support
  - Connecting `CardReaderEvent` reported

- Changes
  - Card removal not required
  - Attaching a signature requires a `Bitmap`

- Fixes
  - Transaction messaging
  - Improved reader error handling
  - Text overlap in `KeyedEntryView`
  - Permissions crash
