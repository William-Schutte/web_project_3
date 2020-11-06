# Project 3: From Portland to Portland
## William Schutte, 2020
Practicum by Yandex
-----
View this project here:
***https://william-schutte.github.io/web_project_3/***

### Overview
This project is the third project for the web-dev course. The purpose of this project is to learn, understand, 
and incorporate adaptive web-design and layouts into a web-site. This project required working off a design brief 
on Figma, an online collaborative interface prototyping tool. 

### Techniques
The designed page includes adaptive CSS flex-boxes and grid layouts to function properly on mobile devices, tablets, 
laptops, and desktop monitors. Media queries were utilized to format objects and entities at commonly used 
resolutions. Internally, the site is designed under BEM methodology, including nested file structure. 

### Technologies
Finally, the project reinforced fundamental skills in CSS, HTML, Git, and GitHub. 
Structured with HTML, styled with CSS, updated with Git, reviewed via GitHub, and presented through GitHub Pages.
Project brief was provided through Figma, communicating dimensions, fonts, font-sizes, colors, images, and general 
page layout. 

-----
#### Update Notes 3/27/2020 - After 3rd Review

##### Fixes:
    Removed target="_blank" for on-site header nav link.
    Added target="_blank" attribute to off-site links.
    Moved animate class from <li> to nested <a> tag in footer.
    Fixed margin-bottom on content-subtitle for lower resolutions
    Added top margin to comments__container at low resolutions to create 44px gap between content-subtitle.
    Fixed margins on header at 320px resolution.
    Change spacing units on lead__caption to em.
    Adjusted padding/margins of lead section to get correct image resolution at 1024px.
    Fixed place__image positioning by moving margins/padding from section to individual elements.
    Fixed place__title positioning in 2x2 grid layout at 768px resolution.
    Removed video__icon-play folder and file, empty rule.
    Replaced use of max-height for video__title with min-height.
    Swapped Cover section positioning. Background is now default, text is absolute positioned.

-----

#### Update Notes 3/25/2020 - After 2nd Review

##### Fundamental Changes:
    Deleted unneeded Reset.CSS file and italic font files (not used).
    Slightly reformatted this ReadMe for clarity.
    Changed multiple font sizes/line heights to px units to better match spec.
    Used 320px, 500px, 768px, and 1024px as dimension cutoffs.
        Used 500px instead of 425px because many sections and elements were much too large and caused overflow between
        426 - 500px resolutions.

##### Fixes by Section:
    Page        Added fall-back font family, sans-serif
    Header      Reformatted (Logo + List of Lang Links), matched spec margins, fixed 320px resolution
    Lead        Updated modifiers to better reflect spec dimensions.
    Intro       Changed HTML formatting (different classes for <p> and <ul>, span class), fixed font sizes for small screens
    Photo-Grid  Moved padding to block instead of modifier
    Places      Fixed Places grid transition from 2 x 2 to 1 x 3, fixed text font sizes at smaller resolutions
    Video       Reformatted into <ul> of videos, added correct link paths. Added target="_blank" attribute to links.
                Fixed modifier naming issue with video__icon-play.
                Fixed scaling of margins and padding inside overlay.
    Cover       Fixed total mess that was the Cover section.
                Wrapped in <a> tag and added hover animation.
                Changed all margins/padding/sizing to explicitly declare height based on screen width.
                Height of cover__link matches height of cover__background.
    Footer      Removed copyright from <ul>. Readjusted margins/padding and text sizes at smaller resolutions.
    
-----

#### Update Notes 3/23/2020 - After 1st Review
Empty file .nojekyll is required for use of BEM file naming conventions with GitHub Pages. GitHub Pages will ignore
filenames beginning with an underscore by default unless .nojekyll is present.

##### Fundamental Changes:

    I previously built the page using Reset.CSS to test out this method. Converted back to Normalize.CSS per reviewer 
    recommendation. This also eliminates the use of HTML Tag selectors in the index.CSS file. 

    Changed all link-hover animations to a unique, reuseable block/class.

    Grouped similar items using <ul> instead of a series of divs (header, intro, photo-grid, places, footer sections).
    Wherever items were converted to a list, an additional container class was created.

##### Smaller Fixes:

    Changed header and footer sections to <header> and <footer> tags.
    Used <section> tags instead of <div> for main content sections.
    Removed all use of the <br/> tag.
    Removed <em> tag and replaced with styling/classes and <span>.
    Renamed photo-grid images to be descriptive rather than numeral.
    Added <a> tag around video links and fixed scaling of overlay.
    Changed video__title elements to <h3>.
    Changed comment__quote elements to <blockquote>.
