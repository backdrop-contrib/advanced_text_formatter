Advanced Text Formatter
=======================

This module is just a formatter (display) of textfield, text area and text
format. The idea behind this is to provide a simple solution, easy to setup,
with few dependencies to display text on website.

Implementation
--------------

The trim function in this module is taken from Views module with a few
modifications.

Integration
-----------

Of course, this module is fully compatible with any modules that use entity
formatters, such as Views or Panels

Besides that, this module is extremely useful when you use it with view modes.
In order to create a new view mode, you can implement the
hook_entity_info_alter() or install Entity view modes module.

Requirements
------------

This module requires that the following modules are also enabled:

 * Entity (Backdrop core, optional if you want to use token replacements)
 * Filter (Backdrop core)
 * Text (Backdrop core)

Installation
------------

- Install this module using the official Backdrop CMS instructions at
  https://docs.backdropcms.org/documentation/extend-with-modules.


Documentation
-------------

Additional documentation is located in the Wiki:
https://github.com/backdrop-contrib/advanced_text_formatter/wiki/.

Issues
------

Bugs and Feature requests should be reported in the Issue Queue:
https://github.com/backdrop-contrib/advanced_text_formatter/issues.

Current Maintainers
-------------------

- Seeking additional maintainers.

Credits
-------

- Ported to Backdrop by [djzwerg](https://github.com/djzwerg).
- Originally written and maintained for Drupal by [Pavlo Tyshchenko](https://www.drupal.org/u/azovsky) and [Nhat Tran](https://www.drupal.org/u/thmnhat).

License
-------

This project is GPL v2 software.
See the LICENSE.txt file in this directory for complete text.
