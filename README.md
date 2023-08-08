# TigerStrike Karate <br>
![titleimage](documentation/doc_images/amiresponsive.png) 
# Description
TigerStrike Karate is a fictional Webpage installed to extend the online presence for the TigerStrike Karate School. The viewer will be able to get a first look into the Karate School by seeing students in practice and getting a introduction of the sensei(main coach). Website visitors will also be able to see the location of the school, opening hours and class times. Furthermore there is a signup form, where you are actually able to sign up online to the karate school or just leave a non-committal inquiry via the message form at the front page.

[Click here to view the Live Project](https://arp-25.github.io/tiger_strike_karate/index.html)


## Table of contents

1. [User Experience (UX)](#User-Experience-(UX))
2. [Features](#Features)
3. [Design](#Design)
4. [Technologies Used](#Technologies-Used)
5. [Testing](#Testing)
6. [Deployment](#Deployment)
7. [Credits](#Credits)


## User Experience (UX)

### User stories

- Visitor Goals
    1. Easily understand what the aim of the page is.
    2. Comfortably navigate through the site and access the content.
    3. Be able to get a quick idea of the benefits signing up to a Karate School.
    4. Get a grasp if a signup is suitable for one self.
    5. Have information where the school is located.
    6. Get in contact via text message, e-mail or phone.
    7. Sign up online.


## Features

### Existing Features

- F01 Navigation Bar
     - The navigation bar is kept very simple to provide a uncomplicated and clear way to navigate through the site. It consists of a logo link to the left and home, gallery and signup link to the right.

![Navbar](documentation/doc_images/readme_features_f01.png) 

- F02 Banner with Slogans
     - The banner is there to greet the site visitor with a welcoming picture.
     - The purpose of the slogans is to show the visitor what benefits he can expect from joining the school.

![BannerSlogans](documentation/doc_images/readme_features_f02.png) 

- F03 Meet the Sensei 
    - In this section visitors are able to get a introduction to the TigerStrike Karate sensei(main coach) by getting a picture, video and short text description presented.

![MeetTheSensei](documentation/doc_images/readme_features_f03.png)   

- F04 Location and Classes
    - Here the visitor gets access to the school location and opening times/classes.
    - For the location a google maps iframe element got embedded.
    - For the classes the user will get the infos from a apparent table.

![LocationClasses](documentation/doc_images/readme_features_f04.png) 

- F05 Contact
    - Small contact form for curious visitors which want to get in touch with a non-commital message.

![Contact](documentation/doc_images/readme_features_f05.png) 

- F06 Footer
    - The Footer element is showcasing all social Links.

![Footer](documentation/doc_images/readme_features_f06.png) 

- F07 Gallery
    - Gallery implemented as a slider to give user a comfortable and easy way to watch through the pictures.

![GallerySlider](documentation/doc_images/readme_features_f09.png) 

- F08 Sign up
    - Form for signing into the school.

![SignUp](documentation/doc_images/readme_features_f08.png)

### Table of Features and User Stories combined

In this table you can see if a User Story from Section One is covered by a implemented Feature.

|                | US01     | US02     | US03     | US04     | US05     | US06     | US07     |
|----------------|----------|----------|----------|----------|----------|----------|----------|
| F01 NavBar     |          | x        |          |          |          |          |          |
| F02 BanSlo     | x        |          | x        |          |          |          |          |
| F03 MeetTS     |          |          |          | x        |          |          |          |
| F04 LocCla     |          |          |          | x        | x        |          |          |
| F05 Contac     |          |          |          | x        | x        | x        |          |
| F06 Footer     |          |          |          | x        |          | x        |          |
| F07 Galler     | x        |          | x        | x        |          |          |          |
| F08 SignUp     |          |          |          |          |          |          | x        |

### Features which could be implemented in the future

- Student reviews/comments.
- Login to access personal account which can contain infos about progress in the course, a learning plattform where you can re-watch lessons or technique videos.
- Forum.
- News section.


## Design

-   ### Imagery
    -   The pictures throughout the site are chosen to present the TigerStrike Karate School including their sensei and students. The viewer is directly given the information of what he can expect from joining the school. 

-   ### Colour Scheme
    -  The color Scheme is adjusted to fit to a Karate School. For example a Karate Gi is usually associated with a white robe and a black belt and just has a minimal look. Therefore a simple white has been chosen for the font and a dark gray (rgb(31, 33, 34))for the background and several elements to keep it clean and provide a good contrast.

-   ### Typography
    -   Google Fonts was used to import Roboto Condensed font into styles.css. It was chosen because it has a modern design, balanced proportions and open letterforms which contribute to its readability.

-   ### Wireframes

    [WireFrames TigerStrike Karate](https://www.figma.com/file/pGU6MCfsyvi8nVRwshKWAI/TigerStrike-Karate?type=design&node-id=0%3A1&mode=design&t=HXw8p3nVZATMsvNZ-1)

    ![WireFrames Screenshot](documentation/doc_images/wireframes.png)


## Technologies Used

### Languages Used

-   [HTML5](https://en.wikipedia.org/wiki/HTML5)
-   [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)
-   [Markdown](https://de.wikipedia.org/wiki/Markdown)

### Frameworks, Libraries & Programs Used

-   [CodeAnywhere:](https://app.codeanywhere.com/) was used as IDE to create the code. It provides good compatibility with github and offers useful IDE extensions.
-   [Google Fonts:](https://fonts.google.com/) was used to import fonts.
-   [Font Awesome:](https://fontawesome.com/) was used to add icons for aesthetic and UX purposes.
-   [GitHub:](https://github.com/) is used as the respository for the projects code after being pushed from Git.
-   [ILoveImg:](https://www.iloveimg.com) was used for resizing images and editing photos for the website.
-   [Figma:](https://www.figma.com/) was used to create the wireframes during the design process.


## Testing

### Validator Testing

For validator testing https://validator.w3.org/ and https://jigsaw.w3.org/css-validator/ were used. The code runs warning and error free.

### Performance

Google Lighthouse in Google Chrome Developer Tools was used to test the performance of the website.

![Lighthouse](documentation/doc_images/lighthouse.png)

### Browser Compatibility

- Testing has been carried out on the following browsers :
    - Chrome Version 115.0.5790.111 (Official Build) (64-bit)
    - Firefox Version 116.0 (64-bit)
    - Edge Version 115.0.1901.188 (Official build) (64-bit)
    - Safari on iPhone (iOS-Version 14.6 (c))

### Test Cases and Results

![ManualTesting](documentation/doc_images/testing_table.png)


## Deployment

### How this site was deployed

- In the GitHub repository, navigate to the Settings tab, then choose Pages from the left hand menu.
- From the source section drop-down menu, select the Master Branch.
- Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.
- Any changes pushed to the master branch will take effect on the live project.

  The live link can be found here - [TigerStrike Karate](https://arp-25.github.io/tiger_strike_karate/index.html) 

### How to clone the repository

- Go to the https://github.com/ARP-25/tiger_strike_karate repository on GitHub.
- Click the "Code" button to the right of the screen, click HTTPs and copy the link there.
- Open a GitBash terminal and navigate to the directory where you want to locate the clone.
- On the command line, type "git clone" then paste in the copied url and press the Enter key to begin the clone process.


## Credits 

### Content 

All content was written by the developer.

### Code

Examples and instructions for basic html and CSS code:

- https://developer.mozilla.org
- https://www.w3schools.com
- https://learn.codeinstitute.net/

Additional searching for problemfixes:

- https://stackoverflow.com
- https://www.youtube.com/?gl=DE&hl=de

### Media 
 
- All icons were taken from [Font Awesome](https://fontawesome.com/).
- All fonts used were imported from [Google Fonts](https://fonts.google.com/).
- All images were downloaded from [Pexels](https://www.pexels.com).

### Shoutout

Special thanks to my Mentor Oluwafemi Medale for helping me out whenever I have a question.