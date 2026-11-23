# Collabora Online

> [!IMPORTANT]
> **About this repository.** Active development of Collabora Online has moved to our
> Gerrit instance at **https://gerrit.collaboraoffice.com**, which is where the source code
> and code review live. This GitHub repository is kept for:
>
> - **Issue tracking** — please [report bugs and request features here](https://github.com/CollaboraOnline/online/issues/new/choose).
> - **Release artifacts** — the nightly container image, the Helm chart, and build assets are published from here.
>
> **Source code changes go to Gerrit, not GitHub.** Follow
> [CONTRIBUTING.md](CONTRIBUTING.md#contributing-to-source-code) and push to Gerrit instead.
> Pull requests here are welcome only for the parts this repository owns — the
> [Helm chart](kubernetes/helm/) and the [docker image build](docker/from-source-gh-action/).

[![Development: Gerrit](https://img.shields.io/badge/Development-Gerrit-orange?logo=git "Code development and review of the application source happen on Gerrit.")](https://gerrit.collaboraoffice.com)
[![Collabora Office Development Preview](https://img.shields.io/badge/Collabora%20Office-Development%20Preview-blue "Test the latest development snaphots of Collabora Office.")](https://www.collaboraoffice.com/downloads/CODA-Hd7wwbJWxm/)


[![Matrix](https://img.shields.io/badge/Matrix-%23cool--dev-turquoise.svg)](https://matrix.to/#/#cool-dev:matrix.org)
[![Telegram](https://img.shields.io/badge/Telegram-Collabora%20Online-green.svg)](https://t.me/CollaboraOnline)
[![Forum](https://img.shields.io/badge/Forum-Discourse-blue.svg)](https://forum.collaboraonline.com/)
[![Website](https://img.shields.io/badge/Website-collaboraonline.github.io-blueviolet.svg)](https://collaboraonline.github.io/)
[![L10n](https://img.shields.io/badge/L10n-Weblate-lightgrey.svg)](https://hosted.weblate.org/projects/collabora-online/)

---

A read-only mirror of the source code is available at
[CollaboraOnline/online.mirror](https://github.com/CollaboraOnline/online.mirror) — see its
[README.md](https://github.com/CollaboraOnline/online.mirror/blob/main/README.md) for build
instructions and project documentation.

## Supported browsers

Collabora Online supports a wide range of modern web browsers on both desktop and mobile platforms.

### Desktop browsers

| Browser | Minimum version | Notes |
|---------|-----------------|-------|
| Google Chrome / Chromium | 90+ | Full support for all features. Recommended for best performance. |
| Mozilla Firefox | 88+ | Full support for all features. Generally well-supported. |
| Apple Safari | 14.0+ | Good support for most features. Some minor UI quirks may occur. |
| Microsoft Edge | 90+ | Full support (Chromium-based). Actively tested. |
| Opera | 76+ | Supported through Chromium base. Full feature support expected. |

### Mobile browsers

| Browser | Minimum version | Notes |
|---------|-----------------|-------|
| Chrome Mobile (Android) | Android 10+ | Good support. Touch interface works well. |
| Safari Mobile (iOS) | iOS 14+ | Limited interface optimizations. Desktop view recommended. |
| Firefox Mobile (Android) | Android 10+ | Good support similar to desktop version. |
| Edge Mobile (iOS/Android) | iOS 14+ / Android 10+ | Supported through Chromium base. |

### Browser requirements

- **JavaScript**: Must be enabled
- **WebSocket support**: Required
- **WebGL**: Optional (for enhanced rendering)
- **Display resolution**: 1024×768 minimum recommended
- **Hardware**: 2 GB RAM and 2 GHz+ processor recommended
- **Network**: 2 Mbps minimum recommended, HTTPS recommended

### Not supported

- Internet Explorer (all versions)
- Browsers older than 2018
- Very old Safari versions (< 12)
