---
layout: default
title: 'wp theme list'
display_global_parameters: true
---

<small>[Commands](/commands/) &raquo; [theme](/commands/theme/) &raquo; list</small>

`wp theme list` - Get a list of themes.

<small>Quick links: <a href="https://github.com/wp-cli/wp-cli/issues?q=is%3Aopen+label%3Acommand%3Atheme-list+sort%3Aupdated-desc">Github issues</a></small>

<hr />

### OPTIONS

[\--&lt;field&gt;=&lt;value&gt;]
: Filter results based on the value of a field.

[\--field=&lt;field&gt;]
: Prints the value of a single field for each theme.

[\--fields=&lt;fields&gt;]
: Limit the output to specific object fields.

[\--format=&lt;format&gt;]
: Accepted values: table, json, csv, yaml. Default: table

### AVAILABLE FIELDS

These fields will be displayed by default for each theme:

* name
* status
* update
* version

These fields are optionally available:

* update_version
* update_package
* update_id
* title
* description

### EXAMPLES

    # List themes
    $ wp theme list --status=inactive --format=csv
    name,status,update,version
    twentyfourteen,inactive,none,1.7
    twentysixteen,inactive,available,1.1



