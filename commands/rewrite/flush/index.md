---
layout: default
title: 'wp rewrite flush'
---

`wp rewrite flush` - Flush rewrite rules.

### DESCRIPTION

Resets WordPress' rewrite rules based on registered post types, etc.

To regenerate a .htaccess file with WP-CLI, you'll need to add the mod_rewrite module
to your wp-cli.yml or config.yml. For example:

apache_modules:
  - mod_rewrite

### OPTIONS

[\--hard]
: Perform a hard flush - update `.htaccess` rules as well as rewrite rules in database.

