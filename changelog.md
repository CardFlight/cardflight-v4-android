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
