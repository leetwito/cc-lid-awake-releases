# cc-lid-awake — releases

Public release artifacts for **cc-lid-awake**, a macOS Claude Code plugin
that keeps your Mac awake with the lid closed while Claude Code is working.

**Source code is private and proprietary.**
Purchase a license at <https://leetwito.gumroad.com/l/cc-lid-awake>.

Every `.dmg` published here corresponds to a tagged release.

## Claude Code plugin marketplace

This repo is also the official Claude Code plugin marketplace for cc-lid-awake.
The installer registers it automatically; to add it manually:

```
/plugin marketplace add leetwito/cc-lid-awake-releases
/plugin install cc-lid-awake@cc-lid-awake
```

The plugin only wires Claude Code hooks to the cc-lid-awake binary — it does
nothing unless the cc-lid-awake app is installed and licensed.
