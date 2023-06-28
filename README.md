# **Woodworking Club**

Live Website: [Woodworking Club](https://nixts.github.io/woodworking-club/index.html)

***
## **Purpose**
Woodworking Club is a comprehensive site that provides information for individuals interested in woodworking and socializing with like-minded woodworking enthusiasts. Woodworking Club offers a diverse range of services, including beginner-courses, open workshops and exclusive member events, all under the guidance of highly skilled and experianced woodworking professionals.

With a primary focus on fostering a vibrant woodworking community, our platform appeals to seasoned craftsmen, as well as individuals with a keen interest in woodworking but limited prior experience.

At its core, this website in its current state, aims to attract new and interested members while also seeking potential donations and partnerships to keep Woodworking Club alive and thriving.

![website mock up](assets/docs/techsini.jpg)

***
## **Features**
### **Existing Features**
+ **Navigation Bar**
  + A fully responsive navigation bar that, upon clicking, jumps to the respective section.
  + Remains fixed to the top throughout the whole site to ensure consistent and easy navigation. 

+ **The landing page image with slogan**
  + Animated Hero Image with a zoom out effect to catch the users attention upon opening the site.
  + The clubs slogan blending in after the hero images animation ends to show the core principles.

![logo, navigation bar and hero image with slogan](assets/docs/website-home.jpg)

+ **What we do & Why we do it**
  + Description of what the Woodworking Club is all about, within colored text boxes to make the texts clearly separated and ease readability. 
  +  Upon reading through this section, the user will see the benefits of joining the woodworking club or making a donation.

![what we do & why we do it section with text boxes and centered image](assets/docs/website-what-we-do.jpg)

+ **About us**
  + Showcasing the team members and their skills as well as personal goals.
  + Hovering over the images makes a personal quote of each team member blend in from the top.
  + The user will experiance a positive feeling upon seeing a very skilled and passionate team that provides guidance and expertise.

![about us section with meet the team sub-section](assets/docs/website-about-us.jpg)

+ **Gallery**
  + A fully responsive masonry style gallery showcasing the workshop, members working on projects and the tools used.
  + These supporting images show how active and healty the community is.
  + The user will be able to easily identify the types of work and events the club puts together.

![masonry style image gallery](assets/docs/website-gallery.jpg)

+ **Courses**
  + This section will allow the user to see exactly when and which course will happen.
  + An interactive Google map makes the location easy to find.

![courses, dates and the location as a google map](assets/docs/website-courses.jpg)

+ **Sign up and Donate**
  + This section will allow the user to get signed up for the different courses. The user will be able to select which course they are interested in.
  + The second section will allow the user to donate either wood/materials, money, tools or other thing to the club. A description field and image upload will make it easy to describe the specific donation.
  + The user will have to insert a full name, e-mail address and select and option, respectivly add a description or upload images.

+ **Footer**
  + The footer section includes a Back to the top button to support navigation.
  + The footer is valuable to the user as it encourages them to keep connected via different social media channels.
  + A newsletter subscription box will allow the user to reaceive a monthly newsletter.

![sign up and donation form](assets/docs/website-sign-up-footer.jpg)

+ **Favicon**
  + A favicon has been added to all pages to enhance recognition in the browser.

![favicon](assets/docs/website-favicon.jpg)

+ **Thank you messages**
  + Upon clicking each submit button, the user will be redirected to a new site displaying a thank you message including a 'back to the homepage'-button

![thank you message](assets/docs/website-thank-you.jpg)

+ **404 Page**
  + In case of clicking on an incorrect or missing link, or typing an invalid path, the user will be redirected to a 404 - Page Not Found site, which includes 'Back to Homepage'-button for easy navigation.

![404 page not found site](assets/docs/website-404.jpg)

### **Features left to implement**
+ A hamburger navigation button for easier and up-to-date navigation on smaller devices such as smartphone and tablets.
+ Scroll animation for a smooth scroll when clicking a navigation element.
+ Due to its location in the heart of switzerland, a language feature for german and french would be a huge quality of life improvement for the users
+ A color pallet for browsers using dark mode
+ Due to the limitations of html and css in this project, the following features could not be added, but would improve the quality of this site significantly:
  + A login feature, user profiles and a user database
  + Automated E-Mail responses to sign-up, donation and newsletter form

***
## Technologies
+ HTML
  + This project uses HTML as the main language used to complete the structure of the Website.
+ CSS
  + This project uses custom written CSS to style the Website.
+ [Font Awesome](https://fontawesome.com/)
  + Font awesome Icons are used for the Social media links contained in the Navigation and Footer section of the website.
+ [Google Fonts](https://fonts.google.com/)
  + Google fonts are used throughout the project to import the *Roboto Condensed* and *Open Sans* fonts.
+ [Codeanywhere](https://app.codeanywhere.com/)
  + Codeanywhere is a cloud-based integrated development environment (IDE) that allows developers to collaborate, write, and execute code from anywhere.
+ [GitHub](https://github.com/)
  + GithHub is the hosting site used to store the source code for the Website and [Git Pages](https://pages.github.com/) is used for the deployment of the live site.
+ [Git](https://git-scm.com/)
  + Git is used as version control software to commit and push code to the GitHub repository where the source code is stored.
+ [iloveimg](https://iloveimg.com/)
  + iloveIMG is used to reduce the file sizes of images before being deployed to reduce storage and bandwith.
+ [Google Chrome Developer Tools](https://developers.google.com/web/tools/chrome-devtools)
  + Google chromes built in developer tools are used to inspect page elements and help debug issues with the site layout and test different CSS styles.
+ [balsamiq Wireframes](https://balsamiq.com/wireframes/)
  + This was used to create wireframes for 'The Skeleton Plane' stage of UX design.
+ [Adove Color-wheel](https://color.adobe.com/de/create/color-wheel)
  + The Adobe Color-Wheel was used to create the color theme.
+ [WebAIM Contrastchecker](https://webaim.org/resources/contrastchecker/)
  + The WebAIM contrast checker was used to check the color theme to allow  accessibility for visually impaired users.
+ [Favicon](https://favicon.io/)
  + Favicon.io was used to make the site favicon 
+ [Techsini](http://techsini.com/multi-mockup/index.php)
  + tecnisih.com Multi Device Website Mockup Generator was used to create the Mock up image in this README

***
## **Testing**
### **Strategy**
#### **Summary**
+ Testing is required on Woodworking Clubs responsive website.
+ This project is static and contains no back-end functionality, testing performed will be on the visual effects and layout of the website.
+ Testing is to be done on the most common browsers such as Chrome, Opera, Firefox, Safari and Edge.
+ Testing it to be done on the most common devices such as Samsung, Apple and Huaweii.
+ No elements should overlap another container div. All elements should remain on the screen at all sizes above 320px.
+ All images should not stretch, pixelate oder disappear on different devices, browsers or when changing the sites resolution.
+ All nav link should direct to the correct section.
+ All external links must open in a new tab.
+ Form element should open a new tab with a tank you message and a 'Back to Homepage'-button.

### **Procedure**
#### **Validator testing**
+ HTML
  + No errors were returned when passing through the official [W3C Validator](https://validator.w3.org/)
    + index.html
    + signup.html
    + donation.html
    + newsletter.html
    + 404.html
  
    ![w3c html validator testing result](assets/docs/validator-html-files.jpg)

+ CSS
  + No errors were teturned when passing through the official [W3C (Jigsaw) Validator](https://jigsaw.w3.org/css-validator/)
    + style.css

    ![w3c css (jigsaw) validator testing result](assets/docs/validator-css-files.jpg)




#### **Responsiveness**
1. Open deployed website in Chrome browser
2. Right clicking an element on the website
3. Select "Inspect Element" to open Chrome Developer Tools

Test criterias are:  
+ Does each div has enough space between one another?
+ Are all images displayed correctly?
+ Are all texts and headers corretly displayed and readable?

Testing by this method is to evaluate responsiveness on various screen sizes and swiftly address bugs and errors before implementing permanent solutions.

This test was repeated using the different browsers mentioned in the summary section above

#### **Navigation and external Links**
1. Open deployed website in different browsers mentioned in the summary section above.
2. Open deployed website on different devices mentioned in the summary section above.
3. Click on each individual navigation element
4. Clicking on each external link

Test criterias are:
+ Does each navigation element jumps to the corresponding section?
+ Does each section has enough space above it to not collide with the navigation bar?
+ Does each external link open a new tab?

### **Test by real Users**
To test the website in real life scenarios, a link to the deployed website has been sent out to Friends and Family with specific instructions on how to test each feature.

The tests have been conducted on the following devices:
+ iPhone 8
+ iPhone 11
+ Samsung Galaxy S14
+ Samsung Galaxy A52
+ Samsung Galaxy S10
+ Samsung Galaxy S20 FE
+ Samsung Galaxy Tab A7
+ Huawei P30

The instruction are as followed:
+ Is each element on screen and displayed correctly?
+ Does the navigation bar stick to the top and work as intended?
+ Is the Hero Image and slogan animation working?
+ Are all images displayed correctly an not stretched or blurred in any way possible?
+ Are the form elements working as intended? After filling out the form, does a new website with a thank you message open?
+ Does each external social media links work?

### Test Results and Resolutions
The following errors were found during extensive testing:

1. On an ultrawide monitor (width 2560px and above) the logo border and logo slogan stretch to much to each side and outside the div.

![logo stretching too much on ultrawide monitors](assets/docs/test-logo.jpg)
+ This is due the width element was set to viewport-width
+ This issue has been resolved by setting a fixed with using pixels 

2. On smaller Smartphone, when clicking a navigation element, the navigation bar cuts off the header for each section.

![navigation bar cutting off headers](assets/docs/test-navigation.jpg)
+ This is due to the scroll-margin-top setting
+ This issue has been resovled by increasing the scroll-margin-top for smaller devices

3. Images in the About us section stretch when viewed on any Apple device.
   
![stretched image on apple device](assets/docs/test-image-size.jpg)
+ This issue arises when the image height is not defined in the media query
+ This issue has been resolved by setting the image height to 'auto'

4. Users complained, that the text paragraphs contain big chunks of blank spaces between words.

![blank spaces between words](assets/docs/test-text-align.jpg)
+ This issue occurs because the 'text-align' property is set to 'justify', which stretches blank spaces to make the text have equal spacing on both sides
+ This issue has been resolved by setting the text-align to 'left'

### **Unresolved Errors, Issues and Bugs**
The following errors were found during extensive testing, but have not been resolved yet:

1. On Apple products, the legend text in the form elements slips out of the form border

![legend text slips out of border](assets/docs/test-form-legend.jpg)
+ This is due to the legend texts styling 'float: left'. This styling was used to set the text withing the form elements border, which works as intended on android and windows devices
+ This issue is resolved by wrapping the 'legend' in a 'span'

***
## **Deployment**
### **Project Creation**
The project was started by navigating to the [template](https://github.com/Code-Institute-Org/gitpod-full-template) and clicking 'Use this template'. Under Repository name I input woodworking-club and checked the Include all branches checkbox. I then navigated to the new [repository](https://github.com/NixTS/woodworking-club). I then clicked the Code drop down and selected HTTPS and copied the link to the clipboard.

Opening [Codeanywhere](https://app.codeanywhere.com/) and clicking "New Workspace", I then pasted the [repository link](https://github.com/NixTS/woodworking-club) into the URL field and clicked "Create". The following commands were used throughout the project:

+ git add filename - This command was used to add fils to the staging area before commiting.
+ git commit -m *commit message explaining the updates* - This command was used to to commit changes to the local repository.
+ git push - This command is used to push all commited changes to the GitHub repository.

### **Using Github Pages**
1. Navigate to the GitHub [Repository:](https://github.com/NixTS/woodworking-club)
2. Click the 'Settings' Tab.
3. Scroll Down to the Git Hub Pages Heading.
4. Select 'main Branch' as the source.
5. Click the Save button.
6. Click on the link to go to the live deployed page.

### **Run Locally**
1. Navigate to the GitHub [Repository:](https://github.com/NixTS/woodworking-club)
2. Click the Code drop down menu.
3. Either Download the ZIP file, unpackage locally and open with IDE (This route ends here) OR Copy Git URL from the HTTPS dialogue box.
4. Open your developement editor of choice and open a terminal window in a directory of your choice.
5. Use the 'git clone' command in terminal followed by the copied git URL.
6. A clone of the project will be created locally on your machine.

***
## **Credits**
### **Content**
+ The content of this website was created by [Tobias Schmauder aka. NixTS](https://github.com/NixTS).
+ The overlay-hover animation in the Abous us section -> meet the team was created by my girlfriend [Valentyna](https://github.com/kayavalentina)
+ The icons in the navigation and footer were taken from [Font Awesome](https://fontawesome.com/)

### **Media**
+ All images found on this website are from [Pexels](https://www.pexels.com/)

### **Acknowledgements**
I'd like to thank my mentor Daisy McGirr for her guidance throughout my project, and mention her very helpful [Youtube](https://www.youtube.com/@IonaFrisbee) channel.

Thanks to all my testers for their time and effort to provide me with valuable feedback.

I'd also like to give a special mention to my girlfiiend [Valentyna](https://github.com/kayavalentina) who provided me with fedback throughout my project. Also her time and effort to keep errands off my shoulders, so i have more time to finish my project.
