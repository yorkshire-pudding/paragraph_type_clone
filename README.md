# Paragraphs Type Clone

Paragraphs Type Clone allows users with the "Administer Paragraph types"
permission to clone paragraph types easily; saving the effort of adding fields
to a new type if the fields required are the same or almost the same.

The name, machine name, label, description and whether or not the paragraphs
can be unpublished from the admin interface are all configurable, whereas field
instances, field groups (if applicable), and permissions (if applicable) are copied exactly.

The module is inspired by Content Type Clone but has a few differences:
- As the name says, this clones paragraph types and not content types which
requires a slightly different form and process to work.
- Node copying is deliberately not included as paragraphs are always within nodes.
- Field groups for all display modes are copied, not just field groups for the
form.
- Instead of rebuilding the paragraph types overview list, a link is placed in
the Configure screen when editing an existing paragraph type. 

## Requirements
This module requires that the following module is also enabled:

- [Paragraphs](https://github.com/backdrop-contrib/paragraphs)

While not required, this module supports:
- the Field Group module and will copy all field groups to the new paragraph
type.
- the Paragraphs Type Permissions submodule (of Paragraphs) and will copy all
permissions to the new paragraph type. 

## Installation
- Install this module using the [official Backdrop CMS instructions](https://backdropcms.org/guide/modules).

## Configuration and Usage
The module has no menu or modifiable settings. There is no configuration. When
enabled, the module will add a "Clone Paragraph Type" link to the Configure
screen when editing an exising paragraph type.

## Issues
Bugs and Feature requests should be reported in the [Issue Queue](https://github.com/backdrop-contrib/paragraphs_type_clone/issues)

## Current Maintainers
- [Martin Price](https://github.com/yorkshire-pudding) - [System Horizons](https://www.systemhorizons.co.uk)
- Collaboration and co-maintainers welcome!

## Credits
- Created for Backdrop CMS by [Martin Price](https://github.com/yorkshire-pudding) - [System Horizons](https://www.systemhorizons.co.uk)
- Inspired by [Content Type Clone](https://github.com/backdrop-contrib/content_type_clone) which was ported to Backdrop and maintained
by [Laryn Kragt Bakker](https://github.com/laryn).

## License
This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.
