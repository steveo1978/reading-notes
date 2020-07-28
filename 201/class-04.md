# Reading Notes for Class 04

## **_HTML Links, JS Functions, and CSS Layout._**

  ### HTML Links
  *There are several types of links in HTML. Below is a list of 5.*

  1 **Links from one website to another.**
  1 **Links from one page to another on the same website.**
  1 **links from one part of a web page to another part of the same page.**
  1 **Links that open in a new browser window.**
  1 **Links that start up your email program and address a new email to someone.**

  1 **Links in HTML use this type of element - < a > following with the href attribute**
  1 **The value of the href attribute is the page you want people to go to when they click on the link.**
  1 **Users can click on aything between the opeing and closing tag to get to the link.**
  1 **URL stands for **_Uniform Resource Locator._** Every web page has it's own URL.**
  1 **When linking to other pages within the same site you use **_relative URL's._****
  
  *There are 5 different Relative Link types.*
  1 **Same folder -  < a > href="reviews.html">reviews</ a >**
  1 **Child folder - < a href="music/listings.html">Listings</ a >**
  1 **Grandchild Folder - < a href="movies/dvd/reviews.html">Reviews</ a >**
  1 **Parent Folder - < a href="../index.html">Home</ a >**
  1 **Grandparent Folder - < a href="../../index.html">Home</ a >**

  *By using an id attribute, you can link to a specific part of your web page.*
  *You can create links to open email programs with an email address in the **TO** field.*

  ## CSS Layout

  1 **CSS treats each html element as if it is in it's own box.**
  1 **This type of CSS box with either be a *Block-level box* or an *Inline* box.**
  1 **If one block-level element sits inside another block-level element then the outer box is the *Containing* or *Parent* element.**
  1 **CSS uses *Positioning schemes* to control a web page**
  1 **There are 5 different positioning schemes used in CSS - 
    * *Normal Flow*
    * *Relative positioning*
    * *Absolute positioning*
    * *Fixed positioning*
    * *Floating elements*

  1 **In normal flow each block-level element sits on top of the next one.**
  1 **Relative postiioning move an element in relation to where it would have been in normal flow.**
  1 **When the position property is given a value of absolute the box is taken out of normal flow and no longer affects the position of the other elements on the page.**
  1 **With fixed positioning its a type of absolute positioning that requires the position property to have a value of fixed.**
  1 **The Float property allows you to take an element in normal flow and place it as far to the left or right of the containing element as possible.**
  1 **When elements are floated, the height of the boxes can affect where the following elements sit.**

  **_Many web pages use multiple columns in their design. This is achieved by using a < div > element to represent each column._**
  
  **_Resolution refers to the number of dots a screen shows per inch._**   

  **_Web designers try to create web pages at or around 960-1000 pixels wide._**