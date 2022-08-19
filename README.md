# Sea Swim Together
The sea swim together site is a landing page for people searching for information on Sea Swimming in Galway.  The sea swimming group offers meetups twice a week in a popular swimming spot.  The site focuses on the health and social benefits that can be gained from sea swimming and swimming with companions.
Users of the website will be able to find out some basic information about the benefits of sea swimming, when and where meetups happen and fill some details into a contact form to recieve further information and get in touch with members.  This site is aimed at people who are looking to try sea swimming.


![alt text](../sea-swim-together-galway/docs/amiresponsivep1top.png)
![alt text](../sea-swim-together-galway/docs/amiresponsivep1middle.png)
![alt text](../sea-swim-together-galway/docs/amiresponsivep1.png)

https://ui.dev/amiresponsive

## Features

### Navigation

* Featured at the top of the page: the navigation shows the club name in the left hand corner.  This also links to the top of the page and increases in size when hovered over.
* There is a navigation menu to the right of the top of the page which has three items: Home, About and Contact.  Each links to the relevant point in the web page and underlines when hovered over and remains underlined if the active page.  Home is currently active as this is all featured on one page.
* The logo is in Font Amatic SC and the navigation Josefin Slab.  I chose these 2 fonts as they work together well on the pages headings and body.  They were sourced from the following article: 
https://govisually.com/blog/2020s-top-20-google-font-pairs-for-your-next-project/ 
and selected as they apeared a less formal, contemporary pairing that would appeal to the sites users.  It has no background as the white contrasts nicely with the hero image selected.
+ The Navigation bar tells the user at the outset the focus of the page and enables them to get to the most important information quickly.

 ![alt text](../sea-swim-together-galway/docs/navbar.png)


### The Hero Image and cover Text

* The next section of the webpage features a hero image depicting a group of swimmers in the sea.  This image was chosen for the site presentation on a wide screen and the image was used in a generator for a colour scheme for the site.  
* There is a different hero image for medium and small screens via media queries as you can see in the images above.  The different pictures were chosen as the shapes/ layouts complimented the different screen types and maintained the color theme.
* There is cover text on the image which acts as a tag line for the site "Sea Swimming Meet ups Galway": to give a quick insight in to the page on landing.  Again, using media queries, the position and size of this cover text changes as the screen size shifts.  It also has an opacity number to allow the hero image to seep through.

 ![alt text](../sea-swim-together-galway/docs/heroimglrg.png)

### The "Why" Section

* The why section is 2 divs containing reasons to sea swim including benefits to physical and mental health and further reasons as to why it's better to swim in groups.  This information is included to encourage the user to try swimming, feel confident and safe to try it Sea Swim Together. 
* These divs are in a container and styled using flex-box.  I accessed an article as recommended on Slack to explain and use flex box for layout (https://css-tricks.com/snippets/css/a-guide-to-flexbox/*/) It was useful for positioning differerent elements but will need much more practice.  On evaluation there would be a way to position all 4 using flex: not in 2 containers and I also may have used an article for the benefits.
* If continuing work on the site I would include images here or break the colors/ shaping as it is a lot of text in one area.
* I added font icons and used styling on the text to emphasise important information.

### The About Section

* Next 2 divs are the About Section which is linked from the navigation bar.  It has a short explanatiion of the origins/ makeup of the group.
* This is also contaoins the details for the days, times and location for meet ups.  Again, font icons and styling were added to the text to draw the user to important information.

    
![alt text](../sea-swim-together-galway/docs/about.png)

### Contact Form
 
* The next section is a small form for the purposes of providing contact details and getting further information on the group and any equipment necessary.
* Code from Love Running was used for the form but stripped back with layout of form elements changed, sizing of inputs and customising of appearence and text.
* Media queries were used to again change the form from horizontal on a wide screen to column on smaller screens.  A border is only present on a smaller screen.
* You can't submit the form without providing relevant information.  The email won't complete without an @. The form returns an error at present.  I had began a thank you page but time did not allow and I ran into issues with placing the footer: I'll be looking at this further.  The submit button has hover functions that dispaly colors in line with the theme.
    

![alt text](../sea-swim-together-galway/docs/form.png)

### Footer

* The footer contains four icons for social media pages for the group and site.  There maybe social media network accounts and video playlists available with relevant safety information.
* Again, the core structure for these links was taken from love running wih styling used keep in with the sites theme and hover elements were added to signpoint to the user what is being selected.
* They place well on medium and smaller screens but rise too high on a larger screen.

![alt text](../sea-swim-together-galway/docs/footer.png)

### Testing

* I tested this page in different browsers: Internet explorer and firefox and it looks and functions well: but mainly worked in and checked the site in Chrome.
* Using dev tools device toolbar I confirmed that the site is responsive throughout and that it was functioning well on all screen sizes.  Adding media queries as required as I went.  Please see first image of the README also.
* I used https://autoprefixer.github.io/ to prefix css as required and ensure compatibility with other browsers.
* I confirm that the navigation, header, about us, sign up, contact text are all readable and easy to understand.
* I have confirmes that the form works at the point of the page: entries required in every field, will only accept email in email field and the submit/ let's swim together button works.























