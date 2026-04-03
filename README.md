# IllegalStack (GZ Fork)

Fork of [IllegalStack](https://github.com/dniym/IllegalStack) with Minecraft 26.1 support.

## Changes from upstream

- Added `v26_1_R1` to `ServerVersion` enum for Minecraft 26.1+ detection
- Fixed version parsing for modern Paper servers (unversioned CraftBukkit packages)
- Updated ProtocolLib dependency to 5.3.0
- Updated Gradle wrapper to 8.12
- Fixed dmulloy2 repository URL

## Original Description

A spigot based plugin dedicated to fixing glitches and exploits that have made it into final Minecraft releases.

## Links
- [Spigot (Original)](https://www.spigotmc.org/resources/dupe-fixes-illegal-stack-remover.44411/)
- [Wiki](https://github.com/dniym/IllegalStack/wiki/FAQ)
- [Discord](https://discord.gg/Gsx4QaT)

## Building this project

Gradle is the recommended way to build the project. Use `./gradlew clean build` in the main project directory to build the
project.
The output is located at `/build/libs/IllegalStack.jar`.
