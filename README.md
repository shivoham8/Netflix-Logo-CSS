# Netflix Logo

The provided HTML and CSS code creates a representation of the Netflix logo using a combination of styling elements. The logo is designed with a skewed red center and borders, resembling the iconic Netflix brand. The code ensures a responsive and centered display on different devices, and the background color is set to azure for added visual appeal. Developers can use and customize this code to incorporate a Netflix-like logo into their web projects or explore and experiment with CSS styling techniques.

## HTML Structure
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Netflix Logo</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="netflix-logo"></div>
</body>
</html>
```

## CSS
```css
body {
    padding: 0;
    margin: 0;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: azure;
}

.netflix-logo {
    height: 15rem;
    width: 3rem;
    border-left: 3rem solid #e50914;
    border-right: 3rem solid #e50914;
}

.netflix-logo::before {
    display: block;
    content: '';
    width: 100%;
    height: 100%;
    background: #e50914;
    transform: skewX(21.5deg);
    box-shadow: 0 0 30px black;
}
```
