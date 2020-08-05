# **CSS Notes**

## **_CSS allows you to create rules that specify how the content of an element should appear. CSS makes your web pages POP with color and design.CSS allows you to make rules that control the way each box or html element is presented._**

+ example - 

<!DOCTYPE html>
<html>
  <head>
    <title>Introducing CSS</title>
    <link href="css/example.css" type="text/css"
       rel="stylesheet" />
       </head>
       <body>
          <h1>css notes</h1>
          <p>-CSS - cascading style sheet 
             - RGB - red green blue -' background-color: rgb(214, 233, 176)'
             - HSL - Hue Saturation Light 
             - Opacity - ???</p>
          <h2>more css notes</h2>
          <p>-Hex code - hexidecimal code - #000000 or #000
             - Layout - remember wireframe - 
             - Rule 
             - selector</p>
       </body>
       </html>   
     
body {
    font-family: Arial, Verdana, sans-serif;}
h1, h2 {
  color: #ee3e80;}
p {
  color: #665544;}

### CSS uses selectors- 
+ universal selector * {}
+ type selector h1, h2, h3, {}
+ class selector .note, {}, p.note, {} 
+ id selector #introduction {}
+ child selector li>a {}
+ decendant selector p,a,{}
+ adjacent sibling selector h1+p {}
+ general sibling selector h1~p {} 

[Link back to Table of Contents](README.md)