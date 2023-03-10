# Changelog

# 0.G

### Changes
- **SAVE-BREAKING:** Reworked/cleaned up mutation IDs to follow a comprehensive naming convention.
- Removed cross-gender restrictions on most traits.
    - Traits that have gender-based variation have been tagged consistently with the new convention.
- Rewrote `name`s/`description`s to be more accurate, more searchable, and seamlessly follow the vanilla flavour text style.
- Added the new `vanity` property to all items.
    - Toggled player display on all items to make this property useful.
- Cleaned up a bunch of typos and formatting inconsistencies.

### Existing Savegames
This is a save-breaking change. Mitigation instructions for existing savegames are below.
1. Load your save using the old version of Whaley's Hair and Tattoo.
2. Use the debug menu (`Player`>`Mutate`) to remove all Whaley-related traits from yourself and NPC followers.
3. Close the game and update Whaley's Hair and Tattoo to the new version.
4. Load your savegame and use the debug menu to re-add your Whaley-related traits to your characters.

# [0.F](https://github.com/neonspectra/whaleys-hair-and-tattoo/releases/tag/0.F)

- Ported from [source](https://www.reddit.com/r/cataclysmdda/comments/dvxkr4/whaleys_hair_tattoo_mod/) to work on 0.F
