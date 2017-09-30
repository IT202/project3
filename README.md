# Project 2 - Using a Bootstrap Template/Theme

With this project, you'll demonstrate that you understand how to use a template as the starting point for a project, resolve issues related to relative URLs, use the Dev tools to explore and understand the template, and make required edits.  

You'll create a version of the __Company__ sample theme on the w3schools site.  

Check the requirements and the hints, and ask questions in Piazza.

## Requirements

1. Change the color from the orange to one of the primary UIC colors. 

2. Change "Company" to some made-up company name.

3. Change the "Services" section from two rows of 3 tiles to one row of 4 tiles.

4. Change the icons on the 4 services.

5. Change the names of the 4 services.

6. Change the images on the "Portfolio" items.

7. Change the text on the "Portfolio" items.

8. Add another "What Our Customers Say" slide/review, with different content.

9. Add another indicator/~~link~~navigation "dot" for that new slide/review (below the slide set.)

10. Name the file `index.html`, in a folder named `project2`, and make sure it's accessible on GitHub.


## Hints

As you start, you may not have any idea how to accomplish some of these things, but the Dev Tools will help you get there.  You'll need to "Inspect" elements, and use the Elements pane in the Dev Tools to explore the structure of a specific element (and the elements above and below in the DOM hierarchy) and to explore the styles applied to a specific element.

First, you need to get the template.  Navigate to w3schools, then to their Bootstrap tutorial, and find the __Company__ theme.  I'm not expecting you to work through the steps of how they built it, but it is useful.)

These hints relate to the numbered requirements.

1. Take a look at https://marketing.uic.edu/visual-elements/ to find the color codes for UIC.  Use the Dev Tools to explore where and how the orange color is being set.

2. Use the search function in your editor to find the text you want to replace.

3. This requires exploration of the elements and understanding the "12 column" layout concept.  Notice that the "Services" section is a container, and that within it are two divs with a class of "row."  Explore the row and note how the 12 columns are accounted for.  Some practice/play/trial-and-error should get you there.

4. Explore one of the "Services" tiles, and note how the image/icon is created.  This theme uses Bootstrap 3.3.7; navigate to that site, then to Components and look at the Glyph Icons that are available. 

5. See #2.

6. You can reference images on the web (as opposed to downloading images into your project.)  The images in the theme are 400 x 300  (inspect them), and you want to use images of the same size.  In Google Image search, one of the __Tools__ allows you to specify the image size 

7. See #2.

8. Do some Inspecting, see how this section is built, find the HTML for one slide element, and copy/paste and edit.

9. Similar to #8, with one wrinkle.  Keep in mind that indexes are zero-based in JavaScript (not that you need to write any JavaScript.)

10. ` add, commit, push `  And don't make any changes directly on GitHub!

To get the Google Map to load, either remove the `apiKey` URL parameter from the `script` tag for the Google Maps API, or update the value with your own key.   Navigate to https://developers.google.com/maps/ , click the __Get Started__ button, select __Google Maps JavaScript API__, and on _that_ page, click the __GET A KEY__ button.  

You're going to need your own key for later projects.


