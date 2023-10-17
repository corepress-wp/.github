# CorePress

CorePress is an experimental fork of WordPress with the goal of making it more modular and faster, while preserving maximum compatibility.

For this, the following features have been moved to plugins
 
- Backwards-compatibility (deprecated functions, hooks, ...) for plugins
- Editing plugin & theme files

We also want to move the following additional features to plugins:

- The plugin/theme repo & updater (only installing zips will be kept in Core)
- Gutenberg (Without it as a plugin, work similar to ClassicPress)
- Multisite (As much as possible, with certain global vars & functions being replaced by fallback implementations unless it's installed)

  
## Modularity without impacting UX

To not impact the Wordpress user experience, the following features will be installed by default:

- Plugin/theme repo & updater
- Gutenberg


## Removed from CorePress

In CorePress, we're not maintaing any theme except Twenty Twenty-Four.

## Motivation

A modular architecture allows for easier updates, faster speed, and makes the code easier to work with.
