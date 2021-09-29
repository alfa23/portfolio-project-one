# RJW Illustration Online Portfolio

Rian Whiteside is an active, industrious Illustrator and digital artist based in the rural South West of the UK. Despite having a *distinctive **style***, *extensive **portfolio*** and *growing **client list***, he ***still** doesn't have a **website!***

### ***Until now...***

**RJW Illustration** is a site that hopes showcase Rian's unique art style to a wider audience online, in a simple-yet-stylish experience. The site will be targeted toward users who enjoy discovering new artists to follow and artworks to appreciate. 

The **RJW Illustration** site will be useful for users and other artists (or potential employers!) wishing to see more of Rian's work, and also offer the opportunity to send him a message, enquire about commissions or discuss collaborations. 

![AmIResponsive Home](readme_media/test_amiresponsive/amiresponsive-01_home.png)

![AmIResponsive Portfolio](readme_media/test_amiresponsive/amiresponsive-02_portfolio.png)

![AmIResponsive Gallery Ink](readme_media/test_amiresponsive/amiresponsive-03_inktober20.png)

![AmIResponsive Gallery Ill](readme_media/test_amiresponsive/amiresponsive-04_illustrative.png)

![AmIResponsive Contact](readme_media/test_amiresponsive/amiresponsive-05_contact.png)

---- 

# UCD: STRATEGY

![Initial Project Doodlings](readme_media/rjwi_planning_docs/pp01_initial_thinx.jpg)

## External User Goals: 

In this section, you should go over the different parts of your project, and describe each in a sentence or so. You will need to explain what value each of the features provides for the user, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things.

## Site Owner Goals:

In this section, you should go over the different parts of your project, and describe each in a sentence or so. You will need to explain what value each of the features provides for the user, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things.

## Potential Features

In this section, you should go over the different parts of your project, and describe each in a sentence or so. You will need to explain what value each of the features provides for the user, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things.

---- 

# UCD: SCOPE

![UCD Strategic Trade-Offs: Importance vs Feasibility](#)

----

# UCD: STRUCTURE

![Balsamiq Site Map](#)

---- 

# UCD: SKELETON

![Balsamiq Mobile Wireframes](#)

![Balsamiq Desktop Wireframes](#)

---- 

# UCD: SURFACE

### Existing Features

- **Site-wide Navigation & Logo Header**

  - Visually balancing the top-left-aligned nav elements, the RJW Illustration logo is rendered top-right using Amatic SC, a cursive web font in a simple, hand-drawn style.
  - Featured on all website pages, the fully responsive header includes links to the Home page, Portfolio landing page and Contact page and is identical in each page to allow for easy navigation.
  
![Site-wide Nav & Logo Header](#)

  - This allows the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button. 

![Header Nav](#)

  - On mouse hover, nav links are highlighted to provide clear user-feedback and the current page is indicated with an underline in the site's chosen accent colour, Chartreuse.

![Header Nav Focus Feedback](#)
  
![Header Nav Active](#)

- **Home Page About Section & Time-lapse Video**

  - The landing includes a photograph with text overlay to allow the user to see exactly which location this site would be applicable to. 
  - This section introduces the user to Love Running with an eye catching animation to grab their attention

![Home Page Copy Panel](#)

![Home Page Time-lapse User-Invoked Video Panel](#)

- **Footer** 

  - The footer section includes links to Instagram and Behance external sites and will open to a new tab, allowing easy navigation for the user. This is valuable to site users as it encourages them to keep connected via social media.
  - Additional site-wide breadcrumb-style nav links included in the footer allow easy user navigation to Home, Portfolio and Contact pages at the bottom of long gallery pages and all pages on smaller, responsive-styled screens.

![Site-wide Footer](#)

![Site-wide Footer Links](#)

- **Portfolio Gallery Selection Page**

  - The Portfolio page serves as a landing page providing users with links to themed galleries of work. 
  - This section is also valuable to the user as it enables them to easily choose between the different thematic styles of illustration Rian creates. 
  - Two gallery choices initially available. Flexbox CSS method utilised allows easy addition & styling for subsequent gallery pages as required.

![Portfolio](#)

![Portfolio gallery title on image hover](#)

- **Gallery Pages: Inktober 2020 & Illustrative**

  - The gallery will provide the user with supporting images to see what the meet ups look like. 
  - This section is valuable to the user as they will be able to easily identify the types of events the organisation puts together. 

![Gallery title header](#)

![Gallery responses: full/1024/768](#)

![Gallery footer links](#)

- **Contact Page**

  - This page will allow the user to get signed up to Love Running to start their running journey with the community. The user will be able specify if they would like to take part in road, trail or both types of running. The user will be asked to submit their full name and email address. 

![Contact copy panel](#)

![Say Hullo!: Contact form panel](#)

For some/all of your features, you may choose to reference the specific project files that implement them.

In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

### Features Left to Implement

- **Further Gallery Pages**

  - 

- **Online webstore**

  - 

## Testing 

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your project’s features and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

## Bugs and fixes:

### **Bug:** Header logo breaking apart

! INSERT SCREENSHOT !

**Issue:** During window resizing RJW Illustration logo would split into two lines. 

**Solution:** Googled the issue, found and implemented the following fix:

How to Prevent Word Wrap on a Web Page: HTML Method
If you only have the one-off instance of two or more words that you want to force the browser to keep on a single line, the easiest way is to use the non-breaking space character, "&nbsp;", to separate those words instead of a normal space.

Sourced from: https://www.thesitewizard.com/css/prevent-word-wrapping.shtml September 2021.

### **Bug:** Gallery responsiveness for screens 600px and below

**Issue:** During responsive testing the columns wouldn't flex from two to one when dropping below 600px.

**Solution:** Finally realised the code was good but the CSS styling order wasn't! Moving the '@media...max-width: 992px' query from after/below the '@media...max-width: 600px" query to before/above it in the CSS heirarchy fixed the issue.

### **Bug:** Ugly response layouts at 615px and iPad screen width (768px)

**Issue:**

**Solution:**

### Unfixed Bugs

You will need to mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a big variable to consider, paucity of time and difficulty understanding implementation is not a valid reason to leave bugs unfixed. 

### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html)

! (readme_media)

- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fvalidator.w3.org%2Fnu%2F%3Fdoc%3Dhttps%253A%252F%252Fcode-institute-org.github.io%252Flove-running-2.0%252Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#css)

## Deployment

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - Click the Pages section in the sidebar
  - From the source section drop-down menu, select the main branch
  - Once the main branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://alfa23.github.io/portfolio-project-one/ 


## Credits 

In this section you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism. 

You can break the credits section up into Content and Media, depending on what you have included in your project. 

### Content 

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The photos used on the home and sign up page are from This Open Source site
- The images used for the gallery page were taken from this other open source site






## External resources utilised:

/* Add a slash symbol (/) before/behind each list item - code below pasted from https://www.w3schools.com/howto/howto_css_breadcrumbs.asp */
.breadcrumb li+li:before {
    padding: 8px;
    color: #fff;
    content: "/\00a0";
  }

/* Add page-container code to manage footer positioning - code below sourced from https://www.freecodecamp.org/news/how-to-keep-your-footer-where-it-belongs-59c6aa05c59c/ •/

