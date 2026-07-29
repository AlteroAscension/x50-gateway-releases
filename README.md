# X50 Gateway releases

This public repository contains only installable X50 Gateway Magisk archives
and their update metadata. Source code, private engineering notes and signing
keys are not published here.

Stable endpoints:

- `gateway/update.json` — standard Magisk update feed;
- `gateway/manifest.json` — RSA-signed Gateway maintenance envelope;
- `gateway/changelog.md` — current release information;
- `gateway/releases/<tag>/x50-gateway-magisk.zip` — immutable versioned module.

Magisk reads `update.json` from the installed module's `updateJson` property.
The Gateway application independently verifies the signed manifest and ZIP
SHA-256 before staging an update.

Do not install an archive from an untrusted mirror. A module update becomes
active only after reboot.
