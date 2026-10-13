# Remove Matched Albums

## Overview

This plugin allows the user to remove completely matched and saved albums from the album pane.

The plugin is based on the Picard v2 \"Remove Perfect Albums\" plugin by ichneumon and hrglgrmpf. See https://github.com/metabrainz/picard-plugins/blob/2.0/plugins/remove_perfect_albums/remove_perfect_albums.py for the original Picard 2 plugin code.

---

## What it Does

This plugin provides an action under the "Plugin Tools" section of Picard's manu menu. When clicked, each of the albums listed in the Albums pane is examined for possible removal. If the album is complete with all tracks matched to an audio file and all of the files have been saved, then the album is removed from the list.

---

## Contributing

Please see the [Contribution Guidelines for MusicBrainz Picard Plugins](https://github.com/metabrainz/picard-plugins-registry/blob/main/PLUGIN_CONTRIBUTING.md) on how to help with development of this plugin.
