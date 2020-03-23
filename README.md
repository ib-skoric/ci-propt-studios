![alt text](./assets/images/documentation/logo_small.png "ProPT Studios Logo")
# ProPT Studios 

ProPT Studios is a professional personal training studio based in Clonee, Co Meath.

This website prevides overview of services, team as well as studio location, classes timetable & contact 
 
## Live demo

Live demo of the website can be found at https://ib-skoric.github.io/ci-propt-studios/ 

![Responsive showcase image of ProPT website](assets/images/documentation/resposive-showcase.png "Logo Title Text 1")


## UX

### User stories

As a prospective client, I want to see what this gym offers, what do people say about it and who are the trainers.

As a prospective and current client, I wish to be able to view the time table and book a slot online. 

As a potential client I want to contact the team because I have some additional questions.

### Strategy

The main design goal is to make important information accesible to new/existing clients while mainataining clean and modern look.

### Scope

For the prospective clients, website offers insight into what the gym offers & who the trainers are. For the existing clietns, the website offers information about the classes & offers curretnly avaialable.

### Structure

Home page displays key 'features' of the gym under the 'What we offer' section.
This is followed by the testemonials of those that are current gym goers.
After which the user can see who the trainers are and finally where the gym is located. 

Classes & timetable offers the user a overwiew of classes the gym currently does as well as the timetable for the week. Below this, the user can read frequently asked questions & their answers.

Contact us page provides a form for users to contact the trainers and to ask any additonal questions regarding the gym and what it offers

### Skeleton

[Landing Page wireframe](assets/images/documentation/landing-wireframe.jpg)

[Classes & Timetable page wireframe](assets/images/documentation/classes-wireframe.jpg)

[Contact us wireframe](assets/images/documentation/contact-wireframe.jpg)

Gallery page was created after a middle project review with my mentor and design was done 'on-the-fly'.

### Surface

Colour scheme chosen for this project reflects the ProPT branding colours.

![alt text](./assets/images/documentation/colour_scheme.png "Project colour scheme")

| Colour name       | Colour RGB Code    
| -------------     |:-------------:| 
| Dark Gunmetal     |#212529
| Mikado Yellow     |#FFB10
| White             |#FFFFF

Font used throughout is Google font's Lato - https://fonts.google.com/specimen/Lato 

## Features

### Existing Features

ProPT studios, until now, did not have a website, so there were no existing fetures.

Marketing and client updates were provided through social media such as Facebook.

### Features Left to Implement

The idea is to implement a back-end for scheduling clients & bookings at a later date.

The Contact us form curretnly has no action, no email gets sent after the button is clicked. The idea is to implement automatic email sending to trainer's emails after the user submits the form. 

After professional photographs are done, the stock photographs currently on the website would be replaced. Actual social media profile links of trainers have intentionally been left out.

## Technologies Used

1. HTML5
2. CSS3
3. Bootstrap v4.4.1 - https://getbootstrap.com/
4. Font Awesome - https://fontawesome.com/start
5. JavaScript - *see Credits*
6. Animate on Scroll (AOS) - https://github.com/michalsnik/aos 

## Testing

The user is presented with a landing (home) page. Website can be navigated using the navingation links at the top-right of the page. Call to action button in the jumbotron element scrolls down the page to the 'What we offer' section of the website. Image to the right in all jumbotrons is hidden on mobile to save precious horizontal viewport space. Scrolling down the page user can see user testemonials and scrolling further profiles of trainers with their short bios. Social media profile links are located under bios (these have been intentionally left out, refer to *Features Left to Implement* section). All of these link open in new tab using _blank attribute. Scrolling down user is presented with a Google Maps map showing the gym location. Map is interactive and scales down well to all resolutions. 

Under Classes and Timetables page user is presented with a range of classes the gym offers. Scrolling down, user can view the timetable which is presented in a image format. By clicking the button below the image, a new tab opens with the PNG image which user can save onto their device. 

Gallery page has no user interaction, animations of hidden from viewport images are achieved using Animate On Scroll library - refer to *Acknowledgements* section

Contact us page contains a contact us form with 5 elements - name (required), email (required), phone number (not required), drop down selection of what the user's query relates to and a text field (required). If any of the required fields are left blank, user is promted to enter them again. Similarly if the email address is in wrong fromat (ie. missing @ sign) user will be promted to enter valid email adddress. Submit button currently has no action (refer to *Features Left to Implement* section)

This has been tested using (all on Macbook Pro with macOS 10.15.3):

+ Google Chrome 80.0.3987.132
+ Opera 67.0.3575.79
+ Firefox 74.0
+ Safari 13.0.5
+ Microsoft Edge for Mac 80.0.361.66

+ Google Chrome on Android (Samsung Galaxy S10+) 80.0.3987.149
+ Safari (Apple iPhone XR) - TBC
+ Safari (Apple iPad XX) - TBC
+ Internet Explorer 10 - via https://www.ieonchrome.com/ 
+ Internet Explorer 11 - via https://www.ieonchrome.com/

## Deployment


## Credits

### Content

All textual content on the website has been written my me.

### Media

Logo has been sourced from [PrPT's Facebok page](https://www.facebook.com/proptstudios/)

Photos have been sourced from [Pexels](https://www.pexels.com/). 

SVG Illustrations used in jumbotrons have been sourced from [Undraw](https://undraw.co/illustrations). 

GIMP 2.10 Image editor has used to apply different effects to images & Sketch 61 for editing SVG files. 

### Acknowledgements

To animate elements Animate on Scroll library's been used - https://github.com/michalsnik/aos.

Code snippet tutorial on how to use inline JavaScript for a button to mimic link opening on click has been found [here](https://www.w3docs.com/snippets/html/how-to-create-an-html-button-that-acts-like-a-link.html).

Code snippet tutorial on how to use inline JavaScript for a button to scroll down to a certain seciton on the website has been found [here](https://stackoverflow.com/questions/16349490/html-css-buttons-that-scroll-down-to-different-div-sections-on-a-webpage).

Code for embeded Google Maps has been generated using [maps.ie Create a map tool](https://www.maps.ie/create-google-map/).


