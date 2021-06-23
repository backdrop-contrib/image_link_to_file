# Image link to file

The Image link to file module is a formatter for image fields that creates a
hyperlink from the image to a file field in the same entity.

This simple module solves a typical use case in which, when clicking on a
preview image (e.g. JPG or PNG file), a PDF file specified as a file field in
the same node should be opened.

To use the formatter, click on the Manage Display tab of a content type that
contains at least an image field and a file field. Then, in the Format column
of the image field, select "Image linked to file". To specify the format
settings, click on the button with the gear to reveal the "Image style"
selector, the "Image link" selector and the "Open image in a new window or tab"
checkbox.

Any of the available image style options can be selected for the image and any
of the file fields can be selected for the linked file. Optionally, the linked
file can be made to open in a new window or tab, rather than in the same window
or tab.

After your selection, click the Update button and then click the Save button.

## Installation and Usage

- Install this module using the [official Backdrop CMS instructions](https://backdropcms.org/guide/modules).
- Further instructions can be found in (and added to) the [Wiki](https://github.com/backdrop-contrib/image_link_to_file/wiki)

## Issues

Bugs and Feature requests should be reported in the [Issue Queue](https://github.com/backdrop-contrib/image_link_to_file/issues)

## Current Maintainers

- [Laryn Kragt Bakker](https://github.com/laryn/), [CEDC.org](https://CEDC.org)

## Credits

- Ported to Backdrop CMS by [Laryn Kragt Bakker](https://github.com/laryn/), [CEDC.org](https://CEDC.org)
- The Drupal 7 version is developed and maintained by [Alex B](https://drupal.org/user/1815724)

## License

This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.
