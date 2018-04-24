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
  <a href="#hosting">Other</a>
  <a href="#contact">Contact</a>
</div>

<h1>Header</h1>
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
    
<button class="accordion">Download-related issues</button>
<div class="panel">
  <p> <p><a href="https://www.reddit.com/r/HaloOnline/wiki/index/download">Did you follow this guide?</a></p>
 </p>
</div>

<button class="accordion">Antivirus</button>
<div class="panel">
  <p> Antivirus fix: To allow updater with malwarebytes: go to "Settings" on right side. Then, Choose "Exclusions" on the top tab. Click, "Add Exclusion" at the bottom. Choose "Exclude a File or Folder". Then choose the Updater.exe in the brower. Similar process with other antivirus programs; they should give a notice of what file was removed, which will need to be added to the exclusion list.</p>
</div>

<button class="accordion">Subection 3</button>
<div class="panel">
  <p> subtext </p>
</div>



<div id="launch" class="menu-category">
<h2 class="menu-category-name">Game Launch Issues</h2>
</div>
<button class="accordion">Black Screen</button>
<div class="panel">
  <p> Black screen on first launch: Steam or other overlays crash it. First time playing? Post your CPU and GPU models.</p>
</div>

<button class="accordion">Crashing</button>
<div class="panel">
  <p> If your game is crashing, make sure the file path to the Halo Online folder doesn't contain any characters like ä or ö </p>
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

<button class="accordion">FPS</button>
<div class="panel">
 <ul>
  <li>In graphic settings, change the FPS fix setting and restart the game.</li>
  <li>In Console (~ or F1 key) type Game.FPSlimiter 0 and then type writeconfig and then restart the game.</li>
  <li>Overlays crash on decrease fps. (discord, steam, etc)</li>
  <li> Right click eldorado -> properties; "disable full screen optimizations" </li> 
  <li> Engine physics tied to FPS, do not try to go over 60FPS </li>\
  <li> Try toggling the windowed mode option (the game does not run in true fullscreen, only windowed fullscreen) </li>
</ul> 
</div>

<button class="accordion">Black Screen</button>
<div class="panel">
  <p> Black screen with scoreboard up: in console (F1 key) type game.stop </p>
</div>

<button class="accordion">High brightness</button>
<div class="panel">
  <p> Settings menu > video > bloom patch </p>
</div>
<button class="accordion">Slow load times</button>
<div class="panel">
<ul>
    <li>In Console (~ or F1 key) type Game.FPSlimiter 0 and then type writeconfig and then restart the game.</li>
    <li>Move Halo Online folder to desktop and/or SSD </li>
</ul>
</div>



<div id="forge" class="menu-category">
<h2 class="menu-category-name">Forge</h2>
</div>

<button class="accordion">Save locations</button>
<div class="panel">
<ul>  
    <li> Forge prefabs go in ElDewrito/mods/prefabs/stuf.prefab </li>
    <li> Forge savefiles go as ElDewrito/mods/maps/<mapName>/sandbox.map </li>
</ul>
</div>

<button class="accordion">Controls</button>
<div class="panel">
  <li><a href="https://www.reddit.com/r/HaloOnline/comments/34h205/forge_controls_keyboard/"> Keyboard controls </a></li>
   <li> <img src="https://cdn.discordapp.com/attachments/434449710846312469/437695959082729492/forge.png" 
             alt="controls" /> </li> 
</div>

<button class="accordion">Subection 3</button>
<div class="panel">
  <p> subtext </p>
</div>



<div id="hosting" class="menu-category">
<h2 class="menu-category-name">Server Hosting</h2>
</div>
<button class="accordion">Port Forwarding</button>
<div class="panel">
<ul>  
  <li><a href="https://www.reddit.com/r/HaloOnline/comments/8e93i4/halo_online_eldewrito_port_forwarding_in_depth/"> Comprehensive port forwarding guide, including a link for dedicated server hosting </a></li>
   <li> <img src="https://i.imgur.com/WpMah4I.png" 
             alt="Simple Guide" /> </li> 
</ul>
</div>

<button class="accordion">Subsection 2</button>
<div class="panel">
  <p> subtext </p>
</div>

<button class="accordion">Subection 3</button>
<div class="panel">
  <p> subtext </p>
</div>



<div id="other" class="menu-category">
<h2 class="menu-category-name">Other issues</h2>
</div>
<button class="accordion">Emblems and stats reset</button>
<div class="panel">
  <ol>
      <li> Press Win + R from desktop to open run dialog box </li>
      <li> Type "%localappdata%" with no quotes then press enter. </li>
      <li> Navigate to the ElDewrito folder (...AppData\Local\ElDewrito) </li>
      <li> Right click keys.cfg and click "Copy" </li>
      <li> Navigate to wherever you've saved eldorado and then paste file in the root folder. (the one that has the ElDorado.exe application). </li>
      <li> Rename the file to autoexec.cfg </li>
      <li> If you delete that autoexec, you will loose your stats again </li>
    </ol>
</div>

<button class="accordion">H3 Weapons crash</button>
<div class="panel">
  <p> Run FMM as admin and reinstall. </p>
</div>

<button class="accordion">XBone Controller not detected</button>
<div class="panel">
  <p> There's been issues with xbox one controllers, we don't know what causes the game to not pick them up </p>
</div>

<button class="accordion">Settings not saving</button>
<div class="panel">
  <p> Move the game out of Program Files. Check if the files or folders are read-only. Test: Run eldorado.exe as admin </p>
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

              
          
