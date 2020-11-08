**


![Image](assets/images/dslogo.png)

**

**DoggyStyle website**
==================




Table of content:
-----------------



 - Description
 - UX
	 - User Stories 
	 - Strategy
	 - Scope
	 - Structure
	 - Skeleton
	 - Surface
 - Technologies
 - Testing
 - Deployment
 - Credits



Description
-----------

DoggyStyle is a website for a dog grooming company. This site showcases the clients work and offers a platform for clients to view prices and book appointments. The live site can be viewed here.
This site was designed as a project to be submitted for grading in the first milestone project in Full Stack Software Development with the Code Institute. 

UX - User Experience
--------------------


----------


**USER STORIES**


----------


External User Goal:  (In order of priority):

 1. As an external user, I want to find contact details for a dog
    groomer.
 2. As an external user, I want to make a booking for my dog to be
    groomed.
 3. As an external user, I want to see examples of work done by the dog
    groomer.
 4. As an external user, I want to check the prices for the grooming
    services.
 5. As an external user, I want to see what services are offered.
 6. As an external user, I want to see where the dog groomers is
    located.
 7. As an external user, I want to be able to view the site on my mobile
    phone or tablet.

Site Owner Goal:

 1. As the site owner, I would like to offer a portal for clients to
    book appointments.
 2. As the site owner, I would like to advertise my contact details and
    location.
 3. As the site owner, I want to increase the profile of my business and
    have a website I can direct potential customers.
 4. As the site owner, I would like to display my prices and services.
 5. As the site owner, I want to showcase the work that I do.


The mockup for this site was done on Adobe Xd. 
[https://xd.adobe.com/view/f6aca366-5b35-47df-9ab1-72c1e0584183-a3ff/](https://xd.adobe.com/view/f6aca366-5b35-47df-9ab1-72c1e0584183-a3ff/)


----------


**STRATEGY**

--------

 - Focus: The main focus of this project is to provide a portal for the
   client to increase their bookings and make it easier for their
   customers to get in touch.
 - Definition: We’ll be creating a website that has a very simple layout
   and, with as little effort as possible allows the users navigate and
   make contact with the business. As this may be the users first
   interaction with the business we want to present a clean, fresh and
   seamless experience. It is important to make a good first impression
   assuring the user that they are in the hands of a caring,
   professional business that will be looking after their dog.
 - Value: Creating an clean and simple portal with multiple avenues to
   initiate contact with the business should make it easier to increase
   interactions with new customers whilst increasing the profile of the
   business. This site will also offer the business a legitimate online
   location where they can direct potential clients to view their work,
   services and prices.


----------


**SCOPE**


----------


Features: 

 - Navigation menu – a simple navigation menu offering the user the
   ability to access the areas mentioned in the users, namely, Prices,
   Gallery and Contact.

 - Footer - There will be a footer containing contact detail, social links and another call to action. 
All the of the pages on the site will have the same header and footer elements, background and imagery. Once the home page is created, this template will be duplicated adding in the unique sections for each page. These will be:
 - Home pages - Sales message containing text with a button below to initiate contact. 
 - Contact pages – a contact form requesting name, address, phone number and a comment section. 
 - Gallery - A gallery containing a selection photographs
 - Prices page - A text window on the prices pages containing the text of the business prices. 

Constraints:
Working with HTML and CSS I will be able to meet the needs of the client as well as tackling each of the scenarios in the user story effectively. However using these technologies alone will limit the site to CSS animations which will be effective but basic. We will not be able to add a google maps window to the contact pages as this requires the use of technologies (Javascript) outside the scope of this project. 


----------


**STRUCTURE**


----------


The site must be structured in a way in order to effectively achieve the main goals of the client. Working off the list of priorities as well as user stories it was decided that the main focuses of the site will be,

 1. Call to action – sales message with booking button.
 2. Prices and services available.
 3. Evidence of work – gallery of past work.

With this in mind we will focus on drawing the eye of the user to the main sales message on the home page, creating an effortless flow towards the initiation of contact. Contact details will also be available on the lower left corner and a contact button in the centre of the footer of every page. 
The prices sections will be clearly labelled on the main page in the navigation menu and once click will open a clear list of services and associated prices.
The gallery will be equally as visible on the main navigation menu opening up a selection of photographs for the user to scroll through. 
Here is a link to a mockup of the website created with Adobe Xd – DoggyStyle Mockup [https://xd.adobe.com/view/f6aca366-5b35-47df-9ab1-72c1e0584183-a3ff/](https://xd.adobe.com/view/f6aca366-5b35-47df-9ab1-72c1e0584183-a3ff/)


----------


**SURFACE**


----------


Given the nature of this business, image is quite important so the aesthetic of the site must reflect that. 
Colours: 

 - To achieve a fresh clean image we will be using a palette of greens
   blues, white and grey.

Typography: 

 - Holtwood One SC font is used on the main logo and will be repeated in
   the menu items in the navigation bar and Sans Serif as the backup
   font.
 - Roboto will be used for content in the main body of the page with
   Sans Serif as the backup. I chose Roboto for its clean line and as it
   pairs nicely with Holtwood One SC.

Effects:

 - To offer feedback on the buttons I will be incorporating a shadow
   effect which disappears when clicked to give the impression of a 3
   dimensional button.
 - I will also have a hover effect over the menu items in the navigation
   bar using Font Awesome icons offering the use more feedback on what
   they are about to click.
 - The active page will also display the Font Awesome icon to indicate
   to the user which part of the site they are currently on.

Imagery: 

 - We will use an image of a field, the sky, clouds and some flowers as
   the background. This will be framed by a soft grey on the bottom and
   a white on top and will be repeated on each page. The image will be
   simple as to avoid any distraction from the main message on the page

Technologies
----------------

 - HTML5 – I used HTML to create the websites main structures
 - CSS3. – I will use CSS to style the components created with HTML and
   create the desired effects described in the ‘Surface’ section.
 - Bootstrap – I decided to use Bootstrap in order to create structures
   on the site and ensure responsiveness.
 - FontAwesome  - The icons from this library are used for the
   navigation icons
 - Google Fonts – Roboto and Holtwood One SC are imported from here.
 - GitPod – IDE used for working on my code
 - GitHub – Used for hosting the files used for the website.
 - Git – Version control used to track changes, commit and push code to
   Github.
 - Gitpod extensions:
	 - Auto Close Tag
	 - Bracket Pair Colorizer
	 - Code Spellchecker
	 - Prettier - Code Formatter
	 - Indent-Rainbow




Testing
-------


Bugs
-------
Site logo shift from left to right hand side of screen when width of screen drops below 992px.
-Changed position to absolute and positioned left and top to 0.

contact button in footer covers the Phone number and email section when screen goes below 578px.
-set contact details to display:none as the footer was too cluttered. 

Contact button is sitting a few pixels off center to the right.
-



Deployment
----------



Credits
-------

**Code used**

https://getbootstrap.com/docs/4.0/components/navbar/ for my navbar

 I found this bit of code on stackoverflow which helped me understand how to display the active page link. 
https://stackoverflow.com/questions/17318170/highlighting-the-current-page-in-a-list-of-links-using-css-html 

**Content**
Image used for site icon https://www.clipartmax.com/middle/m2K9A0A0i8m2m2d3_bathroom-bath-clipart-free-download-clip-art-on-bathing-clip-art/

The background image for the website - https://all-free-download.com/free-vector/download/spring-background_310720.html

Images for gallery were taken from  https://unsplash.com/



**Acknowledgements**

