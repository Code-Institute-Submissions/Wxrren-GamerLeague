# GamerLeague

GamerLeague are a group of competitive gamers ranging from amateur to professional level. Our aim is to provide gamers a competitive setting to compete at the highest level. 

Anyone is able to join the league via the form application on the join us page. There you will find sections to sign up for any Solo, Duo and Squad events. In the tournament section you will find a gallery of recent tournaments held. If you have any issues, 'contact us' is found in the footer, you can fill out your your details and submit any issues you have. Links to our socials are also present.

 
![An images showing the website being responsive across multiple devices](assets/images/am-i-responsive-image.png "Resonsive site")


[You can visit the GamerLeague website here](https://wxrren.github.io/1st-milestone-project-GamerLeague/)
------

## Table of Contents

### [User Experience (UX)](#user-experience-ux)
* #### [User Stories](#user-stories)
* #### [WireFrames](#wire-frames) (View the repository [here](https://github.com/Wxrren/1st-milestone-project-GamerLeague/tree/main/ux/wireframes))
* #### [Design](#design-1)

### [Features](#features-1)
* #### [Existing Features](#existing-features-1)
* #### [Features Left to Implement](#features-left-to-implement-1)

### [Bugs](#bugs-1)

### Testing
* #### Validation Results
* #### Manual Testing
* #### Lighthouse Report

### [Technologies Used](#technologies-used-1)

### [Frameworks, Libraries & Programs Used](#frameworks-libraries--programs-used-1)

### [Deployment and local development](#deployment-and-local-development-1)
* #### [GitHub Pages](#github-pages-1)
* #### [Forking the GitHub Repository](#forking-the-github-repository-1)
* #### [Local Clone](#local-clone-1)

### Credits

### Acknowledgements
------

## User Experience (UX)

The goal of the website is to attract gamers of all levels who would like to compete in a game of their choice. 

There is a clear naviation in the nav bar which directs you on where to join the league or sign up to competitions. It also directs you to a tournaments gallery where they can look at pictures of tournaments others have competed in.

Users can also contact GamerLeague if they have any issues either with the site, a tournament or player - whatever it may be. They can follow the contact us link in the footer and submit their issue.

To make the user experience easy - I wanted the site to have:

* A simple call to action on the main screen with a join GamerLeague button. This will take you directly to a single contact page - Even though this navigation exists on the nav bar - the aim is this button in the center of the screen next to the tagline will motivate gamers to join. 
* A card displaying the tournaments that could be clicked on to redirect you to a the same contact page as the join button - the sign up section is on the lower part of the page. The idea is to have one single contact page that makes it a quicker and easier experience for the user.

## User Stories
To determine which approach to take with site features I detirmined the goals of different users from first time through to frequent users.

### User

* First time User Goals
    * As a user I want to be able understand the main purpose of the site immediately and learn more about the GamerLeague.
    * As a user I want to be able to see what upcoming tournaments are available.
    * As a user I want to be able to easily navigate the site.
    * As a user I want to be able to find how to join the site and do so easily.

* Returning User Goals
    * As a user I want to be able to see hot upcoming tournaments and sign up quickly.
    * As a user I want to be able to easily contact the company should issues arise.
    * As a user I want to be able to view the gallery of recent or previous tournaments for nostalgia or to see what I missed if not attending.
    
* Frequent User Goals
    * As a user I want to be able to see if there is any new upcoming tournaments and sign up quickly.
    * As a user I want to be able to review the gallery and see new photos of recent tournaments
    * As a user I want to see the latest information coming in from pro's or breakdown the latest tournaments with an experience cast.

## Wire Frames

When designing this website I intended the site to have a very minimal design that was easy to spot what was relevant information and how to navigate to where they wanted to be. 

I have made some changes during the creation of the website. These changes were to the [Home Page](#home-page---wireframe-for-desktop-tablet-and-mobile), [Gallery Page](#gallery-page---wireframe-for-desktop-tablet-and-mobile) and the [Join Page](#join-page---wireframe-for-desktop-tablet-and-mobile)

### Home Page - Wireframe for Desktop, Tablet and Mobile.
![An images showing the website wireframes across different devices](ux/wireframes/home-page-wireframe.png "Home Page Wireframe")

* Home page changes

For the home page I was going to initially have 3 cards showing a different game - once clicked these would take you to a page with more dummy tournaments similar to the "upcoming tournaments" section - After discussing this with my mentor we agreed it was a bit too much and to keep it simple. Instead I opted fo the multiple games to be shown in the gallery page and use the games section instead to give more identity and content to the site. I chose to do an about us section with a brief description of the team behind the site and then embedded 2 videos to give the website a professional identity. One was a tutorial from a professional coach in ESports and another was a breakdown of a recent Esports tournament on a talkshow held by retired Esports pros. I felt this would help give the site an identity of a professional gaming league.

### Gallery Page - Wireframe for Desktop, Tablet and Mobile.
![An images showing the website wireframes across different devices](ux/wireframes/gallery-page-wireframes.png "Gallery Page Wireframe")

* Gallery page changes

During the creation of the gallery page I had intended to have a page with 3 sections showcasing tournaments for different games. When putting this together I decided I didn't like the idea of seperating the games as I wanted the gallery to be a page showcasing the GamerLeagues tournaments and work. I instead opted to make it one single pages with the images split into collumns. 3 for Desktop, 2 for Tablet and 1 for Mobile. I then showcased different Esports tournament images - the intention was to showcase the GamerLeague as a professional tournament league and the gallery can be their body of work.

### Join Page - Wireframe for Desktop, Tablet and Mobile.
![An images showing the website wireframes across different devices](ux/wireframes/join-page-wireframe.png "Join Page Wireframe")

* Join Page changes

The changes for the join page were more minimal. After discussing with my mentor Mitko we agreed on having one single contact page split into sections. The top section you can join the league and the bottom you can sign up for tournaments. As I had made the dummy tournaments a "solo", "Duo" and "Squad" it would mean that the sign up form for a solo or duo would only require one or two gamertags. I thought this would look out of place so I decided to make 3 seperate fieldsets in the signup section for each different tournament type. This also then allowed me to make the gamertags a required field that all had to be filled in order to sign up.  

## Design

### Color

The theme I wanted for the website was Red VS Blue. The colours would help to represent competition and they're also used as a reference to an old video series called Red Vs Blue by Machinima.

I chose a Red and blue image that I wanted to be used at the top of the home page and then set a linear gradient of blue to red for the background of the page to match the colours in the picture. I then felt this was too bright and could impact visibility on the site so I added a slight black opaque overlay to make the blue and reds appear a little darker and the content on the website look more visible. 

For the cards on the home page - I chose to keep these without the overlay to stand out from the background and draw the user's eye to them.

* Main colours used on the website:
    ![An image showing 3 colours. Navy, Blue and Red with hex and RGB codes](features/development-images/colours-used.png "Main Colours")
    * #01012c - Used for the Nav bar as it a darker and bolder colour to separate it from the main image on the homepage and the blue and red colours below. This is also used on the main background colour as part of the linear gradient. The black overlay helps darken this a bit more and separate it from the header.
    * #090979 - this is used as the middle part of the gradient to get a transition from dark blue to light blue to red. It helps lighten up the middle portion.
    * #FF0000 - The end part of the gradient. Once mixed in a gradient witht he blue this helps give us the red vs blue theme and make it look like the colours are clashing in the middle 

* Overlay colour: 

![An image showing a black colourwith hex and RGB codes](features/development-images/overlay-colours-used.png "Overlay colours") 

* #000000 - Used as a transparent overlay with RGBA code rgba(0, 0, 0, .6). This helped make the blue and reds appear a little darker so that the content can stand out more.

### Typography

* Nova Square 
    
    * I chose Nova Square as the main font from google fontsas I felt it meshed well with a gaming brand due to the style of the lettering and the boldness of the text to stand out. I also had Sans serif as a back up in case this didn't work.

* Sans Serif

    *  I had Sans Serif for 2 uses. I  had it as a back up in case Nova Square didn't work. I also used it for the Nav bar, buttons and general info as I felt a clear and simple font would make it easiest to take in information and navigate the site.

### WireFrames

I created my wireframes using balsamiq wireframes. I found this simple and effective for coming up with how I wanted the site to look as it had a variety of ready available tools representing different parts of a website so I was able to design it how I envisioned it in my head.

## Features
* This website is targeting people looking to compete in game tournaments for cash prizes
* They can do this by joining the League and signing up to tournaments on the join page.
* Responsive on all device sizes.

### Existing Features

#### Navigation bar

![An image showing the navigation bar for desktop view.](features/development-images/navbar-desktop.png "Navbar Desktop View")
![An image showing the navigation bar for mobile view.](features/development-images/navbar-mobile.png "Navbar Mobile View")

* The Nav bar is fixed to the top of every every page including the contact us page reachable through the footer.
* Includes links to the Home page, Tournaments page and the Signup/Join page. 
* Where you are on the site can be easily identified as your current active page will be highlighted by a red border/background colour as well as a larger font at all times. You can also see which page you are hovering over because each link has a similar effect to the active page where it will turn red and the font will become larger.
* Design is identical across every page.
* Allows the user to easily explore the site by clicking each page at the top. you can get to and from each page without needing the backwards and forwards browser buttons. 
* Has a mobile view consisting of a hamburger icon. Once selected this will bring a dropdown list of the pages as show below: 

![An image showing the navigation bar for mobile view when the page icon is toggled.](features/development-images/navbar-mobile-toggled.png "Navbar Mobile View")

#### Main Heading

![An image showing the main heading of the website.](features/development-images/main-heading.png "Main Heading")

* Main heading consists of a background image with the Red vs Blue theme. The image features a shield and trophy to symbolise competition and a red and blue scoreboard on each side. 
* Background image has an subtle animation that starts the image at full size and slowly zooms in bringing the trophy and shield slightly closer.
* The main heading has a simple tagline to attract competitive users. It also set's the tone immediately for what the site is about.
* Simple call to action in the form of a button to join the league. This button takes you through to the join page.

#### Section 1 - Upcoming Tournaments

![An image showing the upcoming tournaments section.](features/development-images/section-1-upcoming-tournaments.png "Section 1 - Upcoming Tournaments")

* Simple headline - white to stand out.
* Simple instructions for how to sign up to each tournament.
* 3 cards split into different columns. Each with information on a different tournament and an image to tell you which game they are for.
* Each card has a hover effect. When the mouse hovers over the card a red border will apear on the left side and the card font will grow slight larger and drop down.

#### Section 2 - About us

![An image showing the about us section.](features/development-images/section-2-about-us.png "Section 2 - About Us")

* Same card design as previously - shorter and smaller to match the content
* A card explaining who the site owners are and what they do. Goals of the site included.
* x2 embedded youtube videos - one is a talk show hosted by retired professional gamers breaking down a recent tournament. The other is a professional coach in the Call of Duty League teaching players about proessional matches and how outcomes in that match were reached. This gives the site an image of a professional and knowledgeable gaming league. 

#### Footer

![An image showing the website footer.](features/development-images/footer.png "Footer")

* Simple dark navy colour matching the nav bar fixed to the top.
* Links to social media. These will open in a new tab allowing for easier navigation and to avoid the user's confusion in losing the main site. 
* Contact us page and copyright pages are highlighted in red to make them easy to locate. Hover effect in place to make them stand out.
* Copyright page redirects to my github.

#### Tournament page

![An image showing the website tournament page.](features/development-images/gallery-page.png "Gallery")

* The gallery shows users previously run tournaments. This create's authenticity to site as well as shows the user's what they are missing out on.
* Valuable to users who want to see the fun for themselves and feel confident the league is serious.

#### Sign up/join

![An image showing the website join page.](features/development-images/join-gamer-league.png "Join")
![An image showing the website Sign up page.](features/development-images/sign-up-page.png "Sign up")

* Single contact page for both joining the league and signing up to tournaments.
* The user can choose which differnt tournament type they would like to enter.
* Completetion takes you to form dump page on a seperate tab to ensure ease of use for user.
* Password parameters displayed upon hover over password

#### Contact Us Page

![An image showing the website Contact us page.](features/development-images/contactus-desktop-view.png "Contact us")

* Simple contact page with form asking for basic details and a text area to voice any feedback/concerns.
* Completetion takes you to form dump page on a seperate tab to ensure ease of use for user.

## Features Left to Implement

* Upcoming Tournaments Section
   
    * I would like selecting the tournament cards to bring a pop up modal onto the screen allowing for the ability to sign up to tournaments faster.

* Contact Us Page

    * I would like to create a back end so that the data in this form is sent to a business email as well as sending a confirmation to the customer for better user experience.

## Bugs

| Problem         | Action           | Status  |
| ------------------------------------------------|:--------------------------------------:| -----:|
| Hover function not applying to bootstrap nav bar.| Used google dev tools to find the bootstrap CSS, located the allocated class names names provided by bootstrap to target the areas I wanted to apply the hover effect. | Fixed |
|  Text/buttons not centering over main page background image.   | Used the transform: Translate() method found on web3schools. by setting -50 for the x and y axis I was able to center it on the screen. Then I updated the position to absolute and used the top and left commands to get it where I wanted it on top of the image.      |   Fixed |
| Unable to navigate between pages.| Issue with page link missing the **.** in .html. Added in the missing dot. Navigation now working correctly.      |    Fixed |
| Multiple forms on same page are not acting separately when submitting.| Changed unique ID for each input/label within the indivual forms for solo/duo/squad. Each now able to sign in when filling out without requiring the other forms to be completed.      |    Fixed |

---

## Technologies Used

* [HTML5](https://en.wikipedia.org/wiki/HTML5)
* [CSS3](https://en.wikipedia.org/wiki/CSS)

## Frameworks, Libraries & Programs Used

* [Visual Studio Code](https://code.visualstudio.com) 
    * Used to write the code/README.

* [Git](https://git-scm.com)
    *  Tracking changes in my course code and pushing them to github.

* [Github](https://github.com)
    * To store my code/files and deploy my website.

* [Google Fonts](https://fonts.google.com)
    * Used for importing my main font for the website

* [Bootstrap 5](https://getbootstrap.com/docs/5.0/getting-started/introduction/)
    * Used for making web deelopment faster. My usage was for card columns + Nav bar.

* [Font Awesome](https://fontawesome.com)
    * Used for importing logo's for the website.

* [Icons8](https://icons8.com/icons)
    * Hamburger icon for mobile Nav bar toggler.

* [Am I Responsive](https://ui.dev/amiresponsive)
    * Mock picture for README file.

## Deployment and local development

*  ### GitHub Pages

I used GitHub to deploy the live version of the website. To do this I had to: 

1.  Log in to GitHub and locate the GitHub GamerLeague [Repository](https://github.com/Wxrren/GamerLeague)
2.  Locate the "Settings" button at the top of the repository as show here:

![An image showing the repository page with settings highlighted.](deployment/repository-settings-location.png "Settings")

3. look down the "Code and automation" area until you find ["Pages"](https://github.com/Wxrren/GamerLeague/settings/pages) as shown below:

![An image showing the repository page with pages highlighted.](deployment/pages-locations.png "Pages")

4. Under "Source", click the dropdown menu "None" and select "Main" and click "Save".

5. The page will automatically refresh.

6. Scroll back to locate the now-published [site link](https://github.com/Wxrren/GamerLeague) in the "GitHub Pages" section as seen below:

![An image showing the repository page with pages highlighted.](deployment/site-link-github-pages.png "Site Link")

* ### Forking the GitHub Repository

Forking the repository allows you to make a copy of the original repository on my GitHub account to view and change without affecting the original repository. To achieve this, follow these steps:

1. Log in to GitHub and locate the GitHub GamerLeague [Repository](https://github.com/Wxrren/GamerLeague)
2. At the top of the Repository(above the about section) locate "Fork" button.

![An image showing the repository page with Fork highlighted.](deployment/fork-location.png "Fork Location")

3. Once complete you should have a copy of the original repository in your GitHub account.

* ### Local Clone

1. Log in to GitHub and locate the GitHub GamerLeague [Repository](https://github.com/Wxrren/GamerLeague)
2. Above the list of files, click  Code.

![An image showing the repository page with Fork highlighted.](deployment/code.png "Fork Location")

3. Click on the code button, select clone with any of the options provided (These options are HTTPS, SSH or GitHub CLI) and copy the link shown.
4. Open Git Bash
5. Change the current working directory to the location where you want the cloned directory to be created.
6. Type **GIT CLONE**, and then paste the URL you copied earlier.
7. Press Enter to create your local clone.




