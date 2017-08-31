# Final Touch

In this section we look at techniques to change the look and feel of your application. Let's say we want to change the color of our navigation bar. We can right click and inspect element on the header bar, and scroll through the styles section to find the background color. Here it will tell us what file this style came from, at which point we can go to this file and change it ourselves. For every other element in our application we can use this workflow to change the padding, margins, color, font, and so on. We should add all of our changes in a separate css file instead of bootstrap because if we change bootstrap and then we download a new release of bootstrap, we will lose all of our changes.