# saber//games

### Note: This website was an assignment given to me as part of my Web Development module. The challenge consisted of creating a website using only HTML and CSS, without the use of JavaScript, any external libraries, etc.
### The below readme was part of my submission and explained how my website satisfied the requirements of the assignment. 
___

This readme is a brief outline of how the saber//games website satisfies the assignment requirements as set out on Brightspace, as well as an explanation of what features of HTML and CSS I explored that were not covered in the lectures. 

I have chosen Option 1 (Personal Website) for this assignment, with the theme of a video game review blog. The website contains a homepage (index.html), a gallery (gallery.html) and three pages of my choice (review.html, opinion.html and about.html)

All media not my own (i.e. images, videos) is appropriately sourced on each webpage. All other content such as text of articles etc. was written by me.

Every HTML page and the CSS file were checked by the HTML / CSS validators and no errors have been found. No libraries or frameworks have been used in this assignment.

---
## Beyond the Lectures
##### During this assignment I did my best to push myself to use features of HTML and CSS that we did not explicitly cover. The following features were ones that I was particularly proud of:

* ##### The pop-up text display on the front page. When you hover over the images, the opacity of the relevant image reduces and the name and date of the game pops up. The effect works by using overflow:hidden to hide the text outside the frame of the image, and then using transform:translate to move the text into frame on hover.

* ##### Using transition for the hover effect in the nav bar buttons to make the color change a little smoother.

* ##### Experimenting with Japanese text (in the nav bar and in the reviews section) and testing their output in CSS. I speak Japanese and as such wanted to test how the typography would in a website as I am hoping to incorporate some Japanese text in personal web design projects.  

* ##### Using media queries to switch certain elements on the website on and off depending on screen size. This ensures that mobile users also get a good experience when visiting. In particular see index.html which swaps the splash image to something different if the user is on a mobile device.

* ##### Use of flexbox and grid, in particular on the gallery (flexbox) and opinion (grid) pages. While going forward I will probably be using either one or or the other, I wanted to practice using both for the purposes of this assignment.

* ##### Setting a small animation to the buttons located on the about page, making sure that it is subtle (so as to avoid overwhelming the user) but punchy. The animation style is inspired by the login buttons of the Discord home page. 

* ##### Use of "dropcaps" on the review and opinion pages, to make the text feel more like an article. 

* ##### Using vw units on the opinion page to make the text shrink as the viewport gets smaller. 

---
## Main Requirements

### Links to both your own pages and external web pages:
>##### The website contains links to internal pages via the navbar. The "Gallery" page contains a link within each image to the Wikipedia entry for the relevant game, and the "About Me" page contains links to my Github and Grouvee accounts. The Psychonauts 2 review on the reviews page also links to the gallery page.
---
### Navigation bar:
>##### Each page contains the navigation bar, styled in accordance with that pages color scheme.
---
### At least one table used in an appropriate manner:
>##### The table on the gallery page provides additional information in connection with the games listed therein. I thought this was the most appropriate way of presenting this information given how visual the rest of the page is.
---
### At least one list (ordered or unordered):
>##### The nav bar is styled as an inline list. Separately, the image references on the index and review pages are also styled as lists. 
---
### At least one local or embedded video:
>##### The opinion page features an embedded YouTube trailer for the game that is the subject of the article.
---
### At least five CSS3 elements:
##### Among others, I have used the following elements unique to CSS3:
* ##### RGBA (to lower the alpha/opacity)
* ##### border-radius
* ##### box-shadow
* ##### transition
* ##### transform
* ##### text-shadow
* ##### last-child
---
### At least four HTML5 specific elements:
##### Among others, I have used the following elements unique to HTML5:
* ##### \<header>
* ##### \<footer>
* ##### \<section>
* ##### \<article>
* ##### \<aside>
---
### Make use of the following of the CSS positional elements:
>##### I tried to used many different positional elements of CSS on every page, such as position, float, fixed, relative, etc. For example, the footer is "fixed", the image on the opinion page uses "float:right", and I used absolute / relative to position elements on top of each other (together with z-index) on most pages. 
---
### Make use of both block and inline elements:
>##### The nav bar is displayed as an inline-block list. I used both inline and block elements in other parts of the site also. For example, the buttons are displayed as a "block" to ensure that the links are clickable everywhere on the surface of the button, and on the index.html page, the images are arranged by using "inline". Some of the pure inline elemets are used are a and img. I also used a span in one of the footers.
