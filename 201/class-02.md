# Reading notes for class 02

## Text

* When creating a web page, you add **_TAGS_** ('known as **_MARKUP_**') to the contents of the page.
    * Structural Markup - **The elements that you use to show both headings and paragraphs.**
    * Semantic markup - **Provides extra info; where the emphasis is placed in a sentance. Such as a quote, ('and who said it'), meanings of acronyms, and so on.**

* There are 6 levels of headings 
   * ('<h1>')
   * ('<h2>')
   * ('<h3>')
   * ('<h4>')
   * ('<h5>')
   * ('<h6>')

* The html for a paragraph is: ('<p>').
* Html for bold and italic : ('<b>') , ('<i>')
* Html for superscript & Subscript : ('<sup>') , ('<sub>')
* Html for Line breaks & Horizontal rules ('<br />) , ('<hr />')

 ## CSS

* *CSS* allows you to create rules that specify how the content of an element should appear.
* The key to understanding how CSS works is to imagine the there is an invisible box around every html element.
* CSS allows you to create rules that control the way that each single box looks on a web page.
* for CSS to appear correctly on a page you need a slector ('p') , and a declartion ('font-family: arial;').
CSS also uses other elements that are broken down in the declaration, they are the property ('color'), and ('value').
* When a CSS does not display properly it is refered to as a **browser quirk** or a **CSS** bug 
* CSS rules usually appear in a different doc but also sometimes might appear within the html page as well.

## Basic JavaScript instructions

* A script is instructions a computer follows one-by-one. Each step is known as a **STATEMENT** and the are followed by a semicolon.
* It is important to pay close attention to letters and their case sensitivity when using JavaScript.
  * var today = new Date();
    var hourNow = today.getHours();
    var greeting;

    if (hourNow > 18) {
       greeting = 'Good evening';
  } Else if (hourNow > 12) {
       greeting = 'Good afternoon';
  } Else if (hourNow) > 0) {
       greeting = 'Good morning';
  } else {
       greeting = 'Welcome';
  }
  document.write(greeting);

* Statements surrounded by curly brackets are known as **Code blocks**.
* to write a comment that stretches over more than one line, you use a **Multi-line** comment, starting with **/*** and ***/** .
* **Variables** are used to store pieces of info.
* **Arrays** are special variables that store more than one piece of related info.
* **JavaScript** distinguishes between numbers ('0-9'), strings ('text'), and boolean values ('true or false').

  ## Decisions & loops

  == - equal to
  != - is not equal to
  === - strict equal to
  !== - strict not equal to
  > - greater than
  >= - greater than or equal to
  < - Less than
  <= - Less than or equal to.
