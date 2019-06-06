# Rockband Music Page

The Monkees is a 1960’s rock band and have around 50 years experience of performing live at numerous events around the world. They want to have online presence for their fans and to advertise their music toward potential public for gigs and events.
 
 
 Project Link: ![https://mgrammai.github.io/ucd-milestone-project/](https://mgrammai.github.io/ucd-milestone-project/)
 
 
## UX
 
### Strategy

Target Audience | Objective
------------ | -------------
**Fans** = already know the band | **Online presence** for fans = gathering information, knowledge about the band, news...
**Potential "buyers"** = people looking for a band/gig but don't know them yet | **Publicity** = showcases and event performance / sale the band to potentiel clients interested 


- **Reason why**:

Showing the public they exist and what they do.


### Scope

* Key functionnalities
    * Home page - navigation bar, contact and social medias
    * News - latest infos 
    * Our music - who they are, sample of what they do, latest video etc...
    * Gigs and Events - happening soon + link to hire us
    * Hire us - to contact the band for an event

### Structure

One page per feature, information keeping simple for a better view on the website but also to encourage the user to contact the band directly

![Structure detail](/files/read-me-images/structure.jpg)


### Skeleton

* Home page

Carousel with 3 items:
1. Photo with video > link to the news page
2. Live band photo > link to the contact us page
3. Disc picture > link to the music page

![Homepage Wireframe](/files/read-me-images/wireframe-home-carousel.jpg)

* Navigation pages

![Pages Wireframe](/files/read-me-images/wireframe-pages.jpg)
![Pages Wireframe](/files/read-me-images/wireframe-pages2.jpg)

### Surface

* Font: Lato (from Google Fonts)
* Colors:
    * Text: Black
    * Background: #FAFAFA - light grey 
    * Links: #DC143C - a reminder of the color of The Monkees logo
    * Highlights: #DCDCDC - darker grey for some box background 

## Features

The website's goal is to give existing fans the latest news about the band, and curious visitors information about their music and their availability to be booked for a gig.

### Existing Features

- Homepage - allows the user to see right away what is it about (music), the different pages avaible and how to contact the band
- News - the visitor has access to the latest information about the band (new music or event)
- The Band - a quick description of the band and its members
- Our music - the user can learn what kind of music they do and can interact by watching the latest video and listen to their music
- Events - the visitor has all the information about upcoming venue and detailed information about the band being available for hire
- Hire us - the user can contact the band directly to know more about the modality of the hire or ask them specific questions


### Features Left to Implement
- Plugin with instragram pictures / twitter
- Newsletter to be informed about next events...

## Technologies Used

I just wanted to mention that I wanted to use Bootstrap, not only because it was the main example provided in our course but also because I was not familiar at all with it. It was a challenge to understand how it worked and how to build a website around it. I will mention more during the deployment and testing phase.
The website is willingly simple of use, straightforward to have all the information needed.

- HTML
    - All the website was built with HTML using the resources available on Bootscrap and w3schools mostly adapted to build something consistent.

- CSS
    - The styling is built with CSS, trying to use different techniques and adaptations.

- Resources
    - [Pixabay](https://en.wikipedia.org/wiki/The_Monkees) for pictures (homepage and headers)
    - [Youtube](https://www.youtube.com/watch?v=xvqeSJlgaNk) for the video implementation in "Music"
    - [Bootstrap](https://getbootstrap.com) for the javascript and some features (cards, form, carousel) 
    - [w3schools](https://www.w3schools.com/) for the "our album" script allowing to switch from one album to another
    - [Code Institute](https://codeinstitute.net/) in order to build the timeline (Events) and the footer and for The Monkees pictures
    - [Google Images](https://www.google.com) for some extra pictures of the band (in Music fo example) - beware this is for educational purposer only as some images might have copyright on them


## Testing

At the beginning of the project I really wanted to work around one single scrolling page but I had to adapt my project for a better reading purpose. I was not feeling confident it would work the way I wanted it and it would not be as smooth for the user. For a better user experience I worked around one page per item. 

1. Overall navigation / footer:
    1. Tested all links on a desktop and a mobile as a collapsable menu will appear.
    2. Tried to make sure all animations, smooth transition where applied everywhere.
    3. Added a "home" button on the collapsable menu as it was not there on the navigation bar (also making sure it did not appear on the navbar)
    4. Make sure that the navigation bar was also on top using the "sticky top" feature. 
    5. For the pages other than "Homepage" - Wanted an header with a sticky image on the backgroung to add more effect (not working on every devices like iphone/impact but does not impact the overall use of the website)
    2. On mobile devices - realized the logo of the band was not there as we have a collapsable menu so in order to remind the user where he is, tried to include the band logo in every pages

Note: The navigation bar was quite a challenge to implement. Having to style the collapsable bar while also thinking about the desktop one was really time consuming. I wanted different features (ie the collapsable menu to take all the page on mobile devices) but I had to simplify in order to process with the rest of the development. But it certainly would be a "step 2" in improving the website.

2. Homepage:
    1. Tested the carousel on different devices, seems that the arrow is moving when approching it and might get stuck on some devices.
    2. Tried to make sure that everything was consistent (image stopping when mouse comes on it, shadow disappearing from the image...)
    3. Tried to swipe the image with the finger on a mobile to make it more UX friendly.
    4. Noticed that with an iphone, the footer tents to disappear under the bottom bar - same if the call is made at the same time (top green block moving the aspect of the website)

Note: The carousel was quite difficult to implement as I was adding different features one by one, I wanted the shadow on the images that I had to build myself from online resources. I also wanted the whole page to fit only to the screen with no scrollbar. I managed to make it possible on some devices but as I mentionned the footer sometimes desappear. I had to compromise to make it look good but also useful. 
I also thought about a link on the whole picture but then it would have been confusing with the arrow of the carousel so I settle for a button instead.

3. News:
    1. First page created and the simplest one as we only have a few blocks on display 
    2. The images disappear on mobile devices to ease the reading

4. The band:
    1. Used "Cards" tool from bootstrap - made sure all the "cards" stocked on top of each other on mobile devices
 
5. Our music:
    1. The video is embedded directly from Youtube, tested it to make sure it worked and fits everywhere
    2. Used the "tabs" tool from w3schools so had to make sure the design matched and adapted it for images and music links
    3. Tried the audio link that is also disappearing completely id the navigator is not supporting this code - it also disappear on mobiles to ease the reading of the page

6. Events:
    1. Wanted some kind of gallery to add some pictures to the page. Had to work around to make them fit nicely and stack devepending on the device size. They also disappear on mobiles to help the page charge quickly.
    2. Really wanted to implement the timeline from the course example as it fit nicely and is quite straightforward for the events
    
3. Contact:
    1. On mobile the logos appear while on desktop is a band pictures. Here again it was to remind what we were talking about (the monkees) but also to help the page charge quickly on mobile devices
    2. The form was tested, some areas are mandatory - used Bootstrap for the overall form
    3. Added a date input for enquiries about an event - choose this aspect instead of a Google Calendar for the overall look 

--------

[CSS Validator](https://en.wikipedia.org/wiki/The_Monkees) 
[HTML Validator](https://www.youtube.com/watch?v=xvqeSJlgaNk)

## Deployment

The "blank" running code of Could9 was used most of the time. It was quite a challenge at first because the command did not really fit as you have to process into a particular order.
Then I committed on Git every time a new page was build and with an almost "finished" status.

Also due to the upcoming migration with AWS it was chosen to finish the website on Cloud9 and to deploy it from there to avoid any transfer issue.


## Credits


### Content
- Most of the content was written directly to keep it simple and with a tone of proximity with the user. 
- Some informations were plugged from the [Wikipedia page of the Monkees](https://en.wikipedia.org/wiki/The_Monkees)

### Media
- The photos used in this site were obtained from Code Institute, Pixabay and Google Images for some band pictures.
- The video was used from Youtube "The Monkees" page


