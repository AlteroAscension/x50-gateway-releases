# X50 Gateway 2.29.0-elm-steering

- Added ELM327 Bluetooth SPP integration for CAN ID 0x0E0 steering wheel angle (0.1 deg) and rotation rate intake.
- Silent Bluetooth pairing receiver (no confirmation prompt on head unit) and automatic connection watchdog.
- Publishes fresh steering telemetry to Settings.Global (x50_steering_wheel_angle_deg, x50_steering_wheel_rate_dps, x50_steering_wheel_fresh) and /api/telemetry.
- Added dedicated ELM327 tab in Gateway UI with live steering angle indicator, autoconnect toggles, and device selection.
- Magisk module versionCode: 55
- SHA-256: `d2adbc8d92934339bbc7651ba26014b20462e11672b76a385f9b34fcf9d3f258`
- Module ZIP: https://raw.githubusercontent.com/AlteroAscension/x50-gateway-releases/main/gateway/releases/gateway-v2.29.0-elm-steering/x50-gateway-magisk.zip

See the repository CHANGELOG.md and release notes for functional changes.