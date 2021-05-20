<h1 align="center">Cosmepedia</h1>

## Introduction

The purpose of this project is to provide the user with a platform for browsing and, ultimately purchasing high quality personal care products.
The products are categorized according to their function, for example; hair care, face care etc.

Categories included for ease of navigation are as follows:

* Face care
* Hair care
* Body care

## User Experience (UX)

-   ### User stories

    -   #### First Time Visitor Goals

        1. As a First Time Visitor, I want to easily understand what the website is offering.
        2. As a First Time Visitor, I want to be able to easily navigate throughout the site to find content.

    -   #### Returning Visitor Goals

        1. As a Returning Visitor, I want to be able to easily find products that I like.
        2. As a Returning Visitor, I want to subscribe to the newsletter and contact the site owner.

    -   #### Frequent User Goals
        1. As a Frequent User, I want to make repeat purchases.
        2. As a Frequent User, I want to check to see if there are any new products that I might like.

-   ### Design
    -   #### Colour Scheme
        -   Greens, whites and greys.
    -   #### Typography
        -   To create the appropriate aesthetic, the Lobster and Roboto fonts were used.
    -   #### Imagery
        -   The large, background hero image is designed to convey a sense of natural beauty.

## Wireframes

![wireframes-2](https://user-images.githubusercontent.com/71509357/118900333-94aa5580-b908-11eb-9666-c3145ed65e1b.png)



## Technologies used

* HTML5
* CSS
* Bootstrap V5.0
* Fontawesome V5.15.2
* Google fonts
* Chrome developer tools
* Firefox developer tools
* GitHub
* GitPod
* Atom

## Project testing

The project was tested on various browsers and devices to ensure that all pages were fully responsive and that all functionality behaved as anticipated.
HTML validator and Jigsaw validator were used to test each page of the project.
The following combinations of browsers and devices were used for testing;

### Devices
* Sony Xperia 10 II
* Iphone 6S Plus
* Ipad
* Macbook Pro
* 27 inch AOC curved monitor
* Samasung galaxy S8 Plus

### Browsers
* Chrome
* Firefox
* Safari
* Opera
* Brave

Lighthouse was used to check performance. The results are shown below;

![lighthouse-results](https://user-images.githubusercontent.com/71509357/118901450-37fc6a00-b90b-11eb-9fce-eb86aa48ff14.png)


## Project content

* Home/Landing page - index.html
* Face care page - face.html
* Body care page - body.html
* Hair care page - hair.html
* Contact page - contact.html

## CSS and media file management

Each HTML file was assigned it's own corresponding CSS file in order to facilitate easy access and maintenance.

The following CSS files are accessed by the corresponding HTML files;

* style.css - accessed by index.html
* body.css - accessed by body.html
* face.css - accessed by face.html
* body.css - accessed by body.html
* contact.css - accessed by contact.html

### Testing User Stories from User Experience (UX) Section

-   #### First Time Visitor Goals

    1. As a First Time Visitor, I want to easily understand what the website is offering.

        1. Upon entering the site, users are automatically greeted with a clean and easily readable navigation bar to go to the page of their choice. Underneath there is a Hero            Image and a text section with a prompt to find out more.
        2. The user is encouraged to press the 'transform my skin' button which will transform the hero image from grey to full color.
        3. The user will then be presented with three options to navigate to skin, body or hair care.

    2. As a First Time Visitor, I want to be able to easily navigate throughout the site to find content.

        1. The site has been designed to be fluid and never to entrap the user. At the top of each page there is a clean navigation bar with each link clearly marked.
        2. On each page the user can easily navigate to the homepage or another section of the website.


-   #### Returning Visitor Goals

    1. As a Returning Visitor, I want to be able to easily find products that I like.

        1. Product types are clearly displayed in the navigation.

    2. As a Returning Visitor, I want to subscribe to the newsletter and contact the site owner.

        1. The footer on every page contains a newsletter subscription area.
        2. There is also a dedicated contact page where the user can submit their contact details and a message.

-   #### Frequent User Goals

    1. As a Frequent User, I want to make repeat purchases.

        1. The user can easily navigate to the product area of their choice and proceed to make a purchase.

    2. As a Frequent User,  I want to check to see if there are any new products that I might like.

        1. The user would be familiar with the website layout and content; it should be easy for the user to find newly added products on each page.

## Procedure

### Navbar
I started the project by attempting to construct a customized navigation bar from a bootstrap template.
I customized the bar by altering the color, font and navigation links to conform to my aesthetic.

### Footer
After completing the navbar to my satisfaction, I decided that the best course of action was to frame the page by adding a footer.
I dabbled with a footer that included social media links, but opted for one with a simple newsletter signup instead. This decision was made because I did not like the idea of having social media links that did not link to anything.

### Homepage
I decided to keep the homepage simple and clean. I thought that this aesthetic was consistent with the ethos of the site. I did not want to clutter up the landing page with too many items. I felst that keeping the navigation as the main point of interaction was the simplest way to coax the user to make a selection.

### Face care page
For the face care page I opted, again, for a clean and simple aesthetic; unclutered and unencumbered.

### Body care and hair care pages
As with the face care page, I decided to continue with the same parameters so as to ensure that the browsing experience would be uniform and intuitive for the user.

### Contact page
For the contact page I simply constructed a rudimentary form and used CSS and fontawesome Icons to style it.

### Challenges encountered
My biggest problem was trying to eliminate white space on the right of the display in the initial stages of the project. I remedied this by playing around with the CSS file until I achieved a satisfactory result.
Using the Bootstrap grid system really made the whole process much simpler for acheiving a responsive design.

### Known Bugs

-   On some mobile devices the full-color homepage image becomes distorted.


## Project deployment
The completed [project](https://cormacmccarth.github.io/Cosmepedia/) was deployed via GitHub pages.
