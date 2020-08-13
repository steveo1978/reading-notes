# Class 08 Reading Notes

## Chapter 15 CSS Layout

- This Reading assignment will discuss how to control where each element is on a page and how to style a page by using **CSS**.

- *CSS* treats each HTML element as if it's in it's own box or inline box.

- ``Block-level`` boxes start on a new line and act as the main building blocks of any layout.
  - While ``inline boxes`` flow between surrounding text.
  - You can control how much space each box takes up by setting the width of the boxes.
  - To seperate boxes, you can use borders, margins, padding, and background colors.
  - Block-level elements include :
    ``<h1>``
    ``<p>``
    ``<ul>``
    ``<li>``

  - Inline elements include :
    ``<img>``
    ``<b>``
    ``<i>``


- If one block-level element sits inside another block-element then the outer box is known as the **Containing** or **Parent** element.
  - It is common to group a number of elements together inside of a ``<div>`` element. 
  - The ``<div>`` element that contains this group of elements is then referred to as the *containing element*.
  - A box may be nested inside several other block-level elements. The *containing element* is always the *direct parent* of that element.

- CSS has the following *positioning schemes* that allow you to control the layout of a page.
  - **Normal Flow** - Every block-level element appears on a new line , causing each item to appear lower down the page than the previous one.
  - **Relative Positioning** - This moves an element from the position it would be in normal flow, shifting it to the top, right, bottom, or left of where it would have been placed.
  - **Absoulte Positioning** - This positions the element in relation to it's containing element. It is taken out of normal flow.

- To indicate where a box should be positioned, you may also need to use a **Box Offset** property to tell the browser how far from the top or bottom and left or right it should be placed.
  - **Fixed Positioning** - This is a form of absolute positioning that positions the element in relation to the browser window, as opposed to the containing element.
  - **Floating Elements** - Floating an element allows you to take that element out of normal flow and position it to the far left or right of a containing box.
- When you move any element from normal flow, boxes can overlap. The *Z-index* property allows you to control which box appears on top.

- **Resolution** refers to the number of dots a screen shows per inch.

- Pages can be fixed width or liquid ( streachy ) layouts.

- Designers keep pages within 960-1000 pixels wide, and indicate what the site is about within the top 600 pixels.

- Grids help create professional and flexible designs.

- CSS frameworks provide rules for common tasks.

- You can include multiple CSS files in one page.




