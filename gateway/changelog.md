# X50 Gateway 2.29.4-bt-recovery

- Improved Classic Bluetooth discovery with cancel/settle/retry handling for the ECarX radio.
- Failed direct RFCOMM connections now wake the radio through SDP/discovery and retry automatically.
- Pairing PIN injection no longer cancels its own pending bond request; repeat pairing waits for the old bond to be removed.
- Uploads archived and live virtual steering trajectories to Home Assistant.
- New UI toggle 'РџСЂСЏРјРѕРµ РїРѕРґРєР»СЋС‡РµРЅРёРµ (Р±РµР· СЃРѕРїСЂСЏР¶РµРЅРёСЏ)' and dedicated in-app [РџРѕРґРєР»СЋС‡РёС‚СЊ], [РЎРѕРїСЂСЏС‡СЊ], [РћС‚РІСЏР·Р°С‚СЊ] buttons.
- Magisk module versionCode: 59
- SHA-256: `88da6b38bc44a56ecb6c122ae8faa22cbdb4cd6d9634be52e0b930542f15d40d`
- Module ZIP: https://raw.githubusercontent.com/AlteroAscension/x50-gateway-releases/main/gateway/releases/gateway-v2.29.4-bt-recovery/x50-gateway-magisk.zip

See the repository CHANGELOG.md and release notes for functional changes.