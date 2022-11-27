# The Old Dog Bookshop

The Old Dog Bookshop website is designed to give potential customers informative about the shop. This means the site needs to be responsive, allowing visiters to view on any device without quality of experience suffering. The main focus of the site is to give viewers information such as location of the shop, and contact details.

![image of my responsive website](./docs/tech-sini.png)

[Link to my website](https://skyeh-m.github.io/The-Old-Dog/)

## Contents

* [User Experience (UX)](#user-experience-ux)
  * [Project Goals](#project-goals)
  * [Developer and Business Goals](#developer-and-business-goals)
  * [User Stories](#user-stories)

* [Design](#design)
  * [Colour Scheme](#colour-scheme)
  * [Typography](#typography)
  * [Icons and Images](#icons-and-images)
  * [Features](#features)
  * [Accessibility](#accessibility)
  * [Wireframes](#wireframes)

* [Technologies Used](#technologies-used)
  * [Languages Used](#languages-used)
  * [Frameworks, Libraries & Programs Used](#frameworks-libraries-and-programs-used)

* [Deployment](#deployment)

* [Testing](#testing)
  * Automated Testing
    * W3C Validator
    * Wave
    * Lighthouse

  * Manual Testing
  * Bugs

* Credits
  * Code Sections Used
  * Media
  * Text

## User Experience (UX)

### Project Goals
The main goal of The Old Dog website is to advertise the bookshop and give potential customers crucial information that they'd need to shop with us. For example, 

* The site will contain an interactive Google map section on the homepage to enable viewers to locate the shop and plan their journey to visit us.
* The site will also include a written address for customers that would prefer to use a satnav or alternative means of planning their journey. 
* The site will describe the range of items we sell including inspiration for viewers future reads through the Our Collections page. This aims to encourage viewers to visit the shop to purchase books they're interested in, and encourages repeat visiters as the Our Collections page will change every month.
* There will be a contact page which will list the contact details for The Old Dog so that customers can quickly and easily ask any questions they have.
* The design, and navigation of the site will be simple and clear so that information is readily available to enable viewers to answer any questions they may have when visiting the site.

### Developer and Business Goals
* A main developer goal is to make the site as accessible as possible for any customer to use, no matter their needs and abilities. This will be principally achieved by the use of clear design, and alt text for screen readers.
* A focal business goal for the site would be to encourage repeat viewings in the hope that this encourages viewers to visit the shop and make purchases. This will be achieved by having an aesthetically pleasing and easy to navigate site, along with the Our Collections page frequently updating with new book recommendations.

### User Stories
As someone using The Old Dog website I want:
 1. To be able to quickly and easily navigate the site and successfully find any information I'm looking for
 2. To get a feel for the aesthetic and style of the bookshop to know whether items are clearly laid out and accessible, and that there is a large, varied selection of books on offer
 3. When I submit a question using the contact form I want confirmation that this query has been received by the bookshop, and be provided with an estimate of when I'll receive a response
 4. To be inspired to purchase and read books outside of my typical genres of choice, or have my attention drawn to books that I know I'll enjoy but haven't yet heard of
 5. I want to be able to visit The Old Dog website on any device I own whether the quality of the site, or the information available suffering

 ## Design 
 ### Colour Scheme

 ![image of my colour scheme](./docs/colour-scheme.png)

 The primary colour is a dark shade of forest green which speaks to the rustic and well-established nature of the bookshop, it communicates that the shop is reliable. The green colour scheme is evocative of the theme of books in general as it is reminiscent of trees and greenery.

 The lighter shades of green used on the site add an element of visual difference to keep viewers engaged, while also complimenting the focal dark green.

 The dark green used in the logo, title, and footer are the same shade to ensure consistency of style.

 ### Typography
I used [Google Fonts](https://fonts.google.com/) to import the following fonts to the site

 
 * The primary font used for headings and the navigation menu is Libre Baskerville, this was chosen as it's easily readible and promotes the idea that this bookshop is well-established, and 
 dependable.
 ![image of the primary font](./docs/header-text.png)
 * The secondary font used for the body is Libre Caslon Text which was selected for its clear readibility, and design that is reminiscient of fonts used in the text of many books
 ![image of the secondary font](./docs/body-text.png)
 * Both fonts are from the Serif family to ensure consistency throughout the site
 * ????? Are these fonts web safe/accessible ?????

 ### Icons and Images

 * Icons were sourced from [FontAwesome](https://fontawesome.com/), they were selected to be easily understandable and contextually relevant. For example, the Contact Us section has an icon of a phone alongside the header text. Icons are used occasionally to elevate the design of the page to break up chunks of text so the site doesn't lose the engagement of the viewer.  
 * All icons on the site have been titled so that screen readers can provide a description of their appearance for users with different needs.

 * No images used belong to myself and they will all be individually credited in a later section.
 * Images were chosen to give viewers an idea of what the bookshop looks like if they haven't visited the shop in person. The images are warm in tone to convey a friendly and helpful environment where potential customers feel comfortable visiting.
 * Images used in the Contact Us page are positioned in the background with text laid over the top displayed against a white background so viewers aren't distracted by images.

 ### Features
 The Old Dog website includes three main pages, Home, Our Collections, and Contact Us, these pages are all accessible through the navigation menu shown near the top of the screen. A Thank You page is also accessible if a viewer submits a question to the Contact Us page to notify them that their question has been received.

 * The pages include:
   * A navigation bar that enables viewers to navigate to each of the three main pages of the site. The page the viewer is currently on is displayed with an underlined title to show which page is active. Upon hovering over each of the navigation links they'll also be underlined to show the viewer where they are clicking. The navigation bar is responsive meaning that it decreases in size if viewed on smaller screen sizes, and becomes a collapsible hamburger bar if viewed on mobile. This is to streamline the appearance of the navigation bar and reduce clutter on mobile screens.
   * A footer is displayed at the bottom of each page which displays social media links to Facebook, Instagram, and Twitter for viewers to get in contact with us on multiple platforms. 
   * The browser tab includes a [Favicon](https://favicon.io/) of an open book to make the tab stand out among others allowing viewers to revisit our site easily

* Future Implementations
  * In the future a main goal is to allow viewers to purchase books online from the website, and have them delivered to their houses rather than simply encouraging viewers to visit the physical bookshop. The hope is that this would greatly expand the sales of The Old Dog bookshop as it'd allow people not from Sheffield to become frequent customers.

### Accessibility

Accessibility has been in the forefront of my mind throughout the design and construction of The Old Dog website.
* I tested all pages of my site using [WAVE](https://wave.webaim.org/) and have no errors on any page.
* Lighthouse testing for desktop and mobile have scored 100% for accessibility on both

![image of accessibility score](./docs/accessibility.png)
* I used semantic HTML throughout, and have provided aria-labels, alt text on images, and titles wherever possible to enable the best experience possible for viewers using screen readers or alternative technology.
* I used [A11y](https://color.a11y.com/) the Color Contrast Accessibility Validator which determined that no colour contrast issues were found on my site

### Wireframes

Before beginning work constructing my site I created wireframes of mobile, tablet, and desktop appearances of each of my three main pages.

* [Home page wireframe](./docs/home-wireframe.png)
* [Our Collections wireframe](./docs/collections-wireframes.png)
* [Contact Us wireframe](./docs/contact-wireframes.png)

## Technologies Used

### Languages Used
* HTML, and CSS were used to complete this project

### Frameworks, Libraries, and Programs Used
* Adobe XD was used to create Wireframes
* [Birme](https://www.birme.net/) was used to reformat images to a webp
* Bootstrap Version 4.0 was used to create a responsive Navbar and collapsable hamburger menu for mobile
* [Favicon](https://favicon.io/) was used to create a browser tab icon
* [Font Awesome](https://fontawesome.com/) was used for all icons on the pages
* Github was used to store all files for this website
* Gitpod was used to create and edit all original code
* Google Chrome Developer Tools was used for debugging and testing with Lighthouse
* [Google Fonts](https://fonts.google.com/) was used to import both fonts for use on the site
* [Tech Sini](https://techsini.com/multi-mockup/index.php) was used to create a multi device website mockup to demonstrate responsivity
* [Tiny Png](https://tinypng.com/) was used to resize image files to help the browser load pages quicker

## Deployment

The Old Dog website is deployed using Github Pages, this was done by:

1. Login to Github
2. Navigate to the account SkyeH-M, and locate the The-Old-Dog repository
3. In The-Old-Dog repository click on the Settings tab
4. In the Code and Automation subheading in the sidebar click on Pages
5. Under Build and Deployment find the Source section, set the source to deploy from a branch, and set this branch to main, and the folder option to /root 
6. Click save, wait a few minutes and The Old Dog site is now deployed at the URL displayed

## Local Deployment
### How to Clone 

1. Locate the main page of The-Old-Dog repository, click the Code button to the left of the green Gitpod button
2. Copy the URL of the repository, you can click on headings for HTTPS, SSH, and Github CLI to find their individual links
3. Open your own terminal in your editor and change the current working directory to the location of where you want the cloned directory to be
4. In the terminal type git clone, and then paste the URL you copied from The-Old-Dog repository page
5. Press enter to complete

### How to Fork

1. Locate the main page of The-Old-Dog repository
2. Click the fork button in the top right of the screen, between the watch, and star buttons

## Testing

## Automated Testing
### W3 Nu HTML Validator

The Nu HTML Checker was used on each page of The Old Dog site at multiple stages throughout development, below are the final assessments showing no issues or warnings:

* [Home page score](./docs/html-index.png)
* [Our Collections page score](./docs/html-collections.png)
* [Contact Us page score](./docs/html-contact.png)
* [Thank You page score](./docs/html-thank-you.png)

### W3C CSS Validation Service

The W3C CSS Validation Service has also been used throughout the creation of this site, below is the final assessment showing no errors:

* [CSS Validator Score through direct input](./docs/css-validator.png)
* [Here](./docs/css-warnings.png) shows the CSS validator warnings which only state that imported style sheets cannot be checked in direct input

### Wave Testing













