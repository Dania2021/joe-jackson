# Joe Jacksons Ice Cream Website
![Screen shot of Joe Jacksons Ice Cream Website](/assets/readme-files/joe-jackson-img.JPG "Joe Jacksons Ice Cream Website")
Joe Jacksons Ice cream is located in Letterkenny, co Donegal. Joe Jackson Ice Cream is designed to view variety of homemade gelato ice cream flavours, ice cream cakes, sundae and milkshakes. They make their ice cream in small batches and have variety of flavours. 

The website is designed to be responsive so that it is user-friendly and looks appealing on any device.

Visit the live project [here](https://dania2021.github.io/joe-jackson/)

Find the Project Repository [here](https://github.com/Dania2021/joe-jackson)

## Table of Contents
* [User Experience](#user-experience)
  * [Project Goals](#project-goals) 
  * [User Stories](#user-stories)


* [Design](#design)
  * [Colour Scheme](#colour-scheme)
  * [Typography](#typography)
  * [Imagery](#imagery)
  * [Icons](#icons)
  * [Wireframes](#wireframes)

* [Features](#features)
  * [General](#general)
  * [Home Page](#home-page)
  * [Icecream Page](#icecream-page)
  * [Explore Page](#explore-page)
  * [Contact Page](#contact-page)
  * [Thankyou Page](#thankyou-page)
  * [404 Page](#404-page)

* [Technologies Used](#technologies-used)
  * [Language Used](#languages-used)
  * [Framework, Libraries & Programs Used](#framework-libraries--programs-used)

* [Testing](#testing)
  * [Validator Tests](#validator-tests)
  * [Lighthouse Tests](#lighthouse-tests)  
  * [Tools Tests](#tools-test)
  * [Manual Testing](#manual-testing)
  * [Bugs](#bugs)

* [Deployment](#deployment)
  * [Project Deploymant via GitHub Pages](#project-deloyment-via-github-pages)
  * [How to Fork](#how-to-fork)
  * [How to Clone](#how-to-clone)

* [Credits](#credits)
  * [Code](#code)
  * [Content](#content)
  * [Media](#media)

* [Acknowledgements](#acknowledgements)


## User Experience (UX)

 ### Project Goals
 * The goal of this website is to give information about home made gelato ice cream. 
 * Information needs to be correct and displayed in a intuitive and user friendly way.
 * To serve those who prefers to eat vegan ice creams.
 * A website with unique flavours of ice cream.
 
 
 ### User Stories
 * As a user to be able to understand the purpose of Joe Jacksons Ice Cream from the main landing page.
 * As a user to be able to see flavours of ice cream and ice cream cakes with name, image and description.
 * As a user to be able to see make your own sundae, milkshakes and chocolate bar shake with name, image and description.
 * As a user allow to sign up to receive updates of new flavours, promotion and news.
 * As a user want to connect various social media sites quickly and easily.
 * As a user to be able to view the site on a range of device sizes.

 ## Design

 ### Colour Scheme
 ![Colour palette](/assets/readme-files/palette.JPG "Colour palette")
* A Simple and refined colour schemes are used.
* Pale backgrounds are used so that image takes center stage.
* Header and footer are bright in colour to distinguishes those sections from other on the page.
* Colour palette was created by using [Coolers](https://coolors.co/).

### Typography

Google Fonts was used for the following fonts:
* Montserrat is used for headings on the site. It is a serif font.
* Nota Serif is used for the body text on the site. It is a sans-serif font.

### Imagery

The images were used with the permission of owner and I have credited these in credit section.

### Icons

I used icons from Font Awesome to encourage users to click on buttons and to add clear visual indicators to sections on the Icecream page and Explore page.

### Wireframes

Wireframes were created for desktop, tablet and mobile.

[Home page Wireframe](/assets/readme-files/wireframes/wireframe-home.png)

[Ice Cream Wireframe](/assets/readme-files/wireframes/wireframe-icecream.png)

[Explore Wireframe](/assets/readme-files/wireframes/wireframe-explore.png)

[Contact Wireframe](/assets/readme-files/wireframes/wireframe-contact.png)

## Features

The website is comprised of five pages, four of which are accessible from the navigation menu (home page, icecream page, explore page and contact page). The fifth page is a thank you page which is shown once a user submits the form on the contact us page.

* ### General
  All Pages on the website have:

  * A responsive navigation bar at the top which allows the user to navigate through the site. To the left of the navigation bar is an image of joe jacksons logo together with the text Joe Jacksons Ice Cream. To the right of the navigation bar are the links to the websites pages (home, icecream, explore and contact). To allow a good user experience of the site, Joe Jacksons Ice Cream text is hidden with a media query on mobile devices to prevent the navigation bar looking cluttered. When viewing with mobile devices the navigation links change to a burger toggler. This was implemented to give the site a clean look and to promote a good user experience, as users are used to seeing the burger icon when on mobile devices to navigate a site.

  ![Screen shot of navbar](/assets/readme-files/navbar-img.JPG)

 
  * A footer which contains address of Joe Jackson Ice cream, social media icon links to facebook and instagram. Social media links open to new page and icons were used to keep the footer clean and because they are universally recognisable.
  
  ![Screen shot of footer](/assets/readme-files/footer-img.JPG)

* ### Home Page

    * Carousel Section: The carousel shows images of ice cream.

     ![Screen shot of carousel](/assets/readme-files/carousel-img.png)

    * Scoop Range Section: This section feature button with 'call to actions' that quickly directing user to relevant information on ice cream page.

    * Sundae Bar Section: This section feature button with 'call to actions' that quickly directing user to relevant information on explore page.

    * Contact Section: This section feature  button with 'call to actions' that quickly directing user to relevant information on contact page.

      ![Screen shot of carousel](/assets/readme-files/section-img.png)

      Buttons are consistent in design across the site. Buttons feature a right arrow to encourage them to click and be taken to a new page. Buttons change colour when hovered over. The button text is legible both in its normal and hover state. I have used Bootstrap Button classes, which I have customised in the CSS.

* ### Icecream Page

    * The Icecream and Explore pages features heading and sub-navigation. ID names are used to allow the user to jump to the content. This helps the user to quickly find the section that they are looking for. When hovered on sub-navigation an underline appears underneath the link. This further emphasises that this is a clickable link.Aria-labels are used to make their purpose clear to screen readers.   

    * The first section of Icecream page is scoop section. This section is comprised of listing of scoop and splits into eighteen different variety of scoop. The section uses the same reusable CSS classes from the previous pages to make the information styling consistent with previous pages.   


    ![Screen shot of Icecream Page with heading, sub-navigation and scoop](/assets/readme-files/icecream-img.png)


    * The next section is Icecream Cakes, features information about icecream cakes. This section is comprised of listing of cakes and describes two types of icecream cakes.


    ![Screen shot of Icecream Page with Ice cream cake](/assets/readme-files/icecream-cake-img.png)

  
    * Back to top button appears at the bottom of the Icecream and Explore page and saves the user needing to scroll back up to the top of page. The button features an 'up' arrow, to make it clear that it will quickly send users back to the top of the page.


    ![Screen shot of back to top button](/assets/readme-files/back-to-top.png)


* ### Explore Page

   This page provides information about Sundae Bar, Millkshake Bar And Chocolate Bar Shake. The section uses the same reusable CSS classes from the previous pages to make the information styling consistent with previous pages, but size of images are different from the previous page.   


    ![Screen shot of Explore Page with Sundae Bar](/assets/readme-files/explore-img.png)


* ### Contact Page

   This page provides information about opening times, address, get in touch and a map. This page also provides Newsletter that have a sign up form to submit.Tha map section is originally sourced from Coders Coffee House Project.


    ![Screen shot of Contact Page with Sign up form](/assets/readme-files/contact-img.png)


* ### Thankyou Page

  An image and message thanks the user for submitting the form and lets them know someone will be in touch soon.


    ![Screen shot of Thankyou Page](/assets/readme-files/thankyou-img.png)


* ### 404 Page 
 
  I created 404 page in my repository by [GitHub Documentation](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-custom-404-page-for-your-github-pages-site). The 404 page features a message  to help the user navigate back to the hompage if they enter an incorrect URL and this page also have an image.

     ![Screen shot of 404 page](/assets/readme-files/404-img.png)



## Technologies Used

   * ### Languages Used

     HTML and CSS were used to create this website.

   * ### Framework, Libraries & Programs Used

     Balsamiq - Used to create wireframes.

     Font awesome - Used icons from font awesome to visually distinguish sections of the text and on buttons.

     Google Fonts - To import the fonts used on website.

     Git - Used for version control.

     Github - Used to save and store the files for website.

     [Bootstrap Version 5.2.0](https://getbootstrap.com/docs/5.0/getting-started/introduction/) - Sourced code from the Bootstrap documentation when building the Navbar, Carousel, Sections, Buttons and Contact Form were used and modified.

     Google Dev Tools - Used while building the project to test responsiveness and for debugging.

     [Birme](https://www.birme.net/?target_width=900&target_height=900&image_format=webp)  To change to webp format and resize images.

     [Favicon](https://favicon.io/)  To create favicon.

     [Am I Responsive?](https://ui.dev/amiresponsive?)  To show the website image on a range of devices.


## Testing 


  * ### Validator Tests   

    The W3C validator was used to validate the HTML on all pages of the website. It was also used to validate CSS in the style.css file.

    * Index Page HTML

    ![Screen shot of Index page Validator](/assets/readme-files/testing/w3c/index-img.png)

    * Icecream Page HTML

    ![Screen shot of Icecream page Validator](/assets/readme-files/testing/w3c/icecream-img.png)

    * Explore Page HTML

     ![Screen shot of Explore page Validator](/assets/readme-files/testing/w3c/explore-img.png)

    * Contact Page HTML

     ![Screen shot of Contact page Validator](/assets/readme-files/testing/w3c/contact-img.png)

    * Thankyou Page HTML

     ![Screen shot of Thankyou page Validator](/assets/readme-files/testing/w3c/thankyou-img.png)

    * 404 Page HTML

     ![Screen shot of 404 page Validator](/assets/readme-files/testing/w3c/404-img1.png)

    * style.css CSS

     ![Screen shot of  style.css Validator](/assets/readme-files/testing/w3c/css-img.png)


  * ### Lighthouse Tests 

     Joe Jackson Ice Cream was also tested through Chrome Dev Tools - Lighthouse. It was tested on four main areas - Performance, Accessibility, Best Practices and SEO.

     Index Page

      * Lighthouse testing for desktop Index Page

      ![Screen shot of  desktop Index page lighthouse test](/assets/readme-files/testing/lighthouse/index-desktop.png)

      * Lighthouse testing for mobile Index Page

      ![Screen shot of  mobile Index page lighthouse test](/assets/readme-files/testing/lighthouse/index-mobile.png)

     Icecream Page

      * Lighthouse testing for desktop Icecream Page

      ![Screen shot of  desktop Icecream page lighthouse test](/assets/readme-files/testing/lighthouse/icecream-desktop.png)

      * Lighthouse testing for mobile Icecream Page

      ![Screen shot of  mobile Icecream page lighthouse test](/assets/readme-files/testing/lighthouse/ice-cream-mobile.JPG)


     Explore Page

      * Lighthouse testing for desktop Explore Page

      ![Screen shot of  desktop Explore page lighthouse test](/assets/readme-files/testing/lighthouse/explore-desktop.png)

      * Lighthouse testing for mobile Explore Page

      ![Screen shot of  mobile Explore page lighthouse test](/assets/readme-files/testing/lighthouse/explore-light-house-mobile.JPG)

     Contact Page

      * Lighthouse testing for desktop Contact Page

      ![Screen shot of  desktop Contact page lighthouse test](/assets/readme-files/testing/lighthouse/contact-desktop.png)

      * Lighthouse testing for mobile Contact Page

      ![Screen shot of  mobile Contact page lighthouse test](/assets/readme-files/testing/lighthouse/contact-mobile.png)

     Thankyou Page

      * Lighthouse testing for desktop Thankyou Page

      ![Screen shot of  desktop Thankyou page lighthouse test](/assets/readme-files/testing/lighthouse/thankyou-desktop.png)

      * Lighthouse testing for mobile Thankyou Page

      ![Screen shot of  mobile Thankyou page lighthouse test](/assets/readme-files/testing/lighthouse/thankyou-mobile.png)

     404 Page

      * Lighthouse testing for desktop 404 Page

      ![Screen shot of  desktop 404 page lighthouse test](/assets/readme-files/testing/lighthouse/404-desktop.png)

      * Lighthouse testing for mobile 404 Page

      ![Screen shot of  mobile 404 page lighthouse test](/assets/readme-files/testing/lighthouse/404-img.png)

  * ### Tools Test

      * Chrome DevTools

        Chrome DevTools was used during the development process to test, explore and modify HTML elements and CSS styles used in the project.

      * Responsiveness

        [Am I Responsive?](https://ui.dev/amiresponsive?) was used to check responsiveness of the site pages across different devices.
        
  * ### Manual Testing 

      * Browser Compatibility
        
         I performed the following testing using a number of browsers (google chrome, safari, mozilla firefox). There were no visible errors in appearance or functionality

      * Devices Compatibility

         I performed the following testing using a number of devices (Samsung Galaxy S8, iPhone 7, Hp Pro 15 inch)
            

      * Common Elements Testing

         * All Pages

           1. Header

              Clicking on the main logo will bring the user back to the landing page.

           2. Navigation Bar
              
              * Hovering on the different navigation bar's links will trigger hover effect, highlighting the link for the user with an underline.

              * Clicking on the navigation bar's links will bring the user to the specified page.

           3. Footer

              Clicking on the social media links leading to external pages opened correctly in a seperate browser tab.    

         * Index Page

            * On the index page there is a section titled 'Scoop Range' with a button users can click to take them to the Icecream page.

            * On the index page there is a section titled 'Sundae Bar’ with a button users can click to take them to the Explore page. 

            * On the index page there is a section titled 'Contact Us’ with a button users can click to take them to the Contact page.
               

         * Icecream Page

            1. When click on the sub-navigation the user move among related section within the same page.

            2. When user click on bottom to top button it will take to top of the page.

         * Explore Page     

              When click on the sub-navigation the user move among related section within the same page.

         * Contact Page   
               
              1. I tried to submit the form without filling in any input fields. The form worked correctly and directed users to fill in the first name field. I then filled in the first name field and tried to submit the form. Again the form worked correctly and directed the user to fill out the last name field. The form worked correctly and directed the user to fill out the email address field. I filled out the first name, last name and email address and tried to submit the form. The form worked correctly and asked the user to fill in the message field. I filled out the first name, last name, email address and message field and tried to submit the form. The form then opens the thank you page in the same browser window.

              2. Hovering over the submit button will trigger hover effect, highlighting the button for the user.

         * 404 Page

              1. Entering an incorrect address into the address bar will bring the user back to the 404 error page.

              2. Clicking on the logo or using the navbar will bring the user back to landing page.

    * ### Bugs

      * Resolved
       
       1. The navbar would lose its alignment when on smaller devices, with the navbar brand pushing the logo and text down. This did not make for a good user experience. While searching through the bootstrap documentation for navigation bars it directed me to display properties and hiding elements. Once I added the correct class I was then able to hide the text beside logo on devices smaller than a tablet, allowing the alignment of the navbar items to stay in place where I wanted them.
      
       2. When the Contact HTML code is submitted to W3C HTML validator for testing, it produced an error. The testing programming flagged a [bad width on iframe](/assets/readme-files/testing/lighthouse/error.JPG) then I resolve the error by giving value to width and height through ID of iframe.

       3. When the site was tested by Google Chrome Lighthouse tester. It flagged serve images in next gen format. Performance was only measuring at an average of 64%. Lighthouse suggest to [serve image formats](/assets/readme-files/testing/lighthouse/error-msg.JPG) like Webp and AVIF to improve compression and lead to faster download and less data consumption. I have now converted logo, slides images and all the other images in webp format using Birme.

       4. The carousel displayed fine on small screen devices. however when viewed on larger devices you would need to scroll down to see the entire image, which led to a bad user experience. By using media queries I targeted the large screen size and targeted the carousel item image to only take up 90% of the viewport height. This solved the issue by allowing the user to view the image without having to scroll, but the image was now being stretched across the screen. I searched google and stack overflow and it mentioned using object fit and added object-fit: contain to the css which allows the image to correctly maintain its aspect ratio and view correctly.

      * Unresolved
    
      Using just HTML and CSS to create a website has its shortcomings. Unfortunately without knowledge of other languages, contact form on Joe Jacksons Ice Cream have no functionality. Although it seem to accept data but it doesnot send the data to any back-end database. This can be resolved with the knowledge of the back-end languages.
        

## Deployment

  * ### Project Deloyment via GitHub Pages

    The Joe-Jackson repository is stored on GitHub. The site was created using GitPod and the live site is hosted on GitHub Pages. This is a guide to deploy a site on GitHub Pages using GitHub.

    1. Log in (or sign up) to Github.
    2. Find the repository for this project, Joe-Jackson.
    3. Click on the Settings link.
    4. Click on the Pages link in the left hand side navigation bar.
    5. Under source, select branch:main, leave the folder on root and click save.
    6. Your live Github Pages site is now deployed at the URL shown.

  * ### How to Fork

    To fork the Joe-Jackson repository:

    1. Log in (or sign up) to Github.
    2. Locate the repository and click to open the repository.
    3. Click the Fork button in the top right corner.

  * ### How to Clone  
      
    To clone the Joe-Jackson repository:

    1. Log in (or sign up) to GitHub.
    2. Locate the repository and click to open the repository.
    3. Click on the code button, select whether you would like to clone with HTTPS, SSH or GitHub CLI and copy the link shown.
    4. Open the terminal in your code editor and change the current working directory to the location you want to use for the cloned directory.
    5. Type git clone into the command line and then paste the URL copied from GitHub.
    6. Press enter and the local repository clone will be created.  


* ## Credits

  ### Code

  * [Bootstrap 5.2.0](https://getbootstrap.com/docs/5.0/getting-started/introduction/) : Bootstrap library was used throughout the project mainly to make it responsive. I have used and modified code from the Bootstrap documentation when building the Navbar, Carousel, Sections, Buttons and Contact Form.

  * [Code Institute](https://codeinstitute.net/ie/) : I referred to source code from Code Institute's Web Application Development course. I referred to the Coders Coffee House Project code for the google maps iframe.

  ### Content
   
   All the content and information was collated from [Joe Jackson Ice Cream Facebook Page](https://www.facebook.com/joejacksonsletterkenny/)

   ### Media

  * Carousel image on the index page of slide 2, Scoop Range image on index page, Mango Ice Cream on Icecream page and image on Thankyou page are from [Pexels](https://www.pexels.com/).

  * Other than that all the images were used from [Joe Jackson Ice Cream Facebook Page](https://www.facebook.com/joejacksonsletterkenny/).


* ## Acknowledgements  

  

  
   
