# z-indeks
<!--#
1. Przeanalizować proces nakładania w narzędziu deweloperskim przeglądarki.

-->


<!DOCTYPE html>


<html lang="pl">
<head>
    <meta charset="utf-8">
    <meta name="description" content="simple example of html">
    <meta name="author" content="infoShare Academy">
    <meta name="keywords" content="infoshare, academy">
    <title>cw-css-04</title>
    <link rel="shortcut icon" href="images/fcavicon.ico" type="image/x-icon" />

    <link rel="stylesheet" href="styles/test.css" />
</head>
<body>
<main>

<header id="naglowek-strony">
    <!--<div class="logo-witryny logo-witryny-2 right"></div>-->

    <!--<div class="logo-witryny-3 left">kontakt</div>-->


    <!--<div class="wersja-produktu left"> wersja 1.0</div>-->

    <!--<span><br>Nasz text do tekstów<br>lalaalala</span>-->
    <!--<div class="clear"></div>-->

    <div class="klasa">element 1</div>
    <div class="pozycja-relatywna">element 1</div>
    <div class="pozycja-relatywna2">element 1</div>
    <div  class="">element 3</div>
</header>
    </main>

<div class="socjal-media">pozycja</div>

</body>
</html>
/*}*/
main{
    padding: 200px;
background-color: red;
}

header{
    padding: 20px;
    background-color: yellow;
}
div{
    margin: 20px;
    width: 200px;
    height:25px;
   padding: 2px;
    background-color: blue;


}

.pozycja-relatywna{
    margin: 20px;
    width: 200px;
    height:25px;
    padding: 2px;
    background-color: pink;
    right:auto;
    left:auto;
    position: absolute;top:-10px;right:500px;
    z-index: 20000;
}

.pozycja-relatywna2 {

    background-color: blueviolet;
    position: absolute;
    top: 30px;
    right: 50px;
    height: 400px;
    z-index: 200;
}
.socjal-media{
    background-color: white;
    position: fixed;
    top: 100px;
    right: 200px;
    height: 200px;
    z-index: 1000;
}
