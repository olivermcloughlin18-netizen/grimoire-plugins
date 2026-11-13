# Grimoire plugins

Free VST3 plugins from [grimoirebeats.com](https://grimoirebeats.com/plugins/). Mac only for now (Apple silicon and Intel). Windows builds are not ready yet.

Downloads are on the [Releases page](../../releases/latest).

## Install

1. Unzip the download.
2. Move the `.vst3` into `~/Library/Audio/Plug-Ins/VST3/`.
3. These builds are not notarised by Apple yet, so macOS blocks them until you clear the download flag. Open Terminal and run:

   ```
   xattr -dr com.apple.quarantine ~/Library/Audio/Plug-Ins/VST3/*.vst3
   ```
4. Restart your DAW and rescan plugins.

## Notes

These are early versions (0.1). Use them in any music you make, released or not. Please don't resell or re-host the plugins themselves.
