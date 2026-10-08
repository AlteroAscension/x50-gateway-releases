# X50 Gateway 2.30.18-sensor-timing

- Bundles ESP32-S3 firmware 1.1.20 with acquisition timestamps for steering, compass, GPS and vehicle measurements.
- Synchronizes ESP and head-unit clocks periodically and after reconnect/reboot; exposes timing uncertainty and calibration diagnostics.
- Supplies timestamped measurement history to Navigation, including delayed samples, while retaining compatibility with older clients.
- Adds CAN frame cadence/gap and USB parsing diagnostics for trip analysis.
- Install as a Magisk module, reboot the head unit, then update ESP through Gateway. Navigation 0.15.99 uses the new history feed; Relay does not require an update.

- versionCode: 86
- SHA-256: b2d8649439ff6256efc75e036b96bd5af64d0dd74210d3f263da6b5b18b44945
