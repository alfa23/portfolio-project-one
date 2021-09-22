# Portfolio Project One | HTML and CSS Essentials

## Bugs and fixes:

### Bug: Header logo breaking apart

! INSERT SCREENSHOT !
During resizing RJW Illustration logo would split into two lines. Googled the issue, found and implemented the following fix:

How to Prevent Word Wrap on a Web Page: HTML Method
If you only have the one-off instance of two or more words that you want to force the browser to keep on a single line, the easiest way is to use the non-breaking space character, "&nbsp;", to separate those words instead of a normal space.

For example, if the words in question are "The Site Wizard", write it as follows:

The&nbsp;Site&nbsp;Wizard
The browser will then treat that string of characters as though they were part of single word, and by default, not split it up when it crosses the edge of the screen or enclosing block.

Sourced from: https://www.thesitewizard.com/css/prevent-word-wrapping.shtml September 2021.

## External resources utilised:

/* Add a slash symbol (/) before/behind each list item - code below pasted from https://www.w3schools.com/howto/howto_css_breadcrumbs.asp */
.breadcrumb li+li:before {
    padding: 8px;
    color: #fff;
    content: "/\00a0";
  }

/* Add page-container code to manage footer positioning - code below sourced from https://www.freecodecamp.org/news/how-to-keep-your-footer-where-it-belongs-59c6aa05c59c/ •/

