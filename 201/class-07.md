# Reading Notes for Class 07 Tables, Functions, Methods and Objects

## Chapter 06 Tables

**When representing information in a table, you need to think in terms of a grid made up of rows and columns; Bit like a spreadsheet.**

- A table represents info in a grid format. Each block in the grid is reffered to as a *table cell*. 
- In HTML a table is written out row by row.

``<table>`` - element is used to create a *table*.

  - The ``<tr>``  tag is used at the start of each row with this opening tag. It stands for *table row*.
  - The ``<td>``  tag represents the cell of each table. It stands for *table data*.

  - The ``<th>``  tag represents the heading of the table or column. It stands for *table heading*.

- **It is important to note that you should always use the two elements ``<td>`` and ``<th>`` even when a cell has no content because the table will not render correctly**.

- Using the ``<th>`` elements for headings helps people with screen readers, improves the ablity for search engines to index pages, and also gives you greater control over the appearance of tables once you start your css.

- The *colspan* attribute can be used on a ``<th>`` or a ``<td>`` element and it indicates how many columns that cell should run accross.

- The *rowspan* attribute can be used on a ``<th>`` or ``<td>`` element to indicate how many rows a cell should span down the table.

- A table Heading should sit inside the ``<thead>`` element.

- The body should sit inside the ``<tbody>`` element.

- The footer belongs inside the ``<tfoot>`` element.

- Above those three elements help distinguish between the main content of the table and the first and last rows. They too help people with screen readers. 

## Chapter 03 Functions, Methods, and Objects

- Sometimes you will want several objects to represent similar things. *Object constructors* can use a function as a template for creating objects. 
- First you'll want to create the template with the object's properties and methods.

- The *This* keyword is used instead of an object name to indicate that the property or method belongs to the object that *this* function creates.

- After every statement that creates a new property or method for this object it will always end in a semicolon and not a comma.

- The name of the *constructor function* usually begins with a capital letter. The uppercase letter is supposed to help remind developers to use the new keyword when the create an object using that function.

- You create instances of the object using the *constructor function*. The new keyword followed by a call to the function creates a new object. The properties of each object are given as arguments to the function.

- Functions allow you to group a set of related statements together the represent a single task.

- Functions can take parameters and can return a value.

- An object is a series of variables and functions that represent something from the world around you. 

- In an object, variables are known as properties of the object; functions are known as methods of the object.

- Web browsers implement objects that represent both the browser window and the document loaded into the browser window.

- JavaScript also has several built-in objects such as *String, Number, Math, and Date*. Their properties and methods offer functionality that help you right scripts.

- Arrays and objects can be used to create complex data sets(\ and both can contain the other\).

- The *Math* object has properties and methods for mathematical constants and functions.

  ``Math.pi``  - Returns pi, It's also a *property*

  ``Math.round()`` - Rounds number to nearest integer, it's also a method.

  ``Math.sqrt(n)`` - Returns square root of pos number, e.g. , Math.sqrt (9) returns 3. Also a method

  ``Math.ceil()``  - Rounds number up to the nearest integer. Also a method.

  ``Math.floor()`` - Rounds number down to the nearest interger. Also a method.

  ``Math.random()`` - Generates a random number between 0 (\ inclusive\) and 1 (\not inclusive\).

- In JavaScript there are six data types. Five of them are described as simple or primitive, data types. The sixth is the object and it's refered to as a complex data type.

  - **Simple or primitive data types**

  - ``String``

  - ``number``
  
  - ``Boolean``

  - ``undefined``

  - ``Null``

  - **Complex data type**

  - ``Object``

- **Whenever you have a value that is a string, you can use the properties and methods of the *String* object on that value.**



[Return back to the table of Contents](README.md)
  
