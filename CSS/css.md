# CSS

#### What is CSS?
- CSS stands for Cascading Style Sheets
- Used to style the HTML file
#### Types of adding CSS
- Inline
- Internal
- External
#### Examble of Inline CSS
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
#### Examble of Internal CSS
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