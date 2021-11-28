# Beispiellösungen

### About Me Seite mit neuen Klassen:
~~~html
<!DOCTYPE html>
<html> 
  <head>
    <meta charset="utf8">
    <meta name="viewport" content="width=device-width">
    <title>Florian</title>
    <link href="style.css" rel="stylesheet" type="text/css">
  </head>
  <body>
    <h2> Florian Testnutzer </h2>
    <p>Alter: <b>21</b> </p>
    <img src=" https://upload.wikimedia.org/wikipedia/commons/thumb/9/98/OOjs_UI_icon_userAvatar.svg/480px-OOjs_UI_icon_userAvatar.svg.png" alt="Avatar">
    <script src="main.js" ></script> <!-- Hier wird das Javascript file eingebunden -->
    <table>
        <tbody>
            <tr>
                <td>Hobbys</td>
                <td>Fotografie<br></td>
            </tr>
            <tr>
                <td>Lieblingsfarbe</td>
                <td>Rot<br></td>
            </tr>
        </tbody>
    </table>
  
  </body>
</html>
~~~


### CSS:

~~~css
*{
    /* change font for all elements */
    font-family: "Maven Pro";
    color: dimgrey;
}

.h2 {
    font-size: medium;
}

.img{
    height: 200px;
}


~~~