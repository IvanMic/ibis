body {  background-image: url('../images/bg.jpg') }
.strong {  font-weight: 700 }
.widefix {  width: 237px }
a {  color: #1c95b8 }
.hide-title .pane-title {  display: none }
.item-list ul {  margin: 0 }
.item-list ul li {  margin: 0 }
/* removing dotted line on buttons and clickable input elements for Firefox */
input[type="submit"]::-moz-focus-inner,
input[type="button"]::-moz-focus-inner,
button::-moz-focus-inner {  border : 0 }
/* Remove outline on buttons and clickable input elements for WebKit Browsers & IE8 */
input[type="submit"]:focus,
input[type="button"]:focus,
input[type="text"]:focus,
button,
textarea,
a {  outline : none }
.ajax-progress-throbber {
  width: 100px;
  font-size: 11px;
  line-height: 22px;
}
.system-block .tabs {  padding: 10px 0 0 }
/*---------------------------------------------------------[ Maintenance Page */
.maintenance-page #page {  padding: 200px 0 0 }
.under-maintenance {
  background-color: #F45017;
  font-family: 'Droid Serif', Arial, sans-serif;
  font-size: 30px;
  padding: 20px;
}
/*---------------------------------- fixing bug with drop-down menu (all site)*/
.page-header {
  z-index: 500;
  position: relative;
}
/*-----------------------------------------------------------------------------[ not logged in USER FORM]*/
.not-logged-in #user-login .form-text {
  border: 1px solid #B6B6B6;
  height: 26px;
  width: 200px;
  padding: 0px 10px;
  margin: 5px 0px;
  line-height: 26px;
}
#user-login,
.page-newsletter .content-area form {
  background: #f4f4f4;
  padding: 20px;
  margin: 20px;
  border: 1px solid #d9d9d9;
}
#user-login .form-required {  color: #f00 }
#user-login .form-item-name,
#user-login .form-item-pass {  margin-bottom: 20px }
#user-login {
  clear: left;
  float: left;
  overflow: hidden;
}
#user-login .form-item label,
.page-newsletter .content-area form label {
  display: block;
  font-weight: bold;
  font-size: 14px;
}
#user-login  .description,
.page-newsletter .content-area form .description {  color: #8d8d8d }
#user-login .form-submit {  border: 0px }
#user-login  input.form-submit,
.page-newsletter .content-area form input.form-submit {
  padding: 9px 35px 10px 15px;
  background: #1C95B8 url("../images/form-btn-sprite.png") no-repeat right 8px;
  font: bold 14px "Droid Sans", Arial, sans-serif;
  color: white;
  border: none;
  display: inline-block;
  cursor: pointer;
  text-align: left;
}
#user-login input[type="submit"]:hover,
.page-newsletter .content-area form input.form-submit:hover {  background: #167692 url("../images/form-btn-sprite.png") no-repeat right -42px }
/* ===========[ HEADER BLOCKS ]============================================= */
/* logo */
.logo a {
  margin: 13px 0 15px 0;
  display: block;
}
/* header block domain */
.header-block-domain {
  margin-top: 13px;
}
.header-block-domain label {
  float: left;
  font-weight: normal;
  font-size: 12px;
  padding-top: 5px;
}
.header-block-domain .domain-submit {
  width: 25px;
  height: 30px;
  float: left;
  background: url("../images/ui-sprite.png") 4px 3px no-repeat;
}
.header-block-domain .content,
.header-block-search .content {  float: right }
.header-block-domain .domain-submit:hover { }
.header-block-search {  padding: 10px 0 0 0 }
.header-block-search h2,
.header-block-search label {  display: none }
.header-block-search .form-item {
  float: left;
  display: block;
  margin: 0px;
}
.header-block-search .form-text {
  border: 1px solid #eee;
  color: #2c2c2a;
  font-size: 12px;
  margin: 0 0 0 4px;
  padding: 3px 9px;
  width: 248px;
}
.header-block-search .form-submit {
  background: url('../images/ui-sprite.png') no-repeat 4px -29px;
  border: none;
  cursor: pointer;
  height: 23px;
  text-indent: -9000px;
  text-transform: capitalize;
  width: 23px;
  overflow: hidden;
}
.header-block-search .form-submit:hover {  background-position: -194px -30px }
/* submenu */
/*.page-header .roket {  background: url("../images/roket.png") no-repeat scroll right bottom transparent }*/
.page-header .submenu-links {
  padding: 15px 20px 0 0;
  float: right;
}
.page-header .submenu-links h2 {  display: none }
.page-header .submenu-links li {
  float: left;
  margin: 0 3px 0 0;
  position: relative;
}
.page-header .submenu-links li a {
  color: #2c2c2a;
  display: block;
  font-size: 12px;
  padding: 2px 4px;
  text-decoration: none;
}

/* main menu */
.header-links {
  background: url('../images/bg-top-menu.png') repeat-x top left;
  position: relative;
}
.top-main-menu {  float: left }
.header-links .site-menu li {
  float: left;
  height: 55px;
}
.sneaky-panel .pane-content ul {
  list-style-image:url('../images/arrow-blue-small.png');
  list-style-position: inside;
}
.sneaky-panel .pane-content li {
  float: none;
  height: auto;
}
.sneaky-panel .pane-content li a {
  font: 14px/25px 'Droid Sans', Arial, sans-serif;
  color: #161616;
}
.sneaky-panel .pane-content li a:hover {
  color: #1c95b8;
}
.header-links .main-menu-link:hover {  color: #1c95b8 }
.header-links .sneaky-item .main-menu-link {  z-index: 501 }
.header-links .sneaky-hover .main-menu-link {
  background: #efefe7;
  border: 1px solid #C8D2CB;
  border-bottom: none;
  padding-bottom: 16px;
  z-index: 501;
}
.header-links .main-menu-link {
  border: 1px solid transparent;
  color: #393937;
  display: block;
  font-size: 18px;
  padding: 16px 15px 15px;
  text-decoration: none;
  position: relative;
}
.header-links li.active .main-menu-link,
.header-links .top-main-menu li.last.active .main-menu-link {
  background-color: #1c95b8;
  border: 1px solid #8dcadb;
  color: #fff;
}
.header-links li.active .main-menu-link:hover {  color: #fff }
.header-links li.active .active-arrow,
.header-links li .main-menu-link:hover .active-arrow {
  background-image: url("../images/ui-sprite.png");
  bottom: -1px;
  display: block;
  height: 7px;
  left: 50%;
  margin: 0 0 0 -8px;
  position: absolute;
  width: 15px;
}
.header-links li .main-menu-link:hover .active-arrow {  background-position: -500px -133px }
.header-links .sneaky-item .main-menu-link:hover .active-arrow {
  background-position: -534px -133px;
  top: -1px;
}
.header-links ul li.active .active-arrow {  background-position: -517px -133px }
.header-links .menu-second {  float: right }
.header-links .block-menu li {  padding: 15px }
.header-links .top-main-menu .last .main-menu-link {
  background-color: #F55018;
  border: 1px solid #CA4B00;
  padding-right: 40px;
  color: #fff;
}
.header-links .top-main-menu .last .main-menu-link:hover {  color: #fff }
.header-links .top-main-menu li.last.active .go-arrow {  background-position: -955px -471px }
.header-links .top-main-menu .last .go-arrow {
  background: url("../images/ui-sprite.png") no-repeat scroll -785px -471px transparent;
  display: block;
  height: 15px;
  position: absolute;
  right: 17px;
  top: 20px;
  width: 15px;
}
.header-links .sneaky-hover .sneaky-panel {  display: block }
/* breadcrumb */
.breadcrumb {  margin: 0 0 20px 0 }
.breadcrumb li {  float: left }
.breadcrumb .item-list li {  margin: 0 }
html .breadcrumb .item-list .first {  margin: 0 7px 0 0 }
.breadcrumb .first {  border-right: 1px solid #b5b5b4 }
.breadcrumb .first a {
  width: 13px;
  height: 13px;
  display: block;
  text-indent: -999em;
  background: url("../images/ui-sprite.png") no-repeat scroll -787px -88px transparent;
  overflow: hidden;
  margin-left: 0;
}
.breadcrumb .first a:hover {  background-position: -787px -111px }
.breadcrumb li a,
.breadcrumb li {
  margin: 0 4px 0 0;
  text-decoration: none;
  font-size: 11px;
  color: #9c9c9b;
}
.breadcrumb li a:hover {  color: #b2b2b1 }
.breadcrumb .last {  border: none }
.breadcrumb .last a,
.breadcrumb li a.active {  font-weight: bold }
.breadcrumb li span {
  margin: 0 1px 0 0;
}
/* ===========[ FOOTER ]================================================= */
.grid_12.content-footer {  margin-top: 10px }
.page-footer {
  color: #2c2c2a;
  margin-top: 20px;
}
.page-blog .page-footer {  margin-top: 13px }
.page-footer .footer-contact,
.page-footer .site-menu a {  letter-spacing: -0.25px }
.page-footer .menu-wrap {
  /*background: url('../images/bg-footer-menu.png') repeat-x 0 0;*/
  padding: 10px 0;
  border-top: 1px dotted #8f8f8f;
}
.page-footer .menu-wrap .footer-contact a {  text-decoration: none }
.page-footer .menu-wrap .footer-contact a:hover {  text-decoration: underline }
.page-footer .logo-block,
.page-footer .footer-links {
  float: left;
}
.page-footer .footer-contact {
  float: right;
  width: 20%;
}
.page-footer .logo-block {
  width: 20%;
}
.page-footer .footer-links {
  width: 60%;
  text-align: center;
 }
.page-footer .msecond,
.page-footer .menu-second {  padding: 8px 0 0 0 }
.page-footer .site-menu.inline {  display:inline }
.page-footer .site-menu li {  display: inline }
.page-footer .site-menu a {
  color: #2c2c2a;
  text-decoration: none;
  margin: 0 10px 0 0;
}
.page-footer .site-menu a:hover {  color: #72716d }
.footer-logo {
  height: 70px;
  background: url('../images/ui-sprite.png') no-repeat 0 -843px;
  text-align: center;
}
/* .footer-logo span {  font: bold italic 15px/70px "Droid Serif", Arial, sans-serif } */
.footer-logo span {  font: bold italic 15px/70px "Droid Sans", Arial, sans-serif }
/* ===========[ WYSIWYG ]================================================= */
em {  font-style: italic }
strong {  font-weight: bold }
em strong,
strong em {
  font-style: italic;
  font-weight: bold;
}
q::before,
q::after {  content: '"' }
address,
cite,
var {  font-style: italic }
.quiz-question-body,
.section-newsletter .content-area,
.pane-node-body {
  font: normal 14px/20px Arial, sans-serif;
  color: #161616;
}
.gmap_marker ul,
.gmap_marker ol {  padding-left: 15px }
.pane-node-body table,
.section-newsletter .content-area table,
.gmap_marker table {  border-color: black }
.pane-node-body table tbody,
.section-newsletter .content-area table tbody,
.gmap_marker table tbody {  vertical-align: inherit }
.pane-node-body table ul,
.section-newsletter .content-area table ul,
.node-webform table ul,
.gmap_marker table ul {  padding: 0 20px }
.pane-node-body .img-wrapper kbd,
.section-newsletter .img-wrapper .content-area kbd,
.node-webform .img-wrapper kbd,
.gmap_marker .img-wrapper kbd {
  display: block;
  width: 100%;
}
.pane-node-body table ul li,
.section-newsletter .content-area table ul li,
.node-webform table ul li,
.gmap_marker table ul li {  list-style: disc inside none }
#quiz-page .grid_9 {
  width: 680px;
  margin: 0;
  padding-right: 30px;
  background: url('../images/bg-quiz.png') repeat-y 700px 0;
}
.quiz-question-body a:visited,
.section-newsletter .content-area a:visited,
.pane-node-body a:visited {  color: #5f5f5f }
.section-newsletter .content-area ul li,
.quiz-question-body ul li,
.pane-node-body ul li,
.pane-node-body ul li,
.node-webform ul li,
.gmap_marker ul li {  list-style: disc inside none }
.pane-node-body ul li {  list-style: disc outside none }
.section-newsletter .content-area ol li,
.quiz-question-body ol li,
.pane-node-body ol li,
.node-webform ol li,
.gmap_marker ol li {  list-style: decimal inside none }
.pane-node-body ol,
.pane-node-body ul {  margin: 0 0 0 20px !important }
.pane-node-body ul li,
.pane-node-body ol li {  margin: 0 0 5px 0 }
.section-newsletter .content-area ul,
.section-newsletter .content-area ol,
.quiz-question-body ul,
.pane-node-body ul,
.quiz-question-body ol,
.pane-node-body ol,
.quiz-question-body p,
.section-newsletter .content-area p,
.pane-node-body p {
  margin: 0 0 20px 0;
  word-wrap: break-word;
}
.quiz-question-body table p,
.section-newsletter table .content-area p,
.pane-node-body table p {  margin: 0px }
.section-newsletter .content-area h2,
.pane-node-body .field-items h2,
.node-webform .field-items h2,
.content-area h2,
.pane-node-body .field-items h2 span,
.answers .answer-text h2 {
  font-weight: bold;
  font-size: 18px;
}
big * {  font-size: 1.2em!important }
small * {  font-size: 0.8em!important }
.answers .answer-text h3,
.content-area h3,
.pane-node-body .field-items h3,
.section-newsletter .content-area h3,
.node-webform .field-items h3,
.pane-node-body .field-items h3 span {
  font-size: 16px;
  font-weight: bold;
}
.answers .answer-text h4,
.content-area h4,
.section-newsletter .content-area h4,
.pane-node-body .field-items h4,
.node-webform .field-items h4,
.pane-node-body .field-items h4 span {
  font-size: 14px;
  font-weight: bold;
}
.answers .answer-text h5,
.content-area h5,
.section-newsletter .content-area h5,
.pane-node-body .field-items h5,
.node-webform .field-items h5,
.pane-node-body .field-items h5 span {
  font-size: 12px;
  font-weight: bold;
}
.answers .answer-text h6,
.content-area h6,
.section-newsletter .content-area h6,
.pane-node-body .field-items h6,
.node-webform .field-items h6,
.pane-node-body .field-items h6 span {
  font-size: 10px;
  font-weight: bold;
}
.pane-node-body .field-items a {  text-decoration: none }
.pane-node-body .field-items a:hover {  text-decoration: underline }
.manchet {
  font: 400 17px "/* Droid */ Serif", Arial, sans-serif;
  font: 400 17px "Droid Sans", Arial, sans-serif;
}
/* ===========[ Pager ]================================================= */
.item-list .pager {
  position: relative;
  margin-top: 10px;
}
.page-search .item-list .pager {
  margin-bottom: 10px;
  /*overflow: hidden;*/
}
.page-search .towcolright-layout {
  background-position: 10px 0;
}
.pager .pager-item {  float: left }
.pager .pager-title {  padding-left: 10px }
.pager li.pager-item {
  border-right: 1px solid #000;
  padding: 0 5px;
}
.page-employees .pager li.pager-item.last {  padding-right: 0px }
.pager .pager-item a {
  color: #000;
  text-decoration: none;
}
.pager .pager-item.pager-current {  color: #F45017 }
.pager li.pager-next,
.pager li.pager-previous {  border-right: none }
/*.pager .pager-previous {
  position: absolute;
  left: 0;
}*/
.pager .pager-next {  float: right }
.pager .pager-title {  margin-left: 25% }
/*----------------------------------------------------------*/
.description-wrapper {  margin-top: 10px }
.description-wrapper.video {  margin-top: 25px }
.page-blogs .border-wrapper-three {  margin-bottom: 20px }
/*----------------------------------------------------------[ Page layout */
.spage-center,
.vl-wrapper .grid_3 {  min-height: 20px }
ul.tabs {
  font-family: Tahoma, Arial, sans-serif;
  font-size: 11px;
  line-height: 19px;
  padding: 0 0 0 4px;
  border-bottom: 1px solid #C5C5C5;
}
ul.tabs li {
  margin: 0 0 0 4px;
  padding: 0;
  border: 0;
  float: left;
}
ul.tabs li a {  text-decoration: none }
ul.tabs li a:link,
ul.tabs li a:visited {
  display: inline;
  background: #F7F7F7;
  color: #BBBBBB;
  border: 1px solid #C5C5C5;
  border-top-left-radius: 3px;
  -moz-border-radius-topleft: 3px;
  border-top-right-radius: 3px;
  -moz-border-radius-topright: 3px;
  padding: 2px 9px 2px 10px;
  margin: 0;
}
ul.tabs li a:hover,
ul.tabs li a:active {
  color: #5F5F5F;
  background: #F9F9F9;
}
ul.tabs li a.active:link,
ul.tabs li a.active:visited {
  border-bottom-color: white;
  background: transparent;
  color: #515151;
}
ul.tabs.secondary {
  position: relative;
  top: -10px;
}
/* Dropdown menu */
.selectBox-dropdown-menu {
  position: absolute;
  z-index: 99999;
  max-height: 200px;
  border: 1px solid #eee; /* should be the same border width as .selectBox-dropdown */
  background: #FFF;
  overflow: auto;
}
/* Inline control */
.selectBox-inline {
  width: 250px;
  outline: none;
  border: solid 1px #BBB;
  background: #FFF;
  display: inline-block;
  -webkit-border-radius: 4px;
  -moz-border-radius: 4px;
  border-radius: 4px;
  overflow: auto;
}
.selectBox-inline:focus {  border-color: #666 }
/* Disabled state */
.selectBox.selectBox-disabled {  color: #888 !important }
.selectBox-dropdown.selectBox-disabled .selectBox-arrow {
  opacity: .5;
  filter: alpha(opacity=50);
  border-color: #666;
}
.selectBox-inline.selectBox-disabled {  color: #888 !important }
.selectBox-inline.selectBox-disabled .selectBox-options A {  background-color: transparent !important }
/* ===========[ BLOCK TITLE ]================================================= */
/* 28px bold */
.pane-calendar-latest-arrangements-calendar-latest-arrangements .pane-title,
.pane-blogs-latest-posts-blog-latest-post .pane-title,
.pane-global-articles-list-global-articles-list .pane-title,
.pane-ibis-posten-view-ibis-posten-view .pane-title,
.pane-newsletter-newsletter-subscriptions .pane-title,
.pane-ibis-posten-view-ibis-posten-view .pane-title,
.html-block .pane-title {
  /* font: bold 28px "Droid Serif", Arial, sans-serif; */
    font: bold 28px "Droid Sans", Arial, sans-serif;
  
  color: #626261;
}
.html-block .pane-title,
.pane-newsletter-newsletter-subscriptions .pane-title {
  color: #787877;
  font-size: 26px;
}
.main-node .block-title,
.main-node-big .block-title {
  font: bold 30px/36px "Droid Serif", Arial, sans-serif;
  color: #626261;
}
.pane-blogs-latest-posts-latest-posts-blog-page .pane-title,
.pane-blog-bloggers-list .pane-title,
.pane-blog-blog-archive .pane-title,
.pane-latest-comments-latest-posts-blog-page .pane-title,
.pane-archive-pane .pane-title {
  /* font: bold 22px "Droid Serif", Arial, sans-serif; */
    font: bold 22px "Droid Sans", Arial, sans-serif;
  color: #626261;
  padding: 0 0 5px;
  border-bottom: 1px dotted #C6C6C5;
  margin-bottom: 15px;
}
.pane-archive-pane .pane-title,
.pane-latest-comments-latest-posts-blog-page .pane-title,
.pane-blog-bloggers-list .pane-title {  font-size: 20px }
/* ===========[ HTML BLOCKS ]================================================= */
.html-block .pane-title {  margin-bottom: 15px }
.view-front-page-employees h3 a:hover {  color: #1c95b8 }
.html-block .wysiwyg-link span,
.pane-calendar-latest-arrangements-calendar-latest-arrangements .more-link span,
.pane-blogs-latest-posts-blogs-latest-posts .more-link span,
.pane-global-articles-list-global-articles-list .more-link span,
.pane-poll-recent .links span,
.more-link span {
  padding: 0 5px 0 8px;
  height: 13px;
  background: url("../images/ui-sprite.png") no-repeat scroll 0px -169px;
  margin: 0 0 0 5px;
}
.html-block .wysiwyg-link:hover span,
.pane-calendar-latest-arrangements-calendar-latest-arrangements .more-link:hover span,
.view-blogs-latest-posts .more-link:hover span,
.pane-global-articles-list-global-articles-list .more-link:hover span,
.view-ibis-posten-view .more-link:hover span,
.pane-poll-recent .links a:hover span {  background-position: 0px -204px }
.html-block .wysiwyg-link,
.pane-calendar-latest-arrangements-calendar-latest-arrangements .more-link,
.pane-blogs-latest-posts-blogs-latest-posts .more-link,
.pane-global-articles-list-global-articles-list .more-link,
.pane-poll-recent .links a,
.more-link {
  color: #1C95B8;
  font-size: 11px;
  font-weight: bold;
  margin-top: 9px;
  text-decoration: none;
  float: right;
}
.html-block .wysiwyg-link:hover,
.pane-calendar-latest-arrangements-calendar-latest-arrangements .more-link:hover,
.view-blogs-latest-posts .more-link:hover,
.pane-global-articles-list-global-articles-list .more-link:hover,
.view-ibis-posten-view .more-link:hover,
.pane-poll-recent .links a:hover {  color: #156d87 }
.pane-calendar-latest-arrangements-calendar-latest-arrangements .more-link {  background-position: 120px -169px }
.five-things br {  display: none }
.pane-thanks-block {  text-align: center }
.pane-thanks-block .thank-title {
  color: #1C95B8;
  font: bold 54px/51px 'Droid Serif', Arial, sans-serif;
  margin: 26px 0 30px;
}
.pane-thanks-block .thank-body {
  /* font: bold 19px 'Droid Serif', Arial, sans-serif; */
    font: bold 19px "Droid Sans", Arial, sans-serif;
  margin: auto;
  width: 600px;
  color: #303030;
  padding: 0 0 30px 0;
}
/* ===========[ Kalender, Bloggen, IBIS globalt, Posten ]=============================== */
.pane-calendar-latest-arrangements-calendar-latest-arrangements .pane-title,
.pane-blogs-latest-posts-blog-latest-post .pane-title,
.pane-global-articles-list-global-articles-list .pane-title,
.pane-newsletter-newsletter-subscriptions .pane-title,
.pane-ibis-posten-view-ibis-posten-view .pane-title {
  padding: 0px 0 4px 35px;
  line-height: 24px;
  margin: 0 0 10px 0;
  word-wrap: break-word;
}
.pane-newsletter-newsletter-subscriptions .pane-title {  margin: 0 0 4px 0 }
.pane-blogs-latest-posts-latest-posts-blog-page,
.pane-blog-bloggers-list,
.pane-blog-blog-archive,
.pane-latest-comments-latest-posts-blog-page,
.pane-archive-pane {  margin-bottom: 20px }
.pane-latest-comments-latest-posts-blog-page,
.pane-archive-pane,
.pane-blog-bloggers-list {  margin-bottom: 40px }
.pane-blog-bloggers-list .pane-title {
  padding: 6px 0 4px 35px;
  background: url("../images/ui-sprite.png") 0px -712px;
}
.pane-global-articles-list-global-articles-list .pane-title {  background: url("../images/ui-sprite.png") 0px -770px }
.pane-blogs-latest-posts-blog-latest-post .pane-title {  background: url("../images/ui-sprite.png") 0px -715px }
.pane-ibis-posten-view-ibis-posten-view .pane-title {  background: url("../images/ui-sprite.png") -400px -554px }
.ibis-focus h2.pane-title {
  background: url("../images/ui-sprite.png") -400px -602px;
  padding: 8px 0 4px 35px;
}
.pane-newsletter-newsletter-subscriptions .pane-title {  background: url("../images/ui-sprite.png") 0px -607px; width: 350px;
  height: 22px; }
.pane-calendar-latest-arrangements-calendar-latest-arrangements .pane-title {  background: url("../images/ui-sprite.png") 0px -659px;  }
.pane-calendar-latest-arrangements-calendar-latest-arrangements .views-row,
.pane-blogs-latest-posts-blogs-latest-posts .views-row,
.pane-global-articles-list-global-articles-list .views-row,
.view-articles-by-category .views-row {  word-wrap: break-word }
.pane-blogs-latest-posts-blogs-latest-posts .date,
.pane-global-articles-list-global-articles-list .date,
.view-articles-by-category .views-row .date,
.main-node .views-row .date,
.main-node-big .views-row .date,
.two-column-list .views-row .date,
.flat-list .views-row .date,
.three-column-list .views-row .date,
.vertical-list .views-row .date,
.search-result .result-date {
  color: #F45017;
  font-size: 12px;
}
.pane-calendar-latest-arrangements-calendar-latest-arrangements .views-row {
  border-bottom: 1px dotted #c6c6c5;
  padding-bottom: 10px;
  margin-bottom: 15px;
}
.pane-calendar-latest-arrangements-calendar-latest-arrangements h4 {  margin: 5px 0 0 }
.pane-calendar-latest-arrangements-calendar-latest-arrangements h4 a,
.view-front-page-employees .views-row h3 a {  /* font: bold 12px/22px "Droid Serif", Arial, sans-serif */ 
    font: bold 12px/22px "Droid Sans", Arial, sans-serif;}
.pane-calendar-latest-arrangements-calendar-latest-arrangements .views-row p,
.pane-blogs-latest-posts-blogs-latest-posts h4 a,
.view-front-4-elements-view .views-row p,
.view-articles-by-category .views-row p,
.view-front-page-employees .views-row p,
.main-node .block-body,
.main-node-big .block-body,
.two-column-list .block-body,
.flat-list .block-body,
.three-column-list .block-body,
.vertical-list .block-body {
  font: 12px/17px arial, helvetica, clean, sans-serif;
  word-wrap: break-word;
}
.pane-calendar-latest-arrangements-calendar-latest-arrangements h4 {  margin: 0 0 5px 0 }
.pane-calendar-latest-arrangements-calendar-latest-arrangements h4 a {  line-height: 1.23 }
.view-articles-by-category p:hover {  color: #3A3A3A }
.pane-global-articles-list-global-articles-list .field-content a {
  text-decoration: none;
  color: #1f1f1f;
}
.pane-blogs-latest-posts-blog-latest-post,
.pane-ibis-posten-view-ibis-posten-view {  margin: 0 0 45px 0 }
.pane-blogs-latest-posts-blogs-latest-posts .views-row {  padding: 0 0 15px 0 }
.pane-global-articles-list-global-articles-list .views-row {  padding: 0 0 20px 0 }
.pane-blogs-latest-posts-blogs-latest-posts .views-row-last,
.pane-global-articles-list-global-articles-list .views-row-last,
.pane-blogs-latest-posts-blog-latest-post .view-blogs-latest-posts .views-row-last,
.pane-global-articles-list-global-articles-list .view-global-articles-list .views-row-last,
.view-ibis-posten-view .views-row.views-row-last,
.view-blog.ibis-standart-block .views-row.views-row-last,
.view-blogs-latest-posts .views-row.views-row-last,
.view-latest-comments .views-row.views-row-last,
.view-rss-feeds-block .views-row.views-row-last {  border-bottom: 1px dotted #c6c6c5 }
.pane-calendar-latest-arrangements-calendar-latest-arrangements .views-row-last {  margin: 0 }
.pane-global-articles-list-global-articles-list .views-row h4,
.view-rss-feeds-block .views-row h4 {
  /* font: 12px/16px "Droid Serif", Arial, sans-serif; */
  font: 12px/16px "Droid Sans", Arial, sans-serif;
  display: inline;
}
.view-rss-feeds-block .views-row h4 a {  display: inline }
.pane-global-articles-list-global-articles-list .views-row {  color: #1f1f1f }
.pane-blogs-latest-posts-blogs-latest-posts .comments-count,
.flat-list .comments-count,
.three-column-list .comments-count,
.vertical-list .comments-count,
.search-result .result-comment {
  padding-left: 13px;
  color: #f57244;
  background: url("../images/ui-sprite.png") -790px 1px no-repeat;
  font-weight: bold;
}
.pane-blogs-latest-posts-blogs-latest-posts .user-name {
  color: #f57244;
  border-right: solid orange 1px;
  padding-right: 5px;
  font-weight: bold;
  font-size: 12px;
}
.pane-blogs-latest-posts-blogs-latest-posts .user-name a {  color: #f57244 }
.pane-blogs-latest-posts-blogs-latest-posts .user-name a:hover,
.pane-blogs-latest-posts-blogs-latest-posts .date:hover {
  color: #1c95b8;
  cursor: pointer;
}
.five-things {  height: 200px }
.five-things.button {  background: #f1541c url('../images/ui-sprite.png') -225px -237px no-repeat }
.five-things.button:hover {  background: #cf3702 url('../images/ui-sprite.png') -225px -288px no-repeat }
.support-us-here {
  background: #1c95b8;
  width: 220px;
  padding: 0 0 15px 0;
}
.support-us-here .title {
  font: 30px 'Droid Sans', Arial, sans-serif;
  color: #fff;
  padding: 10px 15px;
  line-height: 30px;
}
.support-us-here .orangebutton a {
  background: url("../images/five-things-btn.png") no-repeat scroll 155px 10px #F1541C;
  display: block;
  margin: auto;
  min-height: 45px;
  padding: 0 40px 0 10px;
  width: 140px;
}
.orangebutton .wrapper {
  padding: 5px 0;
  display: block;
}
.not-front .grid_3 .pane-custom {  margin: 0 0 20px 0 }
.support-us-here .orangebutton a:hover {  background: #cf3702 url('../images/five-things-btn-hover.png') 155px 10px no-repeat }
.support-us-here .orangebutton .wrapper {
  color: #fff;
  font: bold 25px 'Droid Sans', Arial, sans-serif;
}
.quote .quotes {
  width: 45px;
  height: 26px;
  background: url('../images/ui-sprite.png') -500px -373px no-repeat;
  margin-top: 25px;
}
.quote .quote-text {
  font: bold 18px  "Droid Sans", Arial, sans-serif;
  margin-bottom: 10px;
}
.quote .quote-author {
  font: bold italic 12px "Droid Serif", Arial, sans-serif;
  color: #f7921e;
}
.calendar-go-back {
  float: left;
}
.calendar-go-back .pane-content a {
  font: 700 14px/1.2  "Droid Sans", Arial, sans-serif;
}
/* ===========[ Block 220 ]================================================= */
.view-articles-by-category .views-row h3 a,
.view-front-page-employees .views-row h3 a,
.main-node .block-title a,
.main-node-big .block-title a,
.pane-search-result .search-result .result-title a {
  color: #161616;
  display: block;
}
.front-page-tabs .tabs-articles-by-category li img,
.view-front-page-employees .views-row img,
.two-column-list .views-row img,
.flat-list .views-row img,
.three-column-list .views-row img,
.vertical-list .views-row img,
.pane-search-result .search-result img {  border: 1px solid #d6d6d6 }
.view-articles-by-category .picture-img img,
.view-front-page-employees .views-row img,
.main-node img,
.main-node-big img,
.two-column-list img,
.flat-list img,
.three-column-list img,
.vertical-list img {
  display: block;
  margin: 0 0 25px 0;
}
.view-front-4-elements-view .picture-img img,
.view-articles-by-category .picture-img img {
  width: 218px;
  height: 138px;
}
.view-articles-by-category .views-row .date,
.pane-global-articles-list-global-articles-list .date,
.main-node .views-row .date,
.main-node-big .views-row .date,
.two-column-list .views-row .date,
.flat-list .views-row .date,
.three-column-list .views-row .date,
.vertical-list .views-row .date,
.pane-search-result .search-result .result-date,
.pane-search-result .search-result .result-category {
  padding: 0 5px 0 0;
  margin: 0 4px 0 0;
  border-right: 1px solid #F45017;
}
/*.page-section .date:hover{
    color: #1c95b8;
    border-color:#1c95b8;
    cursor: pointer;
}*/
.page-section-second .block-body:hover,
.page-section .block-body:hover {
  cursor: pointer;
  color: #3a3a3a;
}
.view-articles-by-category .views-row a,
.view-front-page-employees .views-row a,
.main-node .views-row a,
.main-node-big .views-row a,
.two-column-list .views-row a,
.flat-list .views-row a,
.three-column-list .views-row a,
.vertical-list .views-row a,
.pane-search-result .search-result a {  text-decoration: none }
.view-articles-by-category .views-row .category a,
.main-node .views-row .category a,
.main-node-big .views-row .category a,
.two-column-list .views-row .category a,
.flat-list .views-row .category a,
.three-column-list .views-row .category a,
.vertical-list .views-row .category a,
.pane-search-result .search-result .result-category a {
  color: #f45017;
  font-weight: bold;
  font-size: 12px;
}
.view-articles-by-category .views-row h3,
.main-node .block-title,
.main-node-big .block-title,
.two-column-list .block-title,
.flat-list .block-title,
.three-column-list .block-title,
.vertical-list .block-title,
.search-result .result-title {  margin: 3px 0 7px 0 }
.view-articles-by-category .views-row h3 a,
.two-column-list .block-title a,
.flat-list .block-title a,
.vertical-list .block-title a,
.three-column-list .block-title a,
.search-result .result-title a {
  font: bold 14px/18px "Droid Serif", Arial, sans-serif;
  color: #000;
}
.three-column-list .block-title a {  font-size: 12px }
.view-articles-by-category .category a:hover,
.main-node .category a:hover,
.main-node-big .category a:hover,
.two-column-list .category a:hover,
.flat-list .category a:hover,
.three-column-list .category a:hover,
.vertical-list .category a:hover,
.pane-search-result .search-result a:hover {  color: #1c95b8 }
/* ===========[ Block 140 ]================================================= */
.view-front-page-employees .views-row img {  margin: 0 0 10px 0 }
.view-front-page-employees .views-row h3 {  margin: 0 0 5px 0 }
.view-front-page-employees .views-row img {  width: 138px }
/* ===========[ Block 460 ]================================================= */
.main-node .views-row img {  width: 460px }
.main-node-big .views-row img {  width: 698px }
/* ===========[ POLL ]================================================= */
.form-item {  margin: 0 }
input.form-checkbox,
input.form-radio {  vertical-align: text-top }
.poll {
  background-color: #f7921e;
  padding: 20px 7px 10px 13px;
  width: 200px;
}
.poll .title {
  color: #161616;
  font-size: 22px;
  font-weight: bold;
  letter-spacing: -0.25px;
  line-height: 20px;
  margin: 0 0 17px;
  padding: 0 10px 0 0;
}
.form-item-choice {
  color: #282800;
  font-size: 12px;
}
.form-radios .form-item,
.form-checkboxes .form-item {  margin: 0 0 10px 0 }
.form-radios .form-item label {
  margin: 0 4px 0 26px;
  display: block;
  word-wrap: break-word;
  cursor: pointer;
}
.poll .jquery-checkbox {  float: left }
.poll .jquery-checkbox {  padding: 0 0 2px 0 }
.poll .mark,
.poll .jquery-checkbox-checked .mark,
.poll .jquery-checkbox-hover {
  background-image: url('../images/ui-sprite.png');
  padding: 1px 7px 2px 6px;
}
.poll .mark {
  background-position: -954px -718px;
  cursor: pointer;
}
.poll .jquery-checkbox-checked .mark {  background-position: -954px -766px }
.poll .jquery-checkbox-hover {  background-position: -954px -742px }
.poll .choices {  padding: 0 0 10px 0 }
.poll .form-submit {
  background: url("../images/ui-sprite.png") no-repeat scroll 143px -233px #1C95B8;
  border: medium none;
  color: #FFFFFF;
  cursor: pointer;
  margin: 0 0 0 20px;
  font-size: 15px;
  font-weight: bold;
  padding: 10px 40px 10px 10px;
  width: 177px;
}
.poll .form-submit:hover {  background: url("../images/ui-sprite.png") no-repeat scroll 143px -284px #167692 }
.poll + .links {
  text-align: right;
  margin: 5px 0 30px;
}
.poll + .links a {
  margin-bottom: 30px;
  font: bold 11px/19px "Droid Sans", Arial, sans-serif;
  text-decoration: none;
}
.poll + .links a span {
  background: url("../images/ui-sprite.png") no-repeat scroll 0 -169px transparent;
  height: 13px;
  margin: 0 0 0 5px;
  padding: 0 1px 0 8px;
}
.poll + .links a:hover,
.more-link.ibis-arrow-link:hover {  color: #156D87 }
.poll + .links a:hover span,
.more-link.ibis-arrow-link:hover span {  background-position: 0 -204px }
.bar {  width: 160px }
.foreground {
  height: 12px;
  background-color: #000;
  position: relative;
}
.poll-item {  line-height: 12px }
.poll-item .text {  margin: 4px 0 10px 0 }
.poll-item .percent,
.poll-item .text {  font-size: 12px }
.poll-item .percent {
  position: absolute;
  font-weight: bold;
  top: 0;
  right: -34px;
  width: 30px;
}
.total {  display: none }
/* ===========[ Sectionpage Blocks ]================================================= */
.main-node,
.main-node-big,
.two-column-list,
.flat-list,
.three-column-list {
  padding: 0 0 25px 0;
  margin: 0 0 30px 0;
  border-bottom: 1px dotted #C8C7C6;
  word-wrap: break-word;
}
.main-node-big,
.three-column-list {  padding: 0 0 18px 0 }
.two-column-list .views-row img,
.vertical-list .views-row img {  width: 218px }
.flat-list .views-row img,
.three-column-list .views-row img {  width: 138px }
/*----------------------------------------------Body blocks style and effect*/
.block-body a,
.main-node-big .block-body a,
.two-column-list .block-body a,
.flat-list .block-body a,
.three-column-list .block-body a,
.vertical-list .block-body,
.main-node .block-title a,
.main-node-big .block-title a,
.two-column-list .block-title a,
.flat-list .block-title a,
.three-column-list .block-title a,
.vertical-list .block-title a {
  color: #161616;
  display: block;
}
.block-body a:hover {  color: #3a3a3a }
/*----------------------------------------------------<== END*/
.two-column-list ul {
  float: left;
  background: url("../images/bg-line-vertical.png") repeat-y 50%;
  width: 100%;
}
.two-column-list ul > li {
  display: inline;
  float: left;
  width: 220px;
}
.two-column-list .views-row-first {  margin: 0 10px 0 0 }
.two-column-list .views-row-last {  margin: 0 0 0 10px }
.three-column-list ul li {
  display: inline;
  float: left;
  margin-left: 10px;
  margin-right: 10px;
  width: 140px;
}
.three-column-list ul {
  background: url("../images/bg-3block.png") repeat-y scroll 149px 0 transparent;
  float: left;
}
.three-column-list ul .views-row-first {  margin-left: 0 }
.three-column-list ul .views-row-last {  margin-right: 0 }
.flat-list .views-row {
  float: left;
  width: 100%;
  padding: 0 0 30px 0;
  margin: 0 0 30px 0;
  border-bottom: 1px dotted #C8C7C6;
}
.flat-list .views-row .image-video {
  float: left;
  margin: 0 20px 0 0;
}
.flat-list .views-row .image-video + .block-content {  margin-left: 160px }
.flat-list .views-row-last img,
.flat-list .views-row img,
.flat-list .views-row-last {  margin: 0 }
.flat-list .views-row-last {
  border: none;
  padding: 0;
}
/*.page-section .pane-custom,
.page-category .pane-custom,
.not-front .pane-custom{
  margin-bottom:20px;
}*/
.pane-custom a {  text-decoration: none!important }
.vertical-list .views-row {
  border-bottom: 1px dotted #C8C7C6;
  padding: 0 0 20px 0;
  margin: 0 0 30px 0;
}
/* ibis_posten_view */
.view-ibis-posten-view h3 {
  display: inline;
  font: bold 16px 'Droid Sans', Arial, sans-serif;
}
.view-ibis-posten-view h3 a {
  color: #f45b26;
  text-decoration: none;
}
.view-display-id-pane_vertical_list_height {
  border-bottom: 1px dotted #C8C7C6;
  margin: 0 0 30px;
}
.view-display-id-pane_vertical_list_height .views-row {
  width: 220px;
  float: left;
}
.view-display-id-pane_vertical_list_height .views-row-last {
  border: none;
  margin: 0;
}
.three-column-list {  margin-bottom: 0px }
.view-page-section-page .views-row-last {  margin-bottom: 0px }
.content-area {  margin-top: 15px }
/* layout */
.front .row-one,
.front .row-two {  margin-bottom: 20px }
.front .row-three {
  margin-bottom: 40px;
  padding-bottom: 27px;
}
.front .row-four {  margin-bottom: 13px }
.front .row-five {
  margin-bottom: 30px;
  padding-bottom: 27px;
}
.front .row-five .borderwrap {  background: url('../images/bg-4.png') repeat-y 229px 0 }
.front .row-six {  margin-bottom: 30px }
.front .row-seven { }
/* ===========[ appel-element ]================================================= */
.pane-appel-element {  margin: 0 0 2px 0 }
.view-front-appel-element-view ul,
.view-front-appel-element-view ul li {  margin: 0 }
.view-front-appel-element-view {
  position: relative;
  height: 415px;
}
.view-front-appel-element-view img {  display: block }
.view-front-appel-element-view .appel-text-list {
  /*background: url('../images/arrow-appel.png') no-repeat 0 bottom;*/
  bottom: 0;
  left: 0;
  position: absolute;
  word-wrap: break-word;
  height: 72px;
}
.view-front-appel-element-view .views-row .item {
  color: #fff;
  float: left;
  font-family: "Droid Serif", Arial, sans-serif;
  position: relative;
}
/* big images */
.view-front-appel-element-view .img-appel-list {
  height: 415px;
  overflow: hidden;
  position: relative;
}
.view-front-appel-element-view .img-appel-list li {
  margin: 0;
  position: absolute;
  display: none;
}
.view-front-appel-element-view .img-appel-list .show {  display: block }
/* upmenu */
.view-id-front_appel_element_view {
  position: relative;
  overflow: hidden;
}
.view-id-front_appel_element_view ul {  z-index: 100 }
.appel-text-list {  background: url('../images/arrow-appel.png') no-repeat left bottom }
.appel-text-list .first,
.appel-text-list .third,
.firstpop {  width: 313px }
.appel-text-list .additional-text .field-content {  padding: 0 10px }
.appel-text-list .additional-text .description {
  padding: 10px 0 0 0;
  margin: 10px 0 0 0;
  border-top: 1px dotted #fff;
}
.appel-text-list .first .additional-text,
.appel-text-list .second .additional-text {
  padding: 15px 20px 20px 20px;
  zoom: 1;
}
.appel-text-list .first .additional-text {  width: 279px }
.appel-text-list .second .additional-text {  width: 279px }
.view-id-front_appel_element_view .second,
.view-id-front_appel_element_view .secondpop {  width: 314px }
.appel-text-list li {
  float: left;
  height: 72px;
}
.appel-text-list .additional-text {
  position: absolute;
  z-index: 100;
}
.appel-text-list .additional-text .description {
  visibility: hidden;
  /*opacity: 0;*/
}
.view-id-front_appel_element_view .firstpop,
.view-id-front_appel_element_view .secondpop {
  position: absolute;
  bottom: 72px;
  z-index: 1;
  height: 0px;
}
.view-id-front_appel_element_view .firstpop {  background-image: url('../images/bg-hover.png') }
.view-id-front_appel_element_view .secondpop {
  left: 313px;
  background-image: url('../images/bg-hover-second.png');
}
.view-id-front_appel_element_view .third .field-content {
  padding: 10px 0 0 25px;
  height: 57px;
}
.view-id-front_appel_element_view .appel-text-list a {
  color: #FFFFFF;
  /*display: block;*/
  text-decoration: none;
}
.view-id-front_appel_element_view .appel-text-list {  line-height: 22px }
.view-id-front_appel_element_view .appel-text-list img {  display: inline }
.thirdover {  background-position: right bottom }
/* ===========[ Front_4_Elements, tabs list ]================================================= */
.four_element,
.front-page-tabs {  padding: 0 0 14px 0 }
.four_element,
.front-page-tabs,
.front .row-three,
.front .row-five,
.front .row-one {  border-bottom: 1px dotted #c8c7c6 }
.front .row-one {  padding-bottom: 20px }
.view-front-4-elements-view,
.front-page-tabs .pane-articles-by-category {
  background: url('../images/bg-4.png') repeat-y 229px 0;
  float: left;
  margin: 27px 0 0;
}
.view-front-4-elements-view .elements-list li,
.front-page-tabs .tabs-articles-by-category li {
  display: inline;
  float: left;
  margin-left: 10px;
  margin-right: 10px;
  width: 220px;
}
.view-front-4-elements-view .elements-list .views-row-first,
.front-page-tabs .tabs-articles-by-category .views-row-first {  margin-left: 0 }
.view-front-4-elements-view .elements-list .views-row-last,
.front-page-tabs .tabs-articles-by-category .views-row-last {  margin-right: 0 }
.front-page-tabs .tabs-articles-by-category {
  height: 280px;
  overflow: hidden;
}
/* ===========[ tabs ]================================================= */
.front-page-tabs {
  padding: 0 0 30px 0;
  margin: 0 0 20px 0;
  position: relative;
  height: 333px;
}
/* tabs menu */
.front-page-tabs > .pane-title {
  float: left;
  font: bold 32px/34px "Droid Serif", Arial, sans-serif;
  color: #626261;
}
.front-page-tabs .ui-tabs-nav {
  float: right;
  height: 32px;
  background: url('../images/bg-tabs-menu.png') repeat-x 0 0;
}
.front-page-tabs .ui-tabs-nav li {
  float: left;
  margin: 0;
  position: relative;
}
.front-page-tabs .ui-tabs-nav .last a {  border: none }
.front-page-tabs .ui-tabs-nav a {
  border-right: 1px solid #ccc;
  display: block;
  margin: 1px 0;
  padding: 7px 18px 7px 14px;
  text-decoration: none;
  color: #343432;
}
.front-page-tabs .ui-tabs-nav .active-arrow {
  bottom: 0;
  display: none;
  height: 7px;
  left: 50%;
  margin: 0 0 0 -8px;
  position: absolute;
  width: 15px;
}
.front-page-tabs .ui-state-active .active-arrow {  background-image: url("../images/ui-sprite.png") }
.front-page-tabs .ui-state-hover a {
  background-color: #efefe7;
  color: #1C95B8;
}
.front-page-tabs .ui-state-active a {
  background-color: #1c95b8;
  color: #fff;
}
.front-page-tabs .ui-state-hover .active-arrow {  background-position: -500px -133px }
.front-page-tabs .ui-state-active .active-arrow {
  background-position: -517px -133px;
  display: block;
}
/* tabs items */
.front-page-tabs .ui-tabs-hide {  display: none }
.front-page-tabs .ui-tabs-panel {
  position: absolute;
  top: 32px;
  left: 0;
}
/* ===========[ selectbox Domain ]=================================+========= */
.block-domain-nav {

}
.page-header .selectBox-dropdown {
  display: block !important;
  width: 180px !important;
  height: 15px;
  position: relative;
  border: 1px solid #eee;
  color: #2c2c2a;
  font-size: 12px;
  margin: 0 0 0 4px;
  padding: 4px 9px;
  background: #fff;
}
.selectBox-dropdown .selectBox-label {
  width: 100%;
  display: inline-block;
  white-space: nowrap;
  overflow: hidden;
}
.selectBox-dropdown .selectBox-arrow {
  position: absolute;
  top: 0;
  right: 0;
  width: 30px;
  height: 100%;
  background: url("../images/ui-sprite.png") -780px -56px no-repeat;
}
.selectBox-options {
  border: 1px solid #eee;
  border-style-top: none;
  padding: 0px;
  margin: 0px;
}
.selectBox-options li {
  height: 17px;
  color: #2c2c2a;
  font-size: 12px;
  padding: 6px 7px;
}
.selectBox-options li.selectBox-hover {  background-color: #EEE }
.selectBox-options li.selectBox-selected {  background-color: #C8DEF4 }
/* ===========[ front-page-employees ]================================================= */
.bgwrapper {  background: url('../images/bg-3block.png') repeat-y 229px 0 }
.view-front-page-employees .employees-list li {
  display: inline;
  float: left;
  margin-left: 10px;
  margin-right: 10px;
  width: 140px;
}
.view-front-page-employees .employees-list .views-row-first {  margin-left: 0 }
.view-front-page-employees .employees-list .views-row-last {  margin-right: 0 }
/* ===========[ big banner ]================================================= */
.front .row-six img {  display: block }
.page-section .container_12 .spage-left {  width: 180px }
.page-section .container_12 .spage-center {  margin: 0 30px }
.page-section .content-area .vl-wrapper {
  background: url('../images/vl-sectionpage.png') repeat-y  200px 0px;
  margin-bottom: 20px;
}
.sep-6-3 .bgwrap {  background: url('../images/bg-470-section.png') repeat-y 0 0 }
.sep-9-3 {  background: url('../images/bg-940-section.png') repeat-y 0 0 }
/* ===========[ LEFT MENU ]================================================= */
.spage-left .menu li {  word-wrap: break-word }
.spage-left .menu a {
  font: normal 13px arial, helvetica, clean, sans-serif;
  padding: 10px 0 10px 10px;
  display: block;
  text-decoration: none;
  color: #161616;
  position: relative;
}
.top-level > li > .menu {  padding-bottom: 10px }
.top-level > li > .active-trail,
.top-level > .leaf > a {  padding: 13px 0 13px 10px }
.top-level > li > ul ul {  padding-left: 5px }
.top-level .menu li > .menu {  padding-bottom: 10px }
.spage-left .collapsed ul {  display: none }
.spage-left .menu ul li ul {  margin: 0 0 0 8px }
.spage-left .active-trail.level-one {
  background-color: #f3f3f3;
  border-bottom: 1px solid #ededed;
}
.spage-left .menu .level-one:hover > a {  color: #F57244 }
.level-one > ul {  padding: 0 0 0 10px }
.spage-left .pane-content > ul.menu .expanded ul.menu {
  background-color: #f3f3f3;
  /*border-bottom: 1px solid #ededed;*/
}
.spage-left .menu .level-one > a {
  background-color: #fff;
  border-bottom: 1px solid #ededed;
  font-weight: bold;
}
.spage-left .menu .active-trail.level-one > a,
.spage-left .menu .level-one > a.active {
  /*border-bottom: 1px solid #87c4d5;*/
  background-color: #1C95B8;
  /* background: url('../images/ui-sprite.png') no-repeat -785px -272px; */
  color: #fff;
}
/*.spage-left .expanded.active > a span */
.active .arrow,
.active-trail .arrow {
  background: url("../images/ui-sprite.png") no-repeat scroll -500px 0px transparent;
  height: 5px;
  left: 11px;
  position: absolute;
  bottom: -5px;
  width: 9px;
  display: block;
}
ul.menu .active .arrow {  bottom: -5px }
.spage-left .leaf.level-one > a.active span {  display: none }
.spage-left .menu .level-one ul a {
  border: none;
  background-color: transparent;
}
.spage-left .menu .level-one .expanded .active {  text-decoration: underline }
.spage-left .menu .active-trail ul a,
.spage-left .menu ul a {
  background: url('../images/leftmenu-arrow.png') no-repeat 0 13px;
  padding-left: 8px!important;
}
.spage-left .menu li.active-trail .active-trail {
  border: none;
}
.spage-left .menu ul a.active {
  color: #1c95b8;
  text-decoration: underline;
}
.spage-left .menu a:hover {  color: #1c95b8 }
/*
.spage-left .menu .active-trail ul a.active-trail {
  background-image: none;
  padding-left: 0;
}
*/
.level-one .menu a {  padding: 7px 0 0 }
.level-one > .menu > .last {  padding-bottom: 10px }
.level-one i {
  display: block;
  height: 10px;
  left: 15px;
  position: absolute;
  bottom: -10px;
  width: 14px;
  background: url('../images/ui-sprite.png') no-repeat -785px -272px;
}
/* ===========[ ibis_posten_view ]================================================= */
.view-ibis-posten-view {  font: 12px "Droid Sans" }
.view-ibis-posten-view .views-row-first .title {
  color: #F57244;
  font: bold 16px "Droid Sans", Arial, sans-serif;
  text-decoration: none;
}
.view-ibis-posten-view .views-row-first .category {  display: none }
.view-ibis-posten-view .views-row-first .date {  color: #F57244 }
.view-ibis-posten-view .views-row {  margin: 0 0 10px }
.view-ibis-posten-view .category {  font-weight: bold }
#apachesolr-search .grid_9 {  position: relative }
.page-search .breadcrumb li.last {
  margin: 0 8px 0 0;
  display: block;
  text-decoration: none;
  font-size: 11px;
  color: #9C9C9B;
}
.page-search .search-title {
  font: 44px "Droid Serif", Arial, sans-serif;
  margin: 0 0 20px;
}
.page-search .search-info {
  font: 19px "Droid Serif", Arial, sans-serif;
  margin: 0 0 25px;
}
.pane-search-form {  margin-bottom: 100px }
.page-search .pane-search-result input {
  border: none;
  background: transparent;
}
.page-search .pane-search-form {  display: block }
.page-search .pane-search-form .form-type-textfield {
  display: block;
  height: 23px;
  padding: 6px 8px 0px;
  width: 347px;
  margin: 0 20px 0 0;
  background: url("../images/text-field.png") no-repeat;
  float: left;
  border: 1px solid #B0B0B0;
}
.page-search .pane-search-form .form-type-textfield label {  display: none }
.page-search .pane-search-form .form-submit {
  display: block;
  float: left;
  width: 68px;
  height: 31px;
  line-height: 20px;
  background: url("../images/text-field.png") no-repeat;
  border: 1px solid #B0B0B0;
  font-size: 15px;
}
.page-search .pane-search-form .form-text {
  width: 327px;
  background-color: transparent;
  border: none;
  outline: none;
  font: 15px "Droid Sans", Arial, sans-serif;
}
.page-search .pane-search-result .pane-title {
  font: bold 20px "droid Sans", Arial, sans-serif;
  color: #3a3c3b;
  margin: 0 0 75px;
}
.page-search .pane-search-result .pane-content {
  border-top: 1px dotted #C8C7C6;
  padding: 30px 0 0;
}
.page-search .pane-search-result .search-result {
  float: left;
  width: 100%;
  padding: 0 0 30px 0;
  margin: 0 0 30px 0;
  border-bottom: 1px dotted #C8C7C6;
}
.page-search .pane-search-result .search-result.last {  margin-bottom: 10px }
.search-result .result-image {
  float: left;
  margin-right: 20px;
  width: 140px;
  height: 90px;
}
.search-result .result-image img {
  width: 140px;
  height: 90px;
  display: block;
}
.search-result .result-date,
.search-result .result-category {
  display: inline;
  float: left;
}
.search-result .result-category a {
  text-decoration: none;
  font-weight: bold;
  color: #6c6c6b;
}
.search-result .result-comment {  display: inline }
.search-result .result-content {  word-wrap: break-word }
.search-filter {
  padding: 15px 0 10px;
  border-bottom: dotted #c8c7c6 1px;
}
.search-filter.search-current .pane-title,
.search-custom-pane .pane-title {
  color: #6c6c6b;
  font: bold 18px "Droid Serif", Arial, sans-serif;
}
.search-custom-pane .pane-title {
  padding: 35px 0 20px;
  border-bottom: dotted #c8c7c6 1px;
}
.search-filter .pane-title {
  font: bold 16px "Droid Sans", Arial, sans-serif;
  margin: 0 0 15px;
}
.search-filter h3 {  font: 15px "Droid Sans", Arial, sans-serif }
.page-search .search-filter ul {  margin: 0px }
.page-search .search-filter li {
  color: #f45017;
  font: bold 14px "Droid Sans", Arial, sans-serif;
  margin: 0 0 5px;
}
.search-filter a {
  color: #f45017;
  font-size: 14px;
  font-weight: bold;
  text-decoration: none;
  margin-bottom: 5px;
}
.pane-apachesolr-search-sort {
  position: absolute;
  top: 200px;
  left: 0;
}
.pane-apachesolr-search-sort img {  display: none }
.pane-apachesolr-search-sort.empty {  top: 160px }
.pane-apachesolr-search-sort .item-list li {
  float: left;
  border-right: 1px solid #EBEBEA;
  padding: 8px 10px 8px 0;
  margin: 0 0 0 10px;
}
.pane-apachesolr-search-sort .item-list li.first {  margin: 0px }
.pane-apachesolr-search-sort .item-list a {
  color: #343432;
  text-decoration: none;
}
.pane-apachesolr-search-sort .item-list a:hover,
.pane-apachesolr-search-sort .item-list a.active {  color: #74b6ca }
.selectBox-dropdown {
  display: block;
  width: 184px;
  height: 15px;
  position: relative;
  outline: none;
  float: left;
  border: 1px solid #eee;
  color: #2c2c2a;
  font-size: 12px;
  margin: 0 0 0 4px;
  padding: 3px 9px;
  background: #fff;
}
.selectBox-dropdown .selectBox-arrow {
  position: absolute;
  top: 0;
  right: 0;
  width: 30px;
  height: 100%;
  background: url("../images/ui-sprite.png") -780px -58px no-repeat;
}
.selectBox-options {
  border: 1px solid #eee;
  border-top-style: none;
  padding: 0px;
  margin: 0px;
}
.selectBox-options li {
  height: 17px;
  color: #2c2c2a;
  font-size: 12px;
  padding: 3px 7px;
}
.selectBox-options li:hover {  background-color: #EEE }
.selectBox-options li.selectBox-selected {  background-color: #C8DEF4 }
.borderwrapper-grid_9 {  padding: 0 20px 0 0 }
.page-node-take .borderwrapper-grid_9 {
  border-right: 1px dotted  #C8C7C6;
  margin: 0 0 10px;
}
.pane-easy-hard-selector {
  width: 100%;
  margin: 0 0 5px;
}
.pane-quiz-pane .pane-title,
.pane-easy-hard-selector .pane-title {
  font: 44px "Droid Serif", Arial, sans-serif;
  margin: 0 0 20px;
}
.pane-easy-hard-selector .clearfixx {  clear: both }
.pane-easy-hard-selector+.panel-separator {  margin: 0px }
.pane-easy-hard-selector .field-content {
  float: left;
  position: relative;
}
.pane-easy-hard-selector .field-content a:hover,
.pane-easy-hard-selector .field-content a.active {
  position: relative;
  background: #1C95B8;
  color: white;
}
.pane-easy-hard-selector .field-content a:hover .arrow,
.pane-easy-hard-selector .field-content a.active .arrow {
  background: url("../images/ui-sprite.png") -608px 0px no-repeat;
  width: 15px;
  height: 5px;
  position: absolute;
  top: 27px;
  left: 50%;
  margin-left: -7px;
}
.pane-easy-hard-selector .field-content a {
  /* background-color: #1C95B8; */
  border-top: 1px dotted #C8C7C6;
  border-bottom: 1px dotted #C8C7C6;
  color: black;
  display: block;
  font: 13px "Droid Sans", Arial, sans-serif;
  padding: 8px 15px;
  text-decoration: none;
}
.pane-quiz-pane .pane-content {  position: relative }
.pane-quiz-pane .description-wrapper.quiz {  visibility: hidden }
.field-name-field-image .field-label {  display: none }
.field-name-field-image .field-item img {
  width: 100%!important;
  height: 395px!important;
}
.quizdescription {  margin: 5px 0 0 }
.pane-quiz-pane .field-type-image img {  display: block }
.pane-easy-hard-selector {  height: 33px }
.question-list {
  width: 100%;
  height: 39px;
  background-color: #f7921e;
  color: #fff;
  font: bold 15px "Droid Serif", Arial, sans-serif;
  margin: 0;
}
.question-list .question-number {
  font-size: 20px;
  position: relative;
}
.question-list .question-number.active {  background: #f45017 }
.question-list span {
  display: block;
  padding: 7px 13px 8px;
  float: left;
}
.question-list .question-number.active .btm-arrow {
  position: absolute;
  display: block;
  width: 20px;
  height: 8px;
  padding: 0;
  top: 39px;
  left: 50%;
  background: url("../images/ui-sprite.png") -197px 0px no-repeat;
  margin: 0 0 0 -10px;
}
.question-list .question-numbers { }
.question-list .btm-arrow {  display: none }
.question-list .title,
.question-list .next-quiz {  padding: 9px 15px }
.question-list .title {  font: bold 16px "Droid Sans", Arial, sans-serif }
.question-list .next-quiz {  float: right }
.question-list .next-quiz a {
  text-decoration: none;
  color: #fff;
}
.quiz-content {  position: relative }
.quiz-content .title {
  font: bold 16px "Droid Sans", Arial, sans-serif;
  margin: 20px 0 5px;
}
.quiz-content .body {  display: none }
.quiz-content .quiz-question-body {
  font: 14px "Droid Sans", Arial, sans-serif;
  margin-bottom: 25px;
}
.quiz-content .item-list li {
  margin: 0px;
  padding: 8px 10px;
  float: none;
}
.quiz-content .item-list li.answers li {  list-style: disc inside none }
.quiz-content .answers.even {  background-color: #efefef }
.quiz-content .answers.odd {
  background-color: #ffffff;
  padding: 12px 10px;
}
.quiz-content .form-item {  margin: 0px }
.quiz-content .answer-radio {
  float: left;
  margin-right: 20px;
}
.quiz-content .answer-text {
  font: 14px "Droid Serif", Arial, sans-serif;
  display: inline;
  word-wrap: break-word;
}
.quiz-content .answer-text p {  display: inline }
.quiz-content .answer-text .wrapper {  position: relative }
.quiz-content .form-submit,
.pane-newsletter-newsletter-subscriptions .form-submit {
  font: bold 18px "Droid Serif", Arial, sans-serif;
  border: none;
  background: url("../images/btn-arrow.png") right center no-repeat;
  color: #1c95b8;
  padding-right: 17px;
  margin-left: 30px;
  margin-top: 15px;
  text-decoration: none;
  display: none;
}
.pane-newsletter-newsletter-subscriptions .form-submit {
  font-size: 12px;
  float: right;
  display: block;
  margin-left: 0px;
}
.quiz-content form.show-next .form-submit {
  display: block;
  cursor: pointer;
}
.quiz-content .form-submit.q-back-button {  background: url("../images/btn-back-arrow.png")no-repeat 50px 4px }
.quiz-content .q-skip-button {  display: none }
.quiz-content .form-submit:hover,
.pane-newsletter-newsletter-subscriptions .form-submit:hover {
  background-image: url("../images/btn-arrow-hover.png");
  color: #156d87;
}
.quiz-content .form-submit.q-back-button:hover {  background: url("../images/btn-back-arrow-hover.png")no-repeat 50px 4px }
.quiz-content .form-type-radios label {  display: none }
.quiz-content .form-type-radio .jquery-checkbox {
  background: url("../images/ui-sprite.png") -954px -719px no-repeat;
  display: block;
  width: 16px;
  height: 16px;
  cursor: pointer;
}
.quiz-content .form-type-radio .jquery-checkbox-checked {
  background: url("../images/ui-sprite.png") -954px -789px no-repeat;
  display: block;
  width: 16px;
  height: 16px;
}
.quiz-content .quiz-error {  display: none }
.quiz-content .nochecked .quiz-error {  display: block }
.quiz-content .quiz-error {
  position: absolute;
  font: bold 16px "Droid Sans", Arial, sans-serif;
  color: #fff;
  top: -19px;
  left: 10px;
  padding: 20px 20px 20px 30px;
  background: url("../images/quiz-tooltip.png") no-repeat;
  width: 200px;
}
#quiz_score_possible,
#quiz_score_percent {
  clear: both;
  font: bold 20px "Droid Sans", Arial, sans-serif;
  text-align: center;
}
#quiz-report-form {  font: 14px "Droid Sans", Arial, sans-serif }
em {  font-style: italic }
strong {  font-weight: bold }
em strong,
strong em {
  font-style: italic;
  font-weight: bold;
}
.quiz-question-body li {  list-style: disc }
.page-category .pane-poll-recent {  height: 204px }
.page-category .flat-list,
.page-category .main-node {
  border: none;
  margin: 0px;
  padding: 0px;
}
.page-category .grid_12 .border-wrapper,
.page-taxonomy.section-analyser .grid_12 .border-wrapper {
  background: url("../images/bg_940px.png") repeat-y;
  clear: both;
}
.grid_12 .border-wrapper .clearfixx {
  clear: both;
  margin: 0 0 20px;
}
.page-category .view-footer,
.page-taxonomy .view-footer {
  clear: left;
  float: right;
  margin: -20px 20px 0;
}
.ibis-standart-block .views-row {
  width: 100%;
  padding: 0 0 25px 0;
  margin: 0 0 30px 0;
  border-bottom: 1px dotted #C8C7C6;
}
.view-lottery-view .view-content {
  padding-top: 30px;
  border-top: 1px solid #ddddda;
  margin-top: 15px;
}
.view-lottery-view.ibis-standart-block .views-row {
  padding: 0 0 30px 0;
  margin: 0 0 20px 0;
}
.view-front-4-elements-view .views-row,
.view-blogs-latest-posts .views-row,
.view-global-articles-list .views-row,
.view-front-page-employees .views-row,
.view-ibis-posten-view .views-row,
.view-blog-page .views-row,
.view-blog.ibis-standart-block .views-row,
.view-node-display .views-row,
.view-latest-comments .views-row,
.view-display-id-arrangements .views-row,
.view-display-id-blog_archive_list .views-row,
.sneaky-panel .views-row-last,
.view-rss-feeds-block .views-row {
  margin: 0;
  padding: 0 0 12px;
  border-bottom: none;
}
.pane-calendar-latest-arrangements-calendar-latest-arrangements .views-row {
  padding: 0 0 10px 0;
  margin: 0 0 10px 0;
}
.view-display-id-calendar_arrangements_list.ibis-standart-block .views-row-last {  margin: 0px }
.ibis-standart-block h3 a {
  color: #000;
  /* font: bold 14px/18px "Droid Serif", Arial, sans-serif; */
    font: bold 14px/18px "Droid Sans", Arial, sans-serif;
}
.view-ibis-posten-view.ibis-standart-block h3 a {
  color: #F45017;
  font-size: 16px;
}
.ibis-standart-block .number {  cursor: pointer }
.view-ibis-posten-view.ibis-standart-block span.date {
  color: #000000;
  font-size: 12px;
  border: 0px none;
}
.view-ibis-posten-view.ibis-standart-block .number span {  color: #1c95b8 }
/*------------------------------------------------------------------- Ibibs Posten View*/
.view-ibis-posten-view.ibis-standart-block .date a {
  color: #161616;
  font-size: 13px;
}
.view-ibis-posten-view.ibis-standart-block .date a:hover,
.view-ibis-posten-view.ibis-standart-block .date a:hover span {  color: #c2c2c2 }
.view-ibis-posten-view.ibis-standart-block .date a:hover {  color: #858585 }
.view-ibis-posten-view.ibis-standart-block .date .issue-num-arrow {
  background: url("../images/ui-sprite.png") 0px -124px no-repeat;
  padding-left: 8px;
  color: #161616;
  font-weight: bold;
  font-size: 13px;
  text-transform: none !important;
}
.view-id-ibis_posten_view .views-row .date {
  padding: 0;
  background-image: none;
}
/*----------------------------------------------------------<=END*/
.view-ibis-posten-view.ibis-standart-block h3 a {  display: inline }
.view-ibis-posten-view.ibis-standart-block .number.issue-num-arrow a {  color: #161616 }
.view-ibis-posten-view.ibis-standart-block .number.issue-num-arrow a:hover {  color: #858585 }
.view-ibis-posten-view.ibis-standart-block .views-row-first .date a,
.view-ibis-posten-view.ibis-standart-block .views-row-first .number.issue-num-arrow,
.view-ibis-posten-view.ibis-standart-block .views-row-first .number a,
.view-ibis-posten-view.ibis-standart-block .views-row-first .number.issue-num-arrow a:hover {
  color: #F45017;
  text-transform: lowercase;
  font-weight: normal;
  background: none;
  padding: 0px;
}
.view-ibis-posten-view.ibis-standart-block .views-row-first .date a span {
  color: #F45017;
  padding-left: 0px;
  background: none;
  text-transform: lowercase !important;
  font-size: 12px;
  font-weight: normal;
}
.view-ibis-posten-view.ibis-standart-block .arrow {  padding-right: 5px }
.view-ibis-posten-view.ibis-standart-block .views-row-first .arrow {  display: none }
.view-ibis-posten-view.ibis-standart-block .views-row .arrow {
  color: #1c95b8;
  font-weight: bold;
}
.view-ibis-posten-view.ibis-standart-block .views-row-first .posten-wrapper:hover .date,
.view-ibis-posten-view.ibis-standart-block .views-row-first .posten-wrapper:hover .number {  color: #1c95b8 }
.ibis-standart-block h4 a {  color: #000 }
.ibis-standart-block .category a:hover,
.ibis-standart-block  .category:hover {
  color: #1c95b8;
  border-color: #1c95b8;
}
.ibis-standart-block .number {  font-weight: bold }
.ibis-standart-block img {
  border: 0px solid #d6d6d6;
  margin: 0 0 12px 0;
}
.ibis-standart-block .picture-img {  margin: 0 0 10px 0 }
.ibis-standart-block .picture-img img {
  margin: 0;
  display: block;
}
.ibis-standart-block .file img {  margin: 0 }
.ibis-standart-block .date {
  padding: 0 5px 0 0;
  margin: 0 4px 0 0;
  border-right: 1px solid #F45017;
  color: #F45017;
  font-size: 12px;
}
.date {  text-transform: lowercase }
.view-display-id-calendar_arrangements_list .date {  text-transform: none }
.pane-calendar-latest-arrangements-calendar-latest-arrangements .date,
.view-blogs-latest-posts .date {  border-right: none }
.ibis-standart-block a {
  text-decoration: none;
  /*display: inline-block;*/
}
.ibis-standart-block .category a,
.ibis-standart-block .category {
  color: #f45017;
  font-weight: bold;
  font-size: 12px;
}
.ibis-standart-block .author a {
  color: #f45017;
  font: bold 12px "Droid Sans", Arial, sans-serif;
}
.blog-author {
  font: normal 14px/23px "Droid Sans", Arial, sans-serif;
  color: #000;
  margin: 0 0 10px;
}
.blog-author a {  color: #f45017 }
.view-blogs-latest-posts.ibis-standart-block .author,
.view-arrangements.ibis-standart-block .author,
.view-node-display.ibis-standart-block .author {
  border-right: 1px solid #F45017;
  padding-right: 5px;
}
.node-type-blog .ibis-standart-block .author {  border-right: none }
.view-blog-page .author-name,
.view-node-display .author-name,
.page-blog .author-name,
.author-line .author-name {  color: #F45017 }
.author-line {  display: block }
.page-blogs .view-blog-archive h3 a {
  font-family: "Droid Serif", Arial, sans-serif;
  font-size: 40px;
  font-weight: normal;
  line-height: 44px;
}
.view-blog-page .author-line,
.view-node-display .author-line,
.page-blogs .author-line {
  padding: 0 0 13px 0;
  font-size: 14px;
}
/*.page-frontpage .ibis-standart-block .comments-count {  font-weight: normal }
.view-blogs-latest-posts .hover-wrapper:hover .author a,
.view-blogs-latest-posts .hover-wrapper:hover .date,
.view-blogs-latest-posts .hover-wrapper:hover .author,
.view-blogs-latest-posts .hover-wrapper:hover .comments-count {
  color: #1c95b8;
  border-right-color: #1c95b8;
} */
/*.ibis-standart-block .author a:hover,
.ibis-standart-block .author+.item-list a:hover,
.ibis-standart-block .author:hover {
  color: #1c95b8;
  border-right-color: #1c95b8;
}*/
.ibis-standart-block .field-content a:hover,
.html-block.newsletters-block a:hover {  color: #1c95b8 }
.newsletters-block .wysiwyg-link:hover {  color: #156D87 !important }
.newsletters-block .wysiwyg-link {
  float: none;
}
.newsletters-block p {
  text-align: right;
  padding: 0 0 15px;
}
.ibis-standart-block .author,
.ibis-standart-block .author+.item-list a {
  color: #f45017;
  /*cursor: pointer; */
  font: bold 12px "Droid Sans", Arial, sans-serif;
}
.ibis-standart-block .author+.item-list a.active {  color: #1C95B8 }
.ibis-standart-block .author+.item-list a {  margin-left: 20px }
.ibis-standart-block .author .arrow {
  font: bold 12px "Droid Sans", Arial, sans-serif;
  color: #1C95B8;
  margin-right: 5px;
}
.ibis-standart-block .latest-comment-body {
  color: #1F1F1F;
  line-height: 17px;
  margin-bottom: 5px;
}
.ibis-standart-block .comments-count,
.view-page-section-page .comments-count,
.front-page-tabs .comments-count {
  padding-left: 13px;
  color: #f57244;
  background: url("../images/ui-sprite.png") -790px 2px no-repeat;
  font-weight: bold;
  margin-top: 5px;
  font-size: 12px;
}
.ibis-standart-block h3 {  margin: 5px 0 7px 0 }
.ibis-standart-block .embed {  display: none }
.ibis-standart-block .video {  display: none }
.ibis-standart-block,
.ibis-standart-block p {
  word-wrap: break-word;
  font-family: Helvetica, Arial, sans-serif;
  /*overflow: hidden;*/
}
.ibis-standart-block .arrangements-table {
  table-layout: fixed;
  width: 100%;
  font-family: "Droid Sans Sans", Arial, sans-serif;
  margin-top: 55px;
  overflow: hidden;
}
.col1 {  width: 25% }
.col2 {  width: 75% }
.ibis-standart-block .arrangements-table,
.ibis-standart-block .arrangements-table > tbody,
.ibis-standart-block .arrangements-table > tbody > tr > th,
.ibis-standart-block .arrangements-table > tbody > tr > td {
  border: 0px;
  vertical-align: top;
}
.ibis-standart-block .arrangements-table > tbody > tr > td {  padding: 0px 0px 30px }
.ibis-standart-block .arrangements-table > tbody > tr > th {  padding: 0px 35px 30px 0px }
.ibis-standart-block .arrangements-table > tbody > tr > th,
.ibis-standart-block .arrangements-table > tbody > tr {
  color: #6c6c6c;
  font-size: 16px;
}
.ibis-standart-block .arrangements-table > tbody > tr {  color: #161616 }
.ibis-standart-block .arrangements-table > tbody > tr td {  color: #000 }
.ibis-standart-block .arrangement-author {  color: #f45017 }
.ibis-standart-block p.arrangement-body {
  font-size: 14px;
  line-height: 20px;
  margin-bottom: 30px;
}
.view-blog-page p {  font-size: 14px }
.page-blog  .view-blog-page p {  font-family: "Helvetica", sans-serif }
.ibis-img-460 h3 a {
  font-size: 30px;
  line-height: 30px;
}
.page-blog h3 a,
.view-blog-page.ibis-img-460 h3 a {  letter-spacing: 1px }
.page-blog .ibis-img-460 h3 a {
  font-size: 40px;
  line-height: 44px;
  font-weight: normal;
}
.ibis-img-460 h3 {  margin: 5px 0 15px }
.ibis-img-140 .views-row {
  /*min-height: 90px */;
  overflow: hidden;
  padding: 0 0 25px 0;
}
.view-lottery-view.ibis-img-140 .picture-img img {  margin: 0 }
.ibis-img-140 .picture-img {
  float: left;
  margin: 0 20px 0 0;
}
.ibis-arrow-link a {
  font: bold 12px "Droid Serif", Arial, sans-serif;
  border: none;
  background: url("../images/btn-arrow.png") right 2px no-repeat;
  color: #1c95b8;
  padding-right: 20px;
  text-decoration: none;
}
.ibis-arrow-link a:hover {
  background: url("../images/btn-arrow-hover.png") right 2px no-repeat;
  color: #167692;
}
.pane-menu-menu-category-main-menu {  display: none }
.pane-menu {
  margin: 0 0 35px;
  position: relative;
}
.pane-menu .menu {  width: 100% }
.pane-menu  .menu {
  height: 32px;
  background: url('../images/bg-tabs-menu.png') repeat-x 0 0;
}
.pane-menu  .menu li {
  float: left;
  margin: 0;
}
.pane-menu .menu  a {
  border-right: 1px solid #CCC;
  display: block;
  margin: 1px 0;
  padding: 5px 18px 5px 14px;
  text-decoration: none;
  color: #343432;
  position: relative;
}
.pane-menu .menu a:hover {
  background-color: #efefe7;
  color: #1C95B8;
}
.pane-menu .menu .menu-second-lvl a:hover {  background-color: transparent }
.pane-menu .menu  a.active,
.pane-menu .menu a.active:hover {
  background-color: #1C95B8;
  color: white;
}
.pane-menu .menu .active-arrow {
  bottom: -1px;
  display: block;
  height: 7px;
  left: 50%;
  margin: 0 0 0 -8px;
  position: absolute;
  width: 15px;
}
.pane-menu .menu a.active .active-arrow,
.pane-menu .menu a:hover .active-arrow,
.pane-menu li.active-trail a a.active-arrow {  background: url("../images/ui-sprite.png") -517px -133px }
.pane-menu .menu li a:hover .active-arrow {  background-position: -500px -133px }
.pane-menu .menu-second-lvl {
  position: absolute;
  width: 100%;
  left: 0px;
  background: none;
  display: none;
}
.pane-menu li.parent a.active+.menu-second-lvl.active-parent,
.pane-menu li.parent a.active+.menu-second-lvl,
.pane-menu li.parent:hover a.active+.menu-second-lvl,
.pane-menu.unstatic li.parent:hover a+.menu-second-lvl {  display: block }
.pane-menu li.parent:hover a+.menu-second-lvl {  display: none }
.pane-menu  .menu-second-lvl a.active {
  background-color: transparent;
  color: #1C95B8;
  text-decoration: underline;
}
.pane-menu  .menu-second-lvl a.active:hover {
  text-decoration: none;
  background-color: transparent;
  color: #1C95B8;
}
.pane-menu .menu-second-lvl a {
  padding: 7px 18px 7px 14px;
  text-decoration: none;
  color: #343432;
  display: block;
  border: none;
  margin: 0px;
}
.pane-menu .menu-second-lvl li:hover a {  color: #1C95B8 }
/*******************************************************CSS for Article-page*****************************************************************/
/*.page-node .border-wrapper {
    background: url("../images/bg_940px.png") repeat-y;
    clear: both;
}  */
.pane-custom .custom-border {
  border-bottom: 1px dotted #C8C7C6;
  margin: 0 0 30px;
  padding-top: 14px;
}
.pane-poll-recent+.panel-separator {  clear: both }
.view-node-display .info-wrapper,
.ibis-standart-block .info-wrapper {
  border-top: 1px dotted #C8C7C6;
  border-bottom: 1px dotted #C8C7C6;
  padding: 6px 0 8px;
  margin-bottom: 20px;
  height: 16px;
}
.node-type-arrangementer .ibis-standart-block .info-wrapper {  display: block }
.page-node .view-node-display.ibis-standart-block h1 a,
.page-node .view-arrangements.ibis-standart-block h1 a,
.node-type-page .view-node-display h1,
.page-node .view-node-display.ibis-standart-block h1 {
  font-size: 40px;
  margin: 10px 0 25px;
  display: block;
  line-height: 40px;
  font-weight: normal;
  color: black;
  font-family: "Droid Serif", Arial, sans-serif;
}
.node-type-page .map-region .pane-node-title div {  margin-top: 0 }
.container_12 .page-wrap {  width: 750px }
.page-node .view-arrangements.ibis-standart-block h3 a {  margin-bottom: 10px }
.pane-node-display-node-display .ibis-standart-block .views-row {
  margin: 0;
  padding: 0;
  border: none;
}
.ibis-standart-block h3 a:hover,
.view-articles-by-category .views-row h3 a:hover,
.view-display-id-pane_main_node .block-title a:hover,
.two-column-list .block-title a:hover,
.flat-list .block-title a:hover,
.view-display-id-pane_three_column .block-title a:hover {  color: #1C95B8 }
.jcarousel-skin-front-page-banner {  margin-bottom: -7px }
.page-node .caruseul-wrapper {
  position: relative;
  height: 65px;
}
.page-node .overflow-window {
  margin: 0 auto;
  width: 623px;
  overflow-x: hidden;
  position: relative;
  height: 65px;
  padding-top: 7px;
}
.page-node .width-wrapper .youtube-player,
.page-node .width-wrapper .media-youtube-preview-wrapper,
.page-node .width-wrapper .media-youtube-outer-wrapper,
.page-node.node-type-blog .youtube-player,
.page-node.node-type-blog .media-youtube-preview-wrapper,
.page-node.node-type-blog .media-youtube-outer-wrapper {
  width: 460px!important;
  height: 290px!important;
}
.page-node .view-display-id-slideshow_mini .overflow-window {  width: 355px }
.page-node .jcarousel-control {
  width: 9999px;
  position: absolute;
  left: 0;
}
.page-node .jcarousel-list li {  position: relative }
.page-node .jcarousel-list .description {
  position: absolute;
  bottom: 0px;
  padding: 15px 20px;
  left: 50%;
  margin-left: -44%;
  width: 80%;
  background: url("../images/gallery-alt-hover.png") repeat-y;
  color: #fff;
  font-family: serif;
}
.page-node .overflow-window .img-preview {
  position: relative;
  margin: 0 1px;
  display: block;
  float: left;
}
.page-node .overflow-window .img-preview .arrow {
  position: absolute;
  top: -7px;
  left: 50%;
  margin-left: -5px;
  width: 14px;
  height: 9px;
  background: url("../images/ui-sprite.png") no-repeat -789px -25px;
  display: none;
}
.page-node .overflow-window .img-preview.active-now .arrow {  display: block }
.page-node .overflow-window .img-preview img {
  border: 3px solid #C8C7C6;
  display: block;
  height: 49px;
  width: 81px;
}
.page-node .overflow-window .img-preview.active-now img {  border-color: #1c95b8 }
.section-arrangement .pane-main-picture-or-slideshow {  margin-bottom: 0px }
.pane-embed-after-body {  margin-bottom: 20px }
.pane-main-picture-or-slideshow {  margin: 0 0 30px }
.pane-main-picture-or-slideshow .img-description,
.pane-embed-after-body .img-description,
.pane-quiz-pane .img-description {
  font: 13px/18px sans-serif;
  color: #2c2c2c;
}
.pane-main-picture-or-slideshow img.with-border {  border: 1px solid #000 }
.pane-main-picture-or-slideshow .description span {  color: #fff }
.pane-node-field-issue-author {  margin: 35px 0 25px 0 }
.pane-node-field-issue-author h2,
.pane-node-field-issue-author .pane-content,
.pane-node-field-issue-author .pane-content div {  display: inline }
.pane-node-field-issue-author .field-item,
.pane-node-field-issue-author h2 {
  font: italic 16px/24px "Droid Serif", "Trebuchet MS", Arial, sans-serif;
  color: #161616;
}
.pane-main-picture-or-slideshow .img-owner,
.pane-embed-after-body .img-owner,
.pane-quiz-pane .img-owner {  font: italic 13px/18px  sans-serif }
.my-prev,
.my-next {
  position: absolute;
  top: 16px;
  width: 20px;
  height: 35px;
  cursor: pointer;
}
.my-prev {
  left: 4px;
  background: url("../images/ui-sprite.png") no-repeat -404px -368px;
}
.my-next {
  right: 4px;
  background: url("../images/ui-sprite.png") no-repeat -404px -330px;
}
/*.jcarousel-container.jcarousel-container-horizontal,
.jcarousel-skin-front-page-banner .jcarousel-clip-horizontal{
    width:100%;
}

.jcarousel-skin-front-page-banner .jcarousel-item{
    border:none;
}  */
.pane-node-comments .pane-title,
.pane-node-comment-form .pane-title,
.ibis-focus h2.pane-title {
  font: bold 18px "Droid Serif", Arial, sans-serif;
  color: #626261;
  padding: 15px 0 15px 30px;
  width: 200px;
}
.ibis-focus h2.pane-title {
  font-size: 28px;
  padding-left: 45px;
  display: inline-block;
}
.pane-node-comment-form .pane-title {  padding-top: 40px }
.page-node .pane-node-body {
  margin-bottom: 30px;
  word-wrap: break-word;
}
.page-node .pane-node-comments {  border-top: 1px dotted #C8C7C6 }
.page-node .pane-node-comments .pane-title {  background: url("../images/ui-sprite.png") no-repeat -780px -174px }
.pane-ibis-posten-view-ibis-posten-view .pane-title {
  background: url("../images/ui-sprite.png") no-repeat -400px -556px;
  padding: 6px 0 0px 35px;
}
.pane-node-comment-form .pane-title {  background: url("../images/ui-sprite.png") no-repeat -400px -650px }
.pane-node-comments .pane-content,
.pane-node-comment-form .pane-content {  border-top: 1px dotted #C8C7C6 }
.page-node .comment,
.page-comment-reply .comment {
  margin: 30px 0 0;
  padding: 0 0 25px 40px;
  border-bottom: 1px solid #C8C7C6;
}
/*.comment-form .field-type-text-long {
  margin: 20px 0 0;
}*/
.page-node .comment div,
.page-comment-reply .comment div {
  float: left;
  margin: 0 10px 0 0;
}
.page-node .comment .comment-number,
.page-comment-reply .comment .comment-count {
  font: bold 14px  "Droid Sans", Arial, sans-serif;
  color: #c1c1c1;
}
.page-node .comment .author,
.page-comment-reply .comment .author {
  width: 95px;
  word-wrap: break-word;
  font: bold 14px  "Droid Sans", Arial, sans-serif;
  color: #f7a547;
  text-decoration: none;
}
.page-node .comment .body,
.page-comment-reply .comment .body {
  width: 480px;
  font: 14px Arial, sans-serif;
  word-wrap: break-word;
}
.page-node.node-type-blog .comment .body,
.page-node .width-wrapper .comment .body {  width: 260px }
.page-node .comment .links,
.page-comment-reply .comment .links {  float: right }
.page-node .comment .links li,
.page-comment-reply .comment .links li {
  float: left;
  margin: 0 10px;
}
.page-node .comment-form,
.page-comment-reply .comment-form {
  width: 460px;
  margin-left: 40px;
}
.page-node .spage-center .comment-form,
.page-comment-reply .spage-center .comment-form,
.page-node .border-wrapper-three .comment-form,
.page-comment-reply .border-wrapper-three .comment-form {
  width: 378px;
  margin-top: 30px;
}
.node-type-articles .comment-form {
  margin-left: 40px;
  overflow: hidden;
}
.node-type-articles .width-wrapper-node .comment-form {  margin-top: 20px }
/*.vl-wrapper .comment-form {  margin: 0 }*/
.page-node .comment-form .form-type-textarea label,
.page-comment-reply .comment-form .form-type-textarea label {  display: none }
.form-item,
.form-actions {  margin: 0px }
.spage-center .input-wrapper,
.border-wrapper-three .input-wrapper {
  background: url("../images/comments-form-input-bg.png") no-repeat 0 -42px;
  margin: 10px 0 20px;
}
.input-wrapper {
  background: url("../images/comments-form-input-bg.png") no-repeat 0 0px;
  margin: 10px 0 20px;
}
.page-node .comment-form .form-type-textfield,
.page-comment-reply .comment-form .form-type-textarea {
  /*margin-bottom: 20px;*/
  /*position: relative;*/
  zoom: 1;
}
.field-type-text-long.form-wrapper label.error,
.page-node .comment-form .form-type-textfield label.error,
.page-comment-reply .comment-form .form-type-textarea label.error {
  font-size: 11px;
  color: #f00;
}
.field-type-text-long.form-wrapper label.error {
  position: absolute;
  bottom: -16px;
  font-weight: normal;
}
.page-node .comment-form .input-wrapper input,
.page-comment-reply .comment-form .input-wrapper input {
  background: transparent;
  width: 440px;
  height: 24px;
  border: 0px;
  font: 14px "Droid Sans", Arial, Helvetica, sans-serif;
  color: #7b7b7b;
  padding: 7px 0 7px 0;
  margin-left: 10px;
  outline: none;
}
.page-node .spage-center .comment-form .input-wrapper input,
.page-comment-reply .spage-center .comment-form .input-wrapper input,
.page-node .border-wrapper-three .comment-form .input-wrapper input,
.page-comment-reply .border-wrapper-three .comment-form .input-wrapper input {  width: 358px }
.page-comment-reply .comment-form {  margin-top: 30px }
.page-node .comment-form .form-type-textfield label,
.page-comment-reply .comment-form .form-type-textfield label {
  color: #484848;
  font: 16px "Droid Sans", Arial, sans-serif;
}
.page-node .comment-form textarea,
.page-comment-reply .comment-form textarea {
  border: 0px;
  overflow: auto;
  outline: none;
  padding: 10px;
  resize: none;
  /*width: 458px;*/
  /*height: 190px;*/
  font: 14px "Droid Sans", Arial, sans-serif;
}
.form-textarea-wrapper textarea {  border: 0 }
.text-format-wrapper label {  display: none }
.text-format-wrapper .form-item {  margin: 0px }
.field-type-text-long.form-wrapper {
  position: relative;
  border: 1px solid #adadac;
  /*width: 458px;;;
  padding: 1px;*/
  margin-bottom: 10px;
  margin-left: 1px;
}
.corner {
  position: absolute;
  width: 5px;
  height: 5px;
  background: #fff url("../images/comment-form-sprite.png") no-repeat;
}
.top-left {
  left: -1px;
  top: -1px;
  z-index: 100;
}
.top-right {
  right: -1px;
  top: -1px;
  background-position: -5px 0px;
  z-index: 100;
}
.bottom-left {
  left: -1px;
  bottom: -1px;
  background-position: 0px -5px;
}
.bottom-right {
  right: -1px;
  bottom: -1px;
  background-position: -5px -5px;
}
/*-----------------------------------------*/
.width-wrapper-node {
  width: 680px;
  position: relative;
  padding-right: 20px;
}
.page-taxonomy .border-wrapper {
  overflow: visible;
  background-position: 10px 0;
}
.page-taxonomy .border-wrapper {
  overflow: visible;
}
/* remove overflow:hidden for employees block  */

.border-wrapper,
.towcolright-layout {
  clear: both;
  background: url("../images/bg-two-col.png") repeat-y;
  zoom: 1;
}

#global .field-name-field-cpr-nummer2 label {
    display: none;
}

#edit-field-donation-country {
    display: inline-block;
    margin-bottom: 15px;
}

.ibis-donation-form-tabs .active-title h3 {
    display: block;
}

.form-wrapper .form-item .form-autocomplete {
    background: transparent url("../images/bg-input-default.png") no-repeat;
    width: 308px;
}

.category-page-layout .border-wrapper {
  background-position: 10px 0;
}
.category-page-layout .tow-colum {
  background: url('../images/bg-two-col.png') repeat-y -230px 0;
}

.category-page-layout,
.category-page-layout .border-wrapper,
.towcolright-layout {  /*background-position: 10px 0; _NO__DOTCOMMA__AFTER__*/ }
.content-footer a {  display: block }
.page-employees .width-wrapper,
.node-type-employees .width-wrapper {
  width: 440px;
  padding: 0;
  border: none;
  position: relative;
}
.page-node .pane-node-comment-form .form-actions,
.page-comment-reply .comment-form .form-actions,
.page-comment .comment-form .form-actions,
.page-comment .confirmation .form-actions .form-submit,
.page-node .confirmation .form-actions .form-submit,
.comment-form .form-actions,
.page-newsletter .content-area .form-submit {
  background-color: #1C95B8;
  margin-bottom: 10px;
  display: block;
  float: right;
}
.page-newsletter .content-area .form-submit {
  float: none;
  border: none;
  padding: 5px;
  color: white;
  cursor: pointer;
}
.pane-node-comments .clearfix {  clear: both }
.page-node .pane-node-comment-form .form-actions input,
.page-comment-reply .comment-form .form-actions input,
.page-comment .comment-form .form-actions input,
.page-comment .confirmation .form-actions input,
.page-node .confirmation .form-actions input {  cursor: pointer }
.page-node .pane-node-comment-form .form-actions:hover,
.page-comment-reply .comment-form .form-actions:hover,
.page-comment .comment-form .form-actions:hover,
.comment-form .form-actions:hover,
.page-newsletter .content-area .form-submit:hover {  background: #167692 }
.page-node .pane-node-comment-form .form-actions:hover .form-submit,
.page-comment-reply .comment-form .form-actions:hover .form-submit,
.page-comment .comment-form .form-actions:hover .form-submit,
.page-comment .confirmation .form-actions:hover .form-submit,
.page-node .confirmation .form-actions:hover .form-submit,
.page-node .pane-node-comment-form .form-submit,
.page-comment-reply .comment-form .form-submit,
.page-comment .comment-form .form-submit,
.page-comment .confirmation .form-submit,
.page-node .confirmation .form-submit,
.comment-form .form-submit {
  padding: 9px 29px 10px 10px;
  background: #1c95b8 url("../images/form-btn.png") no-repeat 97% center;
  font: bold 14px "Droid Sans", Arial, sans-serif;
  color: white;
  border: none;
  margin: 0 5px 0 0;
  cursor: pointer;
  float: right;
  margin-bottom: 10px;
}
.page-node .pane-node-comment-form .comment-form .form-actions .ajax-progress {
    clear: both;
    width: 100%;
    position: absolute;
    bottom: 0;
    right: 0;
}
.page-node .pane-node-comment-form .comment-form .form-actions .ajax-progress .throbber {
    float: none;
    display: inline-block;
}

.page-node .pane-node-comment-form .comment-form .form-actions .ajax-progress .message {
    display: inline-block;
}
/* Captcha */
.page-node .pane-node-comment-form .comment-form .form-actions,
.page-node .pane-node-comment-form .comment-form .form-actions:hover,
.page-node .pane-node-comment-form .comment-form .captcha .form-actions:hover .form-submit {
  background: none;
  width: 100%;
  text-align: center;
  padding-bottom: 20px;
  position: relative;
}
.page-node .pane-node-comment-form .comment-form .form-actions .captcha {
  margin-top: 5px;
}
.page-node .pane-node-comment-form .captcha .fieldset-legend {
  color: #484848;
  cursor: default;
  font: 16px "Droid Sans", Arial, sans-serif;
  line-height: 2;
}
.page-node .pane-node-comment-form .captcha .fieldset-description {
  margin-bottom: 5px;
}
.page-node .pane-node-comment-form .captcha .form-item-captcha-response label {
  font-size: 14px;
}
.page-node .pane-node-comment-form .captcha .form-item-captcha-response .form-required {
  display: none;
}
.page-node .pane-node-comment-form .captcha ~ .form-submit {
  background-position: 50px 8px;
  padding-right: 40px;
}
.page-node .pane-node-comment-form .comment-form .form-actions:hover .form-submit {
  background: #167692 url("../images/form-btn.png") no-repeat 97% center;
}
.page-node .pane-node-comment-form .comment-form .form-actions:hover .form-submit:hover {
  background: #167692 url("../images/form-btn-hover.png") no-repeat 97% center;
}
/* end */
.page-comment .confirmation,
.page-node .confirmation {
  margin-left: 40px;
  margin-right: 40px;
}
.page-node .confirmation {
  margin-top: 30px;
  overflow: hidden;
}
.page-comment .confirmation .form-radios .form-item label,
.confirmation .form-radios .form-item label {  display: inline }
.pane-related-links-related-links {
  border-bottom: 1px dotted #bdbcbb;
  margin-bottom: 20px;
  padding-bottom: 10px;
}
.pane-related-links-related-links-view .pane-title,
.pane-related-content-view-related-content-view .pane-title {
  font: 20px "Droid Serif", Arial, sans-serif;
  color: #6c6c6a;
}
.page-node .view-display-id-related_content_view,
.view-related-links {
  padding-bottom: 20px;
  border-bottom: 1px dotted #C8C7C6;
  margin-bottom: 30px;
}
.page-node .view-display-id-related_content_view .views-row {  margin: 10px 0 10px 5px }
.page-node .view-related-content-view .date {
  padding: 0 5px 0 0;
  margin: 0 4px 0 0;
  border-right: 1px solid #F45017;
  color: #F45017;
}
.page-node .view-related-content-view .title a {
  /* font: 12px/16px "Droid Serif", sans-serif;*/
  color: #1f1f1f;
  text-decoration: none;
  word-wrap: break-word;
}
.page-node .view-related-content-view .title a:hover {  color: #1C95B8 }
.view-related-links .views-row {
  margin: 10px 0 10px 5px;
  color: #1C95B8;
  font: 13px "Droid Sans", Arial, sans-serif;
}
.view-related-links .views-row>div>div {  float: left }
.view-related-links .views-row .content,
.newsletters-block .pane-content li {
  display: inline-block;
  width: 203px;
  float: none;
  padding-left: 15px;
  background: url("../images/ui-sprite.png") no-repeat -966px -888px;
}
.view-related-links .views-row a {
  text-decoration: none;
  font-size: 13px;
  color: black;
}
.view-related-links .views-row a:hover {  color: #1C95B8 }
.toolbar-pane {
  position: absolute;
  top: 8px;
  right: 18px;
  width: 395px;
  z-index: 100;
}
.width-wrapper .toolbar-pane {  width: 220px }
.addthis_toolbox.pluses {  float: left }
.toolbar-pane .pane-title {  display: none }
.toolbar-pane .toolbar-item {
  width: 25px;
  height: 20px;
  float: right;
  margin-left: 20px;
  z-index: 1000;
  cursor: pointer;
}
.toolbar-pane .pane-content {
  float: right;
  width: 188px;
}
.toolbar-pane .addthis_toolbox {  float: left }
.toolbar-pane .toolbar-item.email:hover {  background-position: -236px -355px }
.toolbar-pane input.print:hover {  background-position: -275px -355px }
.toolbar-pane input.print {
  background: url("../images/ui-sprite.png") no-repeat -75px -355px;
  text-indent: -9000px;
  text-transform: capitalize;
  border: none;
  width: 25px;
  background-color: transparent;
  cursor: pointer;
}
.toolbar-pane .toolbar-item.pluses {
  background: url("../images/ui-sprite.png") no-repeat 0px -355px;
  position: relative;
  z-index: 1;
  width: 460px;
}
.toolbar-pane .toolbar-item.pluses:hover {  background-position: -200px -355px }
.toolbar-pane .toolbar-item .pluses-wrapper {
  top: 25px;
  display: none;
  height: 100px;
  position: absolute;
  left: -25px;
}
.toolbar-pane .fb-root {  display: block }
.toolbar-pane .toolbar-item.email {
  background: url("../images/ui-sprite.png") no-repeat -36px -355px;
  display: block;
  font-size: 0px;
  margin: 0;
}
/*******************************************************CSS for Blog-page*****************************************************************/
.page-blog .pane-custom .custom-border,
.node-type-blog .pane-custom .custom-border {
  border-bottom: none;
  padding-top: 10px;
}
.border-wrapper-three {
  clear: both;
  background: url("../images/bg-three-col-blog.png") repeat-y;
  /*overflow: hidden;*/
}
.border-wrapper-right-sidebar {
  clear: both;
  overflow: hidden;
}
.view-blog-page.ibis-standart-block .author,
.view-node-display.ibis-standart-block .author {
  font: 14px "Droid Sans", Arial, sans-serif;
  padding: 0 5px 0 0;
  margin: 10px 0;
  color: #000;
}
.view-blog-page.ibis-standart-block .author a,
.view-node-display.ibis-standart-block .author a {  font: 14px "Droid Sans", Arial, sans-serif }
.view-blog-page.ibis-standart-block .author .username,
.view-node-display.ibis-standart-block .author .username {
  font: 14px "Droid Sans", Arial, sans-serif;
  color: #f57a4f;
  padding-left: 5px;
}
.node-type-blog .border-wrapper-three {  margin: 0 0 20px 0 }
/*--------------------------------------------------------------------- [ New features]*/
.section-employees .vl-wrapper {  margin-bottom: 57px }
.page-blog .border-wrapper-three {  margin-bottom: 20px }
.page-blog .ibis-img-460 {  position: relative }
.page-blog .ibis-img-460 .views-row-last {  padding-bottom: 0px }
.section-employees .vl-wrapper .item-list {
  /*position: absolute; */
  right: 0px;
  bottom: -30px;
  width: 445px;
  height: 25px;
}
.section-employees .vl-wrapper .item-list {  width: 459px }
/*.section-employees .employees-list-header {  margin-bottom: 40px }*/
.section-employees .employees-list {  position: relative }
.section-employees .employees-list .top-pager .item-list {
  overflow: hidden;
  top: -43px;
  height: 40px;
}
.page-node .pager {  display: none }
.page-blog .ibis-img-460 .item-list .pager {  margin-top: 19px }
/*.page-blog .bottom-less-space div {
    margin-bottom: 13px;
}*/
.page-blog .bottom-less-space a,
.page-blog .bottom-less-space a img {  display: block }
.ibis-standart-block .author .username:hover,
.ibis-standart-block .year:hover,
.ibis-standart-block .year.active-year {  color: #1c95b8 }
.ibis-standart-block .year.author {
  font: bold 14px "Arial", Arial, sans-serif;
  margin: 10px 0;
}
.view-blog-page.ibis-standart-block .ibis-arrow-link.info-wrapper {
  margin-top: 20px;
  font-weight: normal;
}
.view-display-id-bloggers_list.ibis-standart-block .author,
.view-display-id-bloggers_list.ibis-standart-block .author a {  font-size: 14px }
.view-display-id-blog_archive.ibis-standart-block .date {
  font-weight: bold;
  border-right: none;
}
.view-blog-page.ibis-standart-block .views-row-first h3 {  margin-top: 0px }
/*-------------------------------------- [ New features for blogger detail shadow ] */
.blogger-details-bg h3 {  margin-bottom: 2px }
.blogger-details-bg h3,
.blogger-details-bg h4 {  word-wrap: break-word }
.blogger-details-bg {
  background: url("../images/blogger-block-shadow.png")  no-repeat -230px 0px;
  padding: 12px 0 0 0;
  position: relative;
  left: -5px;
  width: 230px;
  margin-bottom: 41px;
}
.blogger-details-bg .pane-content {
  position: relative;
  background: url("../images/blogger-block-shadow.png") repeat-y  -460px 0px;
}
.blogger-details-bg .views-row {
  padding: 11px 15px 29px;
  margin: 0px 0px 20px;
  background: url("../images/blogger-block-shadow.png") no-repeat  0px bottom;
  position: relative;
  bottom: -12px;
  width: 200px;
}
.view-blog-archive > h3 {  display: none }
.view-blog-archive .views-row p {  padding: 0 0 20px 0 }
.picture-img img {  border: 1px solid #D6D6D6 }
/*-----------------------------------------------------------------------<== [ END ]*/
.view-blogger-details a {  text-decoration: none }
.view-blogger-details a h3,
.view-blogger-details .country a {
  font: bold 14px "Droid Sans", Arial, sans-serif;
  margin-left: 26px;
  color: #000;
}
.view-blogger-details .country a {  font-size: 13px }
.view-blogger-details .img-picture {  margin: 0 0 20px 30px }
.view-blogger-details .img-picture img {  border: 1px solid #D6D6D6 }
.view-blogger-details h4 {  margin-left: 25px }
.view-blogger-details .name-icon {
  background: url("../images/ui-sprite.png") no-repeat -780px -550px;
  width: 21px;
  height: 14px;
  float: left;
  margin-right: 5px;
}
.view-blogger-details .country {
  margin: 10px 0 15px;
  display: inline-block;
  background: url("../images/ui-sprite.png") no-repeat -780px -591px;
}
.view-blogger-details p {
  font-style: italic;
  line-height: 18px;
}
.view-display-id-calendar_arrangements_list .date {
  border-right: none;
  font-weight: bold;
}
.node-type-arrangements .panel-separator {  clear: both }
.pane-node-field-start-date .field,
.pane-node-field-place .field,
.pane-node-field-author .field {  font: 16px "Droid Sans", Arial, sans-serif }
.pane-node-field-author .field {  color: #F45017 }
.node-type-arrangements .pane-node-field-place .pane-title,
.node-type-arrangements .pane-node-field-start-date .pane-title,
.node-type-arrangements .pane-node-body .pane-title,
.node-type-arrangements .pane-node-field-author .pane-title {
  width: 90px;
  float: left;
  color: #6C6C6C;
  font: 16px "Droid Sans", Arial, sans-serif;
  display: block;
  word-wrap: break-word;
}
.node-type-arrangements .pane-node-field-place .pane-content,
.node-type-arrangements .pane-node-field-start-date .pane-content,
.node-type-arrangements .pane-node-body .pane-content,
.node-type-arrangements .pane-node-field-author .pane-content {
  display: block;
  width: 570px;
  margin-left: 90px;
}
.node-type-arrangements .pane-node-field-place,
.node-type-arrangements .pane-node-field-start-date,
.node-type-arrangements .pane-node-body,
.node-type-arrangements .pane-node-field-author {  margin-bottom: 20px }
.pane-main-picture-or-slideshow .field-label {  display: none }
.calendar-list-header .pane-title {
  font: 44px "Droid Serif", Arial, sans-serif;
  margin: 0 0 20px;
}
.employees-list-header .pane-title {
  font: 40px/44px "Droid Serif", Arial, sans-serif;
  margin: 25px 0 25px;
}
.calendar-list-header .pane-content {
  font: 16px "Droid Serif", Arial, sans-serif;
  padding: 0 0 22px 0;
  margin: 0 0 30px 0;
  border-bottom: 1px dotted #C8C7C6;
  line-height: 25px;
}
.employees-list-header .pane-content {
  font: 16px "Droid Sans", Arial, sans-serif;
  padding: 0 0 22px 0;
  /*margin: 0 0 45px 0;*/
  line-height: 25px;
}
.back-to-list {
  float: left;
}
.back-to-list .pane-content a {
  font: bold 14px/2.4 "Droid Sans", Arial, sans-serif;
  background: url("../images/ui-sprite.png") -400px -770px no-repeat;
  padding: 0 0 0 40px;
  display: block;
  color: #393A3A;
}
.spage-center {  position: relative }
.vl-wrapper {  background: url("../images/bg-three-col.png") repeat-y }
.page-employees .spage-center .toolbar-pane,
.node-type-employees .spage-center .toolbar-pane,
.node-type-page .toolbar-pane,
.node-type-arrangementer .toolbar-pane {
  position: static;
  width: 100%;
  padding: 8px 0;
  border-top: 1px dotted #C8C7C6;
  border-bottom: 1px dotted #C8C7C6;
  overflow: hidden;
}
.node-type-page .toolbar-pane {  margin-bottom: 20px }
.spage-center .toolbar-pane {  right: 0px }
.spage-center .toolbar-item {  float: right }
.clearboth {  clear: both }
/* Employees view */
.view-employees-content-view .employee-wrap {  margin: 20px 0px 30px 0px }
.view-employees-content-view .employee-wrap .employee-photo,
.view-employees .employee-wrap .employee-photo {  float: left }
.employee-photo.with-border img {  border: 1px solid #000 }
.view-employees .employee-wrap .employee-photo {  margin: 0 20px 0 0 }
.view-employees .employee-wrap .employee-photo img {  border: 1px solid #d6d6d6 }
.view-employees-content-view .employee-wrap .employee-info,
.view-employees .employee-wrap .employee-info {
  float: left;
  width: 278px;
}
.view-employees .employee-wrap .employee-info {
  width: 360px;
  word-wrap: break-word;
}
.view-employees-content-view img,
.view-employees .picture-img {
  float: left;
  margin-right: 20px;
}
.view-employees-content-view .employee-wrap .e-title,
.view-employees-content-view .employee-wrap .e-name,
.view-employees-content-view .employee-wrap .e-work-area,
.view-employees-content-view .employee-wrap .e-country,
.view-employees-content-view .employee-wrap .e-phone,
.view-employees-content-view .employee-wrap .e-email,
.view-employees .e-title,
.view-employees .e-name,
.view-employees .e-work-area,
.view-employees .e-country,
.view-employees .e-phone,
.view-employees .e-email {  font-family: "Droid Sans", "Trebuchet MS", Arial, sans-serif }
.view-employees-content-view .employee-wrap .e-name,
.view-employees .e-name {
  font-size: 16px;
  font-weight: bold;
  color: #000;
}
.view-employees .e-name {  font-size: 14px }
.view-employees .e-name a {
  text-decoration: none;
  color: #000;
}
.view-employees-content-view .employee-wrap .e-title,
.view-employees-content-view .employee-wrap .e-work-area,
.view-employees-content-view .employee-wrap .e-country {
  font-size: 14px;
  font-weight: normal;
}
.view-employees .e-title,
.view-employees-content-view .employee-wrap .e-title,
.view-employees-donation .e-title {  margin: 0 0 8px 0 !important }
.view-employees-content-view .employee-wrap + .e-phone,
.view-employees-donation + .e-phone,
.view-employees .e-country + .e-phone {  margin: 8px 0 0 }
.view-employees-content-view strong,
.view-employees-donation strong {
  font-weight: normal;
  font-style: normal;
}
.view-employees .e-title,
.view-employees .e-work-area,
.view-employees .e-country {  font-size: 13px }
.view-employees .e-title a {
  text-decoration: none;
  color: #000;
}
.view-employees-content-view .employee-wrap .e-work-area,
.view-employees-content-view .employee-wrap .e-country,
.view-employees .employee-wrap .e-country,
.view-employees  .employee-wrap .e-work-area {  margin: 0 }
.view-employees-content-view .employee-wrap .e-country,
.view-employees-content-view .employee-wrap .e-phone,
.view-employees-content-view .employee-wrap .e-email {  font-size: 14px }
.view-employees .employee-wrap .e-country,
.view-employees .employee-wrap .e-phone,
.view-employees .employee-wrap .e-email {  font-size: 13px }
.view-employees-content-view .employee-wrap .e-email a,
.view-employees .employee-wrap .e-email a,
.view-employees .employee-info a,
.view-employees-content-view .employee-info a {  text-decoration: none }
.view-employees .picture-img {
  height: 120px;
  font-size: 14px;
}
.view-employees .wrapper {
  float: left;
  width: 340px;
}
.view-employees .views-row {
  padding: 20px 0 20px;
  border-bottom: 1px dotted #C8C7C6;
  font: 13px "Droid Sans";
}
.view-employees .views-row.views-row-first {  border-top: 1px dotted #C8C7C6 }
.view-employees-content-view .phone strong,
.view-employees-content-view .email strong {
  font: bold 16px "Droid Sans", Arial, sans-serif;
  color: #000;
}
.view-employees-content-view h4,
.view-employees-content-view .phone,
.view-employees-content-view .email {
  font: 14px "Droid Sans", Arial, sans-serif;
  margin-bottom: 20px;
}
.view-employees-content-view .email a,
.view-employees .email a {
  color: #f57a4f;
  text-decoration: none;
}
.view-employees-content-view p {  clear: both }
.view-employees h3,
.view-employees h4,
.view-employees .phone {
  /*margin-bottom: 10px;*/
  word-wrap: break-word;
}
.view-employees .title {  margin: 0px }
.view-employees .title a {
  color: #000;
  text-decoration: none;
}
/*///////////////////////////////////////////DONATION/////////////////////////////////*/
.pane-main-form .pane-title {  display: none }
.pane-main-form .form-item,
.pane-main-form .form-actions {  margin: 0px }
.pane-main-form .ibis-donation-tabs {
  height: 29px;
  padding-top: 10px;
}
#donation-pane .border-wrapper {  background: none !important }
#donation-pane .pane-page-title .pane-content h1 {
  font: normal 40px "Droid Serif", Arial, Helvetica, sans-serif;
  color: #303030;
  text-align: left;
}
.pane-main-form {  margin-top: 20px }
.pane-main-form form {  padding: 30px 0 10px 20px }
.pane-main-form .ibis-donation-tabs li {
  float: left;
  margin-right: 1px;
}
.pane-main-form .ibis-donation-tabs a {
  padding: 10px;
  background: #f7921e;
  font: bold 16px "Droid Sans", Arial, sans-serif;
  color: #fff;
  text-decoration: none;
  position: relative;
}
.pane-main-form .ibis-donation-tabs a .arrow {
  position: absolute;
  bottom: -7px;
  left: 50%;
  margin-left: -7px;
  width: 13px;
  height: 7px;
  background: url("../images/ui-sprite.png") no-repeat -519px -204px;
  display: none;
  z-index: 100;
}
.pane-main-form .ibis-donation-tabs li.active {
  position: relative;
  bottom: 5px;
}
.pane-main-form .ibis-donation-tabs li.active a {
  padding: 15px 20px;
  background: #f45017;
}
.pane-main-form .ibis-donation-tabs .active a .arrow {
  display: block;
  z-index: 100;
}
.pane-main-form .ibis-donation-form-tabs .wrapper-desc {
  margin: 0 0 20px 0;
  padding-right: 20px;
}
.ibis-donation-form-tabs {  background-color: #fff }
.ibis-donation-form-tabs .selectBox,
.selectBox-dropdown-menu li {  cursor: pointer }
.pane-main-form .amount-changer {  position: relative }
.pane-main-form .selectBox-dropdown {
  float: none;
  margin: 10px 0;
}
.pane-main-form .field-group {  margin-left: 50px }
.pane-main-form .group-choose-support {  overflow: hidden }
.pane-main-form .form-item-amount {
  float: left;
  margin-top: 6px;
  height: 40px;
}
.pane-main-form .form-item-amount > label {
  margin-bottom: 10px;
  font: bold 16px "Droid Sans", Arial, sans-serif;
  color: #303030;
}
.pane-main-form .form-radios label {
  color: #000;
  font: normal 13px "Helvetica", Arial, sans-serif;
}
.pane-main-form .form-item-another-amount {
  display: inline-block;
  float: left;
}
.pane-main-form .form-item-another-amount label {
  float: left;
  margin: 30px 10px 0 0;
}
.pane-main-form .form-item-another-amount label {
  float: left;
  margin: 13px 5px 0 0;
  font: normal 12px "Droid Serif", Arial, sans-serif;
}
.pane-main-form .form-item-another-amount input {
  color: #7d7d7d;
  font-family: "Helvetica", Arial, sans-serif;
  font-size: 13px;
  font-weight: bold;
  width: 60px;
  text-shadow: #fff 1px 1px 2px;
}
.pane-main-form .group-information .field-type-text,
.pane-main-form .group_payment_information .field-name-field-reg-number,
.pane-main-form .group_payment_information .field-name-field-kontonummer,
.pane-main-form .group_payment_information .field-name-field-cpr-nummer,
.pane-main-form .group_payment_information .field-name-field-cpr-nummer2,
.group_cpr_contribution_wrapper .field-name-field-cpr-number-contribution,
.group_cpr_contribution_wrapper .field-name-field-cpr-number-suffix-contrib {
  margin-bottom: 15px;
  float: left;
}
#edit-field-mobile-phone,
#edit-field-phone {
  margin-bottom: 30px;
}

.pane-main-form .group_payment_information .field-name-field-cpr-nummer,
.pane-main-form .field-name-field-cpr-number-contribution {
  clear: left;
  float: left;
  margin: 0 20px 20px 0;
  width: 111px;
}
.pane-main-form .group_payment_information .field-name-field-cpr-nummer label {  width: 115px }
.pane-main-form .field-name-field-reg-number {  width: 126px }
.pane-main-form .field-name-field-kontonummer {  width: 235px }
.pane-main-form .field-name-field-cpr-nummer2,
.pane-main-form .field-name-field-cpr-number-suffix-contrib,
.group_cpr_contribution_wrapper .field-name-field-cpr-number-suffix-contrib {  width: 80px }
.pane-main-form .field-name-field-cpr-nummer2 .field-name-field-cpr-nummer2-wrraper {  padding: 0 }
.pane-main-form .field-name-field-cpr-nummer2 .field-name-field-cpr-nummer2-wrraper input,
.pane-main-form .field-name-field-cpr-number-suffix-contrib input {  width: 69px }
.pane-main-form .field-name-field-cpr-nummer2 label,
.group_cpr_contribution_wrapper .field-name-field-cpr-number-suffix-contrib label {
  width: 170px;
  visibility: hidden;
}
#global .field-name-field-cpr-nummer label { display: none }
.pane-main-form .group_payment_information .field-name-field-reg-number,
.pane-main-form .group_payment_information .field-name-field-cpr-nummer {  margin: 0 20px 20px 0 }
.pane-main-form .group_payment_information .tooltip-anchor {  top: 10px }
.group_payment_information {  position: relative }
.html-desc {
  position: absolute;
  right: -359px;
  top: 30px;
  width: 230px;
  font-size: 12px;
  font-weight: bold;
  display: block;
}
.pane-main-form .group_payment_information,
.pane-main-form .group_cpr_contribution_wrapper {
  border-bottom: 1px dotted #CCCCCC;
  border-top: 1px dotted #CCCCCC;
  margin: 0 0 30px;
  padding: 30px 0 10px;
  width: 600px;
}
.pane-main-form .group_cpr_contribution_wrapper {
  overflow: hidden;
}
.pane-main-form .field-group-format.group-information {
  overflow: hidden;
  margin-top: 30px;
}
.pane-main-form .group-information label,
.pane-main-form .group_payment_information label,
.pane-main-form .group_cpr_contribution_wrapper .field-name-field-cpr-number-contribution label,
.pane-main-form .field-name-field-cpr-number-suffix-contrib label,
.ibis-donation-form-tabs .active-title h3 span{
  font: bold 14px "Droid Sans", Arial, sans-serif;
  color: #303030;
  margin-bottom: 3px;
  display: block;
}
.pane-main-form .group-information .form-required {  color: #000 }
.pane-main-form .group-information label.error,
.pane-main-form .group_payment_information label.error {
  position: absolute;
  font-size: 12px;
  font-weight: normal;
  color: #FF0000;
}
.pane-main-form .field-name-field-first-name,
.pane-main-form .field-name-field-mobile-phone {
  float: left;
  margin-right: 20px;
}
.pane-main-form .field-name-field-postal-code,
.pane-main-form  .field-address,
.field-city {
  float: right;
  margin-right: 20px;
}
.pane-main-form .field-name-field-postal-code,
.pane-main-form .field-name-field-mobile-phone {  clear: both }
.pane-main-form .field-name-field-first-name input,
.pane-main-form .field-name-field-last-name input {  width: 235px }
.pane-main-form .field-name-field-address input,
.pane-main-form .field-name-field-e-mail input {  width: 308px }
/*.pane-main-form .field-name-field-e-mail input,
.pane-main-form .tooltip-anchor{
    float:left;
}*/
.pane-main-form .field-name-field-postal-code input {  width: 80px }
.pane-main-form .field-name-field-mobile-phone input,
.pane-main-form .field-name-field-phone input {  width: 134px }
.pane-main-form .field-group-div label.option,
.pane-main-form .field-name-field-city input {
  width: 188px;
  margin: 0;
}
.pane-main-form .group_contact_information {
  clear: both;
  padding: 0 0 40px 0;
}
#christmas .group-choose-support,
#erhvervspartner .group-choose-support,
#global .group-choose-support {
  overflow: visible;
}
#global .amount-changer div.radio,
#global .amount-changer label.option,
#christmas .amount-changer div.radio,
#christmas .amount-changer label.option,
#erhvervspartner .amount-changer div.radio,
#erhvervspartner .amount-changer label.option {
  display: inline-block;
  vertical-align: top;
}
#global .form-type-radio,
#christmas .form-type-radio,
#erhvervspartner .form-type-radio {
  margin-bottom: 10px;
}

#global .field-group-div label.option,
#christmas .field-group-div label.option,
#erhvervspartner .field-group-div label.option {
  width: 166px;
}
/*--------------------------------------------------------------input forms styles*/
.pane-main-form .form-type-textfield input {
  padding: 9px 5px 8px;
  border: 0;
  background: transparent url("../images/bg-input-default.png") no-repeat;
  height: 16px;
  margin-top: 5px;
}
.pane-main-form .form-item-another-amount .amount-input-wrpaer {
  position: absolute;
  float: none;
  right: 3px;
  bottom: -9px;
}
.pane-main-form .form-type-textfield,
.pane-main-form .amount-input-wrpaer {
  background: transparent url("../images/bg-input-default.png") no-repeat 100% 100%;
  padding-right: 10px;
  position: relative;
}
.pane-main-form .form-item-another-amount {
  background: none !important;
}
.pane-main-form  .form-item-another-amount + span {
  margin-top: 13px;
  display: block;
  float: left;
  color: #7D7D7D;
  font-family: "Helvetica", Arial, sans-serif;
  font-size: 13px;
  font-weight: bold;
}
.pane-main-form .active-input-parent {  background: url("../images/bg-input-focus.png") no-repeat 100% 100% }
.pane-main-form .form-type-textfield .input-focus {  background: url("../images/bg-input-focus.png") no-repeat 0 0 }
.pane-main-form .field-with-errors {  background: url("../images/bg-input-error.png") no-repeat 100% 100% }
.pane-main-form .form-type-textfield label.error {  font-size: 10px }
/*-------------------------------------------------------------- <-- END*/
/* webform text input styling */
.node-webform {
/*change:
  width: 940px;*/
  width:100%;
  display: inline;
  float: left;
}
.node-webform input[type="text"],
.node-webform textarea,
.node-webform .selectBox-dropdown,
.node-webform div.uploader {
  background: #f5f7f9; /* Old browsers */
  background: -moz-linear-gradient(top, #f5f7f9 0%, #dfe5eb 100%); /* FF3.6+ */
  background: -webkit-gradient(linear, left top, left bottom, color-stop(0%,#f5f7f9), color-stop(100%,#dfe5eb)); /* Chrome,Safari4+ */
  background: -webkit-linear-gradient(top, #f5f7f9 0%,#dfe5eb 100%); /* Chrome10+,Safari5.1+ */
  background: -o-linear-gradient(top, #f5f7f9 0%,#dfe5eb 100%); /* Opera 11.10+ */
  background: -ms-linear-gradient(top, #f5f7f9 0%,#dfe5eb 100%); /* IE10+ */
  background: linear-gradient(top, #f5f7f9 0%,#dfe5eb 100%); /* W3C */
  filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#f5f7f9', endColorstr='#dfe5eb',GradientType=0 ); /* IE6-9 */
  border: 1px solid #BEC5C9;
  -webkit-border-radius: 5px;
  -moz-border-radius: 5px;
  border-radius: 5px;
  padding: 5px;
}
.node-webform textarea {  width: auto }
.node-webform .grippie {  display: none }
.node-webform input[type="text"]:focus,
.node-webform textarea:focus,
.node-webform .selectBox-dropdown:focus,
.node-webform div.uploader:focus {
  background: #dfe5eb; /* Old browsers */
  background: -moz-linear-gradient(top, #dfe5eb 0%, #f5f7f9 100%); /* FF3.6+ */
  background: -webkit-gradient(linear, left top, left bottom, color-stop(0%,#dfe5eb), color-stop(100%,#f5f7f9)); /* Chrome,Safari4+ */
  background: -webkit-linear-gradient(top, #dfe5eb 0%,#f5f7f9 100%); /* Chrome10+,Safari5.1+ */
  background: -o-linear-gradient(top, #dfe5eb 0%,#f5f7f9 100%); /* Opera 11.10+ */
  background: -ms-linear-gradient(top, #dfe5eb 0%,#f5f7f9 100%); /* IE10+ */
  background: linear-gradient(top, #dfe5eb 0%,#f5f7f9 100%); /* W3C */
  filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#dfe5eb', endColorstr='#f5f7f9',GradientType=0 ); /* IE6-9 */
}
.webform-component-file {  overflow: hidden }
.node-webform .form-item.form-type-item,
.node-webform .field-name-field-show-menu {  display: none }
.node-webform textarea {  resize: vertical }
.webform-component > label {  font: normal 16px/20px "Droid Sans", Arial, sans-serif }
.webform-component .form-required {  color: #000 }
.pane-main-form .form-radios .form-type-radio {
  float: left;
  margin-right: 15px;
}
/* Uploader */
.node-webform div.uploader {
  width: 190px;
  cursor: pointer;
  padding: 0;
}
div.uploader span.action {
  width: 85px;
  text-align: center;
  text-shadow: #fff 0 1px 0;
  font-size: 11px;
  font-weight: bold;
}
div.uploader span.filename {
  color: #777;
  width: 82px;
  border-right: solid 1px #bbb;
  font-size: 11px;
}
div.uploader input {  width: 190px }
div.uploader.disabled span.action {  color: #aaa }
div.uploader.disabled span.filename {
  border-color: #ddd;
  color: #aaa;
}
div.uploader {
  position: relative;
  float: left;
  overflow: hidden;
}
div.uploader span.action {
  float: left;
  display: inline;
  padding: 2px 0;
  overflow: hidden;
  cursor: pointer;
}
div.uploader span.filename {
  padding: 0 10px;
  float: left;
  display: block;
  overflow: hidden;
  text-overflow: ellipsis;
  white-space: nowrap;
}
div.uploader input {
  opacity: 0;
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  float: right;
  height: 25px;
  border: none;
}
div.uploader {  height: 28px }
div.uploader span.action {
  height: 24px;
  line-height: 24px;
}
div.uploader span.filename {
  height: 24px;
  /* change this line to adjust positioning of filename area */
  margin: 2px 0 2px 2px;
  line-height: 24px;
}
div.uploader.focus span.action,
div.uploader.hover span.action,
div.uploader:hover span.action {  background-position: right -437px }
div.uploader.active span.action,
div.uploader:active span.action {  background-position: right -465px }
div.uploader.focus.active span.action,
div.uploader:focus.active span.action,
div.uploader.focus:active span.action,
div.uploader:focus:active span.action {  background-position: right -493px }
div.uploader.disabled {  background-position: 0 -325px }
div.uploader.disabled span.action {  background-position: right -381px }
.node-webform .selectBox-dropdown {
  width: auto;
  padding: 5px 30px 5px 10px;
  display: inline;
  float: none;
  margin: 0;
}
.node-webform .selectBox-inline {
  height: auto!important;
  padding: 1px;
}
.node-webform .selectBox-inline .selectBox-options {  border: none }
.selectBox-options .selectBox-selected {  background-color: #BEC5C9 }
.selectBox-options li a {  color: #000 }
.node-webform .form-radios .form-item label {
  display: inline;
  margin: 0;
}
.node-webform .selectBox-dropdown .selectBox-label {  display: inline }
/*
.webform-container-inline{
    display:inline-block;
    margin-right:20px;
}
*/
#ui-datepicker-div {
  background-color: #FFFFFF;
  border: 1px solid #BEC5C9 !important;
  box-shadow: 0 0 3px #CCCCCC;
  padding: 0 5px;
}
#ui-datepicker-div table {  width: auto }
#ui-datepicker-div table td {
  width: 32px;
  border: 1px solid #ccc;
  padding: 0;
}
#ui-datepicker-div table td a:hover {  background-color: #ccc }
#ui-datepicker-div .ui-state-highlight,
#ui-datepicker-div .ui-state-active {
  background-color: #f4c997;
  color: #000;
}
#ui-datepicker-div .ui-state-active {  background-color: #f7921e }
#ui-datepicker-div .ui-datepicker-next,
#ui-datepicker-div .ui-datepicker-prev {  cursor: pointer }
#ui-datepicker-div .ui-datepicker-next {  right: 14px }
.pane-main-form #business_partner .form-type-radios .form-type-radio,
.pane-main-form #membership .form-type-radios .form-type-radio {
  float: none;
  margin-bottom: 15px;
}
.form-item .radio,
.form-item .radio span,
.form-item .checker,
.form-item .checker span {
  display: inline-block;
  position: relative;
  bottom: 1px;
}
.form-item .radio span,
.form-item .radio input,
.form-item .checker span,
.form-item .checker input {
  width: 17px;
  height: 18px;
}
.pane-main-form .form-radios .radio,
.node-webform .form-radios .radio,
.node-type-webform .form-type-radio {  position: relative }
.pane-main-form .form-radios .radio span,
.node-webform .form-radios .radio span,
.node-type-webform .form-type-radio span {  background: url('../images/ui-sprite.png') -953px -718px }
.pane-main-form .form-radios .radio.hover span,
.node-webform .form-radios .radio.hover span,
.node-type-webform .form-type-radio.hover span {  background-position: -953px -742px }
.pane-main-form .form-radios .radio span.checked,
.node-webform .form-radios .radio span.checked,
.node-type-webform .form-type-radio span.checked {
  background-position: -953px -766px;
  display: inline-block;
}
.pane-main-form .group_contact_information {  width: 315px }
.pane-main-form .group_contact_information label {
  font: bold 13px "Droid Sans", Arial, sans-serif;
  color: #303030;
}
.pane-main-form .group_contact_information .field-type-list-boolean {  margin-bottom: 15px }
.pane-main-form .group_contact_information .checker,
.page-newsletter .content-area .checker {
  float: right;
  margin: 0px;
  position: relative;
  width: 19px;
  height: 19px;
  display: inline-block;
  vertical-align: middle;
  zoom: 1;
}
.page-newsletter .content-area .checker {  float: none }
.pane-main-form .group_contact_information .checker span,
.page-newsletter .content-area .checker span,
.node-webform .checker span,
.node-webform .checker.focus:active span,
.node-webform .checker.focus.active span {
  background: url("../images/ui-sprite.png") no-repeat -928px -742px;
  -webkit-font-smoothing: antialiased;
  height: 19px;
  width: 19px;
}
.pane-main-form .group_contact_information .checker.hover span,
.page-newsletter .content-area .checker.hover span,
.node-webform .checker.hover span {  background-position: -927px -720px }
.pane-main-form .group_contact_information .checker span.checked,
.page-newsletter .content-area .checker span.checked,
.node-webform .checker span.checked {  background-position: -929px -767px }
.pane-main-form .group_contact_information .checker.hover span.checked,
.page-newsletter .content-area .checker.hover span.checked,
.node-webform .checker.hover span.checked {  background-position: -929px -790px }
.pane-main-form .submit-wrapper,
.node-webform .form-actions {
  background-color: #1C95B8;
  margin: 10px;
  display: inline-block;
}
.node-webform .form-actions {  margin: 0 }
.pane-main-form .form-submit,
.node-webform .form-submit {
  padding: 9px 35px 10px 15px;
  background: #1C95B8 url("../images/form-btn-sprite.png") no-repeat right 8px;
  font: bold 14px "Droid Sans", Arial, sans-serif;
  color: white;
  border: none;
  display: inline-block;
  cursor: pointer;
}
.pane-main-form .form-submit:hover,
.node-webform .form-submit:hover {  background: #167692 url("../images/form-btn-sprite.png") no-repeat right -42px }
.pane-main-form h3 {  display: none }
.pane-main-form .description {
  position: absolute;
  width: 160px;
  background: white;
  border: 1px solid #1C95B8;
  padding: 10px;
  left: 38px;
  top: -20px;
  position: relative;
  display: none;
  min-height: 40px;
}
.pane-main-form .description .arrow {
  position: absolute;
  width: 20px;
  height: 30px;
  left: -20px;
  top: 22px;
  background: url("../images/ui-sprite.png") no-repeat -950px -570px;
}
.pane-main-form .tooltip-anchor {
  width: 20px;
  height: 21px;
  background: url("../images/ui-sprite.png") no-repeat -778px -228px;
  display: block;
  position: absolute;
  right: -20px;
  top: 44%;
  cursor: pointer;
}
.pane-main-form .tooltip-anchor:hover .description {  display: block }
.pane-main-form .big-arrow {
  position: absolute;
  width: 30px;
  height: 68px;
  background: url("../images/ui-sprite.png") no-repeat -926px -619px;
  top: 50%;
  margin-top: -32px;
  right: 0;
}
.pane-main-form form iframe {  float: none }
#shock_every_month,
#deal_a_contribution,
#membership,
#business_partner,
#christmas,
#erhvervspartner,
#global{
  border: 1px solid #f45017;
  position: relative;
}


.field-name-field-purpose,
.field-name-field-title-purpose {
    display: none;
}

#shock_every_month fieldset,
#deal_a_contribution fieldset {
  position: relative;
  overflow: hidden;
}
#shock_every_month .form-item-amount label,
#deal_a_contribution .form-item-amount label {  width: auto }
body #membership .form-item-amount .form-radios label,
body #membership .form-item-amount .form-radios label,
body #business_partner .form-item-amount .form-radios label {  display: inline !important }
#shock_every_month .form-item-amount label,
#deal_a_contribution .form-item-amount label {  display: block }
#business_partner .form-item-amount > label,
#membership .form-item-amount > label {  display: block }
#shock_every_month .form-item-amount .form-radios label,
#deal_a_contribution .form-item-amount .form-radios label {
  display: inline;
  font: normal 12px "Droid Serif",Arial,sans-serif;
}
.contextual-links-region .pane-thanks-block div {  text-align: center }
/* Standart Page Layout */
.container_12 .vl-wrapper {  background: url('../images/bg-standart-page.png') repeat-y 0 0 }
.node-type-page .container_12 .vl-wrapper,
.node-type-page .std-vl {  background: url("../images/bg-line-vertical.png") repeat-y scroll 0 0 transparent }
.node-type-page .std-vl {
  display: inline;
  float: left;
  background-position: 510px 0;
}
.node-type-page .container_12 .vl-wrapper {  background-position: 200px 0 }
.node-type-employees .width-wrapper,
.page-employees .width-wrapper,
.node-type-video .width-wrapper {
  width: 460px;
  padding: 0;
}
.container_12 .spage-left {  width: 180px }
.node-type-page .spage-left,
.node-type-employees .spage-left {  margin-right: 10px }
.container_12 .spage-center {  margin: 0 30px }
.node-type-page .map-region {
  margin: 0 0 0 30px;
  width: 720px;
}
.node-type-page .gmap {  margin-bottom: 50px }
/* Donation Page */
.page-taxonomy .border-wrapper .grid_8 {
  margin: 0 30px 0 0;
  width: 640px;
}
.page-taxonomy .border-wrapper .grid_4 {  width: 260px }
.page-taxonomy .pane-main-right-form {  margin-top: 59px }
.security-icon {
  background: url('../images/icon-security.png') no-repeat 0 0;
  padding: 0 0 0 20px;
  display: inline;
  font: bold 11px Arial;
}
/* Employees Block */
.view-id-employees_donation {  width: 260px }
.ibis-donation-form-right-tabs .inner {
  overflow: hidden;
  width: 260px;
  margin-bottom: 30px;
}
.ibis-donation-form-right-tabs .view-id-employees_donation,
.view-display-id-related_employees_view {
  box-shadow: 0px 0px 6px #ccc;
  width: 260px;
  margin-bottom: 25px;
}
.view-display-id-related_employees_view {  width: 200px }
.view-employees-donation .employees-block,
.view-display-id-related_employees_view {
  padding: 10px;
  background-color: #fff;
}
.view-id-employees_donation .view-header,
.view-display-id-related_employees_view .view-header {
  padding: 15px 10px 12px 10px;
  background-color: #fff;
}
.view-id-employees_donation .view-header h2,
.view-display-id-related_employees_view .view-header h2 {
  background: url('../images/icon-empoeeys.png') no-repeat 0 0;
  padding: 0 0 0 30px;
  font: bold 18px/25px 'Droid Serif', Arial, sans-serif;
  color: #696968;
}
.view-id-employees_donation .view-header .field-content,
.view-display-id-related_employees_view .view-header .field-content {
  word-wrap: break-word;
  font: 12px "Droid Serif", Arial, sans-serif;
  margin-top: 10px;
}
.view-employees-donation .e-photo,
.view-display-id-related_employees_view .e-photo {
  float: left;
  margin: 0 10px 0 0;
}
.view-display-id-related_employees_view .picture-img {  margin: 0 }
.view-employees-donation .e-photo img,
.view-display-id-related_employees_view .e-photo  img {  border: 1px solid #dddddd }
.view-employees-donation .e-photo a,
.view-display-id-related_employees_view .e-photo  a,
.view-display-id-related_employees_view .e-photo img,
.view-employees-donation .e-photo img {  display: block }
.view-employees-donation .e-info,
.view-display-id-related_employees_view .e-info {
  float: left;
  width: 160px;
  word-wrap: break-word;
}
.view-display-id-related_employees_view .e-info {  width: 120px }
.view-display-id-related_employees_view .picture-img {  height: auto }
.view-employees-donation .e-info .e-title,
.view-employees-donation .e-info .e-work-area,
.view-employees-donation .e-info .e-country,
.view-display-id-related_employees_view .e-info .e-name,
.view-display-id-related_employees_view .e-info .e-title,
.view-display-id-related_employees_view .e-info .e-work-area,
.view-display-id-related_employees_view .e-info .e-country {  line-height: 17px }
.view-employees-donation .e-info .e-name,
.view-display-id-related_employees_view .e-info .e-name {
  font-weight: bold;
  font-size: 13px;
  line-height: 13px;
}
.view-employees-donation .e-email a,
.view-display-id-related_employees_view .e-email a {
  color: #f45017;
  text-decoration: none;
}
.view-employees-donation .e-email a:hover,
.view-display-id-related_employees_view .e-email a:hover {  color: #1C95B8 }
.donation-loading {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  z-index: 100;
  background: url('../images/6.gif') no-repeat 50% 50% rgba(255, 255, 255, 0.7);
}
.hide {  display: none }
.pane-node-field-files {  margin-bottom: 20px }
.pane-node-field-files .file img {  display: none }
.pane-node-field-files .file a:hover {  text-decoration: none }
.view-display-id-related_employees_view .views-row {
  border: none;
  padding: 10px 0;
}
.view-display-id-related_employees_view .views-row.views-row-first {  border: none }
/**
  *
  * Google Maps
  *
  */
/* Google maps style */
.gmap-wrapper > div > div {
  position: relative;
  top: 75px;
  left: 32px;
}
.gmap-wrapper > div > div > div {  overflow: visible!important }
#gmap .gmap_marker {
  -moz-box-shadow: 5px 5px 10px rgba(0,0,0,0.5);
  -webkit-box-shadow: 5px 5px 10px rgba(0,0,0,0.5);
  box-shadow: 5px 5px 10px rgba(0,0,0,0.5);
}
.gmap-unnecessary {
  background-color: transparent!important;
  border: none!important;
}
.gmap-unnecessary img {  display: none }
.gmap_marker {
  padding: 15px;
  background: #1C95B8;
  color: white;
  position: relative;
}
.gmap_marker .arrow {
  background: url("../images/ui-sprite.png") no-repeat -781px -272px;
  position: absolute;
  bottom: -12px;
  left: 20px;
  width: 17px;
  height: 12px;
}
.gmap_marker a {
  padding-left: 15px;
  background: url("../images/gmap-link-arrow.png") no-repeat left 4px;
  color: white;
  text-decoration: none;
}
.gmap_marker a:hover {  text-decoration: underline }
.pane-newsletter-newsletter-subscriptions {
  padding-bottom: 27px;
  border-bottom: 1px dotted #C8C7C6;
}
.pane-newsletter-newsletter-subscriptions .newsletter_pane_data {  font-family: Arial, Helvetica, sans-serif }
.pane-newsletter-newsletter-subscriptions .form-text {
  border: 1px solid #C8C7C6;
  width: 212px;
  padding: 3px;
  margin: 10px 0;
  font: bold 12px arial;
  color: #b2b2b2;
}
.pane-newsletter-newsletter-subscriptions label {  display: none }
.pane-newsletter-newsletter-subscriptions .form-checkboxes label {  display: inline; }
.pane-newsletter-newsletter-subscriptions .form-submit {
  font: bold 11px "Droid Sans", Arial, sans-serif;
  cursor: pointer;
}
.pane-newsletter-newsletter-subscriptions .form-item .description {  display: none }
.node-webform .radio + label.option,
.node-webform .checker + label.option {
  font: normal 12px "Droid Sans", Arial, sans-serif;
  padding-top: 3px;
}
.node-webform .webform-component-checkboxes.two-column {  width: 500px }
.node-webform .webform-component-checkboxes.two-column .form-type-checkbox {
  display: inline-block;
  width: 240px;
}
.node-webform .description {
  margin-bottom: 10px;
  word-wrap: break-word;
}
.node-webform .selectBox-inline {  overflow: visible }
.node-webform .selectBox-inline li {  list-style: none }
.spage-center > .pane-custom {
  word-wrap: break-word;
  margin-bottom: 30px;
}
.webform-component-select.two-column {  display: inline-block }
.jquery-checkbox {  cursor: pointer }
/* Black border for image */
.image-black-border {  border: 1px solid #000 }
/* jcarusel */
.page-node .jcarousel-list .description {  background-image: url("../images/gallery-alt-hover.png") }
.page-node .jcarousel-skin-front-page-banner-mini .description {
  left: 47px;
  margin: 0;
  padding: 3px 3px 10px;
  width: 348px;
}
.page-node .jcarousel-skin-front-page-banner .description {
  width: 613px;
  margin: 0;
  left: 23px;
  padding: 3px 4px 10px;
}
.page-node .user-info-from-cookie .description {
  color: #7b7b7b;
  margin-bottom: 20px;
}
table {  border-collapse: separate }
/* News letter block */
.newsletters-block {  border-bottom: 1px dotted #C8C7C6 }
.newsletters-block h2.pane-title {
  font: normal 15px "Droid Serif", Arial, sans-serif;
  color: #343432;
  margin: 10px 0;
}
.newsletters-block .pane-content li {
  font: normal 13px Arial, Helvetica, sans-serif;
  margin: 0 0 7px;
  padding: 0 0 0 10px;
}
.newsletters-block .pane-content li a {  color: #161616 }
.listpage .pane-content {
  font: bold 45px "yanone kaffeesatz", Arial, sans-serif;
  margin-bottom: 20px;
  color: #2E2C2D;
}
.newsletters-block .pane-content ul {  padding: 0 0 5px }
.width-wrapper-node .node-webform {  width: 680px }
.spage-center .node-webform {  width: 460px }
.newsletter-block-title {  display: none }
.pane-page-section-page-pane-three-column + .panel-separator + .pane-page-section-page-pane-three-column {  margin-top: 30px }
.view-filters {  margin: 0 0 30px 0 }
.view-filters .views-exposed-widget {  display: inline-block }
.spage-left .pane-block  .pane-content > .menu >li,
.spage-left .pane-block .menu-block-wrapper {  display: none }
.spage-left .pane-block  .pane-content > .menu >li.level-one {  display: inline }
.spage-left  .pane-content > .menu >li {  display: none }
.spage-left  .pane-content > .menu >li.level-one {  display: inline }
.gmap-wrapper-2 {  overflow: visible!important }
/* news letter page */
.page-newsletter .content-area form {  width: 396px }
.page-newsletter .content-area form .description {
  font-size: 11px;
  margin: 0 0 10px 0;
}
.page-newsletter .content-area form .form-type-checkbox {  margin: 10px 0 }
.page-newsletter .content-area form .form-type-checkbox label {  display: inline }
#edit-field-cpr-nummer2-wrraper {  position: relative }
#edit-field-cpr-nummer2-wrraper .defis,
.field-name-field-cpr-number-suffix-contrib .defis {
  position: absolute;
  top: 12px;
  left: -12px;
}
.field-name-field-cpr-number-suffix-contrib .defis {
  top: 31px;
}
.pane-page-section-page-pane-flat-list .views-row-first {  padding-top: 30px }
.webform-component-radios > label,
.webform-component-checkboxes > label {
  padding-bottom: 13px;
  display: block;
}
.node-type-webform .webform-component-textfield,
.node-type-webform .webform-component-email {  overflow: hidden }
.webform-component-textfield label {
  display: inline;
  float: none;
}
.webform-component-textfield input {
  float: none;
  display: block;
}
.webform-container-inline label {
  float: left;
  line-height: 30px;
}
.webform-container-inline input {  float: right }
.webform-component-select label {  display: block }
.node-type-webform fieldset .webform-component,
.node-type-webform .webform-component {  padding: 0 0 10px 0 }
.node-type-webform .webform-component-textarea,
.node-type-webform .webform-component-checkboxes,
.node-type-webform .webform-component-radios,
.node-type-webform .webform-component-fieldset,
.node-type-webform .webform-component-file,
.node-type-webform .webform-component-textfield,
.node-type-webform .webform-component-email,
.node-type-webform fieldset,
.node-type-webform .webform-component-webform_time,
.node-type-webform .webform-component-webform_grid,
.node-type-webform .webform-component-markup,
.node-type-webform .webform-component-select {  padding: 0 0 50px 0 }
.node-type-webform fieldset .fieldset-wrapper .fieldset-description {
  font: bold 12px "Droid Sans", Arial, Helvetica, sans-serif;
  color: #42484a;
}
.node-type-webform fieldset legend {  font: bold 16px "Droid Sans", Arial, Helvetica, sans-serif }
.node-type-webform fieldset .fieldset-description,
.node-type-webform fieldset legend {  padding: 0 0 20px 0 }
.form-item .description,
.node-type-webform fieldset legend {  color: #303030 }
.form-item .description {  font-size: 12px }
.form-item.webform-container-inline .description {  display: none }
.webform-component-file label {  display: block }
.webform-component-select {  padding: 0 0 50px }
.node-type-webform .pane-page-title h1 {
  font: normal 40px "Droid Serif", Arial, Helvetica, sans-serif;
  margin: 0 0 15px 0;
}
.node-type-webform .field-name-body {
  font: normal 16px/24px "Droid Sans", Arial, Helvetica, sans-serif;
  margin: 0 0 30px 0;
}
.webform-component-webform_grid .webform-grid {
  width: 100%;
  border-collapse: collapse;
}
.webform-component-webform_grid .webform-grid th,
.webform-component-webform_grid .webform-grid td {
  border-bottom: 1px solid #EBEBEB;
  padding: 5px;
}
/* change:
.page-newsletter-confirm .content-area {  width: 940px }*/
.page-newsletter-confirm .content-area {  width: 100% }
.pane-newsletter-newsletter-subscriptions .form-submit {  margin: 0 }
/*========================================================( Custom Block )====*/
.pane-block a {  text-decoration: none }
.pane-block a:hover {  text-decoration: underline }
.pane-block .pane-content {
  font: 400 14px/20px Arial, "Helvetica Neue", Helvetica, sans-serif;
}
.pane-block .pane-content h2,
.pane-block .pane-content h3,
.pane-block .pane-content h4,
.pane-block .pane-content h5,
.pane-block .pane-content h6 {
  font-weight: 700;
}
.spage-center .pane-block .pane-content p {
  margin: 0 0 20px 0;
}
.pane-block .pane-content h1 {
  font: 400 40px/1.2 'Droid Serif', serif;
  margin: 10px 0 25px;
}
.pane-block .pane-content h2 {  font-size: 18px }
.pane-block .pane-content h3 {  font-size: 16px }
.pane-block .pane-content h4 {  font-size: 14px }
.pane-block .pane-content h5 {  font-size: 12px }
.pane-block .pane-content h6 {  font-size: 12px }

.spage-center .pane-block .pane-content ol,
.spage-center .pane-block .pane-content ul {
  list-style-position: outside;
  margin-left: 20px;
}
.spage-center .pane-block .pane-content ol {
  list-style-type: decimal;
}
.spage-center .pane-block .pane-content ul {
  list-style-type: disc;
}
.spage-center .pane-block .pane-content li {
  margin: 0 0 5px 0;
}
.employee-contact-info {  margin: 8px 0 0 0 }
.view-pdf-files-view {  position: relative }
.view-employees .view-header  h1 {
  margin-top: 20px;
  font: 40px/44px bold "Droid Serif";
}
.view-employees .view-header p {
  font: 16px "Droid Sans",Arial,sans-serif;
  padding: 0 0 22px 0;
  line-height: 25px;
}
#quiz_results_summary .answer-1,
#quiz_results_summary .answer-0 {  padding: 15px 0 }
#quiz_results_summary .answer-1 {  color: #060 }
#quiz_results_summary .answer-0 {  color: #600 }
#quiz_results_summary .right-answer {  margin-left: 50px }
/* RSS Icon */
.rss-icon {
  background: url('../images/icon-rss.png') no-repeat 0 0;
  padding: 0 0 3px 24px;
  color: #000;
}
.rss-icon:hover {  color: #1C95B8 }
/*======================================================( Webform Donation)======*/
#shock_every_month_madskolenibolivia {
  border: 1px solid #F45017;
  position: relative;
}
#shock_every_month_madskolenibolivia .form-radios {  padding: 35px 0; }
#shock_every_month_madskolenibolivia .form-radios label {
  display: inline;
  margin: 0;
}
#shock_every_month_madskolenibolivia .form-item-another-amount {
  margin-top: 23px;
}
#shock_every_month_madskolenibolivia .fieldset-wrapper .form-item-another-amount + span {
  margin-top: 35px;
}


/*------------------------------------------------------------------------------
// Madskolen i bolivia */

.bolivia-header {
  margin-top: 20px;
}

.page-presserum .flat-list,
.page-presserum .flat_list_catpage_all,
.page-presserum .vert_list_catpage {
  overflow: hidden;
  padding-top: 25px;
}

.node-type-arrangementer .pane-node-display {
  clear: both;
}
.node-type-arrangementer .view-node-display.ibis-standart-block h1 {
  line-height: 1.2;
}
.node-type-arrangementer .pane-node-display-arrangements-node-view {
  clear: both;
}


/*  */
.node-type-employees .toolbar-pane .pane-content {
  float: left;
  width: 100%;
}
.node-type-arrangementer .toolbar-pane .pane-content {
  float: left;
  width: 100%;
}
.node-type-employees .goback-to-employees,
.node-type-arrangementer .back-to-calendar-link {
  float: left;
  display: block;
  width: 30px;
  height: 18px;
  background: url(../images/ui-sprite.png) no-repeat -399px -776px;
  overflow: hidden;
  text-indent: -9999em;
}

/*-------------------------------------------------------- Slideshow */
.field-name-field-slideshow-images {
    float:left;
    width:100%;
    margin-bottom:10px;
}
.field-name-field-slideshow-images .field-item {
    float:left;
    width:110px;
    height:110px;
}

.field-slideshow-slide img {
    display: block;
    margin: 0;
}

.field-slideshow-caption {
    background: #000;
    color: #fff;
    padding: 5px;
}

.field-slideshow-controls {
    padding:5px 0 0;
}

.field-name-field-slideshow-image {
    margin-bottom: 1em;
}

#field-slideshow-2-wrapper {
    position: relative;
    margin-bottom:10px;
}

#field-slideshow-2-pager {
    position: absolute;
    right: 30px;
    bottom: 0;
    z-index: 99;
}


#field-slideshow-2-pager a {
    padding: 0 2px;
    margin-left: 4px;
    border: 1px solid transparent;
    text-decoration:none;
}

#field-slideshow-2-pager a:hover {
    color: #000;
    border-color: #000;
    background: #fff;
    text-decoration: none;
}

#field-slideshow-2-pager .activeSlide {
    border-color: #000;
}


/* Dontion new form */
#skoleindsamling .field-name-field-municipality,
#skoleindsamling .field-name-field-municipality-school {
    margin-bottom: 15px;
    float: left;
}

#skoleindsamling .field-name-field-municipality,
#skoleindsamling .field-name-field-first-name,
#skoleindsamling .field-name-field-mobile-phone {
    margin-right: 30px;
}

#skoleindsamling .field-name-field-addr-address,
#skoleindsamling .field-name-field-city,
#skoleindsamling .field-name-field-school-name,
#skoleindsamling .field-name-field-postal-code {
    display: none;
}

#skoleindsamling .field-name-field-e-mail {
    clear: both;
}

#skoleindsamling .field-name-field-e-mail input {
    width: 318px
}

#skoleindsamling .tooltip-anchor .description {
    z-index: 50000;
}
#skoleindsamling .group_choose_support {
    padding-bottom: 9px;
}
#skoleindsamling .group-information {
    display: table;
    clear: both;
    overflow: visible !important;
}

#skoleindsamling .group_information {
    border-bottom: 1px dotted #CCCCCC;
    margin: 0 0 30px;
    padding: 30px 0 10px;
}

#skoleindsamling {
    border: 1px solid #f45017;
    position: relative;
}


/*cookie link*/
.page-header .block-domain-nav {
    width: auto;
    float: right;
}
/*link wrapper style*/
.block-cookie-domain-link {
    float: left;
    margin: 15px 20px 0 15px;
    background: url('../images/iconbig.png') no-repeat 10px 2px;
    height: 25px;
    padding-left: 35px;
}
/*link style*/
.cookie-info-link {
    display: inline-block;
    font-size: 12px;
    margin-top: 5px;
    text-decoration: none;
    color: #2c2c2a;
}

.node-type-articles .node-gallery-colorbox .node-title,
.node-type-articles .node-gallery-colorbox .submitted {
  display: none;
}
.menu-block-3{
 display: none; 
}
.responsive {
  display: none;
}
.mobile_appel{
display:none;
}
.menu-block-4 {
display: none;
}

/*********************************************** FORMS ********************************************************/

form#SubscriberForm {
  background: -webkit-gradient(linear, bottom, left 175px, from(#CCCCCC), to(#EEEEEE));
  background: -moz-linear-gradient(bottom, #CCCCCC, #EEEEEE 175px);
  margin: auto;
  position: relative;
  /* width: 100%;
  height: 450px; */
  font-family: Tahoma, Geneva, sans-serif;
  font-size: 14px;
  font-style: italic;
  line-height: 24px;
  font-weight: bold;
    /* background-color: rgb(235, 235, 235) */
  /* color: #09C; */
  text-decoration: none;
  /* -webkit-border-radius: 10px;
  -moz-border-radius: 10px; */
  /* border-radius: 10px; */
  padding: 10px;
  border: 1px solid rgb(28, 149, 184);
  border: inset 1px solid #333;
 /*  -webkit-box-shadow: 0px 0px 8px rgba(0, 0, 0, 0.3);
  -moz-box-shadow: 0px 0px 8px rgba(0, 0, 0, 0.3);
  box-shadow: 0px 0px 8px rgba(0, 0, 0, 0.3); */
}
form#SubscriberForm input {
max-width: 100%;
  padding: 8px 2px;
  border: none;
}
input[type="submit"] {
  background-color: #1C95B8;
  padding: 10px !important;
  border-radius: 3px;
  color: #fff;
  /* border: 20px solid #fff !important; */
}


/* ****************************************************** RESPONSIVE *************************************************************** */


/* @media screen and (max-width: 380px){
	.container_12 >div {
  width: 100%;
}
	.view-front-4-elements-view .views-row, 
	.view-blogs-latest-posts .views-row, 
	.view-global-articles-list .views-row, 
	.view-front-page-employees .views-row, 
	.view-ibis-posten-view .views-row, 
	.view-blog-page .views-row, 
	.view-blog.ibis-standart-block .views-row, 
	.view-node-display .views-row, 
	.view-latest-comments .views-row, 
	.view-display-id-arrangements .views-row, 
	.view-display-id-blog_archive_list .views-row, 
	.sneaky-panel .views-row-last, 
	.view-rss-feeds-block .views-row{
	margin:0;
	padding:0;
	}
	.views-row{
	margin-bottom: 10px;
	}
	.panel-pane{
	width:100%;
	}
	.view-front-4-elements-view .elements-list li, .front-page-tabs .tabs-articles-by-category li{
	width:100% !important; 
	margin-bottom: 10px;
	padding: 5px;
	}
	.elements-list {
	width:100%;
}
    .elements-list li {
	width:100%;
        float:left;
		display:block;
		clear:both;
		background: lightgray;
		}

		.ibis-standart-block .picture-img {
		padding:0;
		float: left;
		display:inline;
	}
	.ibis-standart-block .views-row, .view-display-id-related_employees_view{
	float:left;
	}
	.elements-list li p{
	margin:10px;
	padding:10px;
	}

	.container_12 .spage-left {
	width: 100% !important;
	display:block !important;
	-ms-transition: all 0.4s ease; 
    -webkit-transition: all 0.4s ease;
	-o-transition: all 0.4s ease;	
    transition: all 0.4s;
	}
	.container_12 .grid_3{
	width: 100% !important;
	display:block !important;
	}
	.container_12 .grid_6{
	width:100%;
	}
	.three-column-list ul li{
	width:28% !important;
	}
} */


@media screen and (max-width: 960px){
*{

 -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
	
  /* font: arial,helvetica,clean,sans-serif; */
  
font-family:'droid serif';
  /* font-size: 20px !important; */
  word-wrap: break-word;
}
html{
width:100%;
}
body{
width:100%;
/* max-width: 760px; */
/* min-width:0px; */
font-size:16px/21;
padding: 0 15px 0 15px;
}
.menu{
display: none;
}
.respons_footer{
display:block;
height:300px;
width: 100%;
}
.mobile_appel{
display: block;
width: 100%;
padding: 2em;
background: rgb(28, 149, 184);
color: #fff;
clear: both;
}
.block_stot{
color: #fff;
}
#logo img{
width:100px;
height:auto;
float: left;
}
.view-id-front_appel_element_view {
  display: none;
  position: relative;
  overflow: hidden;
}
.ibis-standart-block .views-row {
  width: 100%;
  padding: 0 0 25px 0;
  margin: 0 0 15px 0;
  border-bottom: 1px dotted #C8C7C6;
  }
.manchet {
  font: 400 22px "Droid Serif", Arial, sans-serif;
}
.clearfix, .container_12 {
  /* zoom:1; */
}

.toolbar-pane .pane-content {
  display: none;
}

/*************************** DONATION *************************************************/
#global{
   float: left;
}
.pane-main-form .ibis-donation-tabs li {
 margin-bottom: 30px;
 font-size: small;
}
.pane-main-form form {
  padding: 180px 0 10px 20px;
}
ul.ibis-donation-tabs {
  display: block;
  margin-bottom: 78px;
}
li .noactive{
background-color: #999;
display: block;
clear: both;
}
.pane-main-form .ibis-donation-tabs a {
  padding: 4px;
  background: #f7921e;
  font: 9px "Droid Sans", Arial, sans-serif;
  color: #fff;
  text-decoration: none;
  position: relative;
}
/*************************** DONATION END *************************************************/
/************************ BACKGROUND LINES NONE ************************************/
.node-type-page .container_12 .vl-wrapper,
.node-type-page .std-vl {  
background: none;
}
.two-column-list ul {
  background:none; 
}
.view-front-4-elements-view, .front-page-tabs .pane-articles-by-category {
  background: none;
  width: 100%;
}
.border-wrapper, .towcolright-layout {
  /* clear: both; */
  background: none;
  zoom: 1;
}
.category-page-layout .tow-colum {
  background: none;
}
.container_12 .vl-wrapper {
  background: none;
}
	.three-column-list ul {
  background: none;
  float: left;
}

.container_12 .vl-wrapper {  background: none }
.node-type-page .container_12 .vl-wrapper,
.node-type-page .std-vl {  background: none }

.front .row-five .borderwrap {  background: none}
#block-search-form {
  float: right;
}
.panel-pane.pane-page-breadcrumb{
display: none;
}
/************************ END BACKGROUND LINES NONE ************************************/
p, a {
/* font-size:1.4em !important;
line-height:120%; */
}

 h3, h1,h2{
 /* font-size: 1.4em !important;
 line-height:2em;
 margin:5px 0 5px 0; */

 }
 .ibis-standart-block h3 {
  margin: 5px 0 7px 0;
  padding:0px;
}
 .page-node .view-node-display.ibis-standart-block h1 a, .page-node .view-arrangements.ibis-standart-block h1 a, .node-type-page .view-node-display h1, .page-node .view-node-display.ibis-standart-block h1, .info-wrapper h1 {
/*   font-size:  3em;*/
  /* change:
  margin: 10px 0 25px;*/
 /* display: block;
  line-height: 1em;
  font-weight: normal;
  color: black;
  font-family: "Droid Serif",Arial,sans-serif; */
    font-size: 2.4em;
  display: block;
  line-height: 1em;
  font-weight: bold;
  color: black;
  font-family: "Droid Sans",Arial,sans-serif;
}

.title{
font-size:1.3em !important;
line-height:120%;
margin: 10px 0 10px 0 !important;
}
	.container_12{
	max-width:100%;
	/* margin-left:15px;
	margin-right:15px; */
	 /* change:padding:0 15px 0 15px;*/
	}


	.container_12 >div {
  width: 100%;
}
.container_12 .grid_12 {
   width:100%; 
   float:left;
}
.container_12 .spage-center {
     /* change:margin: 0px 0px;*/
	}
.page-header, ul.menu{
/*display:none;*/
}
fieldset, img {
  display: block;
  border: 0px none;
  max-width: 100%;
  height: auto;
}
.pane-content div {
/*float:none !important;
font-size:1.1em;
line-height:120%;*/
}
.pane-content div img{
    height: auto !important;
    /* width: 100% !important; */
	/*float: left;*/
	margin-right: 10px;
}
.pane-content .with-border{
   	/*float: left;*/
	 /* change:margin-right: 10px;*/
}
.intro_pdf_block div img{
width:20px !important;
height:auto !important;
display: inline;

}
.intro_section img{
display:block;
float: left !important;
clear:left;
}
.pane-block div img{
}
.intro_section {
width:100%;
}
.intro_section p
{
margin: 14px 0px;
Font-size:14px;
Line-height:20px;
}
.grid_1, .grid_2, .grid_3, .grid_4, .grid_5, .grid_6, .grid_7, .grid_8, .grid_9, .grid_10, .grid_11, .grid_12 {
  display: inline;
  /* float: left; 
  margin-left: 10px;
  margin-right: 10px;*/
}
	.view-front-4-elements-view .views-row, 
	.view-blogs-latest-posts .views-row, 
	.view-global-articles-list .views-row, 
	.view-front-page-employees .views-row, 
	.view-ibis-posten-view .views-row, 
	.view-blog-page .views-row, 
	.view-blog.ibis-standart-block .views-row, 
	.view-node-display .views-row, 
	.view-latest-comments .views-row, 
	.view-display-id-arrangements .views-row, 
	.view-display-id-blog_archive_list .views-row, 
	.sneaky-panel .views-row-last, 
	.view-rss-feeds-block .views-row{
	margin:0;
	padding:0;
	}
	.views-row{
	margin-bottom: 10px;
	}
	.panel-pane{
	width:100%;
	}
	.view-front-4-elements-view .elements-list li, .front-page-tabs .tabs-articles-by-category li{
	width:100% !important; 
	margin-bottom: 10px;
	 padding: 10px; 
	  margin-left: 0px;
  margin-right: 0px;
  border-bottom: 1px dotted #C6C6C5;
	}
	.elements-list {
	width:100%;
}
    .elements-list li {
	width:100%;
        float:left;
		display:block;
		clear:both;
			/* background: lightgray; */
		}

		
	.main-node .views-row img {
  max-width: 100%;
}
	.ibis-standart-block .views-row, .view-display-id-related_employees_view{
	float:left !important;
	display:inline;
	background-color: white;
	padding: 10px;
	  /* width: 46%; 
  margin-right: 4%;*/
	}
	.view-display-id-related_employees_view{
	display:inline !important;
	/* width:30% */
	}
	.elements-list li p{
	/* margin:10px;
	padding:10px; */
	}

	.container_12 .spage-left {
	width: 100% !important;
	display:block !important;
	-ms-transition: all 0.4s ease; /* IE 9 */
    -webkit-transition: all 0.4s ease;
	-o-transition: all 0.4s ease;/* Chrome, Safari, Opera */
    transition: all 0.4s;
	}
	.container_12 .grid_3{
	  width: 100% !important;
  /* display: inline-block !important; 
  float: left !important;*/
	}
	.container_12 .grid_6{
	width:100%;
	}

	.three-column-list ul li{
	width:100% !important;
	}
	.width-wrapper-node {
  width: 100%;
  position: relative;
  padding-right: 0px;
}
.pane-main-picture-or-slideshow img.with-border {
  max-width: 100%;
  height: auto;
  float:left;
}

.container_12 .grid_9 {
  width: 100%;
}
.page-footer .logo-block {
margin-top:15px;
  width: 21%;
}
.site-menu{
display:none;
}

.page-footer .logo-block, .page-footer .footer-links {
  margin-top:15px;
  margin-bottom: 15px;
  float: left;
    width: 100%;
  /* clear: both; */
}
.page-footer .site-menu {
display:inline;
margin-bottom:15px;
}
.page-footer .site-menu li {
  display: block;
  text-align: left;
  height:32px;  
  border-bottom: #030 dotted 1px;
  padding-top: 7px;
}
.page-footer .footer-contact {
  float: left;
  width: 20%;
  min-width: 150px;
}
.two-column-list ul > li {
  display: inline;
  float: left;
  width: 48%;
}
.ibis-standart-block .picture-img {
		/*margin: 0 10px 0 0;*/
		/* float: left;
		display:inline; */
  /* margin: 0;
  display: inline; 
  height: auto !important;
  width: 100% !important;*/
  padding:0;
  margin-right: 10px;
  display: inline;
  float: left;
  clear:right;
	}
.ibis-standart-block .picture-img img {
  /* margin: 0 0 5px 10px; */
  /* margin-right: 10px;
  display: inline;
  float: left; */
}
/***************************************RESPONSIVE MENU SIDR ****************************************************************/
.sidr p {
  font-size: 1.1em;
  margin: 0 0 12px;
  line-height: 133%;
}
.sidr img, .sidr p, .sidr h3{
display:none;
}
.sidr-class-leaf {
 /*  list-style: none !important;
  text-decoration: none;
  padding: 15px;
  height:30px;
  border-bottom: 1px dotted #2c2c2c; */
  
}
sidr-wrapper-0, sidr-wrapper-1,sidr-wrapper-2,sidr-wrapper-3,sidr-wrapper-4{
width:44px;
display:inline !important;
float:left;
}
.sidr-class-leaf a{
  text-decoration: none;
}
.sidr-class-top-main-menu ul li, .sidr-class-orangeknap, .sidr-class-støsidr-class-ttemega-rightmenu-top, .sidr-class-støsidr-class-ttemega-rightmenu-center, .sidr-class-støsidr-class-ttemega-rightmenu-bottom, .sidr-class-sneaky-panel{
/* display:none; */
}
#sidr-0-button {
  text-align: center;
  padding: 0.4em;
  border-radius: 0;
  background: rgb(212, 210, 208);
  color: #000;
  text-decoration: none;
  font-size: 1.5em;
  /* position: relative !important; */
  top: 7px;
  float: left;
  clear: both;
  height: 48px;
  width: 48px;

}	
#sidr-1-button {
 /*  display: block; */
  width: 100px;
  height:48px;
  text-align: center;
  padding: 0.4em;
  border-radius: 0;
  background: rgb(238, 134, 32);
  color: #fff;
  text-decoration: none;
  font-size: 1.2em;
  top: 7px;
  float: left;
  /* clear: both; */
  /* position: relative; */
}
#sidr-2-button {
  display: block;
  text-align: center;
  padding: 0.6em;
  border-radius: 0;
  background: #777471;
  color: #fff;
  text-decoration: none;
  font-size: 1.2em;
  position: relative;
  margin-bottom: 20px;
  width: 100%;
  }
#sidr-3-button {
width: 44px;
height:44px;
display: block;
background-image: url(http://stage.ibis.dk/sites/all/themes/custom/ibis/images/ui-sprite.png);
  background-position-x: 24px;
  background-position-y: 12px;
  background-size: initial;
  background-repeat-x: no-repeat;
  background-repeat-y: no-repeat;
  background-attachment: initial;
  background-origin: initial;
  background-clip: initial;
  background-color: initial;
}
#sidr-0-button:after{
	content: '\2261';
	}
#sidr-1-button:after{content: 'Om IBIS';}
#sidr-2-button:after{content: 'Explore';}
#sidr-3-button:after{content: '';}

.sidr-inner option {
  height: 44px;
  padding: 10px;
  border-bottom: 1px solid #000;
  border-top: 1px solid #444;
}

.header-block-domain .domain-submit, .sidr h2 {
display:none;
}
/*****************************************************************************************************************************/
.issuuembed  div:last-child{
margin-top:20px;
/* width:auto !important;
margin-left:auto !important; */
}
.issuuembed.issuu-isrendered{
width: 100% !important;
height:auto !important;
clear:both;
margin-bottom:15px;
}
 .videoWrapper {
	position: relative;
	padding-bottom: 56.25%; /* 16:9 */
	padding-top: 25px;
	height: 0;
	margin-bottom:15px;
	display:block;
	float:left;
	clear:both;
}
.videoWrapper iframe {
	position: absolute;
	top: 0;
	left: 0;
	width: 100%;
	height: 100%;
}
iframe{
max-width: 100% !important
}

.nogoodwidget{
max-width: 100%;
overflow-x: scroll !important;
}
.snapwidget-widget{
/* max-width: 100%; */
}
/***************************************************** DONATION MODULE *************************************************/
.page-taxonomy .border-wrapper .grid_8 {
  margin: 0 30px 0 0;
  width: 100%;
}
#donation-pane >div{
  width: 100% !important;
  /* float: right; */
}
.pane-main-form .group_payment_information, .pane-main-form .group_cpr_contribution_wrapper {
  border-bottom: 1px dotted #CCCCCC;
  border-top: 1px dotted #CCCCCC;
  margin: 0 0 30px;
  padding: 30px 0 10px;
  width: 100% !important; 
}
.pane-main-form .group_contact_information {
  width: 100%;
  padding-right: 15px;
}
.pane-main-form .form-type-textfield input {
  padding: 9px 5px 8px;
  border: 0;
  /* background: transparent url("../images/bg-input-default.png") no-repeat; */
  background:none;
  height: 44px;
  margin-top: 5px;
  width: 100%;
}
/***************************************************** END DONATION MODULE *************************************************/
.three-column-list ul li, .two-column-list ul li {
  display: block;
  float: left;
  margin-left: 0;
  margin-right:	0;
  width: auto;
}
.flat-list .views-row img, .three-column-list .views-row img {
  width: 138px;
  float: left;
}
}
@media screen and (max-device-width: 959px){
.flat-list .views-row img, .three-column-list .views-row img {
  width: 138px;
  float: left;
  margin-bottom: 7px;
}
.two-column-list .views-row img, .vertical-list .views-row img {
  width: 218px;
  margin-bottom: 7px;
  float: none;
}
.view-page-section-page .views-row-last {
  margin-bottom: 15px;
  margin-left: 0;
}
.view-page-section-page .views-row-first, .view-page-section-page .views-row-even, .view-page-section-page .views-row-last{
  margin-bottom: 25px;
  margin-left: 0;
  border-bottom: #9c9c9c dotted 1px;
  /* padding-bottom: 10px; */
  padding: 10px;
  background-color: white;  
}
.view-page-section-page .views-row-even{
}
.two-column-list ul > li {
  display: block;
  float: left;
  width: 100%;
  margin-bottom: 25px !important;
}
.main-node, .main-node-big, .two-column-list, .flat-list, .three-column-list {
  padding: 0 0 25px 0;
  margin: 0 0 0 0;
  border-bottom: none;
  word-wrap: break-word;
}
}
@media screen and (max-width: 550px){
.ibis-standart-block .picture-img {
 margin: 0 0 7px 0; 
  /* margin-right: 10px;
  width: 100%; */
  height:auto;
  display: block;
  float: none;
}
.ibis-standart-block  {
 margin: 0 0 7px 0; 
  /* margin-right: 10px;*/
  width: 100%; 
  height:auto;
  display: block;
  float: none;
}
.factbox-right{
width: 100% !important;
}
}
.tinynav {
  display: block;
  height: 44px;
  width: 100%;
  list-style-image: none;
}
.mobile-menu{
display:block;
height:50px;
width: 150px;
background:red;
}

/*********************************** MEAN **********************************/
.mean-container .mean-bar img, .mean-container .mean-bar p, .mean-container .mean-bar h3, .mean-container .mean-bar span, 
.sneaky-wrapper{
display: none;
}
