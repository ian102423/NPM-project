# Week 1 Workshop Assignment #

[![Watch the video](https://learn.nucamp.co/pluginfile.php/4095/mod_assign/intro/assignment-task2-xs_redo.png)](https://www.youtube.com/watch?time_continue=176&v=nUfWatE7fIE&feature=emb_title)


## Objectives ##

- In this assignment, you will create the About Us page (aboutus.html) for the Bootstrap website you've been working on. The starter code will be provided for you. 
- Using what you have learned this week, you will configure the About Us page to use Bootstrap, implement the Bootstrap grid system to display the content using row and column classes, and research and use two new Bootstrap classes to responsively hide content for extra small screens.

## Instructions ##
- **Read the workshop assignment instructions on this page and watch the video, but **do not start** the assignment until you are at the in-person workshop.**
- **You will submit your assignment at the bottom of this page.**


## Task 1 ##
- Create a new file in your Bootstrap course project folder (that is, the nucampsites folder in your Bootstrap folder) and name it aboutus.html. Copy and paste the following starter content (or you can download the file via this link):
`<!DOCTYPE html>
<html lang="en">

<head>
    <!-- Required meta tags always come first -->
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>NuCamp: A Better Way To Camp</title>
</head>

<body>

    <header class="jumbotron jumbotron-fluid">
        <div class="container">
            <div class="row">
                <div class="col">
                    <h1>NuCamp</h1>
                    <h2>a better way to camp</h2>
                </div>
            </div> 
        </div>
    </header>

    <div>
        <div>
            <div>
               <h2>About Us</h2>
               <hr />
            </div>
        </div>

        <div>
            <div>
                <h3>Our Mission</h3>
                <p>We present a curated database of the best campsites in the vast woods and backcountry of the World Wide Web Wilderness. We increase access to adventure for the public while promoting safe and respectful use of resources. The expert wilderness trekkers on our staff personally verify each campsite to make sure that they are up to our standards. We also present a platform for campers to share reviews on campsites they have visited with each other.</p>
            </div>
        </div>

        <div>
            <div>
                <h3>Community Partners</h3>
                <h4>Bootstrap Outfitters <small>Outdoor Gear Specialists</small></h4>
                <p>Bootstrap Outfitters supplies you with the gear you need at prices you can't beat.</p>
                <h4>Git Out Expeditions <small>Group Adventure Expeditions</small></h4>
                <p>Join Git Out Expeditions to explore new horizons with a group of other adventurers!</p>
                <h4>Mongo Fly Shop <small>Your Neighborhood Fly Fishing Shop</small></h4>
                <p>Need a new fishing pole, a tacklebox, or flies of all kinds? Stop by Mongo Fly Shop.</p>
                <h4>Node Outdoor Apparel <small>Outdoor Clothes & Shoes</small></h4>
                <p>From polar fleeces to swimsuits, hiking boots to waders, a visit to Node will be sure to get you covered.</p>
            </div>
        </div>
    </div>

    <footer>
        <div class="container">
            <div class="row">
                <div class="col-4 col-sm-2 offset-1">
                    <h5>Links</h5>
                    <ul class="list-unstyled">
                        <li><a href="index.html">Home</a></li>
                        <li><a href="#">About</a></li>
                        <li><a href="#">Sites</a></li>
                        <li><a href="#">Contact</a></li>
                    </ul>
                </div>
                <div class="col-6 col-sm-5 text-center">
                    <h5>Social</h5>
                    <a href="http://instagram.com/">Instagram</a>
                    <a href="http://facebook.com/">Facebook</a>
                    <a href="http://twitter.com/">Twitter</a>
                    <a href="http://youtube.com/">YouTube</a>
                </div>
                <div class="col-sm-4 text-center">
                    Tel: 1-206-555-1234<br />
                    Email: campsites@nucamp.co
                </div>
           </div>
        </div>
    </footer>

</body>

</html>`
- Add the link to the **bootstrap.min.css** file.

- Add the link to the custom **styles.css** file.

- Add the links to the **jquery**, **popper**, and **bootstrap JS** files.

- NOTE: In order to view this page, use npm start from your bash terminal inside the project folder as you have done before. Then, in the address bar where it says "http://localhost:3000/" - add "aboutus.html" to the end so that it says "http://localhost:3000/aboutus.html" and you will be able to see the file. In Week 2, you will be adding navigation links to be able to navigate to this page more easily, but this will work for now. 


## Task 2 ##


- Add formatting to the web page using the Bootstrap grid's **container**, **row**, and **column** classes.

Make sure that:

- The “About Us” title and the "Community Partners" section both stretch across the entire width of their row.
  - The “Our Mission” part occupies only half the width of the row for small to extra large screens.
  - The columns should stack on top of each other for extra small screens (i.e., each column should take an entire row). 
- See the screenshots below as your guide. You can either resize your browser window or use your browser's developer tools to get different viewport sizes.

![image source](https://learn.nucamp.co/pluginfile.php/4095/mod_assign/intro/assignment-task2-xs_redo.png)
![image source](https://learn.nucamp.co/pluginfile.php/4095/mod_assign/intro/assignment-task2-lg.png)

## Task 3 ##

- Apply the **d-none** and **d-sm-block** Bootstrap responsive classes to the **<p>** elements containing the descriptions of the community partners so that they are hidden on only extra small screens. 
  - Read the documentation on these classes [here](https://getbootstrap.com/docs/4.0/utilities/display/). See how the combination of classes shown [here](https://getbootstrap.com/docs/4.0/utilities/display/#hiding-elements) enables you to hide the content for XS screen sizes. 
- Also apply these two classes to the three <p> elements in the body of index.html.
- Afterward, in a XS viewport, the Community Partners section of your aboutus.html page should look like this:

![image source](https://learn.nucamp.co/pluginfile.php/4095/mod_assign/intro/assignment-task3-xs.png)

## Files To Upload ##


You will upload 4 files below for your assignment submission.


- aboutus.html
- index.html
- a screenshot of aboutus.html in a XS viewport
- a screenshot of aboutus.html in a LG viewport
To create the screenshots, we recommend using the [**Full Page Capture**](https://chrome.google.com/webstore/detail/full-page-screen-capture/fdpohaocaechififmbbbbbknoalclacl) Chrome extension.


## Assignment Resources ##
- [**Bootstrap Grid**](https://getbootstrap.com/docs/4.0/layout/grid/)
- [**Bootstrap Responsive Display Utilities**](https://getbootstrap.com/docs/4.0/utilities/display/) (documentation about using the display classes, d-none and d-*-block)
- [**Chrome Extension - Full Page Screen Capture**](https://chrome.google.com/webstore/detail/full-page-screen-capture/fdpohaocaechififmbbbbbknoalclacl)