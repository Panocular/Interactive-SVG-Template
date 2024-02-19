This template can be viewed here: 

https://panocular.github.io/Interactive-SVG-Template/

An example of a completed infographic using this template: 

https://panocular.github.io/case824/

These are the template files for a basic interactive HTML page with SVG polygons on top of a base image. The HTML page can also be embedded in a WordPress post via a iFrames.
The polygons can be clicked to toggle a popup image.
The Entire graphic is responsive if 'index.html' is used.

Temporary image placeholders are provided. 

How to use:

* This template uses 1 base image and 4 additional images.

* Edit the 'interactiveTemplate.svg' file to build a static infographic with 4 polygons and popup images. From this file, you will need the polygon coordinates (to be found in the XML tree) and the relative position of the popup images.

* Edit the 'InteractiveSVG_perc_responsive.html' file:
    Replace the src="***" with your own image URLs.

    The additional image positions are defined in the percentual dimensions of the base image.
    For example: tyle="top: 50%; left: 50%;" will place the additional image in the horizontal and vertical center of the base image, with its top left corner at these coordinates.

    There are 2 classes for image size. 

    class="additional-image" and class="additional-image larger-image"

    As an example, Image4 is larger than the other images, using the "additional-image larger-image" class.

    The SVG polygons have absolute coordinates and should be within the dimensions of the base image.
    For example the top left polygon: polygon id="clickable-polygon1" class="st0" points="400,200 450,200 450,250 400,250"></polygon>  
    These coordinates can be changed manually, or copied from the XML inside the 'interactiveTemplate.svg' file.

* The new HTML file can be hosted on your own server or on a Github page.
