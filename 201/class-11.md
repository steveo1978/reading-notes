# Reading Notes Class 11

## Chapter 16 Images

- **Controlling the size and alignment of your images using CSS keeps rules that affect the presentation of your page in the CSS and out of the HTML markup.**

- You can control the size of an image using the ``width`` and ``height`` properties in CSS.

- Where the ``<img>`` elements appear in the HTML, rather than using ``width`` and ``height`` attributes you can use these names as values for the class attribute.

- Rather than using the ``<img>`` element's allign attribute, web page authors are increasingly using the float property to align images. There are two ways that this is achieved :
    - The ``float`` property is added to the class that was created to represent the size of the image.
    - New classes are created with names such as ``align-left`` or ``align-right`` to align the images to the left or right of the page. These class names are used in addition to classes that indicate the size of the image.

- By defult, images are inline elements. In order to center an image, it should be turned into a ``block-level`` element using the ``display`` property with a value of ``Block``.

- Once it has been made into a *block-level* element, there are 2 ways in which you can horizontally center an image :
  - On the containing element, you can use the **text-align** property with a value of center.
  - On the image itself, you can use the **margin** property and set the values of the left and right margins to auto.

- Repeating images
    ``repeat``  ``repeat-x``  ``repeat-y``  ``no-repeat``
    ``fixed``  ``scroll``

- When an image is not being repeated, you can use the ``background-position`` property to specify where in the browser window the background image should be placed.
    ``background-color``  ``background-image``
    ``background-repeat``  ``background-attachment``
    ``background-position``

- You can create image rollover effects by moving the background position of an image. 

- To reduce the number of images your browser has to load, you can create image sprites.

## Chapter 19 Practical Information

- **SEO** or Search Engine Optimization is a huge topic and several books have been written on the subject.

- SEO helps visitors find you sites when using search engines.

- Analytics tools such as Google Analytics allow you to see how many people visit your site, how they find it, and what they do when they get there.

- To put your site on the web, you will need to obtain a domain name and web hosting.

- **FTP** programs allow you to transfer files from your local computer to your web server.

- Many companies provide platforms for blogging, email newsletters, e-commerce and other popular website tools (to save you writing them from scratch).





[Return to the table of Contents](README.md)