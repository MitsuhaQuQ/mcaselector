# MCA Selector (MTM fork)

#### An external tool to export or delete selected chunks and regions from a world save of Minecraft Java Edition.

This is a fork of [MCA Selector](https://github.com/Querz/mcaselector) by Querz, maintained for worlds made with
[MTM Worldgen](https://github.com/MitsuhaQuQ/MTM_worldGen). It follows upstream closely and adds:

* Rendering of worlds taller than vanilla. The render height limit comes from the world, so MTM worlds (up to Y=799
  by default) render in full, while other worlds keep the vanilla limit of 319.
* Faster rendering, and rendering of large maps within the available memory instead of running out of it.

Bugs that also happen with the official release belong in the [upstream repository](https://github.com/Querz/mcaselector/issues).

<p align="center">
  <img src="https://raw.githubusercontent.com/wiki/Querz/mcaselector/images/Default/default.png" alt="MCA Selector window showing chunk and region grid">
</p>

---

**MCA Selector modifies and deletes chunks in your Minecraft world. Please make backups of your world before using.**

## Download

Downloads are on the [releases page](https://github.com/MitsuhaQuQ/mcaselector/releases/latest):

* **Windows (64-bit):** `mcaselector-<version>-windows-x64.zip`. Extract it and run `MCA Selector.exe`. It brings its
  own Java runtime, so nothing needs to be installed. The executable is not signed, so Windows may show a SmartScreen
  warning the first time it runs.
* **Universal jar:** `mcaselector-<version>.jar` needs Java 21 or newer with JavaFX.
* **macOS and Linux:** `.dmg`, `.deb` and `.rpm` packages, when the release build produced them.

Builds of this fork are not the official ones. The official releases are at https://github.com/Querz/mcaselector.

---

## Wiki

The upstream wiki applies to this fork as well and can be found [here](https://github.com/Querz/mcaselector/wiki).

## Video Tutorials
For people who prefer watching a video to understand how the MCA Selector works, there some very good tutorials on 
YouTube explaining the basics:

* [How To Reset Chunks In Your Minecraft World!](https://www.youtube.com/watch?v=1xx8fwynlRs) by [Farzy](https://www.youtube.com/channel/UCVtz3s3FUxVxBgPl2OWtIJQ)
* [How To Clear Unwanted Chunks In Minecraft 1.16 | MCASelector Tutorial](https://www.youtube.com/watch?v=ADDTXGRJo20) by [Muriako](https://www.youtube.com/channel/UCpt-MjKkc5X4W7bUFV3Dwrw)
* [Preparing Your World for the Nether Update! - The Minecraft Survival Guide](https://www.youtube.com/watch?v=1fiyVvoD9jQ) starting at [2:52](https://www.youtube.com/watch?v=1fiyVvoD9jQ&t=2m52s) by [Pixlriffs](https://www.youtube.com/channel/UCgGjBqZZtAjxfpGSba7d6ww)
* [How To Reset The End Dimension! - The Minecraft Survival Guide](https://www.youtube.com/watch?v=p-2gFkJl_Lo) starting at [8:45](https://www.youtube.com/watch?v=p-2gFkJl_Lo&t=8m45s) by [Pixlriffs](https://www.youtube.com/channel/UCgGjBqZZtAjxfpGSba7d6ww)

---
## Supported Versions
MCA Selector currently supports the following Minecraft versions:

| Minecraft Version | Data Version |
|-------------------|--------------|
| 1.2.1 - 1.12.2    | None - 1343  |
| 1.13 - 1.13.2     | 1444 - 1631  |
| 1.14 - 1.14.4     | 1901 - 1976  |
| 1.15 - 1.15.2     | 2200 - 2230  |
| 1.16 - 1.16.5     | 2566 - 2586  |
| 1.17 - 1.17.1     | 2724 - 2730  |
| 1.18 - 1.18.2     | 2825 - 2975  |
| 1.19 - 1.19.4     | 3105 - 3337  |
| 1.20 - 1.20.6     | 3463 - 3839  |
| 1.21 - 1.21.11    | 3953 - 4671  |
| 26.1 - 26.3+      | 4764 - 5023+ |

There is no guarantee for worlds generated in a Snapshot version to work, even if it is specified in the table above.
This only represents the current development status towards the next Minecraft release. Old Snapshots of past 
Minecraft releases are not officially supported.
