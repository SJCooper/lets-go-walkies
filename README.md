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

While there are no features left unimplimented from the original scope of the site, there are features outlined below that I explored that could possibly be implimented as further addition to the site at a later time. This would require Javascript and as such is beyond the scope of this project as the projects focus was a HTML and CSS front end site.

- __Photo Submission__

  - A form with a file browser element to allow for community members to upload photos from events for submission to be added to the gallery page. 
  - This will add to the level of inclusion for community members.
  - This will add to the exposure for the group as photos could be shown and shared with people outside of the group by current group members.

- __Form Submission User Feedback__

  - As this project was a HTML and CSS front end focussed project, the user inputted information on the signup form opens on a seperate validation page. In future javascript may be inplimented to send an alert to the user to notify wether the form and information contained in it has been recieved correctly or not.

## Testing 

To begin testing the site I checked all user accesible links, forms and buttons worked in as expected in Chrome, Firefox and Safari. This included checking every link from every page at every responsive breakpoint size. As far as was observable there were no errors in any browser in terms of links and user interaction elements.

I then went on to test the site on physical devices available to me which are an iPhone X and iPad Pro (12.9 inch M1 model). This afforded me the opportunity to test landscape and portrait modes on both devices to check responsivness was behaving as expected and it was in every case.

Whilst testing on these apple devices I became aware of a bug in which the sign up form submit button was not styling as expected and instead was using some apparantly default iOS button stylings. I found a potential fix on Stack Overflow which seemed to resolve the problem with minimal additional CSS styling.

![iPad-bug-min](https://user-images.githubusercontent.com/7358665/155914253-634cec2d-c319-4ef3-b27a-e3cec990027d.PNG)
![iPhone-bug-min](https://user-images.githubusercontent.com/7358665/155914293-4157ed3c-0c1f-491f-a87d-a14db0269c14.PNG)
<img width="308" alt="stack-overflow-solution" src="https://user-images.githubusercontent.com/7358665/155914461-7f1c1e91-ef8b-4186-9962-d0a4b5619940.png">

All responsive elements in each of these test cases worked and updated as expected.

### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/)
  - There was one warning for each of the events, gallery and signup pages stating they did not have headers. This was deemed to be a design choice and that the headers were not needed for those particular pages and did not effect the site in any negative way.
  
<img width="582" alt="index-html" src="https://user-images.githubusercontent.com/7358665/155915547-002a4614-1783-46c5-8093-114756188ffa.png">
<img width="904" alt="upcoming-html" src="https://user-images.githubusercontent.com/7358665/155915589-d1602b07-1899-4a1e-b365-61c1121cdc86.png">
<img width="904" alt="gallery-html" src="https://user-images.githubusercontent.com/7358665/155915658-cd644124-c38c-41c9-9aea-0d85aa61aa8e.png">
<img width="904" alt="signup-html" src="https://user-images.githubusercontent.com/7358665/155915702-6d867180-0fdc-4c7d-bfc8-fcd37919de62.png">
<img width="546" alt="404-html" src="https://user-images.githubusercontent.com/7358665/155915750-703c3def-8e9c-4339-8c89-b72ec8394a90.png">

- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/)
  - There was one warning flagged as below which was directly related to the submit button iOS fix and was required for the site to style correctly. This did not impact any usability of the site.

<img width="996" alt="css-validation" src="https://user-images.githubusercontent.com/7358665/155917193-03849545-2dcf-4f75-a285-8512b0bff47b.png">
<img width="469" alt="css-warning" src="https://user-images.githubusercontent.com/7358665/155917203-bf137c8e-1131-407a-bc61-d8cdc921d972.png">

- Lighthouse
  - I ran a lighthouse test case in Google Chrome and the results were acceptable with performance being the lowest but having drastically improved after compressing the site images and lowering their filesizes all to less than 1mb.

<img width="469" alt="lighthouse" src="https://user-images.githubusercontent.com/7358665/155916851-0c0909ba-ab75-4c9c-9486-e9693f65097f.png">

### Unfixed Bugs

There is a known issue in GitPod. I am currently unable to remove the now unused sign-up.png image from the repo without my system crashing. I have tried several solutions to this including full system reboots and closing down of every other program running but to no success. This is not impacting the sites deployment at all but should be noted as the file is no longer used anywhere in the site or README. It should be noted that this is seemingly not a bug but rather a system issue.

<img width="304" alt="image-bug" src="https://user-images.githubusercontent.com/7358665/155923496-0c9f9239-1133-48f9-b271-ed935ec2f726.png">

## Deployment

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch (may show as Main Branch)
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://sjcooper.github.io/lets-go-walkies/index.html 

<img width="1237" alt="deploy" src="https://user-images.githubusercontent.com/7358665/155917884-0bc8b480-f935-4051-afee-9b147a7cc192.png">

## Credits 

### Content 

- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)
- All maps were direct links from [Google maps](https://www.google.com/maps/@53.7750116,-2.7105935,15z)
- This README was created using a template provided for the Love Running project from [Code Institute](https://codeinstitute.net/)
- The fonts used by the site are from [Google Fonts](https://fonts.google.com/)
- Favicon icons and files were taken from [Favicon.io](https://favicon.io/)
- Color swatch image was taken from [coolors.co](https://coolors.co/)
- Photo compression was done using [compresspng](https://compresspng.com/)

### Code

- CSS Flex Grid design and implimentation was taken from [Codepen](https://codepen.io/), specifically Tania Rascias [Easist Flex Grid Ever](https://codepen.io/taniarascia/pen/rOLEGe/) which was shown to me by my mentor Malia Havlicek.
- Code feedback was given by Malia Havlicek as part of my Mentor sessions. 
- Other code was implimented from Code Institutes lessons including the Love Running Project indirectly from what I had learned from them.

### Media

- The photos for the hero image and gallery page were all from [Unsplash](https://unsplash.com/). Any other photos are personal photos owned by myself.
