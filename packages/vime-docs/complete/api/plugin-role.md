# PluginRole

**Type:** `enum<int>`

[View Source](../../../vime-complete/src/core/PluginRole.js)

Identifies the role of a plugin. In other words, it helps the player identify "special" plugins 
that provide some core functionality. For example, the `canSetPoster` property will check if there
are any plugins with the role `POSTER`, before checking for native support.

- `1` - The plugin has a role of `POSTER`, therefore it can set/manage posters.
- `2` - The plugin has a role of `CONTROLS`, therefore it can set/manage controls.
- `3` - The plugin has a role of `CAPTIONS`, therefore it can set/manage captions.
- `4` - The plugin has a role of `SETTINGS`, therefore it can set/manage settings.