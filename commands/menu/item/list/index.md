---
layout: default
title: 'wp menu item list'
display_global_parameters: true
---

`wp menu item list` - Get a list of items associated with a menu

<small>Quick links: <a href="https://github.com/wp-cli/wp-cli/issues?q=is%3Aopen+label%3Acommand%3Amenu-item-list+sort%3Aupdated-desc">Github issues</a></small>

<hr />

### OPTIONS

&lt;menu&gt;
: The name, slug, or term ID for the menu

[\--fields=&lt;fields&gt;]
: Limit the output to specific object fields.

[\--format=&lt;format&gt;]
: Accepted values: table, csv, json, count, ids, yaml. Default: table

### AVAILABLE FIELDS

These fields will be displayed by default for each menu item:

* db_id
* type
* title
* link
* position

These fields are optionally available:

* menu_item_parent
* object_id
* object
* type
* type_label
* target
* attr_title
* description
* classes
* xfn

### EXAMPLES

    wp menu item list &lt;menu&gt;



