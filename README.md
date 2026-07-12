# OrdeON release helpers

This repository hosts downloadable Android artifacts and machine-readable release
information for OrdeON apps.

## OrdeON Merchant

- Metadata: [`ordeon-merchant.json`](./ordeon-merchant.json)
- Expo project: `@wcatly/ordeon-merchant`
- EAS Update channel: `production`
- Android artifact naming: `ordeon-merchant-v<version>.apk`
- GitHub release tag: `ordeon-merchant-v<version>`

OrdeON Merchant uses Expo Updates for automatic compatible JavaScript and asset
updates on Android and iOS. A new signed binary is still required when native code,
permissions, the Expo SDK, or the runtime version changes.

The existing `version.json` and `app-release.apk` belong to OrdeON Companion and
must not be replaced by Merchant releases.
