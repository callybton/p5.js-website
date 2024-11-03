# p5.js Website

This is Nath Freires' and Cally Amisola's forked repository of the [p5.js website](https://github.com/processing/p5.js-website).

## Issue 516 Fix
Issue 516 deals with the responsiveness of the _p5.JS_ website, as certain text and/or classes are cut off when viewed on screens with smaller width. The changes were created in the _styles/global.scss_ file’s _.homepage-header-top_ selector. We adjusted the height and max-height properties and created a new rule for mobile screens using the existing _$breakpoint-tablet_. Previously, the height was set to a calculation that would not adapt to every screen type. Adjusting the default properties and using the custom variable _--spacing-sm_ in the “new” breakpoint fixes the responsiveness of the page while maintaining consistency with the global CSS style rules.
