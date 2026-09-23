# X50 Gateway 2.29.5-trajectory-relay

- Improved Classic Bluetooth discovery with cancel/settle/retry handling for the ECarX radio.
- Failed direct RFCOMM connections now wake the radio through SDP/discovery and retry automatically.
- Pairing PIN injection no longer cancels its own pending bond request; repeat pairing waits for the old bond to be removed.
- Uploads archived and live virtual steering trajectories to Home Assistant.
- New UI toggle 'РџСЂСЏРјРѕРµ РїРѕРґРєР»СЋС‡РµРЅРёРµ (Р±РµР· СЃРѕРїСЂСЏР¶РµРЅРёСЏ)' and dedicated in-app [РџРѕРґРєР»СЋС‡РёС‚СЊ], [РЎРѕРїСЂСЏС‡СЊ], [РћС‚РІСЏР·Р°С‚СЊ] buttons.
- Magisk module versionCode: 60
- SHA-256: `709e258acd0a236ce05f36cf67095b8c50fdf458b14e4e0e9d2ea8062f7cac18`
- Module ZIP: https://raw.githubusercontent.com/AlteroAscension/x50-gateway-releases/main/gateway/releases/gateway-v2.29.5-trajectory-relay/x50-gateway-magisk.zip

See the repository CHANGELOG.md and release notes for functional changes.