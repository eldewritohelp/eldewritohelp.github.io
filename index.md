<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {
    font-family: "Lato", sans-serif;
}

.sidenav {
    height: 100%;
    width: 0;
    position: fixed;
    z-index: 1;
    top: 0;
    left: 0;
    background-color: #111;
    overflow-x: hidden;
    transition: 0.5s;
    padding-top: 60px;
}

.sidenav a {
    padding: 8px 8px 8px 32px;
    text-decoration: none;
    font-size: 25px;
    color: #818181;
    display: block;
    transition: 0.3s;
}

.sidenav a:hover {
    color: #f1f1f1;
}

.sidenav .closebtn {
    position: absolute;
    top: 0;
    right: 25px;
    font-size: 36px;
    margin-left: 50px;
}

@media screen and (max-height: 450px) {
  .sidenav {padding-top: 15px;}
  .sidenav a {font-size: 18px;}
}
</style>
</head>
<body>

<div id="mySidenav" class="sidenav">
  <a href="javascript:void(0)" class="closebtn" onclick="closeNav()">&times;</a>
  <a href="#home" class="active">Home</a>
  <a href="#install">Installation issues</a>
  <a href="#launch">Launch issues</a>
  <a href="#connect">Connection issues</a>
  <a href="#performance">Performance issues</a>
  <a href="#forge">Forge</a>
  <a href="#hosting">Server hosting</a>
  <a href="#contact">Contact</a>
</div>

<h2>Header</h2>
<p>Text</p>
<span style="font-size:30px;cursor:pointer" onclick="openNav()">&#9776; open</span>

<script>
function openNav() {
    document.getElementById("mySidenav").style.width = "250px";
}

function closeNav() {
    document.getElementById("mySidenav").style.width = "0";
}
</script>
     
</body>

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

              
          
