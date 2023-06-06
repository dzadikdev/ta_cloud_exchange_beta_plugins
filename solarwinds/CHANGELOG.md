# 3.0.0
## Added
- Added Support for the incident event type. To pull and ingest this event type update your CE version to 4.1.0
- Added Support for the CTEP alert type. To pull and ingest this alert type update your CE version to 4.2.0.
- Added support for WebTx format3.
## Changed
- Changed error logs to warning if single field is skipped.
- Empty alert, event, and WebTx data will not be sent to the SIEM platform.
## Fixed
- Fixed JSON format of raw data.
## Removed
- Removed priority from the syslog message for the logs that are not transformed in CEF.

# 2.0.1
## Added
- Added Incident ID mapping field in all alerts and events.

# 2.0.0
## Added
- Added support to send raw data to the SIEM Platform.

# 1.0.1
## Fixed
- Fixed Severity mappings for Audit events.

# 1.0.0
## Added
- Initial release.