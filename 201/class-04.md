# Reading Notes for Class 04

## HTML Links, JS Functions, and CSS Layout.

  ### HTML Links
  *There are several types of links in HTML. Below is a list of 5.*

  * Links from one website to another.
  * Links from one page to another on the same website.
  * Links from one part of a web page to another part of the same page.
  * Links that open in a new browser window.
  * Links that start up your email program and address a new email to someone.

  * Links in HTML use this type of element - < a > following with the href attribute
  * The value of the href attribute is the page you want people to go to when they click on the link.
  * Users can click on aything between the opeing and closing tag to get to the link.
  * URL stands for **_Uniform Resource Locator._** Every web page has it's own URL.
  * When linking to other pages within the same site you use **_relative URL's.
  
  *There are 5 different Relative Link types.*
  * Same folder -  < a > href="reviews.html">reviews</ a >.
  * Child folder - < a href="music/listings.html">Listings</ a >.
  * Grandchild Folder - < a href="movies/dvd/reviews.html">Reviews</ a >.
  * Parent Folder - < a href="../index.html">Home</ a >.
  * Grandparent Folder - < a href="../../index.html">Home</ a >

  *By using an id attribute, you can link to a specific part of your web page.*
  *You can create links to open email programs with an email address in the **TO** field.*

  ## CSS Layout

  * CSS treats each html element as if it is in it's own box.
  * This type of CSS box with either be a *Block-level box* or an *Inline* box.
  * If one block-level element sits inside another block-level element then the outer box is the *Containing* or *Parent* element.
  * CSS uses *Positioning schemes* to control a web page
  * There are 5 different positioning schemes used in CSS - 
    * *Normal Flow*
    * *Relative positioning*
    * *Absolute positioning*
    * *Fixed positioning*
    * *Floating elements*

  * In normal flow each block-level element sits on top of the next one.
  * Relative postiioning move an element in relation to where it would have been in normal flow.
  * When the position property is given a value of absolute the box is taken out of normal flow and no longer affects the position of the other elements on the page.
  * With fixed positioning its a type of absolute positioning that requires the position property to have a value of fixed.
  * The Float property allows you to take an element in normal flow and place it as far to the left or right of the containing element as possible.
  * When elements are floated, the height of the boxes can affect where the following elements sit.

  **_Many web pages use multiple columns in their design. This is achieved by using a < div > element to represent each column._**
  
  **_Resolution refers to the number of dots a screen shows per inch._**   

  **_Web designers try to create web pages at or around 960-1000 pixels wide._**

  **_To create a fixed width layout, the width of the main boxes on a page will usually be specified in pixels( as well as their height too)._**

  **_Sometimes an extra html element is used to contain the page, rather than fixing the width of the < body >. This allows the background of the browser window to have a different color than the background of the content._**

  **_A *Liquid Layout* uses percentages to specify the width of each box so that the design will stretch to fit the size of the screen._**

  **_There is a rule on the < body > element to set the width of the page to 90% so that there is a small gap between the left and the right-hand sides of the browser window and the main content._**

  **_The 960 pixel grid is widley used by web designers._**

  **_Grids set consistent proportions and spaces between items which helps to create a professional looking design._**

  **_CSS frameworks aim to make life easier by providing the code for common tasks, such as creating layout grids, styling forms, creating printer-friendly versions of pages and so on._**

  **_You can include the CSS framework code in your projects rather than writing the CSS from scratch._**

  **_There are advantages and disadvantages to doing this as shown below._**
   **Advantages**
      * They save you from repeatedly writing code for the same tasks.
      * They will have been tested across different browser versions( which helps aviod browser bugs).
    
  **Disadvantages**
      * They often require that you use class names in your html code that only control the presentation of the page ( rather than describe its content).
      * In order to satisfy a wide variety of needs, They often contain more code than you need for your particular web page ( commonly referred to as code "bloat").

**_The **_960.GS_** is one of the most popular CSS frameworks used in creating grids to layout pages._**

**_Some web page authors split up their CSS style rules into separate style sheets. For example, they might use one style sheet to control the layout and another to control fonts, colors and so on._**

**_In the html you can use 2 ways to add multiple style sheets to a page. One is on your html page you can link to one style sheet and that stylesheet can use the @import rule to import other style sheets. Or another way is in the html you can use a separate < link > element for each style sheet._**

**_As with all syle sheets, if two rules apply to the same element the rules apply to the same element the rules that appear later in a document will take precedence over previous rules._**

**_You can have multiple CSS files in one page._**

**_Grids help create professional and flexible designs._**

## **Functions, Methods, and Objects**

**_Programmers use functions, methods, and objects to organize their code._**

  * Functions & Methods
  **_Functions consist of a series of satements that have been grouped together because they perform a specific task. While a method is the same as a function, exept methods are created inside of an object._**

  * Objects
  **_Objects are made up of properties and methods._**

  * Built-in Objects
  **_The browser comes with a set of objects that act like a toolkit for creating interactive web pages._**

**_Parameters are pieces of info that is passed to a function._**

**_When you write a function and you expect it to provide you with an answer, the responce is known as a return value._**

**_To create a function, you give it a name and then write the statements needed to achieve its task inside of curly braces. This is known as a function declaration._**

**_When you declare a function, you can then execute all of the statements between its curly braces with just one line of code. This is known as Calling the function._**

**_Sometimes a function needs specific info to preform its task. When you declare the function you give it parameters. Inside the function, the parameters act like variables._**

**_When you call a function that has parameters, you specify the values it should use in the parentheses that follow its name. The values are called *arguments,* and they can be provided as values or as variables._**

**_Some functions return info to the code that called them. When they perform a calculation, they return the result._**

**_Functions can return more than one value using an array._**