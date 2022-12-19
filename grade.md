# Grade
HTML Code Quality: 7/10
Bootstrap / Custom Sass Quality: 7/10
Responsive Design: 6/10
Assignment Requirements: 6/10

Total: 26/40

## Comments

### HTML
Search for `prof feedback` in individual files for specific comments.

### Bootstrap/SASS
- One of the main goals of using Sass and of dividing our code into separate files is to keep things organized and segmented so it is easier to find styles and to keep them properly scoped. You have put a tonne of non-related styles into a single `_main.scss` which defeats the purpose of segmenting the code.
- You should not be using `px` units! I have told you this MANY times, including while you were working on this project.

### Responsive Design
- Its important that you view your website on larger screens, as well as on smaller screens. You have a relatively small Macbook, so although it looks good on your screen, doesn't mean it will work on larger screens like a standard 1920x1080 HD monitor. Your layouts are too wide and do not use containers appropriately to size your items. You don't need an extra monitor to accomplish this. You can use the developer tools in the browser to preview larger screen sizes.
  - Some specific areas where this is an issue: header, footer, intro content, portfolio cards, form.
- Card groups are not responsive. They are too small on small screens in 3 columns and should change layouts.
- Hover states should only be applied on clickable/interactive elements. The skills cards have no interactive action, so should not have a hover/focus. This causing a confusing user experience.
- The background on the form makes the labels/title very hard to read and is an accessibility issue.

### Assignment Requirements
- Missing content:
  - There should be content describing each skill
  - There should be content describing each project
- Home page file should be `index.html` as that is what the browser expects to serve for a home page.
- Site is not live on GitHub Pages