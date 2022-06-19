# The Hike Style's
![Screenshot logo](./assets/media/logo.png)

## Introduction
The Hike Style’s is a site about a social community among people who want to practice outdoor sports between nature and who want to share incredible and unique moments. The site is aimed at people who are adventurous and who want to know nature in interesting places , which where the interest in making new friends and making social encounters is the most important. The Hike Style’s will be useful as a reference for those looking for information on Hike and biking in nature.

![Responsive Screenshot](./assets/media/responsive.png)

[View the live Website on Github Pages](https://llancruzz.github.io/hike-style/) Please note: To open any links in this document in a new browser tab, please press CTRL + Click.

## UX 
### The Hike Style's:
The Hike Style’s is a site created for physical activities among nature . That is, where I used much of the design in green color. The green color represents nature, but also represents growth and vitality. The green color is associated with health and tranquility. It is a balanced and rejuvenating color.

### Color Palette:
![color used in this project](./assets/media/color.png)

## Wireframe mockups
Initially I utilised Balsamiq to produce low fidelity wireframes to organise the site structure, potential content placement locations.

* [Home page Wireframe](https://github.com/llancruzz/hike-style/blob/main/assets/media/home-page.png)
* [Mission page Wireframe](https://github.com/llancruzz/hike-style/blob/main/assets/media/mission-page.png)
* [Photos page Wireframe](https://github.com/llancruzz/hike-style/blob/main/assets/media/photo-page.png)
* [Join Us page Wireframe](https://github.com/llancruzz/hike-style/blob/main/assets/media/join-us-page.png)
* [Thank You page Wireframe](https://github.com/llancruzz/hike-style/blob/main/assets/media/thank-you-page.png)

## Features

### Common Features 
* Navigation Bar

  * The navigation bar features a common design across all four pages in keeping with convention with a logo on the left hand size and the navigation links on the right.
  * The navigation bar includes links on the logo, Home, Mission, Photos and Join Us. The various title links head to their respective pages for easy navigation. The logo links back to the homepage as a typical shortcut users will likely be familiar with.
  * A horizontal line appears under the current page as a visual indicator to the user as to which page they are currently on. With a line appearing underneath the text on hover to visually indicate to users that they are clickable.
  * A color is activated once you click on each navigation link. This means that the page you clicked was visited.

![Navigation bar screenshot](./assets/media/navigation-bar.png) 

* Hero Image

  * Only Home page includes a hero image with a text overlay which further indicates to the user exactly which section of the site they are on.

![Screenshot Hero Immage](./assets/media/hero-image.png)

* Footer
  
  * The lower section of the common footer includes logo links to each of the social media platforms. This provides the user with a visual call to action to prompt them into visiting the organisations social media profiles.
  * These links offer an unintrusive method of promoting the social media channels to the user, providing benefits to the organisation by the way of increased social media following.
  * The lower footer section also includes the copyright notice.

![Screenshot Footer](./assets/media/footer-lower.png)

### Mission Page Features
* Our Mission

  * The main section of the Mission page includes a text about The Hike Style’s mission. It provides users with the main goal. The mission page contains two images in circle format.

![Mission page screenshot](.//assets/media/mission.png)

### Photos Page Features
* Our Gallery

  * The photos page allows users to access high-quality photos of each adventurer’s encounters and activates. This allows users to easily identify the types of journey each person has experienced.

![Photos page screenshot](./assets/media/photos.png)

### Join Us Page Features
* Join Us

  * The contact form provides users with the ability to contact The Hike Style's directly with any queries or comments they may have. The user is asked for their full name, email address and a message.

    ![Join Uss page screenshot](./assets/media/join-us.png)

### Thank You Page Features
* Message

  * When submitting the form, the user will be redirected to a new page, which will thank them for subscribing. The page contains a motivational message. No user information will be stored.

    ![Thank You page screenshot](./assets/media/thank-you.png)

## Testing

The site has been tested by friends in different browsers ( Chorme, Firefox, Safari) and in different smarthphones, laptop and desktop. I personally tested the site extensively with dev tools to ensure the site works responsively not only on mobile devices but also on medium to larger screens. I have personally tested the site extensively with development tools to ensure that the site works responsively not only on mobile devices, but also on medium to large screens. I realized that in some sizes ,the responsiveness was not 100% complete. I fix this problem along with some internet searches and Slack Comunnity and realized that I was using enough property position. So I studied deeply how to use Flex-Box and manage to solve the problem. 

### Validator Testing
* HTML

  * No errors were returned when passing through the official W3C Validator.
    
    * [Home Page](https://validator.w3.org/nu/?doc=https%3A%2F%2Fllancruzz.github.io%2Fhike-style%2Findex.html)
    * [Mission Page](https://validator.w3.org/nu/?doc=https%3A%2F%2Fllancruzz.github.io%2Fhike-style%2Fmission.html)
    * [Photos Page](https://validator.w3.org/nu/?doc=https%3A%2F%2Fllancruzz.github.io%2Fhike-style%2Fphotos.html)
    * [Join Us Page](https://validator.w3.org/nu/?doc=https%3A%2F%2Fllancruzz.github.io%2Fhike-style%2Fjoinus.html)
    * [Letter Thank you Page](https://validator.w3.org/nu/?doc=https%3A%2F%2Fllancruzz.github.io%2Fhike-style%2Fletter-submit.html%3Fname%3DAlan%26email%3Dalan.silvacruz%2540hotmail.com%26message%3DHi%26submit%3DSubmit)

![Screenshot WSC Validator](./assets/media/validator-html.png)

* CSS

  * No errors were returned when passing through the official (Jigsaw) Validator.

    * [Link to results](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fllancruzz.github.io%2Fhike-style%2Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=pt-BR)

![Screen Shot Results CSS validator](./assets/media/css-validator.png)

* Lighthouse

  * I generated a lighthouse report for the deployed site through the Google Chrome Dev Tools. I generated both a desktop and mobile report. The two reports, both for mobile and desktop, reported that the image sizes were too heavy to load. I redacted the images and turned them into Webp archive by the site [EZGIF.COM](https://ezgif.com/jpg-to-webp) and then I improved the performance score.

    * Mobile 
    ![Screenshot Mobile Score](./assets/media/lighthouse-mobile.png)

    * Desktop
    ![Screenshot Desktop Score](./assets/media/lighthouse-desktop.png)
  
  



