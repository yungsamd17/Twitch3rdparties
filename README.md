# Twitch Client Encyclopedia

A non-exhaustive collection of third-party clients, mods and tools for Twitch.

Modeled after [Discord3rdparties](https://github.com/Discord-Client-Encyclopedia-Management/Discord3rdparties).

## Table of Contents

- [Twitch Client Encyclopedia](#twitch-client-encyclopedia)
  * [Table of Contents](#table-of-contents)
  * [Status legend](#status-legend)
  * [Mobile](#mobile)
    + [Android Clients & Mods](#android-clients--mods)
    + [Morphe patch sources (Android)](#morphe-patch-sources-android)
    + [iOS Clients & Mods](#ios-clients--mods)
  * [Desktop](#desktop)
    + [Official Clients](#official-clients)
    + [Third-Party Clients](#third-party-clients)
  * [TV clients](#tv-clients)
  * [Web front-ends](#web-front-ends)
  * [Browser extensions & ad blockers](#browser-extensions--ad-blockers)
  * [Other tools](#other-tools)
  * [Contributing](#contributing)
  * [Further comments](#further-comments)
  * [Disclaimer](#disclaimer)

## Status legend

| Symbol | Meaning |
| ------ | ------- |
| 🟢 | Active |
| 🔵 | Active, but in beta / early / still in development |
| 🟠 | Slow, on hiatus, or activity not confirmed |
| 🔴 | Discontinued, archived, abandoned or outdated |
| ⛔ | Warning (malware risk, ToS risk, privacy concern) |

Language badges used in the tables are listed in [badges.md](badges.md).

## Mobile

### Android Clients & Mods

| Name | Features | Language(s) | Development Status |
| ---- | -------- | ----------- | ------------------ |
| [Twitch Android](https://play.google.com/store/apps/details?id=tv.twitch.android.app) | Official Android client | [Closed source] | 🟢 Active |
| [Xtra](https://github.com/crackededed/Xtra) | Twitch player and browser. VODs and clips with chat replay, offline VOD downloads, Picture in Picture, sleep timer, BTTV/FFZ emotes, themes. Also on [F-Droid](https://f-droid.org/packages/com.github.andreyasadchy.xtra/). | ![Kotlin](https://img.shields.io/badge/-Kotlin-7F52FF?style=flat&logo=kotlin&logoColor=white) | 🟢 Active ⛔ Uses the TTV.lol API, which exposes your Twitch user ID and IP to a third-party proxy |
| [Frosty](https://github.com/tommyxchow/frosty) | Cross-platform client with 7TV, BTTV and FFZ emotes and badges, emote menu and autocomplete, chatters list, themes (incl. OLED), sleep timer, PiP. Also on iOS. | ![Dart](https://img.shields.io/badge/-Dart-0175C2?style=flat&logo=dart&logoColor=white) ![Flutter](https://img.shields.io/badge/-Flutter-02569B?style=flat&logo=flutter&logoColor=white) | 🟢 Active |
| [DankChat](https://github.com/flxrs/DankChat) | Chat-focused client: multi-channel chat (even for offline streamers) with FFZ, BTTV and 7TV emotes. Also on [F-Droid](https://f-droid.org/packages/com.flxrs.dankchat). | ![Kotlin](https://img.shields.io/badge/-Kotlin-7F52FF?style=flat&logo=kotlin&logoColor=white) | 🟢 Active |
| [Twire](https://github.com/twireapp/Twire) | Open-source, ad-free Twitch browser and stream player. VODs with chat replay, BTTV/FFZ/7TV emotes, Picture in Picture, themes. Fork of Pocket Plays. Also on [F-Droid](https://f-droid.org/packages/com.perflyst.twire/). | ![Java](https://img.shields.io/badge/-Java-ED8B00?style=flat&logo=openjdk&logoColor=white) | 🟠 Slow (latest release 2.12.3, Aug 2025; no newer release found) |
| [Chatsen](https://github.com/chatsen/chatsen) | Cross-platform chat client with 7TV, BTTV and FFZ support, built-in video player, auto-completion, notifications, whispers. | ![Dart](https://img.shields.io/badge/-Dart-0175C2?style=flat&logo=dart&logoColor=white) ![Flutter](https://img.shields.io/badge/-Flutter-02569B?style=flat&logo=flutter&logoColor=white) | 🟢 Active |
| [bttv-android](https://github.com/bttv-android/bttv) | Mod of the official Twitch Android app adding BTTV, FFZ and 7TV emotes. Built by patching Twitch **19.0.1** only. No Android TV support, no 7TV zero-width emotes. | ![Java](https://img.shields.io/badge/-Java-ED8B00?style=flat&logo=openjdk&logoColor=white) | 🔴 Pinned to an old Twitch version |
| [Pocket Plays for Twitch](https://github.com/SebastianRask/Pocket-Plays-for-Twitch) | Original open-source, ad-free Twitch player; base of Twire | ![Java](https://img.shields.io/badge/-Java-ED8B00?style=flat&logo=openjdk&logoColor=white) | 🔴 Discontinued |
| [Amaterasu](https://github.com/abstraq/amaterasu) | Open-source client for viewing Twitch streams on iOS and Android | ![Dart](https://img.shields.io/badge/-Dart-0175C2?style=flat&logo=dart&logoColor=white) ![Flutter](https://img.shields.io/badge/-Flutter-02569B?style=flat&logo=flutter&logoColor=white) | 🔴 Unfinished / abandoned |
| [ReVanced Twitch patches](https://revanced.app/) | ReVanced patches for the official Twitch app (e.g. block embedded ads). Older patch versions were pinned to Twitch 14.x. | ![Kotlin](https://img.shields.io/badge/-Kotlin-7F52FF?style=flat&logo=kotlin&logoColor=white) | 🔴 Outdated, use Morphe sources below |
| "Twitch Mod APK" sites | Random pre-modded APKs promising no ads | [Closed source] | ⛔ Unverified, usually outdated, malware and ban risk |

### Morphe patch sources (Android)

[Morphe](https://github.com/MorpheApp/morphe-patches) is a ReVanced successor. Its own patch bundle covers YouTube and YouTube Music, and Twitch patches come from community-maintained sources. You patch the official Twitch APK yourself using Morphe Manager. Patches are pinned to specific Twitch versions.

| Name | Features | Supported Twitch | Development Status |
| ---- | -------- | ---------------- | ------------------ |
| [ryykitty/twitch-patched](https://github.com/ryykitty/twitch-patched) | Block stream ads, hide feed/display ads, BTTV and 7TV emotes, in-app patch settings | 31.4.2 (extended testing ongoing) | 🔵 Early |
| [arandomhooman/hoomans-morphe-patches](https://github.com/arandomhooman/hoomans-morphe-patches) | 7 Twitch patches: 7TV and BTTV emotes, hide display ads, block live ads, fix notifications after patching. Live-ad blocking depends on a third-party proxy; VOD ads are not covered. | 30.7.2 | 🟢 Active ⛔ Ad blocking routes streams through a third-party proxy; users report ads still appearing |
| [K8R8TO/kizu-morphe-patches](https://github.com/K8R8TO/kizu-morphe-patches) | Twitch-only patches (third-party emotes, emote picker, privacy controls, ad handling). Being rebuilt step by step. | n/a | 🔵 Work in progress |

### iOS Clients & Mods

| Name | Features | Language(s) | Development Status |
| ---- | -------- | ----------- | ------------------ |
| [Twitch iOS](https://apps.apple.com/us/app/twitch-live-streaming/id460177396) | Official iOS client | [Closed source] | 🟢 Active |
| [Frosty](https://apps.apple.com/us/app/frosty-for-twitch/id1603987585) ([source](https://github.com/tommyxchow/frosty)) | Cross-platform client with 7TV, BTTV and FFZ support (see Android table) | ![Dart](https://img.shields.io/badge/-Dart-0175C2?style=flat&logo=dart&logoColor=white) ![Flutter](https://img.shields.io/badge/-Flutter-02569B?style=flat&logo=flutter&logoColor=white) | 🟢 Active |
| [Kulve](https://apps.apple.com/us/app/kulve/id6476389316) | Native Twitch client for iPhone/iPad (iOS 18.5+) and Mac. Full third-party emote support, replies and threads, fullscreen chat. Free with optional Kulve Pro subscription. No custom ad blocking, supports Twitch Turbo. | [Closed source] | 🟢 Active |
| [Chatsen](https://apps.apple.com/app/id1574037007) ([source](https://github.com/chatsen/chatsen)) | Chat client with 7TV, BTTV and FFZ support (see Android table) | ![Dart](https://img.shields.io/badge/-Dart-0175C2?style=flat&logo=dart&logoColor=white) ![Flutter](https://img.shields.io/badge/-Flutter-02569B?style=flat&logo=flutter&logoColor=white) | 🟢 Active |
| [frosty-swiftui](https://github.com/tommyxchow/frosty-swiftui) | Experimental native iOS Twitch client by the Frosty author | ![Swift](https://img.shields.io/badge/-Swift-F05138?style=flat&logo=swift&logoColor=white) | 🔴 Dormant (last update Sep 2021) |
| [Amaterasu](https://github.com/abstraq/amaterasu) | Open-source client for viewing Twitch streams on iOS and Android | ![Dart](https://img.shields.io/badge/-Dart-0175C2?style=flat&logo=dart&logoColor=white) ![Flutter](https://img.shields.io/badge/-Flutter-02569B?style=flat&logo=flutter&logoColor=white) | 🔴 Unfinished / abandoned |

> Maintained tweaks or patched builds of the official Twitch iOS app are rare. If you know of one, please open a PR.

## Desktop

### Official Clients

| Name | Link | Infos |
| ---- | ---- | ----- |
| [Twitch](https://www.twitch.tv) | [Web](https://www.twitch.tv), [Windows / macOS](https://www.twitch.tv/downloads) | Main website and desktop app |

### Third-Party Clients

| Name | Features | Language(s) | Development Status |
| ---- | -------- | ----------- | ------------------ |
| [Chatterino](https://github.com/Chatterino/chatterino2) | The standard desktop chat client: native, fast, multi-channel, BTTV/FFZ emotes. Windows, macOS, Linux ([Flatpak](https://flathub.org/apps/com.chatterino.chatterino)). | ![C++](https://img.shields.io/badge/-C%2B%2B-00599C?style=flat&logo=cplusplus&logoColor=white) ![Qt](https://img.shields.io/badge/-Qt-41CD52?style=flat&logo=qt&logoColor=white) | 🟢 Active |
| [Chatterino 7](https://github.com/SevenTV/chatterino7) | Fork of Chatterino with 7TV support | ![C++](https://img.shields.io/badge/-C%2B%2B-00599C?style=flat&logo=cplusplus&logoColor=white) ![Qt](https://img.shields.io/badge/-Qt-41CD52?style=flat&logo=qt&logoColor=white) | 🟢 Active |
| [Chatty](https://github.com/chatty/chatty) ([site](https://chatty.github.io/)) | Chat client with Twitch-specific features and moderation tools. Needs Java. | ![Java](https://img.shields.io/badge/-Java-ED8B00?style=flat&logo=openjdk&logoColor=white) | 🟢 Active |
| [Streamlink Twitch GUI](https://github.com/streamlink/streamlink-twitch-gui) ([site](https://streamlink.github.io/streamlink-twitch-gui/)) | Browse Twitch and watch multiple streams in your own player via Streamlink. Desktop notifications, language filters, customizable chat apps. Windows, macOS, Linux. | ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) ![Ember.js](https://img.shields.io/badge/-Ember.js-E04E39?style=flat&logo=emberdotjs&logoColor=white) | 🟢 Maintained |
| [Kulve](https://apps.apple.com/us/app/kulve/id6476389316) | Native macOS Twitch client (macOS 14+, Apple Silicon) with third-party emotes | [Closed source] | 🟢 Active |

## TV clients

| Name | Features | Language(s) | Development Status |
| ---- | -------- | ----------- | ------------------ |
| [SmartTwitchTV](https://github.com/fgl27/SmartTwitchTV) | Web application giving access to Twitch on smart TVs and Android TV devices without a good official app. Available on Google Play for TVs; APKs on GitHub for phones/tablets. | ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) | 🟢 Active |
| [Morphe Android TV patches](https://github.com/ajstrick81/morphe-androidtv-patches) | Morphe patches for the Android TV Twitch app, including ad suppression. Pinned to specific TV builds. Server-side stitched ads can still appear. | ![Kotlin](https://img.shields.io/badge/-Kotlin-7F52FF?style=flat&logo=kotlin&logoColor=white) | 🟢 Active ⛔ Version-pinned, manual sideloading |

## Web front-ends

| Name | Features | Language(s) | Development Status |
| ---- | -------- | ----------- | ------------------ |
| [Twineo](https://codeberg.org/CloudyyUw/twineo) | Privacy-focused alternative front-end to Twitch, inspired by Invidious and Nitter. Lightweight, minimal JavaScript, AGPL. Public instances exist. | ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![Deno](https://img.shields.io/badge/-Deno-000000?style=flat&logo=deno&logoColor=white) | 🔴 Archived (Aug 2026; last commit Apr 2024) |
| [SafeTwitch](https://codeberg.org/SafeTwitch/safetwitch) | Privacy-respecting Twitch front-end with a Go backend | ![Vue.js](https://img.shields.io/badge/-Vue.js-4FC08D?style=flat&logo=vuedotjs&logoColor=white) ![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat&logo=go&logoColor=white) | 🔴 Frontend repo archived |

## Browser extensions & ad blockers

| Name | Features | Development Status |
| ---- | -------- | ------------------ |
| [BetterTTV](https://betterttv.com) | Third-party emotes and chat/UI improvements | 🟢 Active |
| [FrankerFaceZ](https://www.frankerfacez.com) | Third-party emotes, badges and heavy chat customization | 🟢 Active |
| [7TV](https://7tv.app) | Third-party emotes, paints and cosmetics | 🟢 Active |
| [TTV LOL PRO](https://github.com/younesaassila/ttv-lol-pro) | Removes most livestream ads by using proxies. Available for [Chrome](https://chrome.google.com/webstore/detail/ttv-lol-pro/bpaoeijjlplfjbagceilcgbkcdjbomjd) and [Firefox](https://addons.mozilla.org/addon/ttv-lol-pro/). Does not remove banner or VOD ads. | 🟢 Maintained ⛔ Routes requests through third-party proxies; has mixed user reviews |
| [TwitchAdSolutions (ryanbr fork)](https://github.com/ryanbr/TwitchAdSolutions) | Maintained fork of the original TwitchAdSolutions. Ad-blocking scripts (vaft, video-swap-new) for uBlock Origin or userscript managers, with runtime `localStorage` options and a guide to other solutions. Userscript versions are recommended over uBlock Origin. The [original repo](https://github.com/pixeltris/TwitchAdSolutions) by pixeltris was archived on Mar 5, 2026. | 🟢 Active |

## Other tools

| Name | Features | Development Status |
| ---- | -------- | ------------------ |
| [Streamlink](https://github.com/streamlink/streamlink) | Command-line tool that pipes Twitch (and other) streams into your own player (VLC, mpv). Backbone of several clients above. | 🟢 Active |
| [Twitch Drops Miner](https://github.com/DevilXD/TwitchDropsMiner) | Automates farming Twitch drops | 🟢 Active (stable releases are outdated, use the dev build) ⛔ May violate Twitch ToS |

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) to add or update entries, statuses, and warnings.

## Further comments

- This list is **non-exhaustive** and statuses change quickly. Check the project's repo for the latest activity.
- Twitch deprecated parts of its API in the past (for example v5 in 2022), which broke many older clients. Apps not updated since then are most likely dead.
- Ad-blocking mods and proxies depend on workarounds that Twitch can break at any time. Twitch's live ads are often stitched server-side into the stream, which limits what client-side patches can do.
- Patched official-app mods (Morphe, ReVanced, bttv-android) are tied to specific Twitch app versions. Always use the exact version the patch lists.

## Disclaimer

This is an unofficial community list. It is not affiliated with, endorsed by, or sponsored by Twitch or Amazon. Using third-party clients, mods or ad blockers may violate Twitch's Terms of Service and could put your account at risk. Download software only from official sources, review what permissions and network services an app uses, and use everything at your own risk.
