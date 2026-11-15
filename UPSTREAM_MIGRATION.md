# Upstream integration

- Merged `syncfusion/flutter-widgets` master at `4f7cfc2a`.
- GitHub master still publishes 35.1.37. Applied the official pub.dev 35.1.46 release sources for calendar, core, datepicker and localizations; normalized CRLF and Dart formatting before three-way merging local changes.
- Retained local path dependencies, and declared `collection` for the existing stable sort. No dependency overrides.
- Preserved holiday data, month-cell headers, weekend/holiday colors, today background, stable appointment ordering, compact appointment layout, span-icon suppression and text clipping.
- Release files are applied individually; examples and screenshots remain from GitHub upstream.

## Verified release archives

- `syncfusion_flutter_calendar 35.1.46`: https://pub.dev/api/archives/syncfusion_flutter_calendar-35.1.46.tar.gz
  SHA256: `12b0e2ab604bee47cf4c9dc071144b6a9f2a856545fdf1423fe08e6a5002a5b0`
- `syncfusion_flutter_core 35.1.46`: https://pub.dev/api/archives/syncfusion_flutter_core-35.1.46.tar.gz
  SHA256: `f62f7a981072ce5dfbff4d8cf2fc667322a65ba0cfd13bf357270827b7206191`
- `syncfusion_flutter_datepicker 35.1.46`: https://pub.dev/api/archives/syncfusion_flutter_datepicker-35.1.46.tar.gz
  SHA256: `7ba83d4c9e31fb3b71c7c418050746ff7813de9e7cce02f727ad08acaa125d1b`
- `syncfusion_localizations 35.1.46`: https://pub.dev/api/archives/syncfusion_localizations-35.1.46.tar.gz
  SHA256: `b21a6a7d590949abeca525adab28e0526bc42e2bc3924fa4813a77cde3863d5d`
