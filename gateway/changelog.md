# X50 Gateway 2.29.12-full-trip-journal

- Improved Classic Bluetooth discovery with cancel/settle/retry handling for the ECarX radio.
- Failed direct RFCOMM connections now wake the radio through SDP/discovery and retry automatically.
- Pairing PIN injection no longer cancels its own pending bond request; repeat pairing waits for the old bond to be removed.
- Uploads archived and live virtual steering trajectories to Home Assistant.
- New UI toggle 'Прямое подключение (без сопряжения)' and dedicated in-app [Подключить], [Сопрячь], [Отвязать] buttons.
- Magisk module versionCode: 67
- SHA-256: `9f598ed60798340040e2da3aad294c7b91ea6285a7bcc86a6af2598c72b62583`
- Module ZIP: https://raw.githubusercontent.com/AlteroAscension/x50-gateway-releases/main/gateway/releases/gateway-v2.29.12-full-trip-journal/x50-gateway-magisk.zip

See the repository CHANGELOG.md and release notes for functional changes.