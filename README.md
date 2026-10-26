# Palace Without Dawn — 0.2.1 / build 3

This is an **app-name installation fix**, not a new gameplay or native build. Root Info.plist now uses the English app name and the new version/build. All native code, metadata, Data, icons and other archive member bytes/modes remain identical to the frozen 0.2.0 baseline.

**The in-game HUD still shows “ДВОРЕЦ БЕЗ РАССВЕТА”. The complete UI rename remains pending.** Other Russian gameplay text remains Russian. Newer source Editor checks are separate from validation of the reused native build and are not presented here as shipped 0.2.1 runtime proof.

The unchanged gameplay is a short four-room run with three upgrade choices, directional katana combat, dash, lightning and an original boss. Graphics are temporary prototype forms. There are no real payments, and automatic run/metaprogression saving is not enabled.

## Verification scope

- Current package: only root Info.plist differs; 58 other members / 42547933 uncompressed bytes and their modes were compared with frozen 0.2.0. Final ZIP CRC, raw names, identity, version/build, size and SHA-256 were checked. This delivery reuses the verified 0.2 native code and Data. It contains no fresh native compilation; it is a plist-only installation-name correction.
- Historical **0.2.0 native baseline only**: 66 Unity Play Mode checks, four-room victory and three choices, actual Stop/Play, 26 storage checks without touching player data, zero-error iOS export and Xcode device BUILD SUCCEEDED. These results are not a new 0.2.1 runtime or installation PASS.
- The two 900×1600 screenshots are real captures from that same successful 0.2 baseline. They do not depict a newly renamed native HUD.
- Physical iPhone installation through AltStore, hardware multitouch, native icon appearance and device performance remain untested. The installed AltStore binary was not inspected. No Apple AppID/account/certificate was manually created.

The previous raw Russian app name becomes two spaces under the pinned AltSign registration-name filter. The new raw app name **Palace Without Dawn** passes the package name checks. This metadata correction does not by itself prove successful installation. The unsigned/re-signable IPA requires AltStore re-signing.

## Identity and integrity

- Bundle identifier remains `com.limbo63.palacewithoutdawn`.
- [AltStore source URL remains unchanged](https://raw.githubusercontent.com/Limbo63/palace-without-dawn-releases/main/altstore-source.json).
- Artifact: `PalaceWithoutDawn-0.2.1-b3.ipa`, 13627181 bytes, SHA-256 `a4284d25718064a00800c54e5a6bf37feacf09d4777035d799c96fa426289ea1`.
- Package-tool/documentation source checkpoint: `269905edb81c7b4ec3289105c57f8c769d534e56`.
- Reused native source checkpoint: `3602d78fae05dba5872ac6d08ff9594a087bb55a`.
- Frozen baseline IPA SHA-256: `0e55b3f2de22385088723bce45b64978d575b2a7dd8e7583d0611f27bf240f3c`.
- Release tag: `v0.2.1-prototype.3`. Historical published 0.1 metadata is preserved unchanged; the unpublished 0.2 entry is not added to the feed.

Public delivery contains no source code, personal saves, credentials, provisioning, internal logs or machine paths. Other applications are unaffected.
