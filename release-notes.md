# Palace Without Dawn0.9.1 /build 6 — diagnostic patch

This patch includes the checked HUD/input observer in fresh Unity native/Data. Hero identity and HP have separate rows above the health bar. Narrow/long safe-area layouts avoid footer overlaps; portrait katana and skill touch rectangles have a clear gap. Large profile values fit without truncation.

In active **Training**, open its menu, enable **INPUT OVERLAY**, then resume. The overlay defaults OFF, does not receive raycasts or issue combat actions, and observes pointer/control/orientation/safe-area/focus/pause state using bounded local memory only. No analytics, network, device identifiers or logfile are added. Training still offers temporary Kae/Sayo preview with no XP, coins, purchases, unlocks or main-profile writes; exit starts ordinary Kae.

## Verification and limits

Fresh Unity iOS export: PASS, 0 errors/0 warnings. Fresh unsigned Xcode device Release build: PASS. 57 preflight assertions, 11 package fixtures, CRC/metadata/content and three Mach-O member checks passed. Recent 37-case/871 diagnostic and 3-case/46 default-OFF Editor layout checks are reused with identical runtime bytes; no new physical-touch claim is made. Historical schema2 synthetic profile checks passed without rewriting the fixture. Bundle/save identities are unchanged.

**Physical iPhone/AltStore installation, real simultaneous touches, OS lifecycle/cancellation, performance, native icons and runtime ABI remain unverified.** 121 Xcode warnings versus 120 in0.9 still have the same seven categories. One new generated Generics__22.cpp adds the existing libc++ warning (90 vs 89); other counts are unchanged. The IL2CPP target 11 versus final minOS 15 mismatch remains an explicit runtime/toolchain risk. Successful linking and iOS 15 metadata do not prove device compatibility. The candidate is diagnostic, not production/App Store readiness.

## Integrity

- Artifact: PalaceWithoutDawn-0.9.1-b6.ipa
- Size: 28746452bytes
- SHA256: 1b9545a48928d5433f6632d86631adbedbc0bf807eda59460c172552749d8339
- Bundle ID: com.limbo63.palacewithoutdawn

[Download](https://github.com/Limbo63/palace-without-dawn-releases/releases/download/v0.9.1-diagnostic.6/PalaceWithoutDawn-0.9.1-b6.ipa) · [Stable AltStore source](https://raw.githubusercontent.com/Limbo63/palace-without-dawn-releases/main/altstore-source.json)

Previous 0.9, 0.4, 0.2.1 and0.1 releases retain their original bytes/URLs. Existing screenshots are earlier game-only Editor feature captures (some controlled fixtures), not device or 0.9.1 overlay screenshots. Source code remains private; no saves, credentials, provisioning, internal logs or checkout paths are published. No payment SDK or game account/server is connected.
