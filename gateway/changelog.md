# X50 Gateway 2.30.13-compass-factory-calib

- Automatic fallback to factory Belgee X50 cabin 2D hard/soft iron compass profile (cx=-304, cy=-343, sx=380, sy=437, dir=-1, offset=-74.6°) when user has not yet recorded custom manual circle calibration.
- Fixes raw compass heading distortion across South-West (210°-240°) and North-West (300°-330°) sectors.
- Automatically marks `sensor_calibration_applied: true` and sends calibrated heading to Navigation module.
- Magisk module versionCode: 81
- SHA-256: `aded06fae02a80a2c7d3e89f7983d82bfb1237ad6c429cd449a3c8682aad3991`
- Module ZIP: https://raw.githubusercontent.com/AlteroAscension/x50-gateway-releases/main/gateway/releases/gateway-v2.30.13-compass-factory-calib/x50-gateway-magisk.zip
