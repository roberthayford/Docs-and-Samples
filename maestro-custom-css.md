##### Wide layout for home page while other pages are boxed

`body.home .boxed_lay {max-width: 100%;}`

-----------------------------------------------------

##### To remove the background color from the current menu item

`#top-menu>ul>li.current-menu-item>.menu-item-wrap {background: transparent;}`
`#top-menu .current-menu-item > span .link-text {color:#575757;}`

----------------------------------------------

##### To get rid of the dates on the comments section

`.comment-author time {display:none;}`

------------------------------------

##### To get rid of the dates on all posts, widgets

`#layout article .dopinfo, #layout article time, #layout .small-news time, #layout .post-info, #layout .post time, #layout .post .row .columns time, article .dopinfo, article time {display:none !important;}`

`#layout .small-news .entry-summary, article .dopinfo, article .entry-title{margin-left:0}`

--------------------------------------------

##### To align mega menu

`#primary-navigation-1983 > ul {right:0}`

-----------------------------------------------------------

##### Remove "call to action button", leave text

`.al-right .button {display: none; }`

`.al-right { text-align: center; }`

-----------------------------------------------

##### Add the logo of any size

`#logo { width: auto; } `

--------------------------------------------

##### To remove the date buttons from all posts

`.post>time, .post>.row>.columns>time, article time {
display: none;
}`

--------------------------------------

##### Remove captcha from the contacts page

`#captcha {display: none; }`
`#page_feedback img {display: none;}`

-----------------------------------------------

#####To center image added by the block "Image" in Page Builder

`/* Images */
.alignleft {
    float: left;
    margin: 0 15px 7px 0;
}`
`.alignright {
    float: right;
    margin: 0 0 7px 15px;
}`
`.aligncenter {
    display: block;
    margin-left: auto;
    margin-right: auto;
} `

---------------------------------------------

##### To remove breadcrumbs from all pages

`.breadcrumbs {
display: none;
}`

-----------------------------------------

##### Remove page title from the home page

`.home.page .page-title, a.back {display: none; }`

---------------------------------------------

##### To remove time and date from "recent from portfolio" section

`.folio-item .description .info {display: none;}` 
`.folio-item .description .title {padding-top: 5px; }`

-----------------------------------------------------

##### To change font in vCard widget

`.vcard p {font-family: Georgia, Times, "Times New Roman", serif;}`

-----------------------------------------

##### Change text selection color

`::selection { background: #ff6600; color: #fff; text-shadow: none; }`

---------------------------------------

#####To make current menu text of a certain color

`#top-menu>ul>li.current-menu-item .link-text {color: blue;}`
`#top-menu>ul>li.current-menu-item>.menu-item-wrap{
background: none !important;}`

-------------------------------------------------

#####To hide search form with variant 1 header

`#header.horizontal .form-search {display: none;}`

----------------------------------------------------

#####To place subtitles under tiltes on all widgets

`.widget > .subtitle {top: 21px;}`
`.widget-title, .widget>.title h3 {line-height: 1; padding-top: 0; padding-bottom: 25px;}`

##### To put logo to the center of the header

`#logo {
float: none;
text-align:center;
width:auto;
}`

---------------------------------------

##### To make hover effect on slider images

`.item:hover img.slider_zoom {
-moz-transform: scale(1.2);
-webkit-transform: scale(1.2);
-o-transform: scale(1.2);
-ms-transform: scale(1.2);
transform: scale(1.2);
}`

`.item img.slider_zoom {
-moz-transition: all 1.2s;
-webkit-transition: all 1.2s;
-o-transition: all 1.2s;
transition: all 1.2s;
}`

-------------------------------------------------------

##### To move top panel triange to the right

`#open-top-panel {
position: absolute;
bottom: -22px;
left: 1000px;}`

--------------------------------------------------------

##### To make each menu item of a particular color

`#primary-navigation-61.has-submenu.current-menu-item>.menu-item-wrap {
background-color: green;
}`

--------------------------------------------------
##### To swap the title and subtitle for all widgets

`.widget > .subtitle {
top: 21px;
}`

`.widget-title, .widget>.title h3 {
line-height: 1;
padding-top: 0;
padding-bottom: 25px;
}`

