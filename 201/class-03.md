# Reading Notes for Class 3

## **HTML Lists, CSS Boxes, and JS Control Flow**

* There are 3 different types of HTML lists
  * **_Ordered lists_**- lists where each item in the list is numbered.
  * **_Unordered Lists_**- Lists that begin with a bullet point.
  * **_Definition Lists_**- Are made up of a set of terms along with the definition for each of those terms.

* Ordered lists use the < ol >, and < li > Tags.
* Unordered Lists use the < ul >, and < li > Tags.
* Definition Lists use the < dl >, < dt >, and < dd > Tags.

### *Lists can be nested inside one another.*

### **With *CSS* you can control dimensions of boxes, create borders around boxes, set the margins and padding for the boxes, and also show and hide boxes.**

* The most popular way to specify the size of a box is by use of pixels.
* You can also use percentages, and ems to size boxes as well.
* You can limit the height of a box by using min-height, and max-height properties.
* You can limit the width by using min-width, and max-width properties.
* The overflow property tells the browser what to do if the content contained within a box is larger than the box itself. They give them *values* called **Hidden** and **Scroll** properities.
* There are 3 available properties that can be adjusted to control appearance.
   * **_Border_** , **_Margin_** , and **_Padding_**
* There are 4 individual size of border properties
   * **_Border-top-width_** 
   * **_Border-right-width_**
   * **_Border-bottom-width_**
   * **_Border-left-width_**
* You can control the style of a border by using the **_border-style_** property on your CSS page.
* You can even design the color of your borders by using the property **_border-color_**.
* The **padding** property allows you to specifiy how much space should appear between the content of an element and its border.
* The **Margin** property controls the gap between boxes.
* The **Display** property allows you to turn an inline element into a block-level element or vice versa, it can also be used to hide an element from the page.
* The **Visibility** property allows you to hide boxes from users but it leaves a space where the element would have been. This property can take 2 values - *Hidden* and *Visisble*.
* The **Border-image** property applies an image to the border of any box. It takes a background image and slices it into 9 pieces.
* The **Box-shadow** property allows you to add a drop shadow around a box.
* With CSS3 you can use the **Border-radius** property to create rounded corners.
* You can also use the **Border-radius** property to create elliptical shapes as well.

## JavaScript Loops and Conditional statements

* **For an *If or else* statement the *if* *else* statement checks a condition. If it resolves to *true* the first code block is executed. If the condition resolves as *False* the second code block is run instead.**

* A **Switch** statement starts with a variable called the *Switch value*.
* If you use a data type JavaScript that you did not expect to use, it will try to make sense of the operation rather than report an error.
* Due to type coercion, every value in JavaScript can be treated as if it were true or false.
* The presence of an object or array can be considered truthy and it is often used to check for the existence of an element within a page.
* Logical operators are processed left to right. The short-circuit or *Stop* as soon as they have a result, they also return the value that stopped the processing (not necessarily true of false).
* **Loops** check a condition. if it returns *true*, a code block will run. Then the condition will be checked again and if it still returns *true*, the code block will run again. It repeats until the condition returns *false*.
* There are 3 common types of loops
   * **_for_** - runs specific code a specific amount of times.
   * **_while_** - If you do not know how many times you want to run the code then you use this type of loop.
   * **_do while_** - The **do...while** loop is very similar to the while loop but with one key difference, it will always run the statements inside curly braces at least once, even if the condition evaluates to false.
   * A **For** loop is often used to loop through the items in an array.
   * A **while** loop will continue to run for as long as the condition in parentheses is true.
   * The key difference between a *while* and a *do while* loop is that the statements in the code block come **before** the condition. 

   [Link back to table of Contents](README.md)