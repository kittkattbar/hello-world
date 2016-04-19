
<html>
<head>
  <title>Ollie Bike Sharing</title>
  <meta charset="utf-8"/>
  <link rel="stylesheet" type="text/css" href="main.css">
</head>
<div class="container"
<body>
<div class="nav">
  <h2>Ollie</h2> 
  <ul>
    <li>Sign Up</li>
    <li>search bikes</li>
    <li>reserve a bike</li>
    <li>about us</li>
  </ul>
  </div>
  <div class="main">
   <h1>Ollie Bike Sharing</h1>
  <h3>Share Your Pedals with the World</h3>
  <p> This is the place to be when you need a set of wheels to get you moving in the right direction. Here is a 
  <a href="cities.html">list</a> of cities where you can find us.</p>
<img src="http://www.greatlakesadventureproject.com/wp-content/uploads/2013/09/49_Budget-Bicycle-Center3_ss.png" width="340" height="210"/>
</div>
</body>
</div>
</html>
onst githubMarkdownCss = require('generate-github-markdown-css');

githubMarkdownCss((err, css) => {
    console.log(css);
    //=> '.markdown-body { 
    
<link rel="stylesheet" href="github-markdown.css">
<style>
html, body {
  font-family: sans-serif;
  margin: 0;
  width: 100%;
  height: 100%;
}

h1 {
  font-size: 48px;
}

p {
  max-width: 65%;
  min-width: 500px;
}

h2 {
  text-align: center;
  font-size: 2.6rem;
}

div {
  padding-right: 30px;
  height: 100%;
  width: 100%;
}

video {
  background-color: #000000;
  border: 2px solid black;
}

.container {
  display: flex;
}

.main {
  padding-left: 30px;
  min-width: 75%;
}

.nav {
  background-color: #FFEE00;
  max-width: 25%;
  min-width: 140px;
  flex: 1;
}

.nav h1 {
  padding-left: 20px;
}

</style>
