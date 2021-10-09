# AsyncWebServer_WT32_ETH01

[![arduino-library-badge](https://www.ardu-badge.com/badge/AsyncWebServer_WT32_ETH01.svg?)](https://www.ardu-badge.com/AsyncWebServer_WT32_ETH01)
[![GitHub release](https://img.shields.io/github/release/khoih-prog/AsyncWebServer_WT32_ETH01.svg)](https://github.com/khoih-prog/AsyncWebServer_WT32_ETH01/releases)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](#Contributing)
[![GitHub issues](https://img.shields.io/github/issues/khoih-prog/AsyncWebServer_WT32_ETH01.svg)](http://github.com/khoih-prog/AsyncWebServer_WT32_ETH01/issues)

---
---

## Table of contents

* [Changelog](#changelog)
  * [Releases v1.2.5](#releases-v125)
  * [Releases v1.2.4](#releases-v124)
  * [Releases v1.2.3](#releases-v123)


---
---

## Changelog

### Releases v1.2.5

1. Update `platform.ini` and `library.json` to use original `khoih-prog` instead of `khoih.prog` after PIO fix


#### Releases v1.2.4

1. Fix library compile error with ESP32 core v2.0.0-rc1+. Check [Fix compiler error for ESP32-C3 and mbed TLS v2.7.0+ #970](https://github.com/me-no-dev/ESPAsyncWebServer/pull/970)
2. Verify compatibility with new ESP32 core v2.0.0-rc1+


#### Releases v1.2.3

1. Initial coding to port [ESPAsyncWebServer](https://github.com/me-no-dev/ESPAsyncWebServer) to WT32_ETH01 boards using builtin LAN8720A Ethernet.
2. Add more examples.
3. Add debugging features.
4. Bump up to v1.2.3 to sync with [ESPAsyncWebServer v1.2.3](https://github.com/me-no-dev/ESPAsyncWebServer).

