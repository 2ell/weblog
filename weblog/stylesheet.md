Type: File
Content-Type: text/css
Title: Stylesheet
Location: /style.css


:root {
	--crust: rgb(24, 25, 38);
    --mantle: rgb(30, 32, 48);
	--base: rgb(36, 39, 58);
	--surface0: rgb(54, 58, 79);
	--surface1: rgb(73, 77, 100);
	--surface2: rgb(91, 96, 120);
    --overlay0: rgb(110, 115, 141);
    --overlay1: rgb(128, 135, 162);
	--overlay2: rgb(147, 154, 183); 
    --subtext0: rgb(165, 173, 203);
	--subtext1: rgb(184, 192, 224);
    --text-normal: rgb(202, 211, 245);
    --lavendar: rgb(183, 189, 248);
    --blue: rgb(138, 173, 244);
	--teal: rgb(139, 213, 202);
    --sky: rgb(145, 215, 227);
    --green: rgb(166, 218, 149);
	--yellow: rgb(238, 212, 159);
    --peach: rgb(245, 169, 127);
    --maroon:rgb(238, 153, 160);
	--red: rgb(237, 135, 150);
	--mauve: rgb(198, 160, 246);
	--pink: rgb(245, 189, 230);
    --flamingo: rgb(240, 198, 198);
    --rosewater: rgb(244, 219, 214);

	--transparent:#ffffff0e;
	--transparent2: #ffffff07;

	--gradient1: linear-gradient(60deg, var(--lavendar), var(--teal), var(--rosewater), var(--sky), var(--pink));
	--gradient2: linear-gradient(120deg, var(--lavendar), var(--teal), var(--yellow), var(--pink));
	--gradient3: linear-gradient(120deg, var(--blue), var(--sky), var(--teal));
	--default-font: 'Lato', sans-serif;
	--header-font: 'VC Honey Deck', serif;

	--default-size: 1em;
	--border-radius: 0.7rem;
}

* {
	margin: auto;
}

body {
	font-family: var(--default-font);
	font-size: (--default-size);
	margin: 0 auto;
	color: var(--text-normal);
	background-color: var(--crust);
}

/* ------------------------------------------- [OVERRIDES]*/

.hide {
	display: none;
}

.no-line {
	text-decoration: none !important;
}

/* ------------------------------------------- [TYPOGRAPHY]*/

p, li {
	line-height: 1.5em;
}

main a, 
recent a,
footer a {
	color: var(--subtext0);
	background-image: var(--gradient2);
	background-size: 0;
	-webkit-background-clip: text;
    	background-clip: text;
	border-bottom: 0.2rem solid var(--transparent2);	
	transition: all 0.2s ease-in-out;
	padding-bottom: 0;
}

main a:hover,
recent a:hover,
footer a:hover {
	background-size: 100%;
	color: transparent;
	-webkit-background-clip: text;
    	background-clip: text;
	border-bottom: 0.2rem solid var(--transparent);
	transition: all 0.2s ease;
}

h1, h2, h3, h4, h5, h6 {
	font-family: 'VC Honey Deck', serif;
	font-weight: 400;
	margin: 1rem 0;
}

#weblog-title {
	max-width: 100%;
}

#weblog-title a {
	font-family: 'VC Honey Deck', serif;
	font-weight: 700;
	font-size: 2.8rem;
	text-decoration: none;
}

/* ------------------------------------------ [LAYOUT]*/

hr {
	margin: 0, 0, 2rem;
	background-image: var(--gradient1);
	height: 1px;
	border: 0;
	max-width: 100%;
}

.gradient-bg {
	margin: auto;
	border-radius: var(--border-radius) var(--border-radius);
	transform: translate(0);
	background-color: var(--background);
}
.gradient-bg:before {
  content:"";
  position: absolute;
  inset: 10px;
  transform: translate(0.3em, 0.3em);
  z-index: -4;
  background: var(--gradient1);
  background-blend-mode: lighten;
  filter: blur(1.4em);
}

/* --------------------------------------------------------------------- [TOP]*/

.top a, 
.top-nav a,
nav a,
header a {
	color: var(--subtext0);
	background-image: var(--gradient3);
	background-size: 0;
	-webkit-background-clip: text;
    	background-clip: text;
	border-bottom: 0.2rem solid transparent;	
	transition: all 0.2s ease-in-out;
	padding-bottom: 0;
}

.top a:hover,
.top-nav a:hover,
nav a:hover {
	background-size: 100%;
	color: transparent;
	-webkit-background-clip: text;
    	background-clip: text;
	transition: all 0.2s ease;
}

/* [titlebar] */

.top {
	position: sticky;
	top: 0;
	left: 0;
	height: 3rem;
	background-color: var(--crust);
	width: 100%;
	text-decoration: none !important;
}

.top i {
	padding: 1rem;
	font-size: 1.2em;
}

.top i:hover {
	color: var(--yellow);
}

.top-title {
	margin-top: 0;
	padding-top: 0;
	padding: 1rem;
}

.top-title a {
	text-decoration: none !important;
}

.page-title a {
	color: var(--yellow);
}

.top .right {
	padding: 0.3rem;
	display: block;
	float: right;
}

.top .left {
	display: block;
	float: left;
}

/* [top navigation bar] */
.top-nav {
	position: sticky;
	top: 3rem;
	left: 0rem;
	width: 100%;
	height: 1.6rem;
	background-color: var(--crust);
	border: 1px solid var(--overlay0);
	border-left: 0;
	border-right: 0;
	z-index: 999;
}

.top-nav ul {
	list-style-type: none;
	padding: 0;
}

.top-nav li {
	display: inline-block;
	padding: 0;
	margin: 0;
}

.top-nav .left {
	position: absolute;
	left: 0;
	display: block;
	float: left;
	text-align: center;
}

.top-nav .left a {
	color: var(--subtext0);
	padding-left: 1rem;
	display: block;
	max-width: fit-content;
	border-bottom: none;
	text-decoration: none;
}

.top-nav .right {
	float: right;
	display: block;	
	text-align: center;
}

.top-nav .right a {
	color: var(--subtext0);
	padding-right: 1rem;
	display: block;
	border-bottom: none;
	text-decoration: none;
}

/* [weblog navigation bar] */
nav {
	font-size: 1.2em;
	text-align: center;
	background-color: var(--yellow);
	border-bottom: 1px solid var(--text-normal);
}

nav ul {
	list-style-type: none;
	padding: 1rem;
}

nav li {
	display: inline-block;
	padding: 0 0.5rem 0;
}

nav li a {
	color: var(--mantle);
	display: block
	text-align: center;
	text-decoration: none;
	border-bottom: 0.2rem solid transparent;
	max-height: fit-content;
}

header {
	max-width: 100%;
	background-color: var(--mantle);
	margin: 2em auto 2em;
	padding: 4em 3em 4em;
}

.header-container {
	max-width: 80%;
	margin: auto;
	text-align: center;
}

/* ------------------------------------------- [MAIN]*/


main {
	max-width: 800px;
	margin: auto;
	margin-top: 0.5em;
	padding: .5em .5em .5em .5em;
	word-break: normal;
	hyphens: auto;
}

main p {
	margin: 1rem 0 1rem;
}

main img {
	max-width: 70%;
	margin: auto;
	border: 1px solid var(--lavendar);
	box-shadow: 
		rgba(0, 0, 0, 0.1) 0px 1px 1px, 
		rgba(0, 0, 0, 0.01) 0px -12px 30px, 
		rgba(0, 0, 0, 0.1) 0px 4px 6px, 
		rgba(0, 0, 0, 0.1) 0px 12px 13px, 
		rgba(0, 0, 0, 0.03) 0px -3px 5px;
	}

	.img-box {
	max-width: 90%;
    margin: auto;
 }
	.img-box img {
  	padding: 0 !important;
}

.article-container {
	margin: .5rem .5rem 3rem;
}

.post-info-container {
	padding-bottom: 2rem;
}

.post-info {
    text-decoration: none !important;
	padding: 1rem;
	margin: 0, 2rem;
	float: right;
	text-align: right;
}

.recent {
	max-width: 100%;
	margin: auto;
  	padding: 1em 1em 1em;
	background-color: var(--surface0);
	border: 1px solid  1px solid var(--base);
	border-bottom: 0;
}

.recent-posts {
	margin: 1rem 1rem 3rem;
}

/* ------------------------------------------- [FOOTER]*/

.footer-main {
	position: relative;
	left: 0 !important;
	bottom: 0 !important;
	margin: 0;
	background-color: var(--base);
	padding: 1em 0 1.5em 0;
	text-align: center;
}