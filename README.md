# Project 3: From Portland to Portland
## William Schutte, 2020
Practicum by Yandex
-----
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

### GitHub Pages Link

This page is also available from my GitHub at the following link:

***https://william-schutte.github.io/web_project_3/***

-----
#### Update Notes 3/22/2020 - After 1st Review
Empty file .nojekyll is required for use of BEM file naming conventions with GitHub Pages. GitHub Pages will ignore
filenames beginning with an underscore by default unless .nojekyll is present.

I previously built the page using Reset.CSS to test out this method. Converted back to Normalize.CSS per reviewer 
recommendation. This also eliminates the use of HTML Tag selectors in the index.CSS file. 

Smaller Fixes:
Used <section> tags instead of <div> for main content sections.
Removed all use of the <br/> tag.
Removed <em> tag and replaced with styling/classes and <span>.
Grouped similar items using <ul> instead of a series of divs (header, intro, photo-grid, places sections).
Renamed photo-grid images to be descriptive rather than numeral.