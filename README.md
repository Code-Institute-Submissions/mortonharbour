# Morton Harbour Website Redesign
The clients have requested a redesign of their current website to make it more user-friendly and because they are unhappy with their current site, especially in respect to the colour scheme used.

The website will enable users to get more information on mental health in general as well as have the opportunity to meet the therapists and book an appointment.

## UX

This website is for individuals who are looking for a mental health professional and also for those who just want some more information on mental health therapies.  

The website has been made easily navigable and the font and colours used was specifically chosen to provide the user with a calm and confident feeling.

UX files have been included and can be found under the UX folder.  Wireframes are also added here.  You will note that the wireframes are slightly different to the final product as when developing the website, a better layout was used and it was better customised for usability.

## Features

The website has been divided into a number of pages:

* Index – this is the landing page, with a brief introduction to Morton Harbour and the services they provide as well as links to meeting the team and the newsletter signup.
* About us – this is an introduction to the team members and also a place where the user can see why they are trustworthy and can have confidence in the service that will be provided.
* Therapy – this is split into pages for psychotherapy, hypnotherapy and also emergency therapy.  Each page explains the particular topic and what can be provided by the therapists at Morton Harbour.  In a future build, Emergency Appointments will be amended to include an online appointment booking form.
* Testimonials – a list of Morton Harbour testimonials are provided and will be updated from time to time to include more recent ones.
* 1 in 4 Blog – this is where Morton Harbour will post up to date articles written by themselves other healthcare professionals to broaden the understanding around mental health issues and also to provide some comfort to those suffering with mental health problems.
* Contact – this provides all the contact information for Morton Harbour to enable to users to make contact with Morton Harbour in the best way for them.
* Newsletter – the newsletter feature has been added to most pages so that all users irrespective of which page they are on, will be able to sign up for the newsletter.  The newsletter will be enabled in a later build and is currently non-working.
* Footer – includes links to the mental health registers Morton Harbour therapists belong to.
* Privacy Policy – this has been added to comply with GDPR and to ensure users are aware of what data will be collected and how it will be used and stored.

## Features Left to Implement

* Currently the some of the href links are left with a ‘#’ as the website is not yet active and is to be used as a project for now.  Once the other features below have been enabled, the links will be activated for when the website goes live.
* Newsletter – the newsletter isn’t yet linked up and this will only be done in a future build.
* Emergency appointments – an emergency appointment form will be created in a future build so that appointments can be made online by selecting a specific date and time.  Stripe will also then be linked up to the site so that a user can make an online payment for the emergency appointment when booking.
* The modals for newsletter and contact form submission have an unresolved issue where the form being submitted ignores the required fields.  From research however this seems to be fixed by using JavaScript which I do not currently have the ability to implement so will be fixed in a later build.

## Technologies Used

I used the following technologies for the website.

- HTML
    - The project uses HTML as the main language for the website.
- CSS3 
    - I used CSS3 to customise the style of the website and also to custom style some of the Bootstrap 4 used.
- Bootstrap4
    - Bootstrap 4 is the latest HTML, CSS3 and JavaScript framework, which enables faster development of websites.
- Google Fonts 
    - Google Fonts is a library of free fonts that can be used.  The fonts used in the website is linked from Google Fonts.
- Font Awesome
    - Font Awesome is a library of icons that can be used, there are both free to use and paid for icons.  The icons used on the website are all from the Font Awesome free to use catalogue.
- Git 
    - Git is used for version control and it was used to commit files to git regularly so that changes could be tracked and reverted to if required.
- GitHub
    - GitHub is a repository hosting service that enables us to upload our git repository and host it online.

## Testing

### **Manual testing** 

Whilst developing the website, I frequently previewed the website in order to check the layout and content as well as its responsiveness.  I did this throughout the development period.  

I also created different versions of pages and tested these by previewing to see which versions were more appropriate for the overall design and goal of the website.  The previous versions of pages can be found in the folder called Archive.  

I did come across some issues with the navbar and some other Bootstrap 4 issues where I had to do some research in order to fix some of the layout issues that I came up against.  Some of these were the alignment of the dropdown-items when in mobile view and then again when in desktop view; the order in which images appeared on the about us page and also the order of testimonials so that they didn’t have two of the same colour cards next to one another when in mobile view; font size for mobile and desktop and normal text alignment ie justify for desktop and left aligned for mobile, line-heights etc.  The layout of the About Us page was particularly difficult to finalise as a number of previous designs wasn’t very user-friendly so had to be reworked.

I uploaded to GitHub and then also tested the website using iPhone 5se, 6 and 7.  Most responsive testing was completed in Chrome.

I frequently committed changes to Git to show the progress made throughout and the changes to the website layout.

### **Online validators**

I used HTML and CSS validators to ensure that there were no issues overall with the final product and had to fix a number of issues.  Some of these issues were:

#### *HTML Validator* (https://validator.w3.org/)

- fixed all html file names so there were no spaces
    - for example About Us changed to About_Us
    - updated all the links on all the pages to reflect the changes made
- fixed comments so that they are format of <!--comment--> and not <!-------comment-->.  
- changed </br> to <br> for breaks
- added role to buttons
- updated <img> to have alt attributes for those where the alt attribute was missing
- removed stray /div on all pages that have the newsletter
- removed stray /ol tag from the privacy policy
- under the privacy policy there were a number of 'br' tags and 'table' tags within the 'ol' which was incorrect so reworked so that I did not use a list, but instead used 'p' tags instead.

#### *CSS Validator* (https://jigsaw.w3.org/css-validator/)

* Value Error : font-size Parse Error (1600 – 300 ))) – unable to resolve this error, checked help pages and normally this is resolved by adding appropriate spacing, however this has not resolved the issue.  The appropriate semi-colon is there and also this does not require px or similar at the end of the numbers.
* There were also a number of warnings regarding the use of –moz-transition; -o-transition and –webkit-transition or transform, however these are all required for the different browsers.

## Deployment

The website is deployed to GitHub and is an exact copy of the version on Cloud 9 ide.  I created a repository on GitHub called mortonharbour and then pushed the files to the repository from Cloud 9 ide.

In GitHub I then opened the settings menu and under GitHub pages selected the source as Master Branch to host the webiste on GitHub.

I have deployed as a master branch and the website address is below.  In order to view the website, you can copy and paste the below link into your browser's address bar.  This is a responsive website and will work on mobiles, tablets, laptops and larger devices.

https://salomelamprecht.github.io/mortonharbour 


## Credits

### Content

Hover.CSS (https://github.com/IanLunn/Hover)

* I also used the shadow on hover custom CSS from hover.css by Ian Lunn on GitHub.

### Acknowledgements

* Morton Harbour for allowing me to create a new website for them and to use this as my first project.

