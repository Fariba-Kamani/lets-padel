# Let's Padel

![Let's Padel shown on a variety of screen sizes](assets/images/lets-padel-responsive.png)

Visit the deployed site: [Let's Padel](https://fariba-kamani.github.io/lets-padel/)

Let's Padel is a growing community for everyone who loves playing Padel regardless of gender, age, or skill level. As a padel player myself I usually struggle to find other people to play with when I have spare time and can play. I would have played Padel more often if I had access to more Padel players beyond those in my contact list. I thought this could as well be one of the obstacles for other Padel players like me out there. By creating Let's Padel I am trying to address this issue and help facilitate for Padel players to find and connect and hopefully be able to play Padel as often as they desire.

The way the website works is very straightforward and intuitive. All that needs to be done is for the player to fill in a form, informing us about when and where she/he wants to play, the skill level the player has, and how many players are needed to be able to play a match. We will then try to find other players with the same preferences. Once we have identified all the necessary players, we will reach out to them using the contact details provided in the submitted form.

## CONTENTS

* [User Experience](#user-experience-ux)
  * [User Stories](#user-stories)

* [Design](#design)
  * [Colour Scheme](#colour-scheme)
  * [Typography](#typography)
  * [Imagery](#imagery)
  * [Wireframes](#wireframes)
  * [Features](#features)
    * [The Home Page](#the-home-page)
    * [The Players Page](#the-find-players-page)
    * [The Gallery Page](#the-gallery-page)
  * [Accessibility](#accessibility)

* [Technologies Used](#technologies-used)
  * [Languages Used](#languages-used)
  * [Frameworks, Libraries & Programs Used](#frameworks-libraries--programs-used)

* [Deployment & Local Development](#deployment--local-development)
  * [Deployment](#deployment)
  * [Local Development](#local-development)
    * [How to Fork](#how-to-fork)
    * [How to Clone](#how-to-clone)

* [Testing](#testing)
  * [AUTOMATED TESTING](#automated-testing)
    * [W3C Validator](#w3c-validator)
    * [Lighthouse](#lighthouse)
  * [MANUAL TESTING](#manual-testing)
    * [Testing User Stories](#testing-user-stories)
    * [Full Testing](#full-testing)
  * [Solved Bugs](#solved-bugs)
  * [Known Bugs](#known-bugs)
  
* [Credits](#credits)
  * [Code Used](#code-used)
  * [Content](#content)
  * [Acknowledgments](#acknowledgments)

- - -

## User Experience (UX)

### User Stories


#### First Time Visitor Goals
* I would like to try Padel or play Padel occasionally, and I want to find people to play with.
* I have a different schedule from my padel friends, so I’m looking for other padel players who have a similar schedule to mine.
* I want the website to be intuitive and easy to use.
* I want the website to be responsive and compatible with my device.

#### Returning Visitor Goals

* I want to be able to play Padel more frequently, and I want to find players on a more regular basis.
* Even if I spontaneously decide to play padel, I still want to know that there is a high chance I could find other players to play with by using the website.

#### Frequent Visitor Goals

* I want to be able to see what matches other players have requested and be able to independently join their matches.
* I want to be able to have an account on the website and be able to stay connected to my Padel friends via the website.
* I want to be able to independently upload pictures taken from my Padel experiences on the Gallery page.

- - -

## Design

### Colour Scheme

The Let’s Padel color scheme draws inspiration from the hues commonly seen on padel courts throughout Stockholm. These colors typically include blue, black, and white. The goal was to evoke the same feeling as being on a padel court while maintaining a minimalistic design to avoid visual overload, especially for users with Autism.

The header background features an image of a padel court, with the dominant color being rgb(18, 128, 223) or #1280DF. This color choice also influenced the footer color across all three web pages. To ensure readability, the menu bar font and Font Fantastic icons in the footer are white, creating contrast against the blue background.

 The header title stands out with a slightly different white shade, rgb(250, 250, 243) or #FAFAF3, compared to other links in the navigation bar and footer. For desktop screens, a hovering effect changes the content color of the header and footer to rgb(230, 191, 49) or #E6BF31, maintaining contrast against their backgrounds.

On mobile screens, navigation links appear in a drop-down menu, opening on a transparent rich black background (rgba(1, 1, 21, 0.2)). This ensures visibility against the header background image while keeping the image itself visible. For tablet and desktop screens, a fixed navigation bar beneath the header image displays the navigation links at all times. To distinguish the navbar from the header image, I used rgb(44, 36, 155) or #2C249B.

The body sections alternate between white and Aliceblue backgrounds, aiding users in understanding where one section ends and another begins. Black is used for the font colour on the body to ensure contrast and better visibility.

Lastly, button borders (on all screen sizes) and the fieldset borders (on tablet and desktop screens) share the same blue color as the header image and footer, which is rgb(18, 128, 223). This design creates cohesion with the rest of the website’s color scheme while remaining noticeable to users.

![The Let's Padel Colour Scheme](assets/images/lets-padel-color-scheme.png)

### Typography

Google Fonts was used to import the chosen fonts for use on the site.

![Exo 2](assets/images/Title-font.png)

* For the page title, I have used the Google font Exo 2, which is described as a contemporary geometric sans serif typeface by [Google Fonts](https://fonts.google.com/specimen/Exo+2/about?preview.text=LET%27S%20PADEL&preview.size=42). I chose this font for the title because it looks playful and fun, which goes well with the agenda of the website.

![Roboto](assets/images/body-font.png)

* For the body of the page, I have used the Google font ‘Roboto’ because it is clean, readable, and easy on the eyes, making the user experience as smooth as possible. According to [Google Fonts](https://fonts.google.com/specimen/Roboto/about?query=roboto&selected=Material+Symbols+Outlined:sports_tennis:FILL@0;wght@400;GRAD@0;opsz@24&icon.size=24&icon.color=%235f6368), Roboto is featured in more than 695 million websites. Additionally, according to [Github](https://github.com/googlefonts/roboto), the font provides robust multi-language support and comes in various weights, styles, and alternate glyphs. 

* In case the imported Google fonts don’t load, both fonts will fall back to sans-serif.

### Imagery

All images used on the website have been resized using [Image Resizer.com](https://imageresizer.com/), converted to WebP format with [FreeConver](https://www.freeconvert.com/jpg-to-webp) and compressed using [tinify](https://tinypng.com/) to be optimized for using on the website and help loading the website faster for the users.

The headers on all three pages have a background image of a padel court taken from, https://psauction.com/item/view/975429/mobil-komplett-padelbana-instantpadel-duo-10x20m-ny-och-ej-monterad, to give the user the same feeling as being on the padel court.

You can see the URLs from which the images on the Gallery page are taken, in the list below. All of them have an alt attribute to display text if the image file doesn’t load, and to describe the image for screen readers used by visually impaired users.

* https://thumbs.dreamstime.com/b/serious-middle-aged-latin-man-tennis-player-playing-padel-friendly-match-outdoor-court-spring-focused-hitting-ball-267446063.jpg
* https://www.vanguardlawmag.com/wp-content/uploads/2024/04/IMG_5960.jpg
* https://www.lta.org.uk/49d339/siteassets/play/padel/image/woman-playing-padel2.jpg?w=3200"
* https://tennis-uni.com/wp-content/uploads/padel-tennisspieler-netz-400x267.jpeg
* https://media.istockphoto.com/id/1413274533/photo/four-senior-friends-enjoying-together-while-playing-padel.jpg?s=612x612&w=0&k=20&c=ZuI09DB7woiuqmYD-J5dlzg1ID5VOSoh6m_7gFII4_E="
* https://thepeninsulaqatar.com/get/maximage/20240303_1709445598-694.jpg?1709445599"
* https://thepadelstate.com/wp-content/uploads/2024/02/Sofia-Arujo-1021x500.jpg
* https://rutinasdeportivas.es/medios/2017/01/Quieres-saber-cu%C3%A1les-son-los-beneficios-del-p%C3%A1del-y-porque-es-importante-practicarlo-parejas.jpg

### Wireframes

Wireframes were created for mobile, tablet and desktop using balsamiq.

| Screen size | Home | Find a match | Gallery |
| :--- | :--- | :--- | :--- |
| mobile | ![home page for mobile](assets/images/wireframe-lets-padel-homepage-mobile.png) | ![Find Players page for mobile](assets/images/wireframe-lets-padel-find-a-matchpage-mobile.png) | ![gallery page for mobile](assets/images/wireframe-lets-padel-gallerypage-mobile.png) |
| tablet | ![home page for tablet](assets/images/wireframe-lets-padel-homepage-ipod.png) | ![find Players page for tablet](assets/images/wireframe-lets-padel-find-a-matchpage-ipod.png) | ![gallery page for tablet](assets/images/wireframe-lets-padel-gallerypage-ipod.png) |
| desktop | ![home page for desktop](assets/images/wireframe-lets-padel-homepage-desktop.png) | ![find Players page for desktop](assets/images/wireframe-lets-padel-find-a-matchpage-desktop.png) | ![gallery page for desktop](assets/images/wireframe-lets-padel-gallerypage-desktop.png) |


### Features

The website consists of a home page, a Find Players page and a Gallery page.

All Pages on the website are responsive and have the following features:

* A favicon in the browser tab.

  ![favicon](assets/images/favicon-tab.png)

* The title of the site at the top of every page. This title also acts as a link back to the home page, and it turns into a saffron yellow color when hovered over on desktop screens.

  ![The Let's Padel Title](assets/images/title-link-to-homepage.png)
  ![The Let's Padel Title responsive](assets/images/title-hover-desktop.png)

* **Drop down navigation menu for mobile screens**  

  ![drop down navigation menu](assets/images/dropdown-navigation-menu.png)  

  * **Underlining the active page in the navigation menu**
  * **Navigation menu for screens larger than tablets**
  
    ![navigation menu for screens larger than tablets with underlined active page](assets/images/responsive-nav-menu-active-page.png)

  * **Navigation links turn into Saffron yellow color with an underline of the same color when hovered over on desktop screens** 

    ![navigation menu links on hover](assets/images/responsive-nav-links-by-hover.png)
  

* The footer of the site, located at the bottom of every page, features links to the website’s Facebook, Instagram, email, and phone. These links are displayed using Font Awesome icons. When hovered over on desktop screens, each icon changes to a Saffron yellow color.

  ![footer](assets/images/footer.png)

* White shadow underneath the navigation bar and above the footer to add more distinction between them and the body content for the user.

  ![White box show seperating the header and the footer from the body](assets/images/white-box-shadow.png)

#### The Home Page

![Responsive home page](assets/images/homepage-responsive.png)

* **Quick introduction section or the landing section**

  ![Landing section](assets/images/landing-section.png)

* **About the website section, its purpose and how it works**
  * **Find Players button as well as the word "form" in the about the website section that send the users to the Find Players page**

    ![About section](assets/images/about-section.png)

  * **Responsive button that turns blue with white text by hovering on, on desktops**
  * **Responsive content. The paragraphs show in columns for screens larger than tablets**

    ![About section responsive](assets/images/second-section-responsive.png)

* **Benefits of padel section with font fantastic intuitive icons and responsive content**
![benefits of padel section](assets/images/benefit-section.png)
![benefits of padel on screens larger than tablets](assets/images/benefits-responsive.png)

#### The Find Players Page

![the Find Players page responsive](assets/images/find-players-responsive.png)

  * **Page title and quick instructions for the users**

    ![form page title and user instructions](assets/images/form-title-section.png)

  * **The submit form with two fieldsets and the Vamos button for submitting the form**
  * **Added fieldset border for more visible sectioning on screens larger than tablets**

    ![The submit form](assets/images/submit-form.png)

  * **Hover effect for Vamos button on desktops**

    ![Vamos button with hover effect](assets/images/responsive-vamos-button.png) 


#### The Gallery Page

![the Gallery page responsive](assets/images/gallery-page-responsive.png)

  * **The page title to let users know that they can share their photos**

    ![gallery page title](assets/images/gallery-page-title.png)

  * **Masonry design for displaying the Gallery photos**
  * **Added hover effect to gallery images to make them bigger when hovered on**

    ![gallery images hovered on for desktop](assets/images/hovered-on-gallery-img-desktop.png)

#### Future Implementations

In future implementations I would like to:

1. display the matches the users have requested on the website and allowing the other users to be able to send requests to join the available matches while the match hasn't become full.
2. Uppdating the displayed matches and remove the old ones from the display.
3. Allowing the user to have an account on the website to be able to 
   * add other players in their friend list, 
   * send messages, 
    * keep a record of the matches that have been played 
    * be able to see the status of the match they have requested.

### Accessibility

I have been mindful during coding to ensure that any one can understand my website regardless of auditory, visual or physical disability.

* Semantic HTML has been used to both help the browser to understand the content, also to provide the screen readers with extra functionality to operate by keyboard rather than by a mouse.
* Semantic text structure such as headings, paragraphs, list, ... has been used to help the screen reader to have the indicators it needs to read out the content in a useful way.
* Semantic structural elements such as nav, header, section, footer has been used to provide screen readers with important information that can be conveyed to their users.
* UI controls such as links, buttons and form have been used to allow the user to interact with the website and they can, by browser default, be accessed by using a keyboard or by clicking the tab key to jump from one UI control to another.
* Form labels have been used so that the screen readers can clearly label input fields for their users.
* Aria-label attribute has been used for making more sence of icons, links, background images and interactive elements for the screen reader users.
* Using a hover state on all buttons on the site to make it clear to the user if they are hovering over a button.
* Using a sensible font, font sizes, line heights, color contrast for the text content and sticking to common conventions to make the website intuitive, easy to read and follow for all users.

- - -

## Technologies Used

### Languages Used

HTML and CSS

### Frameworks, Libraries & Programs Used

* [Balsamiq](https://balsamiq.com/) - Used to create wireframes.

* [Git](https://git-scm.com/) - For version control.

* [Github](https://github.com/) - To save and store the files for the website.

* [GitPod](https://gitpod.io/) - IDE used to create the site.

* [Google Fonts](https://fonts.google.com/) - To import the fonts used on the website.

* [Google Developer Tools](https://developers.google.com/web/tools) - To troubleshoot and test features, solve issues with responsiveness and styling.

* [Favicon generator](https://realfavicongenerator.net/) To create favicon.

* [Am I Responsive?](http://ami.responsivedesign.is/) To show the website image on a range of devices.

* [Tinify](https://tinypng.com/) To compress images.

* [Image Resizer.com](https://imageresizer.com/) To resize and compress images. 

* [FreeConver](https://www.freeconvert.com/jpg-to-webp) To convert the images to webp format.
 
* [Webpage Spell-Check](https://chrome.google.com/webstore/detail/webpage-spell-check/mgdhaoimpabdhmacaclbbjddhngchjik/related) - a google chrome extension that allows you to spell check your webpage. Used to check the site and the readme for spelling errors.

- - -

## Deployment & Local Development

### Deployment

The site is deployed using GitHub Pages - [Let's Padel](https://fariba-kamani.github.io/lets-padel/).

To Deploy the site using GitHub Pages:

1. Login (or signup) to Github.
2. Go to the repository for this project, [fariba-kamani/lets-padel](https://github.com/fariba-kamani/lets-padel).
3. Click the settings button.
4. Select pages in the left hand navigation menu.
5. From the source dropdown select main branch and press save.
6. The site has now been deployed, please note that this process may take a few minutes before the site goes live.

### Local Development

#### How to Fork

To fork the repository:

1. Log in (or sign up) to Github.
2. Go to the repository for this project, [fariba-kamani/lets-padel](https://github.com/fariba-kamani/lets-padel)
3. Click the Fork button in the top right corner.

#### How to Clone

To clone the repository:

1. Log in (or sign up) to GitHub.
2. Go to the repository for this project, [fariba-kamani/lets-padel](https://github.com/fariba-kamani/lets-padel)
3. Click on the code button, select whether you would like to clone with HTTPS, SSH or GitHub CLI and copy the link shown.
4. Open the terminal in your code editor and change the current working directory to the location you want to use for the cloned directory.
5. Type 'git clone' into the terminal and then paste the link you copied in step 3. Press enter.

- - -

## Testing

Testing was ongoing throughout the entire project developement. Chrome developer tools were used whilst building to find and resolve any issues that came along and to ensure that everything was working correctly as expected.

Chrome developer tools were also used to ensure that the project is responsive, looks good and functions as it should on all standard screen sizes.

The website has been tested on following browsers; Chrome, Microsoft Edge and Safari. Devices I have tested the project on are VivoBook Asus laptop, iPhone 13, iphone 14 och Samsung Galaxy A14.

Additional testing was done by a few friends on both Android and iOS mobile devices. 

### Automated testing

#### W3C Validator

  - HTML: No errors were returned for index.html, find-match.html and gallery.html when passing through the official [W3C validator](https://validator.w3.org/).

  - CSS: No errors were found for style.css when passing through the official [Jigsaw validator](https://jigsaw.w3.org/css-validator/).

#### Lighthouse

I used Lighthouse within the Chrome Developer Tools to test the performance, accessibility, best practices and SEO of the website.

##### Desktop Results

  * Home page

    ![index.html](assets/images/lighthouse-home-desktop.png)
  
  * Find Players page

    ![find-match.html](assets/images/lighthouse-find-players-page-desktop.png)
  
  * Gallery page

    ![gallery.html](assets/images/lighthouse-gallery-page-desktop.png)

##### Mobile Results

 * Home page

    ![index.html](assets/images/lighthouse-home-mobile.png)
  
  * Find Players page

    ![find-match.html](assets/images/lighthouse-find-player-page-mobile.png)
  
  * Gallery page

    ![gallery.html](assets/images/lighthouse-gallery-page-mobile.png)

### Manual testing

  * **Common features on all pages**

  | Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| Favicon for the browser tab | To show on the browser tab | Opened the website | It shows on the browser tab | Pass |
| Website title | To links the user back to Home page | Clicked on link | It links back to Home page | Pass |
| Website title hover effect | To become yellow by hover on for desktops | Hovered on link | It turns yellow | Pass |
| Dropdown navigation menu for mobiles | To drop down when clicked on | Clicked on navigation icon | navigation menu drops down | Pass |
| Fixed navigation bar with navigation menu on screens larger than tablets | To show on screens larger than tablets | Checked on screens larger than tablets | It shows as expected | Pass |
| navigation links | To direct the user to related pages | Clicked on navigation links | They all direct to their related pages | Pass |
| Showing the active page in the navigation bar with an underline | To underline the related navigation link for the active page | Clicked on the links | The related link to the active page becomes underlined | Pass |
| Navigation links hover effect | To become yellow with a yellow underline by hover on for desktops | Hovered on links | They turn yellow and a yellow underline appears | Pass |
| Footer link icons | To open in a seperate tab | Clicked on each icon | They all direct to their related links openning in a new tab | Pass |
| Footer icons hover effect | To turn yellow on hover for desktops | Hovered on | They turn yellow when hovered on | Pass |

* **Home page**

 | Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| Responsive content in About section |  The paragraphs show in columns in screens larger than tablets | Opened Home page on larger screens | Content shows in three column | Pass |
| form link | To direct to Find Players page | Clicked on link | Find Player page opens | Pass |
| Find Players button | To direct to Find Players page | Clicked on Find Players button | Find Players page opens | Pass |
| Find Players button hover effect for desktops | To turn into white text and blue background when hovered on | Hovered on button | Text turns white while button background turns blue | Pass |
| Responsive content on Padel Benefits section for screens larger than tablets | The list centers in the page | Opened on screens larger than tablets | The list centers | Pass |

* **Find Players page**

 | Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| Submit form | To require enteries on all fields marked with asterisk | Tried submitting without enteries | Doesn't submit and requires enteries | Pass |
| Submit form | To accept enteries only in correct format for every field | Entered wrong enterie format | Doesn't submit and requires correction | Pass |
| Vamos! button | To submit the form successfully | Clicked on Vamos! button | Submits the form and shows all the data sent to server | Pass |
| Fieldset border and legends display on mobiles | Hidden border and left-aligned legends | Opened on mobile | Shows as expected | Pass |
| Fieldset border and legends display on screens larger than tablets | To displays dotted blue border and center-aligned legends | Opened on screens larger than tablets | Shows as expected | Pass |
| Vamos! button hover effect for desktops| To turn into white text and blue background when hovered on | Hovered over the Vamos! button| Text turns white while button background turns blue | Pass |
| Submit page | To open after submitting the form successfully | Filled in the form correctly and clicked on submit (Vamos!) button | User sends to submit page | Pass |


* **Gallery page**

 | Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| Gallery images on mobiles | To show in a single column | Checked on mobile | Shows in a single column | Pass |
| Gallery images on tablets | To show in three columns | Checked on tablet sized screens | Shows in three columns | Pass |
| Gallery images on desktops | To show in four coulmns | Checked on desktops | Shows in four columns | Pass |
| Gallery images hover effect for desktops | The image to come forward and become bigger | Hovered on gallery images | Each comes forward and become larger | Pass |

### Solved Bugs

An issue was reported after some friends with iPhone mobiles had tested the website. The text content "Vamos!" wasn't showing on the submit button on Find Player page in iphone devices. Trouble shooting for this problem was quite hard and time consuming as the submit button was performing just as expected on all screen sizes in Chrome developer tools and the issue was very specific to iPhones. I solved this issue at last by moving the styles targetting the submit button above the styles targetting the input and selection fields in style.css. 

Another issue occured after I created my initial README.md file on Github and not directly in my IDE workspace and commited the changes on Github. After that I was not able to add, commit or push the changes on my workspace and needed to pull to origin and get help from a Code Institute tutor to be able the merge the README.md file I had created and commited to the repository remote and from outside of the IDE.


### Known Bugs

The fields related to input type="date" and input type="time" don't follow the CSS styles intended for them when showed on iphone mobiles. After spending so much time trying to troubleshoot and find a solution to this issue, discussing it with my mentor and tutors; it seems like this might have occured due to iOS safari compatibility and the fact that input time and date are not fully supported in all browsers. I decided to accept the fact that these input fields appear slightly different when displayed on iphones for now.

- - -

## Credits

### Code Used

Throughout the entire project developement I have used the Code Institute course material for HTML and CSS. I have used the tutorials for Love Running walkthrough project represented on the course in order to set up and get started with my project properly, make a dropdown navigation menu using checkbox for mobile screens and make a masonry design for how the images display on the Gallery page.

I have used [Stack Overflow](stackoverflow.com) to get some ideas for how to use regular expression in order to define patterns for the form input validation of input type="text" and input type="tel".

I have as well used the tutor support for how to link to email and phone number in the footer in a way that the user will be linked to user's email client with a specified recipient by using the code <a href="mailto:someone@example.com"></a> and trigger a phone call (for mobiles) by clicking the phone icon link in the footer, using the code <a href="tel:phone-number"></a>. 

### Content

For documentation and creating my README.md file I have taken inspiration from the sample README.md file that my mentor shared with me [The Quiz Arms](https://github.com/kera-cudmore/TheQuizArms/blob/main/README.md) as well as the README.md sample available on the course for Portfolio 1: Assessments Guide Preview.

I used this article available at google fonts in order to understand the critera for choosing a proper font type, [A checklist for choosing type](https://fonts.google.com/knowledge/choosing_type/a_checklist_for_choosing_type).

All the imagery that have been used and where I have taken them from are mentioned under [Imagery](#imagery).

### Acknowledgments

I would like to acknowledge

* My Code Institute mentor Jubril Akulade for reviewing my project and inspiring me to improve my website.
* The Code Institute tutor team for being available and guiding me whenever I was too stuck troubleshooting the issues during the developement of my project.
* My partner and my friends for taking the time and testing my website on their devices and giving me constructive feedback.












