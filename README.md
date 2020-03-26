
**Waste Not Want Not** - ***ReadMe***


This website is designed to allow users to upload items they have within their household or in their possession.
The ultimate goal is to link the search bar to the catalogue and to have an auction section which will manage live 
bids on items.


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

Home 
Catalogue
Get Involved
Contact


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

- <br>Code

- HTML
- CSS
- Java script
- [Bootstrap] (https://getbootstrap.com/)

<br>Externals

- [Font Awesome](fontawesome.com)
- [Google Fonts](https://fonts.google.com/)
- [HTML Validator](https://validator.w3.org/)
- [CSS Validator](https://validator.w3.org/)
- [MDN](https://developer.mozilla.org/en-US/)

<br>Learned from

- [W3schools](https://www.w3schools.com/)
- Sam's Teach Yourself - HTML, CSS, Javascript

<br>Neomorphism

Neomorphism was the initial design concept for the UI. My navigation bar is an ode to this sytle however due to general
restrictions on my current design capabilities and color scheme this was rolled back. I have provided links below to
both.

https://uxplanet.org/neumorphism-in-user-interface-tutorial-c353698ac5c0

https://neumorphism.io/#808080

My search bar was insirped by and predominatnly provided by the below -

**Search bar**

https://www.mockplus.com/blog/post/search-bar-design

https://codepen.io/sebastianpopp/pen/myYmmy


**Get-Involved Contact-box JS**

https://www.w3schools.com/howto/howto_js_popup_form.asp


**MDN**

https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5



## Testing

Testing was maintained throughout site development. I used multiple browsers to ensure the site was as 
responsive as possible to both multiple screen sizes and mobile and tablet devices. 

Each page was tested individually for responsiveness with the 'Catalogue' section proving to be the most
troublesome due to each item within the 'Catalogue flipping to reveal item price, name and description.

Multiple iterations of the form element were tested with the final form being chosen due to it being
simplistic and user friendly with  awhite background and a large 'item description' section.

The site was tested on Google Chrome, Opera, Firefox, GalaxyS8, 

## Deployment

The site was deployed on Github and code is available to view using this site. 

I navigated to my Github account, on the top left of the screen I selected my "Waste-Not-Want-Not"
repository, I then deployed through the settings section by and scrolling to the 'Github Pages'
section roughly 3/4 of the way down the page. Selected my master branch and my page was presented to me as

- Waste-Not-Want-Not : (https://karlitoyo.github.io/Waste-Not-Want-Not/)


> # Credits

Special thanks must be given to the creators of all the above mentioned sources I used to develop 'Waste Not Want Not'.


> # Acknowledgements

To create this website, I used many resources, like Stack Overflow, Bootstrap, W3 Schools, the above provided link for
the search bar, Neomorphism generator (linked above), Sam's Teach Yourself HTML,CSS,JS. My mentor who helped me with many
queries through the construction of the site and also the slack channel which is a knowledge base in itself.