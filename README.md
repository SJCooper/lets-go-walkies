# Let's Go Walkies

Let's Go Walkies is a site that introduces people and their pets to a dog hiking group based in the north west of england. The site offers open and free information regarding events and allows people to sign up for event newsletters and updates. Let's Go Walkies is aimed at dog owners that enjoy socialising their pets and those who might prefer group walks and hikes as oppose to solitary ones. The aim of the site is to aid the growth of the community and to give dog walkers potential new ideas as to suitable dog friendly areas to take their dogs.

![mockup-min](https://user-images.githubusercontent.com/7358665/155905892-1be8d31c-365a-47e7-a995-319c3644f742.png)

## Design And Planning

### Wireframes

- __Original Design__

  - The original wireframe for the site was created using Balsamiq. 
  - Whilst the finished site evolved drastically from the original sketched out wireframes, they provided a starting part for the sites creation.
  - The wireframe aided in the creation of the basic html structure which other elements were added to throughout the design process.

<img width="1532" alt="balsamiq-wireframe-min" src="https://user-images.githubusercontent.com/7358665/155908181-466044e3-89b6-46db-ba9b-7fe32cf2f71e.png">

- __Color Swatch__

  - The chosen colors for the site were chosen to emphasize the nature based theme of the group. 
  - The colors were checked initially to make sure their contrast would be adequate in terms of readability using https://webaim.org/resources/contrastchecker/

![color-palette](https://user-images.githubusercontent.com/7358665/155908581-1d598bc1-b671-49ed-86ea-adc1e133c744.png)
<img width="730" alt="contrast-checker" src="https://user-images.githubusercontent.com/7358665/155908887-59c6d02c-341b-46b8-8403-0b35643c16c1.png">

## Features 

### Existing Features

- __Navigation Bar__

  - Featured on all pages, the fully responsive navigation bar includes links to the Home page (from the site logo and home page navigation link), Upcoming events page, Gallery page and Sign Up page.
  - The navigation bar is identical on each page to allow for easy site and page navigation. 
  - The navigation link of the currently viewed page is displayed differently (complete solid border) to allow the user to quicky see what part of the site they are viewing.
  - When hovering over a navigation bar element, the elements colors will invert with a subtle animation to allow the user to easily see what they are selecting.
  - On smaller screen sizes the navigation elements use shorter key words to aid in the reponsive design of the navigation menu.
  - This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button. The navigation bar is also sticky and always visable to allow for immediate navigation when required by the user.

<img width="1435" alt="fullsize-navbar" src="https://user-images.githubusercontent.com/7358665/155905845-b51086a2-3e20-40a5-82cc-136f8220aa10.png">
<img width="452" alt="small-navbar" src="https://user-images.githubusercontent.com/7358665/155905870-570d92bc-2731-4738-ad91-106309b9b3c7.png">

- __The landing Page Hero Image and Headline__

  - The landing page includes a hero image with headline text side by side to allow the user to see exactly who this site is aiming to connect with. 
  - This is the first thing someone visiting the site will see so is presented in a clear and concise way to convey the main site focus to the user.

<img width="1580" alt="hero-headline" src="https://user-images.githubusercontent.com/7358665/155906196-25dee8fc-23c5-4179-b3e7-5fa5b8ffdb83.png">

- __About Us Cards__

  - The about us section card will allow the user to quickly see the benefits of joining in with the group, even if it is just for ideas of places to go on their own.
  - The cards will serve to highlight the main positives of joining the community and show the welcoming nature of the group.
  - The user will see the benefit of signing up for the newsletter to get more in depth information about upcoming walks and group events.

<img width="1092" alt="about-us" src="https://user-images.githubusercontent.com/7358665/155906279-1a462211-51ae-4458-b51d-d88d670c4e7f.png">

- __The Footer__ 

  - The footer section includes links to the relevant social media sites for Let's Go Walkies. 
  - The links will open to a new tab to allow easy navigation for the user. 
  - The footer icons rotate and scale up when hovered over to aid in selection by giving visual cues for the user.
  - The footer is valuable to the user as it encourages them to keep connected to the group via social media.

<img width="580" alt="footer" src="https://user-images.githubusercontent.com/7358665/155906343-a88a1bf0-40cd-423d-98f9-2319fde8acc9.png">

- __Upcoming Events__

  - This page will allow the user to see upcoming group meets, when they will happen, and where exactly they will be held using embedded google maps. 
  - This pages content will be easy to maintain and update and will keep the required information in an easy to find and read area. 

<img width="1115" alt="upcoming" src="https://user-images.githubusercontent.com/7358665/155906505-9f37d7b0-8521-4e4d-869e-3cd884366fb7.png">

- __Gallery__

  - The gallery page will provide the user with supporting images to see what the meet ups look like as events. 
  - This section is valuable to the user as they can see the types of walks the group has completed in the past. 
  - The gallery is styled in a masonary style which makes transitioning to smaller screensizes using fewer columns much simpler and keeps the flow of the gallery as smooth as possible.
  - the gallery style allows for easy addition of content that will automatically size to fit the scheme.

<img width="1301" alt="gallery-min" src="https://user-images.githubusercontent.com/7358665/155906666-bfa22709-17f7-4941-b34a-7854596123b5.png">

- __The Sign Up Page__

  - This page will allow the user to sign up to Let's Go Walkies newsletters mailing list. 
  - The user will be able to specify how many dogs and of what breeds they are. This can help facilitate introductions between the group and may help the user to find commanalities with current members.
  - The user will be asked to submit their full name and email address. 
  - The sign up form has validation on each section apart from breed.
  
<img width="1301" alt="signup-min" src="https://user-images.githubusercontent.com/7358665/155907500-9b471536-8e6a-4cec-951d-ea6cfe6cac44.png">

- __The 404 Page__

  - This page will allow the user to find their way back to the main site pages in the event they reach a 404 page link by mistake. 
  - The 404 page clearly states to the user that the nav links are to be used to relocate back to normal site navigation.
  
<img width="2560" alt="404" src="https://user-images.githubusercontent.com/7358665/155911330-ca15f829-9543-4cfb-9c19-ba0c9e962538.png">

### Features Left to Implement

- While there are no features left unimplimented from the original scope of the site, there is one feature outlined below that I explored that could possibly be implimented as further addition to the site at a later time. This would require Javascript and as such is beyond the scope of this project as the projects focus was a HTML and CSS front end site.

- __Photo Submission__

  - A form with a file browser element to allow for community members to upload photos from events for submission to be added to the gallery page. 
  - This will add to the level of inclusion for community members.
  - This will add to the exposure for the group as photos could be shown and shared with people outside of the group by current group members.

- __Form Submission User Feedback__

  - As this project was a HTML and CSS front end focussed project, the user inputted information on the signup form opens on a seperate validation page. In future javascript may be inplimented to send an alert to the user to notify wether the form and information contained in it has been recieved correctly or not.

## Testing 

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your project’s features and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

To begin testing the site I checked all user accesible links, forms and buttons worked in as expected in Chrome, Firefox and Safari. As far as was observable there were no errors in any browser in terms of links and user interaction elements.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

### Validator Testing 

MAKE SURE TO DO THE VALIDATOR CHECKS AGAIN ONCE ALL SITE FEATURES ARE IMPLIMENTED!!!!!! ADD SCREENSHOTS OF ALL VALIDATOR SCORES FOR ALL PAGES

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fvalidator.w3.org%2Fnu%2F%3Fdoc%3Dhttps%253A%252F%252Fcode-institute-org.github.io%252Flove-running-2.0%252Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#css)

### Unfixed Bugs

You will need to mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a big variable to consider, paucity of time and difficulty understanding implementation is not a valid reason to leave bugs unfixed. 

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub) 

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://code-institute-org.github.io/love-running-2.0/index.html 


## Credits 

In this section you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism. 

You can break the credits section up into Content and Media, depending on what you have included in your project. 

ADD PHOTO CREDITS, GOOGLE MAPS, CODE INSTITUTE LOVE RUNNING README TEMPLATE, FONT AWESOME, GOOGLE FONTS...

### Content 

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The photos used on the home and sign up page are from This Open Source site
- The images used for the gallery page were taken from this other open source site
