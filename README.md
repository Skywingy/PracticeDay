# PracticeDay

Drop-down Menus

You know what we’re talking about here. Picture a nav-bar or a button and when you click it the menu slides down nicely. As mentioned previously, you already know everything you need to create this element. Here are some things to keep in mind:

You can allow the menu to show up either on click or on hover.
You should hard-code the menu items into your HTML but hide/reveal them using JavaScript. You can do this either by adding a class (visible or something) or by manually setting the style in JS.
Make sure the code is reusable! You should be able to create multiple drop-downs on a page without repeating the JavaScript code.
If you bundle your code into a module you can publish it to npm and then install and use it anytime you like! Nothing like publishing your own modules to make you feel like a pro 😎.
Mobile menus

Mobile versions of your sites are almost definitely going to need their own menu implementation. Depending on how you decided to implement your drop-down, you could reuse it here, but there are tons of more inventive options out there.

Browse the web for some inspiration, pick something and try to implement it!
Image slider

Again, there’s not much instruction needed here - just practice.

Create a simple image carousel. It should contain arrows on each side to advance the image forward or backward. It should automatically move forward every 5 seconds. It should contain the little navigation circles at the bottom that indicate which slide you are on (and they should be click-able to advance to that particular slide).

Don’t spend too much time worrying about getting your images to display at the correct size – it’s more important to get the slider sliding.

This one is a little more involved than the last two, so think about how you would set up the different elements within the site.  
Set up a very wide div which will contain the individual “slides” of each image. By appropriately positioning that div inside a container div (which acts like a picture frame), you can choose which slide is visible at any given time.
Once you have the slider positioned properly, build functions for “next” and “previous” which will advance to the next or previous slide accordingly. Make the transitions smooth using simple effects.
Set up arrow buttons which activate those functions and play with cycling through the images.
Add in some navigation dots at the bottom of the slides. Make a horizontal series of empty circles with CSS immediately below the slideshow. Each circle represents a slide, so whenever a new slide is activated, its corresponding circle gets filled in so you can tell where in the show you are. Make each circle link to that particular slide, so you can click on the circle and it will jump to that slide.
Add a timeout which advances the slides every 5 seconds.
Play around with your slideshow!
