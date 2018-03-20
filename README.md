# Extensions for Foundation for Sites

These are some extensions for Foundation for Sites that I will likely need to use in future projects.

## Basic use

Assuming you are building your Foundation theme from SCSS:

1. Import Foundation
    + `@import 'foundation-sites/scss/foundation';`
2. Import Foundation Extentions
    + `@import 'foundation-sites-extensions/scss/foundation-extensions';`
3. Override any variables you would like to customize
    + `$white: blue;`
4. Include the portions you would like in your theme
    + `@include foundation-extensions-everything;`

For a list of variables that can be set, see: `scss/_defaults.scss`