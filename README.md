/* CSS Reset */
html,body,div,span,applet,object,iframe,h1,h2,h3,h4,h5,h6,p,blockquote,pre,a,abbr,acronym,address,big,cite,code,del,dfn,em,img,ins,kbd,q,s,samp,small,strike,strong,sub,sup,tt,var,b,u,i,center,dl,dt,dd,ol,ul,li,fieldset,form,label,legend,table,caption,tbody,tfoot,thead,tr,th,td,article,aside,canvas,details,embed,figure,figcaption,footer,header,hgroup,menu,nav,output,ruby,section,summary,time,mark,audio,video{margin:0;padding:0;border:0;font-size:100%;font:inherit;vertical-align:baseline;}
/* HTML5 */
article,aside,details,figcaption,figure,footer,header,hgroup,menu,nav,section{display:block;}body{line-height:1;display:block;}*{margin:0;padding:0;}html{display:block;}ol,ul{list-style:none;}blockquote,q{quotes:none;}blockquote:before,blockquote:after,q:before,q:after{background:transparent;}table{border-collapse:collapse;border-spacing:0;}*,*:before, *:after {-webkit-box-sizing:border-box;-moz-box-sizing:border-box;box-sizing:border-box;}ins{background:#fff;}
/* Body Layout */
body#layout ul,#layout ul {display:none;}
body#layout #outer-wrapper, body#layout .post-inner, body#layout .sidebar, body#layout .sidebartop {padding:0;}
body#layout #wrapper, body#layout .post-inner, body#layout .sidebar-inner {padding:0;}
body#layout .header-wrapper {margin-top:0;}
body#layout #header {min-height:0px;width:100%;}
body#layout #headerdua {width:30%;float:right;}
body#layout .sosial-atas li{display:none}
#layout,#layout .widget-content,#layout .add_widget {border:none;}
body#layout .add_widget {border:1px solid #ddd;}
#layout .add_widget a {color:#111;}
#layout #header{min-height:0px;width:100%;margin:10px 0 0 0;}
#layout #main-wrapper{width:70%;float:right}
#layout #sidebar-wrapper{width:30%;right:0;padding:0;float:left}
#layout .draggable-widget .widget-wrap2 {background:#c1cfd9;}
#layout #banner,#layout #banner2 {background-color:#444;padding:20px 0!important;margin-bottom:20px;}
#layout #banner .widget,#layout #banner2 .widget{width:80%;margin:5px auto!important;overflow:hidden;float:none}
#layout #banner .add_widget,#layout #banner2 .add_widget{width:80%;margin:5px auto!important;overflow:hidden;float:none}
#footer-xwidget .footer-widget {width:31.7%;float:right;margin-right:10px;}
#footer-wrapper {overflow:hidden;margin:0 auto 20px auto;padding:20px 0 0;}
#layout #footer-wrapper #column1,#layout #footer-wrapper #column2{margin:0}
/* Layout */
body {background:#f1f1f1;font-family:'Changa';font-size:14px;font-weight:400;text-align:right;color:#000;margin:0;padding:0;}
.navbar,.post-feeds,.feed-links{display:none;}.section,.widget{margin:0;padding:0;}strong,b{font-weight:bold;padding:0;}cite,em,i{font-style:italic;}a:link,a:visited {color:#e74c3c;text-decoration:none;transition:all .3s}a:hover,a:hover:visited {color:#000}a img{border:none;border-width:0;outline:none;}img{max-width:100%;vertical-align:middle;border:0;}abbr,acronym{border-bottom:1px dotted;cursor:help;}sup,sub{vertical-align:baseline;position:relative;top:-.4em;font-size:86%;}sub{top:.4em;}small{font-size:86%;}kbd{display:inline-block;font-size:90%;color:#e74c3c;}mark{background-color:#ffce00;color:#182025;}p,blockquote,pre,table,figure,hr,form,ol,ul,dl{margin:1.5em 0;}hr{height:1px;border:none;background-color:#999;}code,pre,samp{font-family:monospace,monospace;}kbd{font-family:Changa;}
pre{white-space:pre;word-wrap:normal;overflow:auto;font-size:13px;margin:0;}*:focus {outline:0!important;}h1,h2,h3,h4,h5,h6{font-weight:700;line-height:normal;}h1{font-size:200%}h2{font-size:180%}h3{font-size:160%}h4{font-size:140%}h5{font-size:120%}h6{font-size:100%}
.post-body blockquote{position:relative;margin:0 auto;padding:24px 45px 24px 20px;line-height:24px;text-shadow:0 1px 1px white;background-color:#f2f6c1;border:1px solid rgba(0,0,0,0.05);border-radius:4px;}
.post-body blockquote:before,.post-body blockquote:after{content:'';position:absolute;top:0;bottom:0}
.post-body blockquote:before{right:20px;border:2px solid rgba(239,207,173,0.7)}
.post-body h1{font-size:200%}.post-body h2{font-size:180%}.post-body h3{font-size:160%}.post-body h4{font-size:140%}.post-body h5{font-size:120%}.post-body h6{font-size:100%}
.post-body h1 b,.post-body h2 b,.post-body h3 b,.post-body h4 b,.post-body h5 b,.post-body h6 b{font-weight:700;}
input,button,select,textarea{font-size:100%;line-height:normal;vertical-align:baseline;font-family:inherit;}
textarea{display:block;box-sizing:border-box;}
input.placeholder_text,textarea.placeholder_text{color:#888}
input::-webkit-input-placeholder,textarea::-webkit-input-placeholder,input:-moz-placeholder,textarea:-moz-placeholder,input.placeholder_text,textarea.placeholder_text{color:#444}[placeholder]:focus::-webkit-input-placeholder{transition:opacity .5s .5s ease;opacity:0}
.post ul li span{position:relative;display:block;padding:0;margin:.5em 2em .5em 0;text-decoration:none;}
ol {counter-reset:li;list-style:none;padding:0;margin:0;}
ol ol {margin: 0 2em 0 0;}
.post ol li{position:relative;display:block;padding:0;margin:.5em 2em .5em 0;background:#fff;text-decoration:none;}
.post ol li:before {content:counter(li);counter-increment:li;position:absolute;right:-2.5em;height:2em;width:2em;text-align:center;}
.post-body ul {position:relative;display:block;padding:0;margin:.5em 1.5em .5em 0;text-decoration:none;}
/* Post Table */
.post-body table {width:100%;}
.post-body table td,.post-body table caption{background:#fff;border:0;padding:10px;text-align:right;vertical-align:top}
.post-body table th{background:#ddd;border:0;padding:10px;text-align:right;vertical-align:top}
.post-body table.tr-caption-container {border:0;margin:0;}
.post-body th{font-weight:700;}
.post-body table caption{border:none;font-style:italic;}
.post-body td, .post-body th{vertical-align:top;text-align:right;font-size:13px;padding:3px 5px;border:1px solid #97b28e;}
.post-body th{}
.post-body th:hover{background:#d2d2d2;}
.post-body table tr:nth-child(even) > td {background-color:#f9f9f9;}
.post-body table tr:nth-child(even) > td:hover {background-color:#fbfbfb;}
.post-body td a{color:#444;}
.post-body td a:hover{color:#cf4d35;}
.post-body table.tr-caption-container td{border:0;padding:0;background:#fff;line-height:17px;overflow:hidden;text-align:center;text-overflow:ellipsis;white-space:nowrap;font-weight:700;color:#000;}
.post-body table.tr-caption-container, .post-body table.tr-caption-container img, .post-body img {max-width:100%;height:auto;}
.post-body li {list-style-type:square;}
.post-body td.tr-caption{background:#222!important;color:#fff!important;font-size:85%;padding:10px!important}
.sr {visibility:hidden;width:0;height:0;}
.clear{clear:both}
html {-webkit-font-smoothing:antialiased;}
::selection {background:#eafdb7;text-shadow:none;}
.post-body ::selection {background:#eafdb7;color:#000;}

/* this boxs by : http://www.7lolblogger.com  */
holoblogger {
display: block;
padding: 3px;
color: #FFF;
text-align: right;
direction: rtl;
font: 12px 'DroidKufi-Regular',tahoma,arial;
border-radius: 4px;
max-width: 800px;
margin: 5px auto;
}
@font-face {
font-family: 'DroidKufi-Regular';
src: url('http://dl.dropbox.com/u/22531314/webfont/fonts/DroidKufi-Regular.eot');
src: url('http://dl.dropbox.com/u/22531314/webfont/fonts/DroidKufi-Regular.eot?') format('embedded-opentype'),
url('http://dl.dropbox.com/u/22531314/webfont/fonts/DroidKufi-Regular.woff') format('woff'),
url('http://dl.dropbox.com/u/22531314/webfont/fonts/DroidKufi-Regular.ttf') format('truetype');}
holoblogger#Blue {
background: #64AEDF url(https://jetara.googlecode.com/svn/trunk/header-6.png) no-repeat;
border: 1px solid #4A94C5;
  background-size: cover;
}
holoblogger#red {
background: #C93E3E url(https://jetara.googlecode.com/svn/trunk/header-6.png) no-repeat;
border: 1px solid #AA2828;
  background-size: cover;
}
holoblogger#Green {
background: #3EC99D url(https://jetara.googlecode.com/svn/trunk/header-6.png) no-repeat;
border: 1px solid #2BA37D;
  background-size: cover;
}
holoblogger#Gray {
background: #AFAFAF url(https://jetara.googlecode.com/svn/trunk/header-6.png) no-repeat;
border: 1px solid #999;
  background-size: cover;
}
holoblogger#Black {
background: #222 url(https://jetara.googlecode.com/svn/trunk/header-6.png) no-repeat;
border: 1px solid #111;
  background-size: cover;
}
holoblogger#Purple {
background: #9351DB url(https://jetara.googlecode.com/svn/trunk/header-6.png) no-repeat;
border: 1px solid #8B24C5;
  background-size: cover;
}
holoblogger#Orange {
background: #E98745 url(https://jetara.googlecode.com/svn/trunk/header-6.png) no-repeat;
border: 1px solid #C06A2F;
  background-size: cover;
}
