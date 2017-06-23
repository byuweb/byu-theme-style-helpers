# byu-theme-style-helpers
Provide baseline styles and variables for the BYU 2017 theme.

This repo contains a collection of short css files that can be referenced to easily add styles to existing websites. 

In most cases, they provide classes like .byu-button and .byu-table-header. Classes being with "byu-" for namespacing reasons,
so it will ideally not interfere with existing styling.

There are some exceptions, where it is directly styling elements. The font-related files, for example, set fonts for 
headings and paragraphs and divs, etc. In these cases, the files are CAPITALIZED and you should review them thoroughly before loading them on your site.


TO USE
------------
1. Load the CSS:
* You are welcome to download or git clone these files. 
* Reference css files from the cdn.

2. Add the `byu-something` classes to your elements to make use of the styling. All files with lowercase names (i.e. 'byu-button', not 'Font..') have css that has been namespaced with `byu-` prefixes on classes.

None of these files should immediately change any of your styling; the styling will be applied when and where you apply the appropriate classes.


FROM THE CDN
------------
Select css files that have been marked as ready for widespread use have been included into the cdn. You can see the current list of included files by looking at the list of endpoints in this repo's `cdn-config.yml` file.

These files can then be accessed via this format:

## Example Endpoints

```entrypoints:
  buttons.css: 'Adds button classes for BYU buttons - several BYU color options available.'
  tables.css: 'Adds a class to style tables nicely with BYU colors'
  box-shadows.css: 'Adds box-shadow classes for elements.'
```

## Example Reference Points
```
https://cdn.byu.edu/byu-theme-style-helpers/latest/buttons.css
https://cdn.byu.edu/byu-theme-style-helpers/latest/tables.css
https://cdn.byu.edu/byu-theme-style-helpers/latest/box-shadows.css
```
