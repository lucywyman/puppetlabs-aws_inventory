## Release 0.4.0

### New features

* **Set `resolve_reference` task to private** ([#6](https://github.com/puppetlabs/puppetlabs-aws_inventory/pulls/6))

    The `resolve_reference` task has been set to `private` so it no longer appears in UI lists.
    
## Release 0.3.0

### New features

* **Added `target_mapping` parameter in `resolve_reference` task** ([#1407](https://github.com/puppetlabs/bolt/issues/1407))

  The `resolve_reference` task has a new `target_mapping` parameter that accepts a hash of target attributes and the resource values to populate them with.

## Release 0.2.0

### Bug fixes

* **Expand `credentials` path relative to Boltdir** ([#1162](https://github.com/puppetlabs/bolt/issues/1162))

  The `credentials` option will now be expanded relative to the active Boltdir the user is running bolt with, instead of the current working directory they ran Bolt from. This is part of standardizing all configurable paths in Bolt to be relative to the Boltdir.

## Release 0.1.0

This is the initial release.
