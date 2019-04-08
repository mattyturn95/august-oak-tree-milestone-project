# AUGUST OAK TREE - BAND WEBSITE

(This Website was Developed on Visual Studio Code)

Milestone Project One: User-Centric Frontend Development - Code Institute

A website that takes you deeper into the lives and music of the August oak tree band.
What I am trying to achieve for the band is to help them boost there public profiles on multiple platforms such as on the Web, Soundcloud,
Youtube & Facebook. Creating a website that allows users to get a feel for there music and understand what drives them to create the music 
that they do. 

I want users to feel at ease when looking at the layout of the website and that is why I opted to go for the minimalistic approach with
colors that are easy on the eye and with very few options to get lost within the site.

Here is a link to my Live Website deployed on Github.pages <br>
[Click here](https://mattyturn95.github.io/august-oak-tree-milestone-project/index.html)

# UX

This website if for the August Oak Tree Band,

Although the band has several social media accounts available to the public I wanted to create a sole hub for users to gain access and
get in touch with the band members via one main portal (the website).

Whilst preparing my thoughts for the website I believed that it would be best to divide the website into 4 pages<br>
 (ABOUT -index.html, MUSIC-music.html, GALLERY-gallery.html & CONTACT-contact.html) 

 I believed that my design would become too complex if i were too have everything crammed into one page with 4 sub-sections
 <br>
 * As a music enthusiast, I would like to see what the band has to offer in terms of music and videos.
 * As a user of the Website, I would like to be able to have a look at social media accounts such as SoundCloud, Youtube & Facebook
 * As a Possible manager/talent rep i would like to be able to get in touch with the band and create a connection via the contact form
 * As a Frequent web user looking to come accross new music within this Genre I want to see this site come up in the top Google Pages

 I performed Mockups Using only pen and paper to get a rough idea on how the layout should be coded. <br>
 here is a link to my Mockups <br>
 [Click here](https://github.com/mattyturn95/august-oak-tree-milestone-project/tree/master/mockups)

 # FEATURES

 ### EXISTING FEATURES ###

 This website has the following Features <br>
 * Photo Gallery that allows users to scroll through enlarged thumbnails upon clicking.
 * Media (plays songs upon clicking the play button - altering volume and also an option to download the songs)
 * Video - to see what the band produces in terms of video and music collaberated together
 * contact form where one can get in touch with the band via the contact.html page

 ### FEATURES LEFT TO IMPLEMENT ###

 * possible page that could give an in depth overview of upcoming performances
 * Live updates 
 * Merchandise for sale such as t-shirts and hats

 # TECHNOLOGIES USED

 * HTML
   * Used to create semantic layout of the website

 * CSS
   * Used to style the website with class names

 * JQUERY
   * Used for DOM Manipulation
     * [Click Here](https://jquery.com/)

 * BOOTSTRAP
   * Used to help provide an array of pre-set classes to help organise the layout of the website such as the grid-system
     * [Click Here](https://getbootstrap.com/)

 * FANCYBOX
   * used to create a responsive gallery used within the gallery.html page and for photos rendered on mobile devices
     * [Click Here](http://fancyapps.com/fancybox/3/)


  # TESTING

  During the process of developing my site I came accross a few problems.

 (1) one of the first problems that i came accross was when rendering the website on mobile view the navbar height was affected when transitioning
  to mobile devices, I was able to fix this by adding a media query within my CSS file (main.css)
  <br>
  <br>
 (2) When Developing my Music.html page i first started off by embedding songs directly from Soundcloud and into my site
 this created a negative user experience as it was not original and did not fit into the layout of my design (I tested the site through various devices
 such as the iphone 6, Sony Xperia and Samsung s8) and made use of devtools to help figure out where all of the problems lay.
 <br>
 <br>
 (3) With regards to the Gallery.html page I struggled to create a positive user experience at first with regards to the layout of 
  my gallery table and the table displayed on mobiles. I then came up with the idea of displaying the table format only on medium screens and large screens
  and hiding the table on xs-devices and sm-devices using the code [xs-hidden & sm-hidden} and visa versa.
  <br>
  <br>
  (4) Finally, when the Contact form was added I had been following other Code Institute students projects to see if I could gather ideas on how to make my project more informative to the users. It occured to me that i should make use of a Modal form on my contact page to show users that the submit button is purely just a button with no real function as yet. I then added a message with in the modal to show users that the button has no real function.
  <br>
  <br>
  (5) Upon the development of my Project i constantly tested the pages through various browsers such as Firefox, Google Chrome and Opera & experienced no problems whatsoever during the process of deployment and testing.
  
# DEPLOYMENT

This site is hosted on Github Pages, deployed from the master branch. There are no differences between the development and deployed version.

* To clone this repository to run locally, you can do the following:

* Create a new repository on Github

* Clone my repository with the following commands on your IDE (machine):

    ```
    git clone https://mattyturn95.github.io/august-oak-tree-milestone-project.git
    git remote rename origin upstream
    git remote add origin *URL TO NEW GITHUB REPO*
    git push origin master
    ```
 * Deploy to Github by going to settings and changing the Source from none to Master Branch: reload the page and you should see a link pop up within the settings which will take you to your deployed website
 
 # CREDITS
 
 ### Content ###
 
 * the band information was copied from August Oak Trees Facebook Page
    * [Click Here](https://www.facebook.com/pg/augustoaktree/about/?ref=page_internal) 
 * The Modal deployment was gathered from W3 Schools
    * [Click Here](https://www.w3schools.com/bootstrap/bootstrap_modal.asp)
 * Social Links Images were gathered from Font Awesome 
   * [Click Here](https://fontawesome.com/icons)
   
   
 ### Media ###
 
 * All Images were Gathered from The August Oak Tree Facebook Page and have written consent from the band members upon request
    * [Click Here](https://www.facebook.com/pg/augustoaktree/photos/?ref=page_internal)
 * All Songs were gathered and downloaded from The bands Soundcloud page
    * [Click Here](https://soundcloud.com/augustoaktree)
 * The Media code was gathered from W3 schools to play the songs 
    * [Click Here](https://www.w3schools.com/html/html_media.asp)
  * The Gallery table was gathered from a youtube video 
     * [Click Here](https://www.youtube.com/watch?v=cPltsWlCdu8&t=926s)
     
  ### Acknowledgments ###
  
  * I Received inspiration from browisng through various music/band websites in order to try and implement my own original ideas
  * I would also like to say thank you to all of the amazing feedback that I received from the Slack-forum when coming across problems
 
 


 