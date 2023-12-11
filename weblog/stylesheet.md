Type: File
Content-Type: text/css
Title: Stylesheet
Location: /style.css

:root {
	--foreground: #F8F8F2;
	--background: #282A36;
	--link: #9580ff;
	--accent: #BD93F9;
	--background-color: #282a36;
  	--main-color: #44475a;
  	--comment: #6272a4;
  	--cyan: #8be9fd;
  	--green: #50fa7b;
  	--orange: #ffb86c;
  	--pink: #ff79c6;
  	--purple: #bd93f9;
	  --purple-faint: #ac9cc2;
  	--red: #ff5555;
  	--yellow: #f1fa8c;
}

/* -------------------------------------------------------------------------------------------- [ MOBILE ] */
@media (max-width: 600px) {
  .weblog-title a {
    font-size: 2rem;
  }

  header nav li a {
	font-size: 0.8rem;
	padding: 0.2rem;
  }

}

* {
	margin: auto;
}

body {
	font-family: 'Lato', sans-serif;
	font-size: 1em;
	color: var(--foreground);
	background: var(--background);
}


.centre {
	text-align: center !important;
}

.spacing {
	min-height: 2em;
	margin-bottom: 2em;
}

.post-spacing {
	margin-bottom: 2em;
}

/* -------------------------------------------------------------------------------------------- [ TITLES ] */

.weblog-title {
	text-align: center;
	margin: auto;
	text-shadow: .1em .1em 0.2 hsla(202, 54%, 93%, 1);
}

.weblog-title a {
	font-size: 3rem;
	padding-top: 0.5rem;
	line-height: 3.5rem;
}

.description {
	text-align: center;
	color: var(--foreground);
	opacity: 0.9;
	margin-top: -0.1rem;
}


/* -------------------------------------------------------------------------------------------- [ EFFECTS ] */

.shadow {
	text-shadow: 6px 6px 0px #0000000c;
	z-index: 1;
}

.b-shadow {
	box-shadow: 6px 6px 0px #0000000c;
}

.gradient1 {
background-image: linear-gradient(8deg, var(--yellow), var(--cyan)) !important;
	background-size: cover;
    color: transparent !important;
    -webkit-background-clip: text;
    background-clip: text;
	z-index: 10;
}

.gradient:hover {
    background-image: linear-gradient(20deg, var(--yellow), var(--purple), var(--cyan)) !important;
	background-size: cover;
    color: transparent !important;
    -webkit-background-clip: text;
    background-clip:;
	z-index: 10;
}


/* ----------------------------------------------------------------------------------------- [ HEADER/NAV ] */

header {	
	background: #44475a;
	border-radius: 0.7em;
	max-width: 50vw;
}


header {
	margin-top: 2em;
	padding: 2em 2em;
	box-shadow: 6px 6px 6px 6px #0000000c;
}

header nav {
	text-align: center;
}

header nav ul {
	list-style-type: none;
	margin: 0;
	padding: 0;
}

header nav li {
	display: inline-block;
}

header nav li a {
	display: inline-block;
	padding: 0.4rem;
	text-align: center;
	text-decoration: none;
}

header nav li a:hover {
	color: var(--foreground);
	text-shadow: 6px 6px 0px #0000000c;
}

/* ----------------------------------------------------------------------------------------------- [ TYPE ] */

h1, h2, h3, h4, h5, h6 {
	font-family: 'VC Honey Deck', serif;
	margin: 1rem 0;
	text-shadow: 6px 6px 0px #0000000c;
}


p, li {
	max-width: 60cw;
	line-height: 1.5em;
}

a:link { color: var(--purple); }
a:visited { color: var(--purple); }
a:hover { color: var(--pink); }
a:active { color: var(--pink); }

main a, footer  a {
	text-decoration: none;
	border-bottom: 1px dotted var(--purple-faint);
}

/* -------------------------------------------------------------------------------------- [ SECTIONS ] */


main {
    max-width: 30em;
	margin-top: 0.4em;
	padding: 2em 2em;
}

.card {
	padding: 1rem;
	border-radius: 0.7rem;
	box-shadow: 6px 6px 6px 6px #0000000c;
}

.header-img {
  border-radius: 0.7em;
  opacity: 0.7;
  filter: saturate(4) !important;
  background-blend-mode: multiply;
}

.img-box {
	padding: 0;
	max-width: 90%;
    margin: auto;
 }

.img-box img {
  margin: 0 !important;
  padding: 0 !important;
  border-radius: 0.7em;
  opacity: 0.7;
  filter: saturate(4);
  background-blend-mode: multiply;
}

.img-card {
	border-radius: 40%;
	max-height: 250px;
	max-width: 250px;
}

.prami-logo {
	height: 1em;
	transition: all 0.3s ease;
	margin: 0 .3em -.1em 0;
}

/* ------------------------------------------------------------------------------------------- [POST] */

article {
	margin-top: 1rem;
}

aside {
	margin-bottom: 0.5rem;
}

.post-info {
    text-decoration: none !important;
	margin-top: 1.5em;
	text-shadow: 6px 6px 0px #0000000c;
}

.post-info, .post-tags {
	font-size: 0.9em;
	color: var(--accent);
	text-align: right;
}

.post-info i:nth-child(2) {
	padding-left: 1em;
}

.tag {
	font-size: 0.8rem;
    background-color: var(--purple);
	color: var(--background) !important;
	padding: .1em .2em;
	margin: .8em 0 0 .4em;
	border-radius: 0.7em;
	display: inline-block;
}

.tag a {
	border-bottom: none !important;
	text-decoration: none !important;
}

.post-info i {
	padding-right: 0.2rem;
}

.stream {
	max-width: 50%;
}

hr {
	background-image: linear-gradient(135deg, var(--purple), var(--cyan));
	background-size: 100%;
	padding: 0.04rem;
	border: 0;
}

.div-yellow {
	margin-top: 1em;
	background-image: linear-gradient(120deg, var(--purple), var(--yellow), var(--purple));
	height: 0.01rem;
}

.div-pink {
	margin-top: 1em;
	background-image: linear-gradient(120deg, var(--pink), var(--cyan), var(--pink));
	height: 0.01rem;
}

code {
	padding: .2em .3em;
	border: 1px solid var(--accent);
	white-space: pre-wrap;
	word-wrap: break-word; 
}

pre, code {
	font-family: 'MD IO 0.4';
	font-size: 90%;
}

pre code {
	background: #000;
	color: #eee;
	display: inline-block;
	padding: 1em;
	white-space: pre-wrap;
	word-wrap: break-word;   
}

img {
	max-width: 100%;
}

table {
	border-collapse: collapse;
}

td, th {
	padding: .75em;
	text-align: left;
	border: 1px solid var(--accent);
}

/* -------------------------------------------------------------------------------------- [ FOOTER ] */

footer {
	position: relative;
	left: 0;
	bottom: 0;
	width: 100%;
	margin-top: 1em;
	background-color: var(--main-color) !important;
	color: var(--foreground) !important;
	padding-top: 2em;
	padding-bottom: 1em;
	box-shadow: 6px 6px 6px 6px #0000000c;
}

footer p {
	font-size: 0.9em;
	font-family: 'VC Honey Deck', serif;
	color: var(--foreground);
	text-align: center;
}

#footer a {
    text-decoration: none !important;
	text-transform: lowercase;
	color: var(--foreground) !important;
	font-family: 'VC Honey Deck', serif;
}