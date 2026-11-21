# TeaaMC Mods

Distribution of the TeaaMC Battle Royale client mod for Fabric.

## Install

1. Install [Fabric Loader](https://fabricmc.net/use/) and [Fabric API](https://modrinth.com/mod/fabric-api) for your
   Minecraft version.
2. Download `TeaaMC-<your Minecraft version>.jar` from the [latest release](../../releases/latest) and put it in your
   `mods` folder. Keep only one TeaaMC jar there.

Installed copies update themselves: a newer build is downloaded in the background and replaces the jar after you
quit Minecraft, so it runs from the next launch. Every downloaded jar is checked against the SHA-256 in
[`updates.json`](updates.json).

## Files

- `updates.json`: the latest build for each Minecraft version (read by the mod, served through GitHub Pages).
- [Releases](../../releases): every published build as `build-<number>`, with one jar per Minecraft version.
