---
category: utilities
order: 20
url: guide/dev_devtools
menu-title: Developer Tools
meta-title-short: Developer Tools
---
<!--
Copyright (c) 2003-2017, CKSource - Frederico Knabben. All rights reserved.
For licensing, see LICENSE.md.
-->

# Using Developer Tools Plugin to Customize Dialog Windows

<info-box info="">
</info-box>

An optional CKEditor plugin called [Developer Tools](https://ckeditor.com/cke4/addon/devtools) displays tooltips with information about editor dialog windows, such as:

* dialog window name,
* dialog window tab name,
* dialog window element ID,
* dialog window element type with a link to an appropriate entry in the {@link api/index CKEditor API}.

{@img assets/img/devtools_01.png}

This feature is aimed at developers who would like to {@link guide/dev/howtos/dialog_windows/README customize their CKEditor instances} or {@link guide/plugin_sdk/intro/README create their own plugins}. It is only useful in the development phase and makes no sense in a production environment, so do remember to get rid of it before you upload CKEditor to your production server!

<info-box hint="">
</info-box>

## Customization Options

The Developer Tools plugin provides two configuration options:

* {@linkapi CKEDITOR.config.devtools_styles CKEDITOR.config.devtools_styles} &ndash; sets the CSS styles applied to the tooltip.
* {@linkapi CKEDITOR.config.devtools_textCallback CKEDITOR.config.devtools_textCallback} &ndash; contains a function that returns the text displayed in the tooltip.

## Developer Tools Demo

See the [working "Developer Tools" sample](https://sdk.ckeditor.com/samples/devtools.html) that showcases how easy it can be to get information about editor dialog windows and their elements.

## Related Features

Read more about customizing CKEditor dialog windows in the {@link guide/dev/howtos/dialog_windows/README Dialog Windows} HOWTO article. It explains how to set default values for dialog window fields or configure dialog window properties with some help from the Developer Tools plugin.