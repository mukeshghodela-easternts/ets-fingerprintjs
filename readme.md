<!-- <p align="center">
  <a href="https://fingerprint.com">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="" />
      <source media="(prefers-color-scheme: light)" srcset="" />
      <img src="" alt="FingerprintJS logo" width="312px" />
    </picture>
  </a>
</p> -->
<p align="center">
  <a href="https://www.npmjs.com/package/@fingerprintjs/fingerprintjs">
    <img src="https://img.shields.io/npm/v/@fingerprintjs/fingerprintjs.svg" alt="Current NPM version">
  </a>
  <a href="https://www.npmjs.com/package/@fingerprintjs/fingerprintjs">
    <img src="https://img.shields.io/npm/dm/@fingerprintjs/fingerprintjs.svg" alt="Monthly downloads from NPM">
  </a>
  <a href="https://www.jsdelivr.com/package/npm/@fingerprintjs/fingerprintjs">
    <img src="https://img.shields.io/jsdelivr/npm/hm/@fingerprintjs/fingerprintjs.svg" alt="Monthly downloads from jsDelivr">
  </a>
</p>
<!-- <p align="center">
  <a href="https://discord.gg/39EpE2neBg">
    <img src="https://img.shields.io/discord/852099967190433792?style=for-the-badge&label=Discord&logo=Discord&logoColor=white" alt="Discord server">
  </a>
</p> -->

This is a JavaScript-only way to fingerprint a user with better than 90% accuracy in as few bytes as possible and no cookie storage, utilizing the ETS FingerprintJS library. The library generates a unique identifier for a user's browser by considering various browser and system properties, including user agent, language, screen resolution, plugins, etc., and employs the MurmurHash3 algorithm for generating the identifier.
## Quick start

```html
<script>
  // Initialize the agent at application startup.
  import { uid } from 'ets-fingerprintjs'
  console.log(uid)
</script>
```