# CSS

#### What is CSS?
- CSS stands for Cascading Style Sheets
- Used to style the HTML file
#### Types of adding CSS
- Inline
- Internal
- External
#### Example of Inline CSS
```html
<!DOCTYPE html>
<html lang="en" style="background:black">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <p style="color: white;">
        <!-- Text comes here -->
    </p>
</body>
</html>
```
#### Example of Internal CSS
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        html{
            background: red;
        }
        body{
            color: yellow;
        }
    </style>
</head>
<body>
    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Beatae sapiente corporis quis error possimus in?</p>
</body>
</html>
```
#### Example of External CSS
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Beatae sapiente corporis quis error possimus in?</p>
</body>
</html>
```
##### And Adding styles in style.css
```css
html{
     background: red;
}
body{
    color: yellow;
}
```
#### Types of Selectors in CSS
- Element Selector
```css
h1{
    color:red
}
```
- Class Selector
```css
/* <h1 class="class_name">TEXT</h1> */
.class_name{
    color:red
}
```
- ID Selector
```css
/* <h1 id="id_name">TEXT</h1> */
#id_name{
    color:red
}
```
- Universal Selector
```css
*{
    color:red
}
```
