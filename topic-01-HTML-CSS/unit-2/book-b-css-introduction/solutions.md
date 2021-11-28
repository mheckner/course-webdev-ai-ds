# Beispiellösungen

### About Me Seite mit neuen Klassen:
#### Super nerdy version for no reason
~~~html
<!DOCTYPE html>
<html>
<head>
    <meta charset="utf8">
    <meta name="viewport" content="width=device-width">
    <title>Wade</title>
    <link href="style.css" rel="stylesheet" type="text/css">
</head>
<body>
<h2> Wade Winston Wilson </h2>
<p>Alter: <b>45</b> </p>
<img src=" https://pngimg.com/uploads/deadpool/deadpool_PNG103.png" alt="Avatar">

<h2 id="studium">Studium:</h2>
<p>Studiengang: <span id="Studiengang" >Schauspiel</span></p>
<p>"Laughing can serve you in dark moments and even help you crawl your way out." - Ryan Reynolds</p>

<h2>Nice to know:</h2>
<table>
    <tbody>
    <tr>
        <td class="left_col">Herkunft</td>
        <td class="right_col">Vancouver</td>
    </tr>
    <tr>
        <td class="left_col">Hobbys</td>
        <td class="right_col">Kenjutsu<br>Mint Mobile<br>Aviation American Gin</td>
    </tr>
    </tbody>
</table>
<script src="script.js" ></script> <!-- Hier wird das Javascript file eingebunden -->

</body>
</html>
~~~


#### Standard version
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

<h2 id="studium">Studium:</h2>
<p>Studiengang: <span id="Studiengang" > Künstliche Intelligenz und Data Science</span></p>
<p>Der wahrscheinlich zukunftssicherste Studiengang der Informatik</p>

<h2>Nice to know:</h2>
<table>
    <tbody>
    <tr>
        <td class="left_col">Herkunft</td>
        <td class="right_col">München</td>
    </tr>
    <tr>
        <td class="left_col">Hobbys</td>
        <td class="right_col">Fotografie<br>Mountainbiking</td>
    </tr>
    </tbody>
</table>
<script src="script.js" ></script> <!-- Hier wird das Javascript file eingebunden -->

</body>
</html>
~~~


### CSS:

~~~css
*{
    /* change font for all elements */
    font-family: "Maven Pro";
    color: dimgrey;
    margin: auto;
    vertical-align: center ;
    text-align: center;
    background: lightgrey;
}

.h2 {
    text-align: center;
    font-size: 30px;
}

img{
    height: 200px;
    border-radius: 100%;
}

#Studiengang{
    color: black;
    font-style: italic;
}
 /* Styling der Tabelle */
table, th, td {
    border: 1px solid black;
    vertical-align: center ;
    text-align: center;
}

table {
    border-collapse: collapse;
}

.left_col{
    width: 100px;
    height: 50px;
    
}

.right_col{
    width: 200px;

}



~~~