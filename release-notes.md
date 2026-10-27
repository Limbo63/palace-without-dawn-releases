# Palace Without Dawn 0.9.0 / build 5 — diagnostic prerelease

An original single-player action roguelite in a changing Japanese magical castle. This candidate includes a pool of five ordinary layouts (three selected per run), varied encounters, and two Hollow Bell warning/attack/recovery patterns: Falling Bell and Resonant Sweep.

The explicitly labelled **Training / Preview** menu temporarily selects Kae or the adult water heroine Sayo, with her directed water wave. Training grants no XP/coins, records no heroine unlock and makes no main-profile writes. Entering ends the current run without reward; exit starts a fresh ordinary Kae run. Ordinary Kae progression and saves remain separate. No payment SDK, account system or server is connected.

## Verification and limits

- Fresh Unity IL2CPP export passed with 0 errors and 0 warnings. Fresh Xcode arm64 iOS device Release build succeeded. No old gameplay native or Data was reused.
- Editor training/lifecycle/input-isolation and save checks passed. The final export preflight passed 54 checks, including an independent synthetic 0.4-format save; packaging fixtures passed 11 tests. These are not physical touchscreen or real user-save migration results.
- Final IPA metadata, stable bundle identity, device binaries, content checks, ZIP CRC, size and SHA-256 passed.
- **120 Xcode warning lines remain**, with the same seven causes/counts as 0.4. Unity IL2CPP compilation target is 11.0 while final binaries declare minOS 15.0. This libc++ warning is understood, not declared universally harmless. Static audit found no new imports or missing bundled dependencies/exports. Declared iOS 15.0 is not a device compatibility guarantee.
- **Actual touch/multitouch, physical iPhone/AltStore installation, native icon appearance, device performance and runtime ABI/system-symbol availability remain unverified.** The existing Editor automation/input limitation is not a device PASS. This unsigned/re-signable diagnostic candidate is not production or App Store readiness.

Bundle ID, stable source URL and save identity remain unchanged. Previous versions and downloads remain available.

Artifact: `PalaceWithoutDawn-0.9.0-b5.ipa` — **28,687,007 bytes**.
SHA-256: `c441d6d028fada5e42f103c7ba841043a31a6bc2bb798aedcca9feac9252b967`.

## Actual Editor feature captures

These contain only game pixels, not device screenshots or concept art. The room was recorded at the room checkpoint, the boss at a controlled pattern fixture, and preview/water at the training checkpoint. All shown features are included in this candidate; warning/water fixtures are not ordinary-run balance evidence.

![Included room encounter, actual Editor capture](https://raw.githubusercontent.com/Limbo63/palace-without-dawn-releases/v0.9.0-diagnostic.5/assets/room-folded-scroll-0.9.0.png)
![Hollow Bell warning, controlled Editor fixture](https://raw.githubusercontent.com/Limbo63/palace-without-dawn-releases/v0.9.0-diagnostic.5/assets/boss-warning-0.9.0.png)
![Training / Preview, actual Editor capture](https://raw.githubusercontent.com/Limbo63/palace-without-dawn-releases/v0.9.0-diagnostic.5/assets/training-panel-0.9.0.png)
![Sayo wave, controlled Editor training fixture](https://raw.githubusercontent.com/Limbo63/palace-without-dawn-releases/v0.9.0-diagnostic.5/assets/sayo-wave-0.9.0.png)
