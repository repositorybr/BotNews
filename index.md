
<html lang="en">
<head>
<title>DataCenter Status | OwlGram</title>
<meta name='viewport' content='width=device-width, user-scalable=0'>
<link href="css/app.css?v=6" rel="preload" as="style">
<link rel="stylesheet" href="css/app.css?v=6">
<link href="css/button.css" rel="preload" as="style">
<link rel="stylesheet" href="css/button.css">
<link rel="icon" type="image/x-icon" href="https://owlgram.org/favicon.ico">
<link rel="dns-prefetch" href="https://fonts.gstatic.com">
<link rel="preconnect" href="https://fonts.gstatic.com">
<link rel="preload" href="https://fonts.googleapis.com/css?family=Roboto:100,300,400,500,700%7CGoogle+Sans:400,500%7CProduct+Sans:400&amp;display=swap&amp;lang=en" as="style" crossorigin>
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Roboto:100,300,400,500,700%7CGoogle+Sans:400,500%7CProduct+Sans:400&amp;display=swap&amp;lang=en" crossorigin>
<script src="https://cdnjs.cloudflare.com/ajax/libs/bodymovin/5.8.1/lottie.min.js" type="4c4d36a7029cd859b63de6ec-text/javascript"></script>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.0/jquery.min.js" type="4c4d36a7029cd859b63de6ec-text/javascript"></script>
<script src="js/button.js" type="4c4d36a7029cd859b63de6ec-text/javascript"></script>
<script src="js/blob_drawable.js" type="4c4d36a7029cd859b63de6ec-text/javascript"></script>
<script src="js/dc_blob_animation.js" type="4c4d36a7029cd859b63de6ec-text/javascript"></script>
<script src="js/app.js?v=2" type="4c4d36a7029cd859b63de6ec-text/javascript"></script>
</head>
<body oncontextmenu="if (!window.__cfRLUnblockHandlers) return false; return false;" data-cf-modified-4c4d36a7029cd859b63de6ec-="">
<div class="top_menu">
<a href="/">
<img class="logo_top" src="//owlgram.org/img/owlgram.svg" alt="logo" />
</a>
<div class="right_text_container">
<div>
<div>
LAST UPDATE
</div>
<div id="loading_date" class="placeholder"></div>
</div>
</div>
</div>
<div class="top_bar">
<div id="header_loader">
</div>
<div>
Here you can see the various status of <a target="_blank" href="https://core.telegram.org/api/datacenter">Media Datacenter</a> in realtime from the section below
</div>
<div class="material_button" onclick="if (!window.__cfRLUnblockHandlers) return false; refreshPage()" data-cf-modified-4c4d36a7029cd859b63de6ec-="">
<div class="c-button">
<div>
<img src="img/restart.svg" alt="icon_restart">
<div>Refresh Page</div>
</div>
<div class="c-ripple js-ripple">
<span class="c-ripple__circle"></span>
</div>
</div>
</div>
</div>
<div class="top_bar">
<div class="header_text">
Datacenter Status
</div>
<div class="item_ripple c-button_white loading" id="dc1_tab">
 <div>
<div>
<blob-animation style="color: #329AFE"></blob-animation>
<img src="img/ic_pluto.svg" alt="datacenter_icon">
</div>
<div>
<div>
MIA, Miami FL, USA - DC1 </div>
<div>
149.154.175.50 </div>
<div id="dc1_status"></div>
</div>
<div>
<div class="placeholder"></div>
<div class="placeholder"></div>
<div class="placeholder"></div>
</div>
</div>
<div class="divider"></div>
<div class="c-ripple_white js-ripple">
<span class="c-ripple_white__circle"></span>
</div>
</div>
<div class="item_ripple c-button_white loading" id="dc2_tab">
<div>
<div>
<blob-animation style="color: #8B31FD"></blob-animation>
<img src="img/ic_venus.svg" alt="datacenter_icon">
</div>
<div>
<div>
AMS, Amsterdam, NL - DC2 </div>
<div>
149.154.167.50 </div>
<div id="dc2_status"></div>
</div>
<div>
<div class="placeholder"></div>
<div class="placeholder"></div>
<div class="placeholder"></div>
</div>
</div>
<div class="divider"></div>
<div class="c-ripple_white js-ripple">
<span class="c-ripple_white__circle"></span>
</div>
</div>
<div class="item_ripple c-button_white loading" id="dc3_tab">
<div>
<div>
<blob-animation style="color: #DA5653"></blob-animation>
<img src="img/ic_aurora.svg" alt="datacenter_icon">
</div>
<div>
<div>
MIA, Miami FL, USA - DC3 </div>
<div>
149.154.175.100 </div>
<div id="dc3_status"></div>
</div>
<div>
<div class="placeholder"></div>
<div class="placeholder"></div>
<div class="placeholder"></div>
</div>
</div>
<div class="divider"></div>
<div class="c-ripple_white js-ripple">
<span class="c-ripple_white__circle"></span>
</div>
</div>
<div class="item_ripple c-button_white loading" id="dc4_tab">
<div>
<div>
<blob-animation style="color: #F7B139"></blob-animation>
<img src="img/ic_vesta.svg" alt="datacenter_icon">
</div>
<div>
<div>
AMS, Amsterdam, NL - DC4 </div>
<div>
149.154.167.91 </div>
<div id="dc4_status"></div>
</div>
<div>
<div class="placeholder"></div>
<div class="placeholder"></div>
<div class="placeholder"></div>
</div>
</div>
<div class="divider"></div>
<div class="c-ripple_white js-ripple">
<span class="c-ripple_white__circle"></span>
</div>
</div>
<div class="item_ripple c-button_white loading" id="dc5_tab">
<div>
<div>
<blob-animation style="color: #4BD199"></blob-animation>
<img src="img/ic_flora.svg" alt="datacenter_icon">
</div>
<div>
<div>
SIN, Singapore, SG - DC5 </div>
<div>
91.108.56.100 </div>
<div id="dc5_status"></div>
</div>
<div>
<div class="placeholder"></div>
<div class="placeholder"></div>
<div class="placeholder"></div>
</div>
</div>
<div class="c-ripple_white js-ripple">
<span class="c-ripple_white__circle"></span>
</div>
</div>
</div>
<script src="/cdn-cgi/scripts/7d0fa10a/cloudflare-static/rocket-loader.min.js" data-cf-settings="4c4d36a7029cd859b63de6ec-|49" defer=""></script></body>
</html>
