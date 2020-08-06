# Read: 06 - JS Object Literals; The Dom

## CH: 03 Object Literals

- Objects group together a set of variables and functions to create a model of something you would recognize from the real world. In an **_Object_**, variables and functions take on new names.

- **In an object Variables become known as properties. Properties tell us about the object.**
- **In an object Functions become know as methods. They reprsent tasks that are associated with the object.**

``var hotel = {``            <------------------------- Properties

``name: 'Quay',``            <------------------------- "        "

``rooms: 40,``               <------------------------- "        "

``booked: 25,``              <------------------------- "        "

``gym: true,``               <------------------------- "        "

``roomTypes: ['twin', 'double', 'suite'],``    <------- Properties

``checkAvailability: Function(){``             <-------- Method

``return this.rooms - this.booked;``           <-------- Method

  ``}``          <---------------------------------------- Method

``};``

- Literal notation is the easiest and most popular way to create objects.\(There are several ways to create objects.\)
- You access the properties or methods of an object using dot notation. You can also access properties using square brackets.


## CH: 05 Document Object Model

- **_The document Object model or DOM_** **specifies how browsers should create a model HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window**

- The *DOM* is neither part of the HTML, nor is it a part of the JavaScript; It has a seperate set of rules.
- The *DOM* is called an object model because the model *(The DOM tree)* is made of objects. Each object represents a different part loaded in the browser window.
- The DOM is also called the **Application Programming Interface (API)**. User Interfaces let humans interact with programs.
- The DOM tree is a model of a web page. As a browser loads a web page, It creates a model of that page. The model is know as the DOM tree, and it get stored into the browsers memory. It consists of 4 different types of nodes.
- At the top of the DOM tree is the **Document node**, It represents the entire web page.
- **Element nodes**, are the HTML elements on a web page. They describe the structure of the page.
- The **Attribute nodes**, are the opening tags of HTML elements. Not the children of the elements that carry them, just part of that element. 
- Then there are the **TEXT nodes**, once you have accessed an element node, you can then reach the text within that element. This is stored in its own text node. Text nodes cannot have children. 

- **Accessing and updating the DOM tree involves two steps:**
  1 **Locate the node that represents the element that you want to work with.**
    1 **Use its text content, child elements, and attributes.**

    - Step one Access the Elements:

- Here are some common ways to select an individual element: 
     ``getElementById()``

     ``querySelector()``

- Here are three common ways to select multiple elements:
     ``getElementByClassName()``

     ``getElementByTagName()``

     ``querySelectorA11()``

   - Step two Work with those Elements:
     - Access / Update text nodes.

   ``nodeValue``

   **nodeValue** - This property lets you access or update contents of a text node.

  - Work with HTML Content.
     ``innerHTML``

     **innerHTML** - Lets you access child elements and text content.

     ``textContent``

     **textContent** - Lets you have access to just the text content.

     - There are several methods that let you create new nodes, add nodes to a tree, and remove nodes from a tree, those are listed below :

     ``createElement()``

     ``createTextNode()``

     ``appendChild()``

     ``removeChild``

- Access or update attribute values

    ``className / id``

    **className / id** - Lets you get or update the value of the class and id attributes.

    ``hasAttribute()``

    ``getAttribute()``

    ``setAttribute()``

    ``removeAttribute()``

    - Above, the first checks if an attribute exists. The second gets its value. The third updates the value. Then the fourth removes an attribute.

- **The terms *Elements* and *Element nodes* are used interchangeably but when people say the DOM is working with an element, it is actually working with a node the represents that element.**

- Methods that find elements in the DOM tree are called *DOM queries*. 
- When people talk about storing elements in variables, they are really storing the location of the elements within the DOM tree in a veriable. The properties and methods of that element node work on the variable.
- DOM queries may return one element, or they may return a *NodeList*, which is a collection of nodes.
   - Methods that return a single element node:
    ``getElementById('id')``

    ``querySelector('css selector')``

   - Methods that return one or more elements (as a nodelist):
    ``getElementByClassName('class')``

    ``getElementsByTagName('tagName')``

    ``querySelectorAll('css selector')``

- *Browsers offer tools for viewing the DOM tree.





[Click here to return to the main table of contents](README.md)



