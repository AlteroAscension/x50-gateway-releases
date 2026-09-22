# X50 Gateway 2.29.4-bt-recovery

- Direct Insecure RFCOMM socket connection (bypasses Android pairing/bonding and stock head-unit Bluetooth restrictions).
- Multi-tier RFCOMM socket fallback: Insecure SPP UUID -> Insecure Channel 1 -> Secure SPP UUID -> Secure Channel 1.
- Added BLUETOOTH_PRIVILEGED to Magisk PrivApp whitelist and runtime elevation via su.
- Added ElmPairingReceiver manifest-level receiver for 100% reliable ACTION_PAIRING_REQUEST capture.
- Pre-set PIN injection on createBond and cancelPairingUserInput dismissal.
- New UI toggle 'Прямое подключение (без сопряжения)' and dedicated in-app [Подключить], [Сопрячь], [Отвязать] buttons.
- Magisk module versionCode: 59
- SHA-256: `554e3ba97f562f98810501f05f4243f1145e49cd043600259423cfb07d6fa9fe`
- Module ZIP: https://raw.githubusercontent.com/AlteroAscension/x50-gateway-releases/main/gateway/releases/gateway-v2.29.4-bt-recovery/x50-gateway-magisk.zip

See the repository CHANGELOG.md and release notes for functional changes.