<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {
    font-family: "Lato", sans-serif;
}

.sidenav {
    height: 100%;
    width: 180px;
    position: fixed;
    z-index: 1;
    top: 0;
    left: 0;
    background-color: #212121;
    overflow-x: hidden;
    padding-top: 20px;
}

.sidenav a {
    padding: 6px 8px 6px 16px;
    text-decoration: none;
    font-size: 18px;
    color: #818181;
    display: block;
}

.sidenav a:hover {
    color: #f1f1f1;
}

.main {
    margin-left: 180px; /* Same as the width of the sidenav */
    font-size: 18px; /* Increased text to enable scrolling */
    padding: 0px 10px;
}

@media screen and (max-height: 450px) {
    .sidenav {padding-top: 15px;}
    .sidenav a {font-size: 18px;}
}
</style>
</head>


<div class="sidenav" id="sidenav">
  <a href="#home" class="active">Home</a>
  <a href="#install">Installation issues</a>
  <a href="#launch">Launch issues</a>
  <a href="#connect">Connection issues</a>
  <a href="#performance">Performance issues</a>
  <a href="#forge">Forge</a>
  <a href="#hosting">Server hosting</a>
  <a href="#contact">Contact</a>
  <a href="javascript:void(0);" style="font-size:15px;" class="icon" onclick="myFunction()">&#9776;</a>
</div>

<div style="padding-left:16px">
<div id="home" class="menu-category">
<h2 class="menu-category-name">Home</h2>
  <p>Resize the browser window to see how it works.</p>
</div>

<script>
function myFunction() {
    var x = document.getElementById("sidenav");
    if (x.className === "topnav") {
        x.className += " responsive";
    } else {
        x.className = "topnav";
    }
}
</script>

<head>
    function w3_open() {
    document.getElementById("sidenav").style.display = "block";
}
function w3_close() {
    document.getElementById("sidenav").style.display = "none";
}
    </head>

<head>
<meta name="viewport" content="width=device-width, initial-scale=1">

<style>
.accordion {
    background-color: #eee;
    color: #444;
    cursor: pointer;
    padding: 18px;
    width: 100%;
    border: none;
    text-align: left;
    outline: none;
    font-size: 15px;
    transition: 0.4s;
}

.active, .accordion:hover {
    background-color: #ccc;
}

.accordion:after {
    content: '\002B';
    color: #777;
    font-weight: bold;
    float: right;
    margin-left: 5px;
}

.active:after {
    content: "\2212";
}

.panel {
    padding: 0 18px;
    background-color: white;
    max-height: 0;
    overflow: hidden;
    transition: max-height 0.2s ease-out;
}
</style>
</head>


<body>
<div id="install" class="menu-category">
<h2 class="menu-category-name">Installation Issues</h2>
</div>
<button class="accordion">Subsection 1</button>
<div class="panel">
  <p> subtext </p>
</div>

<button class="accordion">Subsection 2</button>
<div class="panel">
  <p> subtext </p>
</div>

<button class="accordion">Subection 3</button>
<div class="panel">
  <p> subtext </p>
</div>



<div id="launch" class="menu-category">
<h2 class="menu-category-name">Game Launch Issues</h2>
</div>
<button class="accordion">Subsection 1</button>
<div class="panel">
  <p> subtext </p>
</div>

<button class="accordion">Subsection 2</button>
<div class="panel">
  <p> subtext </p>
</div>

<button class="accordion">Subection 3</button>
<div class="panel">
  <p> subtext </p>
</div>



<div id="connect" class="menu-category">
<h2 class="menu-category-name">Connection Issues</h2>
</div>
<button class="accordion">Subsection 1</button>
<div class="panel">
  <p> subtext </p>
</div>

<button class="accordion">Subsection 2</button>
<div class="panel">
  <p> subtext </p>
</div>

<button class="accordion">Subection 3</button>
<div class="panel">
  <p> subtext </p>
</div>



<div id="performance" class="menu-category">
<h2 class="menu-category-name">Performance Issues</h2>
</div>
<button class="accordion">Subsection 1</button>
<div class="panel">
  <p> subtext </p>
</div>

<button class="accordion">Subsection 2</button>
<div class="panel">
  <p> subtext </p>
</div>

<button class="accordion">Subection 3</button>
<div class="panel">
  <p> subtext </p>
</div>



<div id="forge" class="menu-category">
<h2 class="menu-category-name">Forge</h2>
</div>
<button class="accordion">Subsection 1</button>
<div class="panel">
  <p> subtext </p>
</div>

<button class="accordion">Subsection 2</button>
<div class="panel">
  <p> subtext </p>
</div>

<button class="accordion">Subection 3</button>
<div class="panel">
  <p> subtext </p>
</div>



<div id="hosting" class="menu-category">
<h2 class="menu-category-name">Server Hosting</h2>
</div>
<button class="accordion">Subsection 1</button>
<div class="panel">
  <p> subtext </p>
</div>

<button class="accordion">Subsection 2</button>
<div class="panel">
  <p> subtext </p>
</div>

<button class="accordion">Subection 3</button>
<div class="panel">
  <p> subtext </p>
</div>



<script>
var acc = document.getElementsByClassName("accordion");
var i;

for (i = 0; i < acc.length; i++) {
  acc[i].addEventListener("click", function() {
    this.classList.toggle("active");
    var panel = this.nextElementSibling;
    if (panel.style.maxHeight){
      panel.style.maxHeight = null;
    } else {
      panel.style.maxHeight = panel.scrollHeight + "px";
    } 
  });
}
</script>

<br>

<div id="contact" class="menu-category">
<h3 class="menu-category-name">Contact</h3>
<p><a href="https://github.com/eldewritohelp/eldewritohelp.github.io/issues">Report issues with this page here</a></p>

</div>

              
          
