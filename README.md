# Onkey

A floating desktop companion for macOS, with no legs and all 73 corrected animation frames.

## Download

Get **Onkey-1.2.1.dmg** from the [latest release](https://github.com/HighTierRoach/onkey/releases/latest), drag Onkey into Applications, and open it.

Requires an Apple silicon Mac running macOS 12 or later.

## Controls

- Drag Onkey to move it.
- Right-click for animation and update controls.
- Choose Onkey → Check for Updates to install the newest version.
- Press Command-Q to quit.

Movement sequences pause for a random 8–18 seconds. Onkey includes idle, movement in both directions, waving, jumping, falling, waiting, reviewing, and 16 look directions.

## Automatic updates

Version 1.2.1 connects to this repository's releases by default. It checks daily for signed updates, downloads them in the background, and installs them when Onkey quits. Update feeds and archives are verified against Onkey's embedded public key.

If you already have version 1.2, choose **Onkey → Update Source**, enter `https://github.com/HighTierRoach/onkey`, and then choose **Check for Updates**.

The app works offline. Update checking contacts GitHub; system profiling is disabled.

## Release signing

This release is ad hoc code signed and is not Apple notarized. Update archives and feeds use a separate Ed25519 signature. Sparkle's license notice is included in the app and release assets.
