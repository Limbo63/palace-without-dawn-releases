# Palace Without Dawn 0.4.0 / build 4 — diagnostic prototype

- Original prototype heroine, demons and Japanese rooms, with simple animation and hit feedback.
- English gameplay HUD, a four-room run with upgrade choices and the Hollow Bell boss.
- Kae experience/levels, earned coins and permanent katana upgrades, separate from temporary run upgrades.
- Versioned local saves, exactly-once reward receipts, schema migration and corruption recovery.

This is a fresh Unity IL2CPP export and Xcode device build of the art/progression source. It does not reuse the 0.2 gameplay binary or Data.

## Verified

- Editor: 112 storage, 41 progression service, 51 real Play Mode progression, 153 visual/layout and 66 combat checks passed.
- Actual save → Stop/Play → load, duplicate-reward protection and damaged/empty-file recovery were checked using isolated test profiles.
- Fresh Unity 6000.5.10f1 iOS export: PASS, 0 errors, 0 warnings. Fresh Xcode Release arm64 device build: BUILD SUCCEEDED.
- Final IPA: identity/version, English raw names, AltSign registration-name filter, arm64 device Mach-O, forbidden-content audit, ZIP CRC, size and SHA-256 passed.

## Unverified

Physical iPhone/AltStore installation, actual touch/pointer controls, hardware multitouch, native icon appearance and device performance remain unverified. Editor automation does not establish a touch PASS. The IPA is unsigned and requires AltStore re-signing.

The screenshots are real Editor captures of this source with an isolated test profile. They are not iPhone installation evidence. Art and balance remain prototypes. No payment SDK, account system or game server is connected.

Bundle ID: `com.limbo63.palacewithoutdawn`. The existing AltStore source URL and save identity are unchanged. Previous published versions remain available.

IPA: `PalaceWithoutDawn-0.4.0-b4.ipa`  
Size: 27177794 bytes  
SHA-256: `3477d59c5b407b94c6519b80637ac75363a8432e0bfffd591689aee706967a7b`  
Private source checkpoint: `2c148e37acb731f3d40e5115d3c83aba053e05e0`.
