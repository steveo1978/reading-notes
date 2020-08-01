# Reading Notes for Class 05

## **Reading notes Chapter 05 HTML Images; CSS Color & Text

### Chapter 05 - Images

**There are many different thinks to consider when deciding on and preparing images for a website, and taking proper time to get them right will make the page more professional and attractive.**

*When choosing an image for your page the images should;*
  - Be relevant
  - convey information
  - Convey the right mood
  - Be instantly recognisable
  - Fit the color palette

**If you are creating a site from scratch, it is a good idea to create a folder for all the images that the site will use.**

****<img>****Element is used to add an img to a webpage. It must carry the following two attributes:
    - *SRC, Which tells the browser where it can find the image file.*
    - *alt, This provides a text description of the image that describes the image if you cannot see it.*
    - *tittle, This provides additional info about the image when you hover you mouse over the image.*

**you can also use following two attributes for **_height_** and **_Width_**. which measure each in pixels.**

**_When using HTML you can place images either before a paragraph tag or inside of it or in the middle of the paragraph._**

*The align attribute was used to indicate how other parts of a page should flow around an image, but is removed in HTML5.*

**There are 3 rules for creating images;
  - Save images in the right format.
  - Save images at the right size.
  - Measure images in pixels.

When you use an image that has many different colors it's a good idea to use the image as a *JPEG*, Because it can pick up the suble differences in colors better than a standard picture format.

Use a *GIF* or *PNG* format when saving images with few colors or large areas of the same color.

The images you use on your site should be the same width and height that you want them to appear on your page.

When cropping an image it is important not to lose valuable info. It's always good practice to source the image that is the correct shape if possible.

Do not use centimeters or inches when sizing an image on the screen. You should size your image using a set of dimensions called pixels.

Vector images differ from bitmap images and are resolution-independent.

An animated GIF shows several frames of an image in sequence and therefore can be used to create simple animations.

If you want to create an image that is partially transparent or see through you would use either of these two formats;
  - *Transparent GIF*
  - *PNG*

## Chapter 11 - Color 

**Colors can bring you pages to life**

The color property allows you to specify the color of text inside of an element. You specify any color by using CSS in one of three ways.
  - **RGB Values** - These express colors in terms of how much red, green, and blue are used to make it up. Example rgb(\100,100,90\).
  - **HEX Codes** - These six-digit codes represent the ammount of red, green, and blue are used in a color, preceeded by a pound or hash sign. ex #ee3380.
  - **Color Frames** - There are 147 predefined color names that browsers recognize. ex *DarkCyan*

  CSS treats each HTML element as if it appears in a box, and the *background-color* property sets the color of the background for that box.

  When deciding on a foreground and background colors it is important to ensure that there is enough contrast for the text to be legible.

  CSS3 has the *Opacity* property, which allows you to specify the opacity of an element and any of it's child elements.

  The CSS3 *rgba* property allows you to specify a color just like you would with an rgb value, but adds a fourth value to indicate opacity.

  CSS3 also uses **Hue, Saturation, and Lightness** values to specify color.
    - **HUE** is the colloquial idea of color. It is often represented by a color circle.
    - **Saturation** is the ammount of gray in a color. It is represented by a percentage.
    - **Lightness** is the ammount of white or black that is in a color. Lightness is sometimes refered to as *Luminosity*. it too is also represented by a percentage.

## Chapter 12 TEXT

The properties that allow you to control the appearance of text can be split into two groups.
  - Those that directly affect the font and it's appearance.
  - Those that would have the same effect on text no matter what font you choose.

**Formatting of your text can have significant effect on how readable your pages are.**  

There are 3 different types of typeface terminology
  - **Serif** fonts have extra details on the ends of the main strokes of the letters.
  - **Sans-serif** fonts have straight ends to letters, and therefore have a much cleaner design.
  - **Monospace** fonts have the same width while non-monospace fonts have different widths.

  **The font weight adds emphasis and can also affect the ammount of white space and contrast on a page.**

  *Italic fonts have a cursive aspect to some of it's lettering.*

  **_In condensed versions of the font , letters are thinner and closer together._**

  **It is improtant to note that when choosing a typeface that a browser will only display it if it is installed on to the users computer.**

  **If you want to use a wider range of typefaces there are many different options , but you need to have the right license to use them.** 

  **You can control the space between lines of text, individual letters , and words. Text can also be aligned to the left, right, center, or justified. It can also be indented.**

  **You can use pseudo-classes to change the style of an element when a user hovers over or clicks on text, or when they have visited a link.**


