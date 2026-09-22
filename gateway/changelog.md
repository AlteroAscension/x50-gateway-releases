# X50 Gateway 2.29.1-elm-pin-pairing

- Configurable pairing PIN selector (presets `1234`, `0000`, and custom PIN input) in Gateway ELM327 settings.
- Direct in-app pairing (`[Сопрячь]`) and unpairing (`[Отвязать]`) for scanned Bluetooth adapters.
- High-priority `ACTION_PAIRING_REQUEST` interception suppressing the stock head unit dialog and auto-injecting the configured PIN.
- Corrected legacy PIN authentication flow without extraneous confirmation callbacks for PIN variants.
- Real-time CAN ID 0x0E0 steering wheel angle intake, fresh telemetry publishing, and live dashboard indicator.
- Magisk module versionCode: 56
- SHA-256: `5ead0554b9d56884bbd9dabc2fde2b0bcf4dc3a9ff0c6387005453fd0d7ca7ba`
- Module ZIP: https://raw.githubusercontent.com/AlteroAscension/x50-gateway-releases/main/gateway/releases/gateway-v2.29.1-elm-pin-pairing/x50-gateway-magisk.zip

See the repository CHANGELOG.md and release notes for functional changes.