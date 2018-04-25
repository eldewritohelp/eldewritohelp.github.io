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
  <a href="#audio">Audio issues</a>
  <a href="#performance">Performance issues</a>
  <a href="#forge">Forge</a>
  <a href="#hosting">Server hosting</a>
  <a href="#hosting">Other</a>
  <a href="#contact">Contact</a>
</div>

<h1>El Dewrito 0.6 Help</h1>
<p>This is an unofficial compilation of commonly seen issues with ED 0.6 for Halo Online. <a href="https://imgur.com/a/WAHDW1d">If you haven't already done so, please read through this guide.</a></p>
<p><a href="https://gist.github.com/dany5639/7807e2d094f8823a30bf4ac027f9b2ec">Link to a gist MegaFAQ with most possible solutions</a></p>


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
  <p><a href="https://www.reddit.com/r/HaloOnline/wiki/index/download">Did you follow this guide? </a></p>
 <p>Due to IP concerns by Microsoft, the links to download the version of Halo Online (ms23_106708) needed to run this mod will not be distributed. The links to download the mod itself (El Dewrito 0.6), however, are still available. </p>
</div>

<button class="accordion">Antivirus</button>
<div class="panel">
  <p> Antivirus fix: To allow updater with malwarebytes: go to "Settings" on right side. Then, Choose "Exclusions" on the top tab. Click, "Add Exclusion" at the bottom. Choose "Exclude a File or Folder". Then choose the Updater.exe in the brower. Similar process with other antivirus programs; they should give a notice of what file was removed, which will need to be added to the exclusion list.</p>
</div>



<div id="launch" class="menu-category">
<h2 class="menu-category-name">Game Launch Issues</h2>
</div>
<button class="accordion">Black Screen</button>
<div class="panel">
  <ul> 
      <li>Black screen on first launch: Steam or other overlays crash it. First time playing? Post your CPU and GPU models.</li>
    <li> There's a problem with higher end GPU's where graphics break completely or blackscreen on boot. There's no fix as 
this is an unoptimised alpha build which has poor AMD and Intel GPU support which ElDewrito devs sadly can't fix without source code.
Report it on /r/HaloOnline bi-weekly thread, we'll verify in time, there's thousands of bug reports, it won't be fixed soon.</li>
      <li> Try this: Cut and paste dewrito_prefs.cfg outside of the folder for backup, launch the game. If it doesn't work, put the file back. </li>
      <li> In dewrito_prefs.cfg change Game.FPSlimiter from 1 to 0 </li>
      </ul>
</div>

<button class="accordion">Crashing</button>
<div class="panel">
   <ul>
   <li>If your game is crashing, make sure the file path to the Halo Online folder doesn't contain any characters like ä or ö </li>
       <li> Crashing with steam? Game needs to be run as administrator </li>   
    </ul>
</div>

<button class="accordion">Nothing happens</button>
<div class="panel">
  <p> If nothing happens when you open eldorado.exe and you can verify that your antivirus has not removed any files, then this is likely an install issue. Reinstall the game. 
      <br>If you installed just ms23, you need to download the updater and run it for the game to work.</p>
</div>

<div id="connect" class="menu-category">
<h2 class="menu-category-name">Connection Issues</h2>
</div>
<button class="accordion">Scoreboard or loading screen stuck while joining game</button>
<div class="panel">
  <p> Try alt+tabbing out and back into the game </p>
</div>



<div id="audio" class="menu-category">
<h2 class="menu-category-name">Audio Issues</h2>
</div>
<button class="accordion">No sound in game</button>
<div class="panel">
 <ul> 
<li>Disable all other Playback Devices in Windows settings except for the ONE device that you want to use.
<br> Set the ONE device that you want to use as Default.
<br> Restart the game and verify the Sound settings are set to default.
<br>If this does not work, try running the game as Administrator.
<br>
<br>These settings also work for fixing your microphone, just apply the same idea to Recording Devices
<br>If you are still having issues, try to DISABLE VOICE CHAT -> APPLY -> ENABLE VOICE CHAT -> APPLY  </li>
<li> Try restarting the game </li>
     </ul>
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
  <li> Engine physics tied to FPS, do not try to go over 60FPS </li>
  <li> Try toggling the windowed mode option (the game does not run in true fullscreen, only windowed fullscreen) </li>
     <li> Try running as administrator </li>
</ul> 
</div>

<button class="accordion">Input lag</button>
<div class="panel">
    <p><a href="https://pastebin.com/EdtCNngk">Try the solutions in this pastebin</a></p>
</div>

<button class="accordion">Black Screen</button>
<div class="panel">
<ul>
  <li> Black screen with scoreboard up: in console (F1 key) type game.stop </li>
  <li>In Console (~ or F1 key) type Game.FPSlimiter 0 and then type writeconfig and then restart the game.</li>
</ul>
</div>

<button class="accordion">High brightness</button>
<div class="panel">
  <p> Settings menu > video > bloom patch; may need to restart game </p>
</div>
<button class="accordion">Slow load times</button>
<div class="panel">
<ul>
    <li>In Console (~ or F1 key) type Game.FPSlimiter 0 and then type writeconfig and then restart the game.</li>
    <li>Move Halo Online folder to desktop and/or SSD </li>
    <li> Turn off overlays (steam, nvidia, discord, etc) </li>
</ul>
</div>



<div id="forge" class="menu-category">
<h2 class="menu-category-name">Forge</h2>
</div>

<button class="accordion">Save locations</button>
<div class="panel">
    <ol>
        <li> Forge prefabs go in ElDewrito/mods/prefabs/stuf.prefab </li>
        <li> Forge savefiles go as ElDewrito/mods/maps/[mapName]/sandbox.map 
            </li>
    </ol>
    </div>
    
<button class="accordion">Controls</button>
<div class="panel">
<ul>
  <li><a href="https://www.reddit.com/r/HaloOnline/comments/34h205/forge_controls_keyboard/"> Keyboard controls </a></li>
  <li> <img src="https://i.imgur.com/PvHDVqi.png" 
             alt="controls" /></li> 
     <li> <img src="https://i.imgur.com/CKzo5te.png" 
             alt="controls" /></li>  
    </ul>
</div>


<button class="accordion">How to download and install custom maps and gametypes</button>
<div class="panel">
    <p>
<a href="https://www.forgehub.com/"> Maps/Variants can be downloaded from other users on this website </a>
<br>Keep in mind there are uploads on this website that are not for ElDewrito 0.6. You cannot filter by game yet.
<br>
<br><a href="https://imgur.com/XyNdUx0">Folder location for putting maps/variants/prefabs</a>
<br>
<br>Here are some commonly downloaded map packs:
<br><a href="https://mega.nz/#!C8cSjQJJ!XOxdwTa1ChSnJj2LEYIvPHNg1ORimIlqqQWTFs7GaNk"> MLG Maps and Variants [Created by SimplyStats] </a>
<br><a href="https://www.forgehub.com/maps/0-6-release-mappack.6220"> 24 maps, 5 variants, 64 prefabs. [Created by Clutchism] </a>
    </p>
    </div>
<button class="accordion">Forge hosting/multiplayer</button>
<div class="panel">
<p> Don't create a server for hosting forge - this causes desync issues and there is no fix for it right now. There is no multiplayer forge at the moment. </p>
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
    <li> <a href="https://www.yougetsignal.com/tools/open-ports/"> Use this to check that ports UDP 11772 and TCP 11775 and 11777 are open. </a></li>
</ul>
</div>

<button class="accordion">Errors</button>
<div class="panel">
  <p> Make sure DirectX 9 June 2010 update is installed </p>
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

<button class="accordion">How to change server browser</button>
<div class="panel">
  <p> open dewrito_prefs.cfg, change first line to Game.MenuURL "URL_here" </p>
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



              
          
