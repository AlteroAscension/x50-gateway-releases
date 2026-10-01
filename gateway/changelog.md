# X50 Gateway 2.30.14-compass-factory-calib

- Automatic fallback to factory Belgee X50 cabin 2D hard/soft iron compass profile (cx=-304, cy=-343, sx=380, sy=437, dir=-1, offset=-74.6°) when user has not yet recorded custom manual circle calibration.
- Fixes raw compass heading distortion across South-West (210°-240°) and North-West (300°-330°) sectors.
- Automatically marks sensor_calibration_applied: true and sends calibrated heading to Navigation module.
- Bundles updated ESP32-S3 firmware 1.1.16 with Golden Balanced Profile v2 (analytical 3D ellipsoid calibration).
- Hardware compass calibration control in Gateway UI (Start collection, Apply & save to NVS, Cancel, Reset to factory).
- Magisk module versionCode: 82
- SHA-256: `5b9849c392b8451abc0f34bb61df020f1ef73f430bc9b4c37974a639076ffe78`
- Module ZIP: https://raw.githubusercontent.com/AlteroAscension/x50-gateway-releases/main/gateway/releases/gateway-v2.30.14-compass-factory-calib/x50-gateway-magisk.zip