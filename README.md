# Portfolio Project One | HTML and CSS Essentials

## Bugs and fixes:

### Bug: Header logo breaking apart

! INSERT SCREENSHOT !

Issue: During window resizing RJW Illustration logo would split into two lines. 

Solution: Googled the issue, found and implemented the following fix:

How to Prevent Word Wrap on a Web Page: HTML Method
If you only have the one-off instance of two or more words that you want to force the browser to keep on a single line, the easiest way is to use the non-breaking space character, "&nbsp;", to separate those words instead of a normal space.

Sourced from: https://www.thesitewizard.com/css/prevent-word-wrapping.shtml September 2021.

### Bug: Gallery responsiveness for screens 600px and below

Issue: During responsive testing the columns wouldn't flex from two to one when dropping below 600px.

Solution: Finally realised the code was good but the CSS styling order wasn't! Moving the '@media...max-width: 992px' query from after/below the '@media...max-width: 600px" query to before/above it in the CSS heirarchy fixed the issue.

## External resources utilised:

/* Add a slash symbol (/) before/behind each list item - code below pasted from https://www.w3schools.com/howto/howto_css_breadcrumbs.asp */
.breadcrumb li+li:before {
    padding: 8px;
    color: #fff;
    content: "/\00a0";
  }

/* Add page-container code to manage footer positioning - code below sourced from https://www.freecodecamp.org/news/how-to-keep-your-footer-where-it-belongs-59c6aa05c59c/ •/

