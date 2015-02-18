This readme file is a description of the improvements made to Project 4.  

The following changes were made to Project P4:


**Changes to main index.html- Checked with Pagespeed Insights:**

font is already added in style, no noticeable effect when deleted, removed link.
Moved data in print.css to style.css.
Resized images pizzeria.jpg and profilepic.jpg to achieve higher performance.
removed px=100, due to resizing image to meet specs.



**Changes to pizza.html data to optimize FPS performance:**

Variables removed from for loops, to improve FPS.
Optimized pizzasDiv to improve FPS.
Changed # of pizzas to 32.
Optimized image for background pizzas.
moved items & numOfItems- They are not created until the .mover class is loaded.



References:

-Piazza Forums
-Google P4 Office Hours: https://plus.google.com/u/0/hangouts/onair/watch?hid=hoaevent%2Fcomnga3cdvrpkjm7dvb4l71ph2o&ytl=dSlVrVCnrvk&hl=en
-Pagespeed Insights: https://developers.google.com/speed/pagespeed/insights/
-Google Analyzing Critical Rendering Path: https://developers.google.com/web/fundamentals/performance/critical-rendering-path/analyzing-crp#performance-patterns
-Google Optimizing the Critical Rendering Path: https://developers.google.com/web/fundamentals/performance/critical-rendering-path/optimizing-critical-rendering-path

