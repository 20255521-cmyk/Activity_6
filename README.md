e:

<!DOCTYPE html>

<html lang="en">

<head>

<meta charset="UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Xyla Cayso</title>

<style>

* {

margin: 0;

padding: 0;

box-sizing: border-box;

}

body {

font-family: Arial, sans-serif;

background: #A8A492;

color: #200f0f;

}

header {

background: #A8A492;

color: white;

text-align: center;

padding: 22px;

}

header h1 {

font-size: 25px;

letter-spacing: 2px;

}

nav {

background: #333333;

text-align: center;

padding: 15px;

}

nav a {

color: white;

text-decoration: none;

SIT-FO-045 Page 4 of 10

font-size: 13px;

font-weight: bold;

margin: 0 25px;

}

nav a:hover {

color: #cccccc;

}

input[type="radio"] {

display: none;

}

.card {

width: 90%;

max-width: 900px;

min-height: 500px;

margin: 40px auto;

background: white;

padding: 50px;

text-align: center;

border-radius: 10px;

box-shadow: 0 4px 15px rgba(0, 0, 0, 0.12);

}

.page {

display: none;

}

#home-btn:checked ~ .card #home,

#about-btn:checked ~ .card #about,

#gallery-btn:checked ~ .card #gallery,

#contact-btn:checked ~ .card #contact {

display: block;

}

.page h2 {

font-size: 28px;

margin-bottom: 12px;

}

.subtitle {

color: #888888;

font-size: 14px;

margin-bottom: 30px;

}

SIT-FO-045 Page 5 of 10

.description {

max-width: 600px;

margin: 20px auto;

color: #666666;

line-height: 1.7;

font-size: 14px;

}

.images {

display: flex;

justify-content: center;

gap: 25px;

margin: 30px 0;

}

.images img {

width: 120px;

height: 120px;

object-fit: cover;

border-radius: 50%;

border: 4px solid #555555;

}

.button {

display: inline-block;

margin-top: 20px;

padding: 12px 25px;

background: #555555;

color: white;

text-decoration: none;

border-radius: 20px;

font-size: 12px;

}

footer {

background: #333333;

color: white;

text-align: center;

padding: 18px;

font-size: 12px;

}

SIT-FO-045 Page 6 of 10

@media (max-width: 600px) {

nav a {

margin: 0 8px;

font-size: 11px;

}

.card {

padding: 30px 20px;

}

.images {

gap: 10px;

}

.images img {

width: 90px;

height: 90px;

}

}

</style>

</head>

<body>

<input type="radio" name="page" id="home-btn" checked>

<input type="radio" name="page" id="about-btn">

<input type="radio" name="page" id="gallery-btn">

<input type="radio" name="page" id="contact-btn">

<header>

<h1>Xyla's Creatives</h1>

</header>

<nav>

<label for="home-btn">

<a>HOME</a>

</label>

<label for="about-btn">

<a>ABOUT</a>

</label>

<label for="gallery-btn">

<a>GALLERY</a>

</label>

<label for="contact-btn">

<a>CONTACT</a>

</label>

SIT-FO-045 Page 7 of 10

</nav>

<main class="card">

<div id="home" class="page">

<h2>

Welcome 

</h2>

<p class="subtitle">

HUMAN INTERACTION ACTIVITY 5 LABORATORY

</p>

<div class="images">

<img src="https://encrypted-
tbn0.gstatic.com/images?q=tbn:ANd9GcSl8ySIBUUgVtw7I4bkN9HK-IBDNIb-grZseAVooL0S-g&s"

alt="firstprof.png">

<img src="https://encrypted-
tbn0.gstatic.com/images?q=tbn:ANd9GcSl8ySIBUUgVtw7I4bkN9HK-IBDNIb-grZseAVooL0S-g&s"

alt="Creative Image 2">

<img src="https://encrypted-
tbn0.gstatic.com/images?q=tbn:ANd9GcSl8ySIBUUgVtw7I4bkN9HK-IBDNIb-grZseAVooL0S-g&s"

alt="Creative Image 3">

</div>

<p class="description">

“The visual design needs to tell the story. It’s not design for design. It 
needs to reflect reality. The design needs to have a flow that goes well with the story and 
supports the story.” —Patrice Vermette

</p>

</div>

<button type="button">LEARN MORE</button>

<div id="about" class="page">

<h2>

About Me

</h2>

<p class="subtitle">

Get to know Xyla Cayso.

</p>

<p class="description">

Hi! I'm Xyla Cayso.
