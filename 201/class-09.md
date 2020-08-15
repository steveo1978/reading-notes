# Class 09 Reading Notes Forms and JS Events

## Chapter 07 Forms

- HTML borrows the concept of a form to refer to different elements that allow you to collect information from visitors to your site. 

- Whether you are adding a simple search box to your website or you need to create more complicated insurance applications, HTML forms give you a set of elements to collect data from your users.

- **The best known form on the web is probably the search box that sits right in the middle of GOOGLE's homepage.**

- listed below are several different types of forms that do different things.
  - Adding text :      **Text Input**     **Password Input**     **Text Area**
  - Making choices :   **Radio Buttons**  **Checkboxes**         **Drop-down Boxes**
  - Submitting forms : **Submit Buttons** **Image Buttons**
  - Uploading files :  **File Upload**

- A form may have several form controls, each gathering different info. The server needs to know which piece of inputted data corresponds with which form elements.

- **You should never change the name of a form control in a page unless you know that the code on the server will understand this new value.**

- Form controls live inside a ``<form>`` element. This element should always carry the action attribute and will usually have a method and id attribute too.

- Every ``<form>`` element requires an action attribute. Its value is the URL for the page on the server that will receive the information in the form when its submitted.

- Forms can be sent using one of two methods: get or post.
  - The *get* method is ideal for: short forms, and when you are just retrieving data from the web server. 
  - With the *post* method the values are sent in HTTP headers. you should use the post method if your form: **Allows users to upload a file**
        **Is very long**
        **Contains sensitive data**
        **Adds information to, or deletes information from, a database**

- The ``<input>`` element is used to create several different form controls.
- When the *Type* attribute has a value of text, it creates a single-line text input. ex. -  ``type="text"``        
- You can use the ``maxlength`` attribute to limit the number of characters a user may enter into the text field. 
- When the ``type="password"`` attribute has a value of password it creates a text box that acts just like a single-line text input, except the characters are blocked out. 

- The ``<textarea>`` element is used to create a mutli-line text input. Any text that appears between the opening ``<textarea>`` and closing ``</textarea>`` tags will appear in the text box when the page loads.

- ``type="radio"`` radio buttons allow users to pick just one of a number of options.

- ``type="checkbox"`` checkboxes allow users to select (and unselect) one or more options in answer to a question.

-  The ``<select>`` element is used to create a drop down list box.

- The ``<option>`` element is used to specify the options that the user can select from.

- ``type="file"`` This type of input creates a box that looks like a text input followed by a **Browse** button. 

- ``type="submit"`` the submit button is used to send a form to the server.

- ``type="image"`` if you want to use an image for the submit button, you can give the type attribute a value of image.

- The ``<button>`` element was introduced to allow users more control over how their buttons appear, and to allow other elements to appear inside the button.

- ``type="hidden"`` This type of example also shows a hidden form control.

- Each form control is given a name, and the text the user types in or the values of the options they select are sent to the server.

- HTML5 introduces new form elements which make it easier for visitors to fill in forms.


## Chapter 14 Lists, Tables & Forms

- There are several CSS properties that were created to work with specific types of HTML elements, such as lists, tables, and forms.

- The ``list-style-type`` property allows you to control the shape or style of a bullet point also knowns as a marker.
  - it can be used on rules that apply to the ``<ol>`` , ``<ul>`` , and ``<li>`` elements.

- Lists are indented into the page by default and the ``list-style-position`` property indicates whether the marker should appear on the inside or the outside of the box containing the main points.

- As with several of the other CSS properties, there is a property that acts as a shorthand for list styles. It is called ``list-style`` and it allows you to express the markers' style, image and position properties in any order.

- If you have empty cells in your table, then you can use the ``empty-cells`` property to specify whether or not their borders should be shown.

  - ``font-size`` sets the size of the text entered by the user.
  - ``color`` sets the text color.
  - ``background-color`` sets the background color of the input.
  - ``border`` adds a border around the edge of the input box.
  - ``border-radius`` can be used to create rounded corners.
  - ``:focus`` pseudo-class is used to change the background color of the text input when it is being used.
  - ``:hover`` pseudo-class applies the same styles when the user hovers over them with their mouse.

- Table cells can have different borders and spacing in different browsers, but there are properties you can use to control them and make them more consistent.

- Forms are easier to use if the form controls are vertically aligned using CSS.

- Forms benefit from styles that make them feel more interactive. 


## Chapter 06 Events

- **When you browse the web, your browser registers different types of events. Scripts often respond to these events by updating the content of the web page which makes the page feel more interactive.**

- Events occur when users click or tap on a link, hover or swipe over an element, type on the keyboard, resize the window, or when the page they requested has loaded. 
- When an event occurs, or fires, it can be used to trigger a particular function.
- The events can trigger the kinds of changes the DOM is capable of. 

- UI events occur when a user interacts with the browser's user interface (UI) rather than the web page.
  - ``load`` ----- Web page has finished loading 
  - ``unload`` --- Web page is unloading 
  - ``error`` ---- Browser encounters a JS error
  - ``resize`` --- Browser window has been resized
  - ``scroll`` --- User has scrolled up or down the page

- Keyboard events occur when a user interacts with the keyboard.
  - ``keydown`` --- User first presses a key
  - ``Keyup`` ----- User releases a key
  - ``keypress`` -- Character is being inserted

- Mouse events occur when a user interacts with a mouse, trackpad, or touchscreen.
  - ``click`` ----- User presses and releases a button over the same element
  - ``dblclick`` -- User presses and releases a button twice over the same element
  - ``mousedown`` - User presses a mouse button while over an element
  - ``mouseup`` --- User releases a mouse button while over an element
  - ``mousemove`` - User moves the mouse 
  - ``mouseover`` - User moves the mouse over an element
  - ``mouseout`` -- User moves the mouse off an element 

- When an event has occurred, it is often described as having *fired* or been *raised*.

- When the user interacts with the HTML on a web page, there are three steps involved in getting it to trigger some JS code.
  - Step 1: Select the **element** you want the script to respond to.
  - Step 2: Indicate which **event** on the selected node will trigger the responce
  - Step 3: State the **code** you want to run when the event occurs

- *Event handlers* let you indicate which event you are waiting for on any particular element. There are three types of event handlers.
  - HTML event handlers
  - Traditional DOM event handlers
  - DOM level 2 event listeners

- HTML elements nest inside other elements. If you hover or click on a link, you will also be hovering or clicking on its parent elements. 

- Event handlers/ listeners can be bound to the containing ``<li>`` , ``<ul>`` , ``<body>`` , and ``<html>`` elements, plus the document object, and the window object.
- The order in which the events fire is known as *event flow*, and events flow in two directs.
- The flow of events only really matters when your code has event handlers on an element and one of its ancestor or descendant elements.

- Binding is the process of stating which event you are waiting to happen, and which element you are waiting for that event to happen upon.

- When an event occurs on an element, it can trigger a JS function. When this function then changes the web page in some way, it feels interactive because it has responded to the user.

- You can use event delegation to monitor for events that happen on all of the children of an element.

- The most commonly used events are W3C DOM events, although there are others in the HTML5 specification as well as browser-specific events.




[Return to the table of Contents](README.md)