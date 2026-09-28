# Third-Party Notices

SSClash binaries may bundle or interoperate with the following third-party
software. This file applies to the distribution repository
[zerolabnet/SSClash-Go](https://github.com/zerolabnet/SSClash-Go).

## Bundled in the SSClash binary (compile-time)

| Component | License | Notes |
|-----------|---------|-------|
| [gorilla/websocket](https://github.com/gorilla/websocket) | BSD-2-Clause | WebSocket client for the Mihomo API |
| [Twemoji](https://github.com/twitter/twemoji) (Mozilla flags subset, `TwemojiMozilla-flags.woff2`) | CC-BY-4.0 | Embedded web UI static asset; regional-indicator flag glyphs in proxy names |

Twemoji graphics © Twitter, Inc and other contributors, used under
[Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/).
The font file is a flags-only subset (not the full Twemoji set).

## Installed at runtime (not part of the SSClash license)

| Component | License | Notes |
|-----------|---------|-------|
| [Mihomo (Clash.Meta)](https://github.com/MetaCubeX/mihomo) | GPL-3.0 (typical) | Downloaded separately by installers or the web UI into `/opt/clash/bin/clash`. Governed by the Mihomo project license. |

SSClash itself is distributed under the proprietary [LICENSE](LICENSE) in this
repository. Using Mihomo requires compliance with Mihomo's license terms.
