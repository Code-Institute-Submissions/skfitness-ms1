# [SK FITNESS](https://shanekennyb.github.io/skfitness-ms1/)  

**Note this is not a real website and was built as a project website for my Code Institute MS1.**

SK FITNESS is a newly built state of the art gym situated on the outskirts of Limerick City in Clarina.
It targets members of all ages to come and join our friendly gym community.

![Sk Fitness mockup](images/am-i-responsive.png)  

You can view the live site here [https://shanekennyb.github.io/skfitness-ms1/]

# User Experience (UX)  

1. Strategy   

    This website is designed in a mobile first approach, it is designed so the user can navigate throughout the site with lots of call to action buttons.
    User Stories:  
---   
    * "As a user I would like to navigate easily throughout website"  
    * "As a user I would want to check class times"  
    * "As a user I want to know about the gyms facilities"  
    * "As a user I would like to check membership prices"  
    * "As a user I would like to contact the gym"

    Project Goals:  
  
    * A fully functional website with a fixed navigation bar so user can easily access each landing page.
    * A class timetable with classes/times/days.
    * A gallery page where visitors can see the gyms facilities.
    * A list of our price range for students and adults.  
    * A contact page where users can contact gym and write a short message to us.  

2. Scope  

3. Structure  

4. Skeleton  

    ## Wireframes 
    --- 
    * [Wireframes Home page](wireframes/Wireframe-home.pdf)  

    * [Wireframes Classes page](wireframes/Wireframe-classes.pdf)  

    * [Wireframes Gallery page](wireframes/Wireframe-gallery.pdf)  

    * [Wireframes Contact page](wireframes/Wireframe-contact.pdf)  

    * [Wireframes Log In modal](/wireframes/Wireframe-login.pdf)  

5. Surface

    ## Design
    --- 
    * Colours  
        * Background color of grey - #34393B  
        * Header and footer color - #0f0707
        * All text shade of white - #FAFAFA  
        * Buttons colour of red - #dc3345

    * Typography  
        * I have chosen Lato font all headings.
        * I have chosen Roboto for all content with a fall back of sans serif.

    * Images - All images sourced from [Unsplash](https://unsplash.com/) and [Pixabay](https://pixabay.com/) 
        * My hero image will be a picture if a man and woman working out together in the gym.
        * Images in my gallery will show memebers working out in the gym and also gym facilities.

## Features  
--- 
* 4 page website with a home/classes/gallery/contact pages.  
* Fixed navigation bar to allow users to navigate easily throughout site.  
* Fixed footer on mobile devices with links to gyms social media pages.  
* Image carousel with images from gym.  
* Contact form for users to message gym.  
* Fully responsive site.  

## Features left to implement  
--- 
* In the future would like to add a sign up page where user's can create an account.  
* I would also like to have a booking system where users can book a class.

## Technologies Used
--- 
### Lanuages Used
* [HTML5](https://en.wikipedia.org/wiki/HTML5)   

* [CSS3](https://en.wikipedia.org/wiki/CSS)  

### Frameworks | Libraries | Programs Used

* [Bootstrap](https://getbootstrap.com/docs/4.5/getting-started/introduction/)  

* [Font Awesome](https://fontawesome.com/)  

* [Google Fonts](https://fonts.google.com/)  

* [jQuery](https://jquery.com/)  

* [Git](https://git-scm.com/)  

* [GitHub](https://github.com/)  

* [GitPod](https://www.gitpod.io/)

## Resources  
* [Balsamiq](https://balsamiq.com/)  

* [Unsplash](https://unsplash.com/)  

* [Pixabay](https://pixabay.com/)

* [Coolers](https://coolors.co/)  

* [W3schools](https://www.w3schools.com/)   

* [Stack overflow](https://stackoverflow.com/)  

* [CSS-TRICKS](https://css-tricks.com/)

## Testing  
--- 
### Functionality Testing

| Test          | Action        | Expected Outcome          | Result
| ------------- |:-------------:| -------------:| -------------:
| Nav Bar test      | Click on nav links | Open each page         | Pass
| Log In button test      | Click on log in button      |   Open modal for log in         | Pass
| Modal close button | Click on modal close button      |   Close modal         |       Pass
| Check required when there is an empty input field in modal | Leave an input field blank | A required pop up message | Pass
| Check page logo + name anchor | Click on logo | Take you to home page | Pass
| Check classes CTA in our facilities section | Click on classes | Take you to classes page | Pass
| Check gallery CTA in our facilities section | Click on gallery | Take you to gallery page | Pass
| Check contact CTA in contact info section | Click on contact | Take you to contact page | Pass
| Check social media icons | Click on each icon | Open a new page for each social media icon | Pass
| Check each input field on contact page | Type text into each section | Text enters each field | Pass
| Check required when there is an empty input field in contact us section | Leave an input field blank | A required pop up message | Pass  

### Browser Compatibility  

* Checked website on google chrome with no errors  
* Checked website on firefox with no errors
* Checked on Microsoft Edge with no errors  

### Responsiveness  

For Responsiveness i payed special attention to screen size as small as iphone 5 and large screens upto 5120px x 2880px (Imac Pro)  
* On iphone 5 website worked as i wanted it to  
* Tested on my iphone 8 and found text overflow on one of my about divs changed div height to fix this  
* Everything worked fine on ipad screen size  
* Everything worked fine on desktop screen size  
* On xx-large screen (5120px x 2880) there was some spacing issues and text was too small, to rectify this I set a new media query for larger screens  

### Code Validation  

* Checked my html code on [W3 https://jigsaw.w3.org/css-validator/](https://validator.w3.org/) which showed no errors.  
* Checked my CSS code on [W3 https://jigsaw.w3.org/css-validator/](https://jigsaw.w3.org/css-validator/) which show no errors.
Showed 4 warnings. 
1. 'Imported style sheets are not checked in direct input and file upload modes' googled this and found someone else had asked this 
on [Stack Overflow](https://stackoverflow.com/questions/25946111/importing-css-is-ending-up-with-an-error) and that this is not a problem.  
2. '-moz-transition is an unknown vendor extension'  
3. '-webkit-transition is an unknown vendor extension'  
4. '-o-transition is an unknown vendor extension'  
-Again googled these warnings and am happy there is no problem.  

### Other Testing  

* Check all spellings on [Free Online Spell Checker](https://www.online-spellcheck.com/)  
* Website speed check on [Uptrends](https://www.uptrends.com/) and passed with a very good speed score.

### User Stories  

* I can navigate easily throughout the website  
* I can check class times on the class timetable  
* I can check about facilities in our facilities section and can look at the gallery page to see pictures  
* I can check the classes page for different prices  
* I can contact the gym about any message I have on the contact us page

## Known Bugs + Solutions  
---  

* When I opened my classes.html page on mobile my class timetable was too big to fit screen.  
To rectify this problem I created 3 separate timetables, one for each class time.  

* When I opened modal log in and close button displayed to the right side.  
To rectify this I set a width value for modal footer.  

* My footer was not staying at the bottom of website.  
To rectify this I set the position of footer to absolute.

## Deployment  
---  

This website was hosted on GitHub pages, follow the steps below to access:  
* Firstly go to my [GitHub](https://) repository.
* Click on **settings** at the top of page.
* Scroll down to **GitHub Pages** heading.
* Click on the dropdown menu and select **master branch**.
* The pages will then refresh.
* Then scroll down to **GitHub Pages** again and it will say *"your site is published at"* with a link to site.
* The code can be run through *clone* or *download*.
* To do this open the repository, click on the green **code** button and then select either **clone** or **download**.
* If you select clone this will provide a url which you can use on your software IDE.
* If you select download option this will provide a link to download a ZIP file which
can be opened on your local software.


## Credits  
---  

### Code Credits  

* Nav bar, timetable, modal and carousel code taken from [Bootstrap](https://getbootstrap.com/docs/4.5/getting-started/introduction/)  
* Footer social icon design taken from Rosie project on [Code Institute](https://codeinstitute.net/)  
* The wireframes were created on [Balsamiq](https://balsamiq.com/)  
* Colours were chosen on [Coolers](https://coolors.co/)  
* Images for hero image and carousel gallery were taken from [Unsplash](https://unsplash.com/) and [Pixabay](https://pixabay.com/)  
* All fonts on website were taken from [Font Awesome](https://fontawesome.com/)  

### Acknowledgements

* Credit to my mentor Brian Macharia who gave me some great advice throughout this project  
* Credit to Jim Lynx who created a great information video on slack  
* Credit to the slack community who are always very helpful  
* Credit to CI (Code Institute) for all there help throughout



