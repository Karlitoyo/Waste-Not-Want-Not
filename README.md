
**Waste Not Want Not** - ***ReadMe***


This website is designed to allow users to upload items they have within their household or in their possession.
The final site will be designed as an auction site which will manage live bids on items with partner or designated
charities recieving percentage donations from the sale of items / administration fees based on user uptake.


The website development and purpose has been broken down, into the detailed sections below -

  > ## Contents


* [Features](https://github.com/Karlitoyo/Waste-Not-Want-Not#UX)
    - [Users](https://github.com/Karlitoyo/Waste-Not-Want-Not#Users)
    - [Strategy](https://github.com/Karlitoyo/Waste-Not-Want-Not#Strategy)
    - [Scope](https://github.com/Karlitoyo/Waste-Not-Want-Not#Scope)
    - [Structure](https://github.com/Karlitoyo/Waste-Not-Want-Not#Structure)
    - [Skeleton](https://github.com/Karlitoyo/Waste-Not-Want-Not#Skeleton)
    - [Surface](https://github.com/Karlitoyo/Waste-Not-Want-Not#Surface)
 * [Development](https://github.com/Karlitoyo/Waste-Not-Want-Not#Development)
    - [Current-Features](https://github.com/Karlitoyo/Waste-Not-Want-Not#Current-Features)
    - [Further-Development](https://github.com/Karlitoyo/Waste-Not-Want-Not#Further-Development)
 * [Technologies-Utilised](https://github.com/Karlitoyo/Waste-Not-Want-Not#Technologies-Utilised)
 * [Testing](https://github.com/Karlitoyo/Waste-Not-Want-Not#Testing)
 * [Deployment](https://github.com/Karlitoyo/Waste-Not-Want-Not#Deployment)
 * [User-Stories](https://github.com/Karlitoyo/Waste-Not-Want-Not#User-Stories)
 * [Credits/Media](https://github.com/Karlitoyo/Waste-Not-Want-Not#Credits/Media)
    - [Acknowledgements](https://github.com/Karlitoyo/Waste-Not-Want-Not#Acknowledgements)


  > # UX

The Website is to be an auction sytle platform with charitable donations built into the user experience, partner 
charities recieve a donation from either of the individual seller or the auction site administrators monthly / yearly 
donation as a percentage of revenue.

The Nav bar is always visible to the user being spread across the page above the site content and below the main
hero-image. This encourages users to navigate through the website easily. The user can choose to either sign-up with items they
wish to add to the catalogue, browse the Catalogue, read the about section or search for specific items via the Home-page.


## Users

The site has a target audience of individuals between the age of 20-70. These individuals are the predominant buyers & sellers
within the economy. From a user perspective searching the Catalogue for desired items is the primary focus of the site. Having a 
trail image and search bar as the home page with navigation was the primary idea to limit distraction and to give the idea of starting
a journey through searching the Catalogue of items.


## Strategy

I took inspiration for my design from 'Neomorphism' which is minamalistic and eye catching. My colour scheme 
however did not suit this style and so I decided to keep the navigation style with shadows below and change the 
colour scheme to be more eye catching to the user.


## Scope

The purpose of the site is to find a way for users to buy/sell unwanted items while also providing charities much
needed funds fluidly and autonimously with donations built into each sale.


## Structure

---Home---

The home page is a simplifies user interface providing a simple search bar which is planned to link to the Catalogue 
page. The UX has been simplified to allow for ease of use and to encourage users to search the Catalogue. In future 
versions I would anticipate top items being placed below the search bar for quick user access to items in demand within
the Catalogue.

---Catalogue---

The Catalogue page is the main repository of items available on the website. Users can browse the Catalogue of available
items and in planned future versions view prices related to individual items and place bids as auctions are live. 
The responsiveness of multiple images which flip to reveal price , name, and description proved challenging however
it is good for tablet and desktop monior + large monitor.

---Get Involved---

The Get Involved section allows users to register on the website and provide a brief description of the item they 
wish to upload to the site. In planned future versions an image upload section will be active allowing upload of
items upon successfull registration.

---Contact---

The Contact section provides useful contact information for queries users may have including an e-mail address
and contact number. This section also provides a brief synopsis of the individuals behind the website. I made use of JS 
in this section to provide a pop up box on the bottom right hand section of the page. This hides the information 
unless a user specifically requires this information for genuine requets.


## Skeleton

Wireframes for the main navigation pages can be found below -

- [Wireframes](Balsamiq-Wireframes/Waste-Not-Want-Not.png)

## Surface

The colour scheme was intended to be eye catching and vibrant. The hero-image was initially (and still planned to be)
a scrolling catalogue of highly sought items.

 > # Development

 ## Current-Features

Within my code I have used HTML, CSS, JS, and Bootstrap. I have utilised a number of resources to complete my 
first milestone project most notably the book "Sams Teach Yourself - HTML,CSS,JavaScript (third edition). 
I have also referenced the sites - W3 Schools, Stack Overflow, Slack, FreeCodeCamp. For my search bar I have linked
the specific link below to the creator. I customised the CSS to reflect how I wished it to look. The code below will
produce a magnifying icon however I ammended this to produce the circle shown within my home page also changing colors
as appropriate.

JS is used for the contact page which produces a pop up for email and contact information. This was initially sourced
through W3schools and then amended to fit purpose. The inital code was for a request for information by inputting 
e-mail and contact information with this information then being submitted. This was challenging to amend as each attempt 
to close the contact box would re-fresh the webpage. I amended the JS by entering 'return false' after the 'close form'
section within the my script in the contact.html page.


## Further-Development

It is intended to link the search bar within the 'Home Page' section to the Catalogue to allow users to search the 'Catalogue'
section. It is also my intention to re-place the hero-image with a alternating selection of most-desired items'. Upon going 
live and being connected to a server the 'Get-Involved' section will also have an image upload upon successful 'Sign-up'.


## Technologies-Utilised

For the project I utilised -

- HTML
- CSS
- Java script
- [Bootstrap](https://getbootstrap.com/)


- [Font Awesome](fontawesome.com)
- [Google Fonts](https://fonts.google.com/)
- [HTML Validator](https://validator.w3.org/)
- [CSS Validator](https://validator.w3.org/)
- [MDN](https://developer.mozilla.org/en-US/)


- [W3schools](https://www.w3schools.com/)
- Sam's Teach Yourself - HTML, CSS, Javascript

## Testing

Testing was maintained throughout site development. I used multiple browsers to ensure the site was as 
responsive as possible to both multiple screen sizes and mobile and tablet devices. 

Each page was tested individually for responsiveness with the 'Catalogue' section proving to be the most
troublesome due to each item within the 'Catalogue flipping to reveal item price, name and description.

Multiple iterations of the form element were tested with the final form being chosen due to it being
simplistic and user friendly with  awhite background and a large 'item description' section.

The site was tested on Google Chrome, Opera, Firefox,IE10, Large screen monitor, Laptop, Desktop, Mobile (GalaxyS8).

HTML Validator has shown some errors within the HTML code itself relating to the sizing of the slide show hero images
this was unavoidable and in line with expectations. Code also states errors with unclosed "br" tags and some Further
errors with regard to HTML comments. Javascript "btn" tag also shows as an error however function is unaffected. An interesting
error is the div id="row split" which I used to split the contact page into two seperate sections for about information.
Fully functional however it states this must not contain white space. However removing the css style .split has about
negative effect of function of website and it is something I am unable to explain after much testing as I am aware only
only ID attribute can be assigned to div elements..

I have tested the website on a number of different systems as outlined in the development section. I initially 
tested on a large screen and laptop and mobile. Using the large screen I changed the browser windown size from 
large to small repeatidly to ensure Media Queries were woring corresctly and to mitigate page repsonse issues.
Unfortunately desktop screens which I mistakenly assumed would be included were not and caused errors upon my 
initial submission. This has now been identified and resolved. A further issue I encountered was my catalogue 
section on IE edge which was setting display to "ms flex wrap" causing the grid system to become unresponsive.
This was fixed thorugh an update to the CSS however upon running on IE10 the catalogue item comments which 
should show upon the image flip are not showing this was not a problem on Microsoft Edge. Unfortunately I was 
unable to remedy the IE10 bug. In the final version of the site the bottom social network links are not live
as the do not direct currently to related waste not want not sites.

## Deployment

The site was deployed on Github and code is available to view using this site. 

I navigated to my Github account, on the top left of the screen I selected my "Waste-Not-Want-Not"
repository, I then deployed through the settings section by and scrolling to the 'Github Pages'
section roughly 3/4 of the way down the page. Selected my master branch and my page was presented to me as

- Waste-Not-Want-Not : (https://karlitoyo.github.io/Waste-Not-Want-Not/)

**Cloning**

Can be achieved by selecting the green highlighted button which states - "Clone or Download" via the 
webpage: (https://github.com/Karlitoyo/Waste-Not-Want-Not) this will give the option of downloading a .zip file 
or opening in desktop an option to close using HTTP is also given for cloning and running project locally. through
gitpod make use of the git pull function (if required to update the branch) and git clone and then git push to named
repository.

**Version-Control**

In my initial version I took a sytle from neomorphism as mentioned previously and styled the navigation to work
within a neomorphism style website. Upon review of the colour scheme and mechanics of the website I re-developed 
the design using a more bootstrap oriented approach. In the second version (re-design) I too the navigation from
bootstrap and also the carousel style hero slideshow. This is fundamentally a better design and ease of programming
is straight forward. The initial slideshow involved the use of javascript functions. (While interesting to learn
it is more complex and therefore more prone to error than bootstrap carousel).


> # User-Stories

## First-User
Initial feedback was positive for the purposes of the assignment however requests were made for further content 
visable on site which has been noted however this will be more realistic upon live users creating content through 
upload.

## Second-User
Second user requested for clearer hero images however again this was due to the portrait orientation of my upload
which was then edited in a picture editor 'GIMP'. Upon reflection it may have been easier to re-take photographs 
for the hero section however the functionality was priority over content as site is not live currently.

## Developer comments
The final site will have a working search bar linked to the catalogue, I also wish to encorporate a bidding service
this will take time and development. I am currently undertaking the Javascript section of the course and API's in
particular. I am looking forward expanding my knowledge and implementing what I learn to this site going forward.
Although my home page is minamalistic this was the intention as I wish for users to visit the site and search the 
catalogue of items as a priority.


> # Credits

Special thanks must be given to the creators of all the above and below mentioned sources I used to develop 'Waste Not Want Not'.

My search bar was insirped by and predominantly provided by the below -

**Search bar**

https://www.mockplus.com/blog/post/search-bar-design

https://codepen.io/sebastianpopp/pen/myYmmy


**Get-Involved Contact-box JS**

https://www.w3schools.com/howto/howto_js_popup_form.asp


> # Acknowledgements

To create this website, I used many resources, like Stack Overflow, Bootstrap, W3 Schools, the above provided link for
the search bar, Neomorphism generator (linked above), Sam's Teach Yourself HTML,CSS,JS. My mentor who helped me with many
queries through the construction of the site and also the slack channel which is a knowledge base in itself.

**MDN**

https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5

**Neomorphism**

Neomorphism was the initial design concept for the UI. My navigation bar is an ode to this sytle however due to general
restrictions on my current design capabilities and color scheme this was rolled back. I have provided links below to
both.

https://uxplanet.org/neumorphism-in-user-interface-tutorial-c353698ac5c0

https://neumorphism.io/#808080