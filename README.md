# CssBootPortfolio
Unit 02 CSS and Bootstrap Homework: Responsive Portfolio




# Goal
The reason why I did this project was to learn how bootstrap interacts with the HTML structure and existing CSS styles. I wanted the content of my pages to be well posistioned and proportioned in a fashion that makes the content easy to read/navigate through for the user.  I applied bootstrap to my static portfolio project I did in the past and indeed saw how it affected my website in a responsive fashion.


# Header Section (All Pages)
The header section initially had three links and text with my name that were simply just floating at the top of the screen that remained static no matter the size of the window. When I applied a couple bootstrap column classes to the elements, I was able to make the links as one column and my name in text as it's own column, thus allowing the elements to be responsive to the size of the window. I did run into a problem though, when the window was at a small size, both the links and name were not positioned and sized correctly, so I did need to make a media query at the window size to fix the issue.


# About Section
My goal was to have the content container to be at the left of the screen when the window is large and to be more centered when it sizes down. Both at larger window sizes for the columns, I set the content creater to take up 8 columns and created an empty div element with a column class that takes up 4 columns. They then center up with the window when it sizes down to a medium size screen and so on.


# Portfolio Section
This section I had alot of trouble with. Even with the responsiveness of the bootstrap column classes, the positioning with all the images and lables were not in the exact places I wanted them to be in, so I needed to apply a transform property with a translate value to position the images appropriately. Again with media queries, when the window was small, I needed to center up the images, so I applied the transform property and translate value to that media query class to center up the images and lables as well.


# Contact Section
This section needed the least amount of work initially. Much like the about me section, I added a column to main container that only takes up 8 columns out of the 12 when it is at a large widow size ; it then takes up all 12 columns when it sizes down to a medium screen size and smaller.

# Conslusions
Throughout the experience of rebuilding my mock portfolio with the use of bootstrap, I learned that incorporating the framework to build a responsove website can be a great asset when wanting to create content that fuctions easily/smoothly for the user. Through the use of bootstrap, I think what makes my website stand out is how balanced I was able to keep the conent in terms of composition, no matter the window size. 




##Static Website
https://ryanmosely.github.io/portfolioAssignment/

##Bootstrap Respnsive Website
https://ryanmosely.github.io/CssBootPortfolio/
