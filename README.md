# Monkees Website - Milestone Project 1

## The Brief:

> ### Create a Website for a Band
>Build a static (front-end only) website for a band. 
>The band is a 1960’s rock band and have around 50 years experience of performing live at numerous events around the world. 
>**You have been given the following requirements after interviews with the client’s representatives:**
>Their primary target audiences are their fans and potential fans who wish to use the site to see and hear clips from their back catalog, 
>and any new material as it becomes available. Also, the band would like to use the site to showcase their music and publicise 
>their availability to perform at events such as weddings and Christmas parties.
>**The band has provided a number of assets that they would like to showcase on their website:**
>* Photos of the band members
>* A video clip
>* Audio clips

>Also, they are in the process of creating a social media presence and would like to add links to their Facebook, Twitter and YouTube pages.

Given this set of criteria, I decided to create a website that conformed to the aesthetic of a sixties pop band through its style of colors and fonts.
The navigation would be basic and therefore, intuitive. The aim is not to break new design and functionality ground but to create a site
that is easy and obvious to move around, while fulfilling all of the above criteria.

There will be some functionality added at a design and presentation level that will not work on the site at its current stage of development. This
project is for showcasing HTML5 & CSS3 only. For that reason, some buttons and forms will be used to demonstrate future possible actions by users,
however, the functionality is not present at this time. Those elements that require further development can have their functionality added at a later
date, when the requisite coding languages have been acquired.

## UX

The primary stakeholders involved in this website are the band - _The Monkees_. They wish to not only showcase some of their music to established fans
but to also bring some tasters to potential fans and prospective clients. They are seeking to garner greater employment through performing at weddings 
and events too. They also wish to sell their merchandise. Given this last requirement, I have provided a link in the navbar to their already established
website that hosts and sells their merchandise. That link has a `target="_blank"` attribute set so as to not navigate the users away from our site.

The other stakeholders involved in this site are the fans and potential clients. These users are looking to find and listen to music while gathering
information about when and where the band is playing, or is available to play. Given these reasons, I have included a tour schedule with locations
and embedded a contact form that potential clients can fill in in order to contact the band about their availibility.

### The Monkees
* They want to promote their music.
* They need potential clients to be able to book functions.
* They want to sell their merchandise.
* They need fans and potential clients to have information about their tour dates and availibility.

###  Fans
* They want to be able to listen to the music and watch some videos of the band.
* They want to access information about the band and their tour dates.
* They wish purchase band merchandise.

### Potential Clients
* They want to hear some of the bands music and see how they perform.
* They need to know the bands schedule and when they could be available.
* They need to contact the band to arrange possible performances.

Please see the [wireframes](https://github.com/Hermeticpoet/milestone-project-1/tree/master/Wireframes) directory in the repository for wireframes of the Mobile First pages of the project.

------------

## Features

### Established Features
* Video - allows users to see a video of a performance of the band.
 
* Image links - allows users to access the wikipedia pages of each band member and the group as a whole. These open to external pages.

* Contact / Booking form - allow users to contact the band for events bookings.

* Audio media players - allow users to play a number of songs from past albums.
 
* Tour calender and venues list - allow users to see when and where the band is playing.

* Navbar buttons - allows users to navigate around the site with inutitive ease.
 
* Footer - provides users with copyright information and to contact or follow the band through social media links. 
  These links also open to external sites.

#### Hidden Features
* There is an easter egg of sorts to be found on the listen page. Users who hover their mouse over the album covers will get a list of title tracks.

### Features Still to Implement
* Back-End functionality - The contact form and Buy Now buttons will need some additional coding to become fully functional.
  This will also be the case for purchasing tickets for shows through the site. Buttons have been added for design / layout
  purposes at this stage of development but they are not functional as yet.

------------

## Technologies Used

### HTML5
The project uses [HTML](https://www.w3schools.com/html/html5_intro.asp) to structure the site.

### CSS3
The project uses [CSS](https://www.w3schools.com/css/css_intro.asp) to style the site.

### BOOTSTRAP 4
The project uses [Bootstrap](https://getbootstrap.com/docs/4.1/getting-started/introduction/) to aid in both the styling (CSS and Components) 
and structure (Grid System) of the site, as well as aid in the creation of a responsive design (Grid System).

### Google Fonts
The project uses [Google Fonts](https://fonts.google.com/) to add specific fonts to aid in the personal design elements of the site.

### W3C Validators
I used the [W3C validation](https://validator.w3.org/) tools to check my code for this project.

### CSS Matic
All shadowing effects where created using [CSS Matic](https://www.cssmatic.com/box-shadow) shadowing tools.

------------

## Testing

### Scenarios:
#### Monkees User Story: 
_Promoting music & selling merchandise:_
* Go to **Home** page
* See if the latest album appears with a button to purchase it
* See if the video appears and that it can be played on all browsers
* Does the image of the band playin in Winter Gardens show up
 
_Providing information about the band:_
* Go to the **About** page
* See if all 5 sections appear with their respective images
* Does each section change color to highlight to user that it is a clickable link
* Do the links take user to an external wikipedia page for the relevant section

_Booking the Band for Events:_
* Go to the **Bookings** page
* See if the timeline of Bands schedule appears
* Check if veunues & dates for performances is also showing
* Provide a clear **_Contact_** form with placeholders to assist users

### Fans User Story:
_Accessing music, videos, merchandise and latest information:_
* Social Media links are provided for fans to click and follow the band
* Hovering over each social media links changes its color to highlight its a navigation link
* Tour dates and venues for performances are provided
* A **Store** link is provided in the header navbar to access merchandise
* Video and Audio files are embedded to allow for listening directly on the site

### Potential Clients User Story:
_Checking Availibility and Sampling some Music:_
* Video and Audio files are embedded to allow for sampling of band's music directly on the site
* Tour dates and venue scheduling allow clients to see availibility in what locations
* Contact form embedded to allow contacting the band for possible events

### Responsiveness of the Site
The site was tested with the 5 major browsers; Mozilla, Chrome, IE, Opera & Safari. All initial testing suggested no major issues with compatibility.
Chrome's devtools was further used to test cross-platform compatibility and the various breakpoints on my design. Bootstrap's grid system
allowed for most of this to work without too many issues. There were a few issues in regards to what rules I should apply to achieve my desired
outcomes. For instance, the use of .col classes with offsets to manoeuvre columns to the centre of the viewport or whether use flexbox. I have 
for the most part attempted to use flexbox rules, however, in some instances it was necessary to use the offset col classes instead.

Getting the images and video elements to shrink or expand at the various breakpoints was difficult and took some time. I consulted Stack Overflow 
and the W3C website for information about how to do so. After that, it was a matter of some trial and error to see what worked. Typically, these 
elements just required a specified width and a height set to auto.

I used rems and ems for sizing the most important typographical elements, including margin and padding. However, where I took code from other sites, 
such as, using the CSS Matic site to create box shadowing, I retained the site specific use of pixels. 

#### Development Issues
There was a particularly difficult issue with one element on 2 browsers. The song titles and their respective audio controls on the listen page did not 
align centrally on two of the browsers - Mozilla & Safari. Flexbox was used to align the items (heading & its controls) with one another and the same grouping below it. 
However, the first grouping that contains the 'Daydream Believer' song does not align correctly in these two browsers. This was made more puzzling by the 
fact that the same layout and style rules were used in the row below and the headings & audio controls aligned perfectly there? I did not manage to 
fully resolve this issue for those two browsers (as any change I made to correct the alignment for them would then affect the other browsers too) at that time.
Therefore, I rewrote the code in a less semantic manner and used only columns with offsets to align the elements. At that point, I discovered that I
had actually added an extra row container that was causing the original issue. This then allowed me to go back to my original code and use flexbox to align all
the elements correctly. Thus, resolving that issue. 

-----------

## Deployment

I created a repository on Github, linking my project on Cloud9 to it. I committed and pushed content to this respository at various stages of the 
project, e.g. when I created a new page structure or completed the styling of a group of similar elements. I then deployed the website through Github pages.

------------

### Credits

#### Content
* The code for the Social Media links and their transitions was taken from the UCD-Resume project. I did alter the style to suit my preference.
* The Google Fonts copyright Glyphicon was obtained at <https://glyphicons.bootstrapcheatsheets.com/#>.
* The video and image auto-sizing was obtained at <https://www.w3schools.com/css/css3_box-sizing.asp>.
* The code for the contact form was obtained from the Resume Project but slightly altered.
* The code for the inverse-collapsing-navbar was taken from <https://getbootstrap.com/docs/4.0/components/navbar/> and again personalized.
* The layout of the Grid System came from Bootstrap but was assisted with by my Mentor (Chris Zielinski).

#### Media
* The photos, video and audio files used in this site were obtained from <https://github.com/aaronsnig501?tab=repositories>. Github user
  Aaron Sinnot is a tutor with Code Institute.

------------

### Acknowledgments

* I used the template for the README.md provided by various students of Code Institute on Slack.
* The fixed appearance of the collapsed navbar button was suggested to me by numerous CI students on Slack.