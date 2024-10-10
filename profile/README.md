# CorePress

CorePress is an experimental modern CMS with the goal of being modular and fast, while preserving maximum compatibility with WordPress and its plugins.

For this, the following features have been moved to plugins
 
- Backwards-compatibility (deprecated functions, hooks, ...) for plugins
- Editing plugin & theme files

We also want to move the following additional features to plugins:

- The plugin/theme repo & updater (only installing zips will be kept in Core)
- The CorePress updater
- Gutenberg (Without the plugin, work similar to ClassicPress)
- Multisite (As much as possible, with certain global vars & functions being replaced by fallback implementations unless it's installed)

## Modularity without impacting UX

To not impact the Wordpress user experience, the following features will be installed by default:

- The CorePress updater
- Plugin/theme repo & updater
- Gutenberg

Plugins that reimplement feature that is shipped out of the box with WordPress will be featured more prominently in the plugin repo.

## Reimplementing the plugin downloading system

The plugin repository will also be completely reimplemented soon.

## Removed from CorePress

In CorePress, we're not maintaing any theme except Twenty Twenty-Four in the main repository.

## Motivation

A modular architecture allows for easier updates, faster speed, and makes the code easier to work with.

Movign the plugin repo to a plugin also reduces dependence on any hardcoded server.

## Unique plugins/features

We're also working on some new/enhanced plugins made specifically for CorePress to enhance your experience:

- Git versioning
- Backups
- SEO

More information on these plugins will be published during development.

## Plugin & theme sources

Plugins & themes will be by default sourced from CorePress repos, with WordPress repos being also accessible. Because we try to maintain 100% compatibility, every WordPress plugin should work out of the box or with help of our compatibility plugin.
