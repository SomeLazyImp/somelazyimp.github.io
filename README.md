<!DOCTYPE html>
<head>
   <title>shellsharks</title>
   <link rel="shortcut icon" href="/assets/img/favicon.ico">
   <link rel="alternate" type="application/rss+xml" title="Post Feed" href="https://shellsharks.com/feed.xml">
   <link rel="alternate" type="application/rss+xml" title="Notes Feed" href="https://shellsharks.com/note-feed.xml">
   <link type="text/plain" rel="author" href="https://shellsharks.com/humans.txt" />
   <link rel="canonical" href="https://shellsharks.com/">
   <link rel="apple-touch-icon" href="/assets/img/apple-touch-icon.png">
   <link rel="indieweb" href="/indieweb.txt" />
   <link href="https://github.com/shellsharks" rel="me">
   <!--IndieAuth Provider-->
   <link rel="authorization_endpoint" href="https://indieauth.com/auth">
   <!--IndieAuth-->
   <link rel="token_endpoint" href="https://tokens.indieauth.com/token">
   <!--IndieAuth token endpoint--> <!--needed for button css-->
   <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-alpha.6/css/bootstrap.min.css" integrity="sha384-rwoIResjU2yc3z8GV/NPeZWAv56rSmLldC3R/AZzGRnGxQQKnKkoFVhFQhNUwEyJ" crossorigin="anonymous">
   <link href='/assets/css/style.css' rel='stylesheet' type='text/css'>
   <script src="https://kit.fontawesome.com/97b21a4e7f.js" crossorigin="anonymous"></script> <!--Font Awesome v5-->
   <meta charset="utf-8">
   <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
   <meta name="viewport" content="width=device-width, initial-scale=1">
   <meta name="author" content="Michael Sass" />
   <meta name="description" content="Cybersecurity Research and More" />
   <meta name="keywords" content="shellsharks, infosec, bestof, project, training, red, blue, cve, vm, apple, tools, technology, desksetup, podcasting, python, nmap, reverseengineering, ida, technical, dev, exploitdev, code, cdev, linux, minix, bugbounty, blogging, appsec, pentesting, privacy, risk, thirdparty, network, dns, nessus, tenable, life, cloud, sans, oscp, hackthebox, kali, review, metasploit, burp, inboxzero, foss, svsm, vulnscape, aws, academy, osint, tesla, shellsharks, threatmodeling, git, jekyll, actions, cicd, mastodon, fediverse, management, tech, threadiverse, kbin, lemmy, indieweb, cja, tara" />
   <meta content="shellsharks" property="og:site_name">
   <script> const currentTheme = localStorage.getItem('theme') ? localStorage.getItem('theme') : null; if (currentTheme) { document.documentElement.setAttribute('data-theme', currentTheme); } </script>
   <meta content="shellsharks" property="og:title">
   <meta content="website" property="og:type">
   <meta content="Cybersecurity Research and More" property="og:description">
   <meta content="https://shellsharks.com/" property="og:url">
   <meta content="https://shellsharks-images.s3.amazonaws.com/shellsharks.png" property="og:image">
<body>
   <div class="panel" id="main">
      <div class="hamburger-menu" style="overflow:auto; position:relative;">
         <input id="menu__toggle" type="checkbox" /> <label class="menu__btn" for="menu__toggle"> <span></span> </label>
         <ul class="menu__box ">
            <li class="menu__section">Social
            <li><a href="https://infosec.exchange/@shellsharks" target="_blank" class="menu__item"><i class="fab fa-mastodon"></i> Mastodon</a>
            <li><a href="/podcast" class="menu__item"><i class="fas fa-microphone-alt"></i> The Shellsharks Podcast</a>
            <li><a href="https://infosec.pub/c/cybersecurity" target="_blank" class="menu__item"><i class="fas fa-hamburger"></i> Infosec.Pub</a>
            <li><a href="mailto:mike@shellsharks.com" class="menu__item"><i class="fas fa-envelope"></i> Email</a>
            <li><a href="https://www.linkedin.com/in/mikesass" target="_blank" class="menu__item"><i class="fa fa-linkedin"></i> Linkedin</a>
            <li><a href="https://discord.gg/3rkHgtcYbb" target="_blank" class="menu__item"><i class="fab fa-discord"></i> Shellsharks Discord</a>
            <li><a href="https://github.com/shellsharks" target="_blank" class="menu__item"><i class="fa fa-github"></i> Github</a>
            <li><a href="https://www.threads.net/@mk3s" target="_blank" class="menu__item"><i class="fas fa-at"></i> Threads</a>
            <li><a href="https://bsky.app/profile/shellsharks.com" target="_blank" class="menu__item"><i class="fas fa-sun"></i> Bluesky</a>
            <li class="menu__section">Site Navigation
            <li><a href="/about" class="menu__item"><i class="fas fa-address-card"></i> About</a>
            <li><a href="/notebook" class="menu__item"><i class="fas fa-sticky-note"></i> Notes</a>
            <li><a href="/more" class="menu__item"><i class="fas fa-drafting-compass"></i> Projects</a>
            <li><a href="/statboard" class="menu__item"><i class="fas fa-tachometer-alt"></i> Statboard</a>
            <li><a href="/roadmap" class="menu__item"><i class="fas fa-road"></i> Roadmap</a>
            <li><a href="/changelog" class="menu__item"><i class="fas fa-exchange-alt"></i> Change Log</a>
            <li><a href="/more#archives" class="menu__item"><i class="fas fa-archive"></i> Archives</a>
            <li><a href="/pro" class="menu__item"><i class="fas fa-certificate"></i> Shellsharks Pro</a>
            <li><a href="/tags" class="menu__item"><i class="fa fa-tags"></i> Tags</a>
            <li><a href="/uses" class="menu__item"><i class="fas fa-desktop"></i> Uses</a>
            <li><a href="/resume" class="menu__item"><i class="fas fa-user-tie"></i> Resume</a>
            <li><a href="/sharkweek" class="menu__item"><i class="fas fa-calendar-week"></i> >Shark Week</a>
            <li><a href="/fediverse" class="menu__item"><i class="fas fa-project-diagram"></i> Fediverse</a>
            <li><a href="/feed.xml" class="menu__item"><i class="fas fa-rss"></i> Posts RSS</a>
            <li><a href="/note-feed.xml" class="menu__item"><i class="fas fa-rss-square"></i> Notes RSS</a>
            <li><a href="/.well-known/security.txt" class="menu__item"><i class="fas fa-bug"></i> Report a Bug</a>
            <li><a href="/humans.txt" class="menu__item"><i class="fas fa-user"></i> Humans</a>
            <li><a href="indieweb.txt" class="menu__item"><i class="fas fa-compass"></i> IndieWeb</a>
            <li><a href="https://ko-fi.com/shellsharks" class="menu__item"><i class="fas fa-coffee"></i> Buy me a Coffee</a>
            <li><a href="/ocean" class="menu__item"><i class="fas fa-water"></i> the Ocean</a>
            <li class="menu__section">Other
            <li><a href="https://mastodon.social/@sass" target="_blank" class="menu__item"><i class="fab fa-mastodon"></i> Mastodon.Social</a>
            <li><a href="/public.pgp" class="menu__item"><i class="fas fa-key"></i> PGP Public Key</a>
            <li><a href="https://fediverse-webring-enthusiasts.glitch.me/profiles/shellsharks_infosec.exchange/index.html" target="_blank" class="menu__item"><i class="far fa-circle"></i> Webring Enthusiasts</a>
            <li><a href="https://fedia.io/m/cybersecurity" target="_blank" class="menu__item"><i class="far fa-folder-open"></i> Fedia.io</a>
            <li><a href="https://feedly.com/i/subscription/feed%2Fhttps%3A%2F%2Ffeedly.com%2Ff%2FneuQ4GZtuykzD5qcSDS93WyG" target="_blank" class="menu__item"><i class="fab fa-readme"></i> Feedly</a>
            <li><a href="https://ts.la/michael65140" target="_blank" class="menu__item"><i class="fas fa-car"></i> Tesla Referral</a>
            <li><a href="https://web.archive.org/details/https://shellsharks.com" target="_blank" class="menu__item"><i class="fas fa-history"></i> Wayback</a>
            <li><a href="https://www.reddit.com/user/mk3s/" target="_blank" class="menu__item"><i class="fab fa-reddit-alien"></i> Reddit</a>
            <li><a href="https://twitter.com/shellsharks" target="_blank" class="menu__item"><i class="fa fa-twitter"></i> Twitter</a>
            <li><img src="/assets/img/avatar.png" height="50" style="bottom: -45px; position: relative; padding: 0px 0px 10px 0px; display: block; margin:auto;" />
         </ul>
      </div>
      <div align=center>
         <!--<img src="https://shellsharks-images.s3.amazonaws.com/logos/avatar-earthday.png" height="300" width="300"/><br/><br/>--> <!--<img src="https://shellsharks-images.s3.amazonaws.com/logos/avatar-circus.png" height="300" width="300"/><br/><br/>--> <!--<img src="https://shellsharks-images.s3.amazonaws.com/logos/avatar-valentines.png" height="300" width="300"/><br/><br/>--> <!--<img src="https://shellsharks-images.s3.amazonaws.com/logos/avatar-prochoice.png" height="300" width="300"/><br/><br/>--> <!--<img src="https://shellsharks-images.s3.amazonaws.com/logos/avatar-columbus.png" height="300" width="300"/><br/><br/>--> <!--<img src="https://shellsharks-images.s3.amazonaws.com/logos/avatar-halloween.png" height="300" width="300"/><br/><br/>--> <!--<img src="https://shellsharks-images.s3.amazonaws.com/logos/avatar-christmas.png" height="300" width="300"/><br/><br/>--> <!--<img src="https://shellsharks-images.s3.amazonaws.com/logos/avatar-newyears-2023.png" height="300" width="300"/><br/><br/>--> <img src="/assets/img/avatar.png" height="300" width="300"/><br/><br/> <img src="/assets/img/shellsharks.gif" style="position:relative; margin-left: 20px;max-width:350px;width:90%;"/><br/>
         <p style="padding-bottom: 5px;">
            <i><span class="hov altcolor" style="font-weight:600;">Infosec</span> <i class="fas fa-grip-lines-vertical fa-sm"></i> <span class="hov altcolor" style="font-weight:600;">Technology</span> <i class="fas fa-grip-lines-vertical fa-sm"></i> <span class="hov altcolor" style="font-weight:600;">Life</span></i>
            <link rel="stylesheet" href="/assets/css/super-search.css">
         <div style='display: none'><a rel="me" href="https://infosec.exchange/@shellsharks">Mastodon</a></div>
         <div class="social" id="icons">
            <ul>
               <li><a href="https://infosec.exchange/@shellsharks" target="_blank"><i class="fab fa-mastodon grow" title="Mastodon"></i></a>
               <li><a href="/podcast" ><i class="fas fa-microphone-alt grow" title="The Shellsharks Podcast"></i></a>
               <li><a href="mailto:mike@shellsharks.com" ><i class="fas fa-envelope grow" title="Email"></i></a>
               <li><a href="https://www.linkedin.com/in/mikesass" target="_blank"><i class="fa fa-linkedin grow" title="Linkedin"></i></a>
               <li><a href="https://discord.gg/3rkHgtcYbb" target="_blank"><i class="fab fa-discord grow" title="Shellsharks Discord"></i></a>
               <li><a href="https://github.com/shellsharks" target="_blank"><i class="fa fa-github grow" title="Github"></i></a>
            </ul>
            <ul>
               <li><a href="/about" ><i class="fas fa-address-card grow" title="About"></i></a>
               <li><a href="/notebook" ><i class="fas fa-sticky-note grow" title="Notes"></i></a>
               <li><a href="/more" ><i class="fas fa-drafting-compass grow" title="Projects"></i></a>
               <li><a href="/statboard" ><i class="fas fa-tachometer-alt grow" title="Statboard"></i></a>
               <li>
                  <a href="/captains-log">
                     <i class="fas fa-journal-whills grow" title="Captain's Log"></i>
                     <div class="icon-color" style="position:absolute; margin-left: -6px; margin-top: -6px; font-size:12px;">Jul 31</div>
                  </a>
               <li>
                  <i id="searchbtn" class="fas fa-search icon-color grow" onclick="showsearch('clicked')" style="font-size: 30px;" title="Search"></i>
                  <div class="icon-color" style="position:absolute; font-size:12px; margin-top:-6px;">57 Posts</div>
               <li><i id="themetoggle" class="fas fa-adjust" onclick="switchTheme('clicked')" title="Toggle Theme"></i>
            </ul>
         </div>
         <!-- --> <!-- -->
         <div class="search" id="js-search" style="display: none">
            <input autofocus="autofocus" type="text" placeholder="Search" class="search__input form-control" id="js-search__input">
            <ul class="search__results" id="js-search__results"></ul>
         </div>
         <div id="blog" style="text-align:center;">
            <ul class="posts" style="list-style-type:none;display:inline-block;text-align:left;position:relative;padding-right:30px;">
               <li><span style='font-family:andale mono, monospace;font-size:0.95em;'>08/11/23</span>&emsp;<a href="/notes/2023/08/11/ivory-vs-feditext#title">Ivory vs Feditext</a>
               <li style=""><span style='font-family:andale mono, monospace;font-size:0.95em;'>07/17/23</span>&emsp;<a href="/indiemark-score#title">Shellsharks IndieMark Score</a>
               <li style=""><span style='font-family:andale mono, monospace;font-size:0.95em;'>07/16/23</span>&emsp;<a href="/indieweb#title">IndieWeb Assimilation</a>
               <li style=""><span style='font-family:andale mono, monospace;font-size:0.95em;'>07/15/23</span>&emsp;<a href="/whats-on-my-iphone#title">What's on my iPhone</a>
               <li style=""><span style='font-family:andale mono, monospace;font-size:0.95em;'>07/14/23</span>&emsp;<a href="/crown-jewels-analysis#title">Crown Jewels Analysis</a>
               <li style=""><span style='font-family:andale mono, monospace;font-size:0.95em;'>07/10/23</span>&emsp;<a href="/shellsharkweek-2023#title">Let's go hunt! doo-doo doo</a>
               <li style=""><span style='font-family:andale mono, monospace;font-size:0.95em;'>06/28/23</span>&emsp;<a href="/threadiversal-travel#title">Threadiversal Travel</a>
               <li style=""><span style='font-family:andale mono, monospace;font-size:0.95em;'>12/28/22</span>&emsp;<a href="/sans-mgt512-gslc-review#title">SANS MGT512 & GIAC GSLC Review</a>
               <li style=""><span style='font-family:andale mono, monospace;font-size:0.95em;'>12/24/22</span>&emsp;<a href="/santa-ttps#title">Threat Profile: Santa Claus</a>
               <li style=""><span style='font-family:andale mono, monospace;font-size:0.95em;'>11/17/22</span>&emsp;<a href="/mastodon#title">Stars, Boosts & Toots</a>
               <li style=""><span style='font-family:andale mono, monospace;font-size:0.95em;'>08/25/22</span>&emsp;<a href="/dynamize-jekyll#title">Dynamization of Jekyll</a>
               <li style=""><span style='font-family:andale mono, monospace;font-size:0.95em;'>08/25/22</span>&emsp;<a href="/cyber-clout#title">Boosting Your Cyber Clout</a>
               <li style=""><span style='font-family:andale mono, monospace;font-size:0.95em;'>07/30/22</span>&emsp;<a href="/threat-modeling#title">The Enchiridion of Impetus Exemplar</a>
               <li style=""><span style='font-family:andale mono, monospace;font-size:0.95em;'>07/27/22</span>&emsp;<a href="/inbox-zero-part-2#title">The Science of Inbox Zero</a>
               <li style=""><span style='font-family:andale mono, monospace;font-size:0.95em;'>07/25/22</span>&emsp;<a href="/shellsharks-logo#title">The Shellsharks Logo Chronicles</a>
               <li style=""><span style='font-family:andale mono, monospace;font-size:0.95em;'>07/25/22</span>&emsp;<a href="/shellsharkweek-2022#title">We're going to need a bigger blog</a>
               <li style=""><span style='font-family:andale mono, monospace;font-size:0.95em;'>06/21/22</span>&emsp;<a href="/cybercomplexity#title">Cybercomplexity</a>
               <li style=""><span style='font-family:andale mono, monospace;font-size:0.95em;'>12/29/21</span>&emsp;<a href="/getting-into-information-security-playbook#title">10-Step Getting-Into-Infosec Playbook</a>
               <li style=""><span style='font-family:andale mono, monospace;font-size:0.95em;'>09/28/21</span>&emsp;<a href="/sans-sec450-review#title">SANS SEC450 Review</a>
               <li style=""><span style='font-family:andale mono, monospace;font-size:0.95em;'>08/16/21</span>&emsp;<a href="/cybersecurity-role-map#title">Cybersecurity Role Map</a>
               <li style=""><span style='font-family:andale mono, monospace;font-size:0.95em;'>08/11/21</span>&emsp;<a href="/sans-sec460-review#title">SANS SEC460 & GIAC GEVA Review</a>
            </ul>
            <ul class="pagination pagination-sm" style="display: flex; justify-content:center;">
               <li class="disabled"><span aria-hidden="true">&laquo;</span>
               <li><a href="/">&nbsp;First</a>&nbsp;&nbsp;
               <li class="active"><a>1<span class="sr-only">(current)</span></a> &nbsp;&nbsp;
               <li><a href="/page/2/#blog">2</a> &nbsp;&nbsp;
               <li><a href="/page/3/#blog">3</a> &nbsp;&nbsp;
               <li><a href="/page/3/#blog">Last&nbsp;</a>
               <li><a href="/page/2/#blog">&raquo;</a>
            </ul>
         </div>
      </div>
      <script> function showsearch(input) { var sbox = document.getElementById("js-search"); if (input == 'clicked' && sbox.style.display === "none") { sbox.style.display = "block"; document.getElementById("blog").style.display = "none"; document.getElementById("js-search__input").focus(); document.getElementById("searchbtn").class = "primarycolor"; } else if (input == 'clicked' && sbox.style.display === "block") { document.getElementById("js-search__input").blur(); sbox.style.display = "none"; document.getElementById("blog").style.display = "block"; document.getElementById("searchbtn").style = "font-size: 30px"; document.getElementById("searchbtn").class = "icon-color"; } } var aTags = document.getElementsByTagName("a"); var searchText = "Captain's Log"; var found; for (var i = 0; i < aTags.length; i++) { if (aTags[i].textContent == searchText) { found = aTags[i]; found.innerHTML = "Captain's Log (Latest Entry: July 31, 2023)"; break; } const toggleSwitch = document.querySelector('#themetoggle'); const currentTheme = localStorage.getItem('theme') ? localStorage.getItem('theme') : null; if (currentTheme) { document.documentElement.setAttribute('data-theme', currentTheme); if (document.documentElement.getAttribute('data-theme') == 'dark') { document.getElementById('themetoggle').setAttribute("class", "fas fa-sun"); } else if (document.documentElement.getAttribute('data-theme') == 'light') { document.getElementById('themetoggle').setAttribute("class", "fas fa-moon"); } else if (document.documentElement.getAttribute('data-theme') == 'classic') { document.getElementById('themetoggle').setAttribute("class", "far fa-moon"); } } else { document.getElementById('themetoggle').setAttribute("class", "far fa-moon"); } function switchTheme(e) { if (document.documentElement.getAttribute('data-theme') == 'dark') { document.documentElement.setAttribute('data-theme', 'light'); localStorage.setItem('theme', 'light'); document.getElementById('themetoggle').setAttribute("class", "fas fa-moon"); } else if (document.documentElement.getAttribute('data-theme') == 'light') { document.documentElement.setAttribute('data-theme', 'classic'); localStorage.setItem('theme', 'classic'); document.getElementById('themetoggle').setAttribute("class", "far fa-moon"); } else if (document.documentElement.getAttribute('data-theme') == 'classic') { document.documentElement.setAttribute('data-theme', 'dark'); localStorage.setItem('theme', 'dark'); document.getElementById('themetoggle').setAttribute("class", "fas fa-sun"); } else { document.documentElement.setAttribute('data-theme', 'dark'); localStorage.setItem('theme', 'dark'); document.getElementById('themetoggle').setAttribute("class", "fas fa-sun"); } } toggleSwitch.addEventListener('change', switchTheme, false); } </script> <script src="/assets/js/super-search.js"></script> <script> console.log("sharkin' them shells..."); </script>
   </div>
   <br/> 
   <center><a href="/disclaimer"><img id="disclaimer" src="/assets/img/disclaimer.png" alt="License & Disclaimer" style="width:150px;"></a> </center>
   <br/> 
   <noscript>
      <div class="panel" align="center" style="font-weight:bold;">
         <h1>JavaScript required for some functionality of the site.</h1>
      </div>
   </noscript>
