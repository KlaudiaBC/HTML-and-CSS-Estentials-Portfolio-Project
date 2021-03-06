# HTML and CSS Essentials: "FindYOU" Portfolio Project
## Welcome!

<p align="center">
  <img src="https://github.com/KlaudiaBC/HTML-and-CSS-Estentials-Portfolio-Project/blob/a3dae41511896d59bd79bbfa2378a1048313fcd4/assets/images/readme-img/firstpic.jpg?raw=true" alt="responsive design">
</p>

### This is my Portfolio 1 Project regarding the Code Institute's Diploma in Software Development (E-commerce Applications).
It is a single page website, which contains four independent sections and the navigation bar (sticky on top of the page) designated to make all of the components easily accessible.

## Content
The theme of the website is meditation and mental self-improvement. Page is designed as a promotion of self-help that can be achieved through practises leading to control the mind. Nowadays, facing the corona crisis, there is more and more demand for therapy and psychological help. WHO calls depresion a common mental disorder and estimates that it can affect even 5% of the worldwide population therefore I believe the topic is very accurate to current social issues and following trends.

## User journey
- as first the user see a home page with a featured carousel which indicates the theme of the website (wellness, meditation, self-care)
- further: user is introduced with a basics of meditation
- user can also find the explanation of the positive effects of meditation
- the gallery of motivational pictures as well as a subscription form should provide the user with inspiration and encourage to join the community
- the main goal of development is to ensure a pleasant and satisfying journey
- a navigation bar sticked to the top of the page should provide easy access to any part of the page, user would like to go to

## UX Design:
### Strategy Plane:
There are several design practises to make a page easy to read and accessible:
- easy navigation - navbar sticked to the top of the page
- scrollspy - indicates user position on the page
- formatted amount of information with the possibility of learning more by clicking on anchor tags attached to particular positions
- important information formatted as bold
- included short video tutorial for beginners
- colour contrast- dark background as the response to latest web design fashion trends (see more in colour layout)

### Scope Plane:
There are following features included into project:
- logo - top of the page
- carousel including images
- navigation bar with scrollspy - top of the page
- social media links - in the footer
- YouTube video embedded in the iframe
- gallery
- input form

### Structure Plane:
The content is built via 4 separated sections:
- section 1 - Home page - a carousel with an images indicating the purpose and theme of the website
- section 2 - Our path - introduction of theories and goals
- section 3 - Inspirations - a gallery element containing inspirational images
- section 4 - Join Us - an input form which allows you to register for meditation meetings.

### Sceletorn Plane:
Wireframe project was designed for a desktop but the project is responsive and can be displayed on every device.
See the initial project in the Balsamiq Software:

<p align="center">
  <img src="https://github.com/KlaudiaBC/HTML-and-CSS-Estentials-Portfolio-Project/blob/a3dae41511896d59bd79bbfa2378a1048313fcd4/assets/images/readme-img/balsamiq_wireframe_project1.jpg?raw=true" alt="wireframe project">
</p>

## Layout
### Colour range
I have used the shade of blue colour (#123146) as a background. It starts dark from the top and fades slightly to a lighter shade on the bottom of the page.
As mentioned before, the reason for a dark mode of the page is the growing popularity of the dark background. There is also a significant number of users who are switching their settings on the devices to a dark mode. According to the latest search done by Android: 81,9% of android users claim to use the dark mode on their devices.This trend has been used by many tech giants, who have introduced the dark version of their website/application: Meta, Reddit, Youtube, Samsung, Apple and many more.
Colour #123146 is a mixture of blue and grey. Those shades also have many emotional connotations:
- dark blue is often recognized as a royal shade, often means reliable authority, loyalty and confidence
- a horizontal rule brings a touch of light blue - calming, shooting colour, symbol of connection with a nature

<p align="center">
  <img src="https://github.com/KlaudiaBC/HTML-and-CSS-Estentials-Portfolio-Project/blob/a3dae41511896d59bd79bbfa2378a1048313fcd4/assets/images/readme-img/colors.jpg?raw=true" alt="colours">
</p>

Additional colours:
- Orange: a colour of positive energy, which is a main message of the page. It brings a light, breaks the boringness and bursts with youthfulness, energy, and happiness. Designers also believe that orange colour inspires creativity and uplift people???s moods.
- Lightcyan - very bright shade of cyan, a colour of the text, logo and navigation bar, as a basic contrast to the background.

### Typography:
As a main font I choose Montserrat, a sans serif typeface. The reasons: high readability, often chosen for a simple and clean-looking design.

## Implementation process:
I have used this project to deploy different features, play with code and exercise the practises commonly used in developer work, like commiting a code and pushing it into a branch. The design of the page had changed multiple times as an effect of curiosity, trying different approaches and simply training the coding skills.
Stages of implementation:
- 15.01 - I have started this project from the very basic structure of HTML and CSS.
- 16.01 - First version included: nested lists, input form, tabel (with times of meetings). / Version 1 - see below.
- 17.01 - I have attached a bootstrap 4 extension to a project and started an exchange of bootstrap components with the one I wrote by myself. First feature was a carousel on the top of the page.
- 18.01 - I adjusted a navigation bar with a bootstrap version and built a section 2. I found the information provided too long and detalic, therefore I format the text for shorter and added extra anchor tags, which could provide more information for users who want to know more. There was a white double border around each paragraph.  / Version 2 - see below.
- 19.01 - I adjusted the footer into a bootstrap version, removed the borders from paragraphs (because it was bringing too much confusion and might affect user experience). I also adjusted an input form into a bootstrap extension.
- 20.01 - I added styling and moved the elements inside a dom to achieve a clear and easily readable front-end layout. Also the video needed to be embedded and social media buttons in the footer had to be fixed (did not display the logos).
- 21.01 - After a consultation with my mentor, I decided to add an extra section, where I included a gallery with inspirational images. I also made sure the elements on the page are correctly displayed and there is enough contrast between colours. I ran the first tests which indicated basic mistakes in HTML (fixed).  / Version 3 - see below.

<p align="center">
  <img src="https://github.com/KlaudiaBC/HTML-and-CSS-Estentials-Portfolio-Project/blob/a3dae41511896d59bd79bbfa2378a1048313fcd4/assets/images/readme-img/3version.jpg?raw=true" alt="3 versions of design">
</p>

- 23.01 - The code was approved by the W3C validator. Unfortunately my Performance score was very low, therefore I decided to optimise the images.
- 24.01 - I realised that the names for my classes are not specific enough and changed them to suit future implementations. I also reduced the amount of css written over an ID of the elements. Instead I added a class to the element, thanks to which I can use the particular css styling on other elements by attaching the particular class to this element. The pictures were still too big so I resized them. After a code review in my study group, I also added a feedback to a submit button and improved responsive design in the footer (display was not correct on the mobile devices).
- 26.01 - To make a project more correct with the standards, I had changed the css file and converted the main styling to a small size screen, then applied media queries to the medium/large size screen. I also changed the format of pictures from .jpg to .webp following a suggestion of the Lighthouse report, which improved my performance score (see below: testing).

<p align="center">
  <img src="https://github.com/KlaudiaBC/HTML-and-CSS-Estentials-Portfolio-Project/blob/2d610639ac0d4b7eec05f20cc1bab11c76e4c075/assets/images/readme-img/lighthouse1.jpg?raw=true" alt="lighthouse1">
</p>


After a consultation with my mentor I had added a scrollspy component, debug the form - I had included a name attribute to specify the name of a form Element.
- 29.01 - The last change before submitting my project was adding a discernible name to the links included in the paragraph element to improve my accessibility score. Then once again I ran all the tests - manual and via developer tools. The results are below.


## Technologies used:
- HTML5 and CSS3
- GitHub, Gitpod and Git
- Bootstrap version 4
- FontAwesome
- VS code
- Wireframe Software Balsamiq

## Acknowledgement:
In this place I would like to thank everyone, who added an knowledge and value to this project:
- Code Institute course materials and walkthroughs
- lead and support of my Code Institute Mentor - Guido Cecilio
- Code Institute Slack Community
- Tutorials by Mosh and Scrimba
- W3schools
- Stack Overflow
- Pexels (for images)

## Deployment:

The project was deployed to GitHub Pages using the following steps:

1. Log in to GitHub and locate the GitHub Repository
2. At the top of the Repository - go to "Settings" Button.
3. Scroll down the Settings page and locate the "GitHub Pages" Section.
4. Click the dropdown button called "None" and select "Master Branch".
5. The page will automatically refresh and provide you with a link to the "GitHub Pages" deploying your project in the live-view.

## Testing:
Tests have been performed on the: Firefox, Internet Explorer, Chrome and Safari.
Testing also included different devices:
- iPhone 11
- Lenovo TAB m10
- Samsung Galaxy Note
- Samsung Galaxy s20
- Motorola G10

All the results are consistent.

The features, which was taken into a testing:
- check if the buttons works
- check if images are displayed correctly
- check if all the anchor tags are opening in new tab
- check if the social media buttons are working and opening in new tab
- check if the submit button gives user a correct feedback
- check if the attached video is working
- check if the slide function in the carousel is working
- check if the scrollspy component is working correctly

### Lighthouse
- Desktop:
<p align="center">
  <img src="https://github.com/KlaudiaBC/HTML-and-CSS-Estentials-Portfolio-Project/blob/2d610639ac0d4b7eec05f20cc1bab11c76e4c075/assets/images/readme-img/lighthouse_desktop.jpg?raw=true" alt="lighthouse desktop score">
</p>

- Mobile:
<p align="center">
  <img src="https://github.com/KlaudiaBC/HTML-and-CSS-Estentials-Portfolio-Project/blob/2d610639ac0d4b7eec05f20cc1bab11c76e4c075/assets/images/readme-img/lighthouse_mobile.jpg?raw=true" alt="lighthouse mobile score">
</p>

### W3C validator:
- HTML
<p align="center">
  <img src="https://github.com/KlaudiaBC/HTML-and-CSS-Estentials-Portfolio-Project/blob/a3dae41511896d59bd79bbfa2378a1048313fcd4/assets/images/readme-img/w3c_validator.jpg?raw=true" alt="W3C validator score">
</p>

- CSS:
<p align="center">
  <img src="https://github.com/KlaudiaBC/HTML-and-CSS-Estentials-Portfolio-Project/blob/a3dae41511896d59bd79bbfa2378a1048313fcd4/assets/images/readme-img/w3c_css_validator.jpg?raw=true" alt="W3C CSS validator score">
</p>

### GT metrix:
<p align="center">
  <img src="https://github.com/KlaudiaBC/HTML-and-CSS-Estentials-Portfolio-Project/blob/5f53e2b75998c4b5f30ecb93ae635ffd66305590/assets/images/readme-img/gtmetrix.jpg" alt="GT metrix score">
</p>
