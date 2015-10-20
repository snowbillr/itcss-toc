# itcss-toc
Automatically create a table of contents comment for your main.scss ITCSS file.

Running this:
```
itcss-toc css/main.scss
```

Generates this:
```
/*------------------------------------*\
  #MAIN
\*------------------------------------*/

/**
 * CONTENTS
 *
 * SETTINGS
 * Config...............Configuration and environment settings.
 * Global...............Globally-available variables and settings/config.
 * Colors...............Manage our color palette in isolation.
 *
 * TOOLS
 * Functions............Some simple helper functions.
 * Mixins...............Globally available mixins.
 * Aliases..............Some shorter aliases onto longer variables.
 *
 * GENERIC
 * Normalize.css........A level playing field.
 * Box-sizing...........Better default `box-sizing`.
 * Reset................A pared back reset to remove margins.
 * Shared...............Sensibly and tersely share global commonalities.
 *
 * ELEMENTS
 * Page.................Page-level styles (HTML element).
 * Headings.............Heading styles.
 * Links................Hyperlink styles.
 * Lists................Default list styles.
 * Images...............Base image styles.
 * Quotes...............Styling for blockquotes, etc.
 *
 * OBJECTS
 * Wrappers.............Wrappers and page constraints.
 * Layout...............Generic layout module.
 * Headline.............Simple object for structuring heading pairs.
 * Media................The media object.
 * List-bare............Lists with no bullets or indents.
 * List-inline..........Simple abstraction for setting lists out in a line.
 * Crop.................A container for cropping image and media content.
 *
 * COMPONENTS
 * Logo.................Make our logo a reusable component.
 * Page-head............Page header styles.
 * Page-foot............Page footer styles.
 * Nav primary..........The site’s main nav.
 * Nav secondary........Secondary nav styles.
 * Masthead.............Site’s main masthead.
 * Sub-content..........Secondary/supporting content.
 * Panel................Simple panelled boxout.
 * Score................Score lozenge for place ratings.
 * Buttons..............Button styles.
 * Avatar...............General avatar styles.
 * Testimonial..........Quote styles.
 * Calendar.............Simple static calendar component.
 * Headline.............Basic heading style for generic headlines.
 * Promo................Promotional box styling.
 *
 * SCOPES
 * Prose................Set up a new styling context for long-format text.
 *
 * THEMES
 * Red..................Simple red theme for the site.
 *
 * TRUMPS
 * Headings.............Reassigning our heading styles to helper classes.
 * Widths...............Simple width helper classes.
 * Debug................Visual health-check tool.
 * Shame.css............Short-term hacks and quick-fixes.
 */
 ```
 (see the [ITCSS demo project](https://github.com/csswizardry/discovr/))
