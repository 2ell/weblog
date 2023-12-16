Type: File
Content-Type: text/css
Title: Stylesheet
Location: /style.css

/* variables -------------------------------------------------------------------------------------------- [ VARIABLES ] */
:root {
	--transparent:#ffffff0e;
	--foreground: #F8F8F2;
	--foreground-faded: #f8f8f25b;
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
	  --purple-faint: #ccb9e6;
  	--red: #ff5555;
  	--yellow: #f1fa8c;

	--gradient1: linear-gradient(135deg, var(--yellow), var(--purple), var(--cyan));
	--gradient2: linear-gradient(135deg, var(--cyan), var(--purple));

	--border-radius: 0.7rem;
}


/* body -------------------------------------------------------------------------------------------- [ BODY ] */

* {
	margin: auto;
}


body {
	font-family: 'Lato', sans-serif;
	font-size: 1.2em;
	margin: 0;
	padding: 2em;
	color: var(--foreground);
	background: var(--background);
}

a {
	text-decoration: underline;
	color: var(--foreground);
	background-image: var(--gradient2);
	background-size: 0;
	-webkit-background-clip: text;
    	background-clip: text;
	border-bottom: 0.2rem solid var(--transparent);	
	transition: all 0.6s ease-in-out;
	padding-bottom: 0;
}

a:hover {
	background-size: 100%;
	color: transparent;
	-webkit-background-clip: text;
    	background-clip: text;
	border-bottom: 0.2rem solid var(--transparent);
	transition: all 0.4s ease;
}

/* mobile -------------------------------------------------------------------------------------------- [ MOBILE ] */

@media (max-width: 500px) {
	body {
		font-size: 1em;
		padding: 1em;
	}
	main {
		padding: 1.5em;
	}
}

@media screen and (max-width: 600px) {
  header {
	width: 80%;
  }
}


/* override classes -------------------------------------------------------------------------------------- [ OVERRIDES ] */

.centre {
	text-align: center !important;
}

.no-btm {
	margin-bottom: 0;
	padding-bottom: 0;
}

.spacing {
	min-height: 2em;
	margin-bottom: 2em;
}

.post-spacing {
	color: transparent;
	background-image: none;
	border: 0;
	margin-bottom: 2em;
}

/* titles -------------------------------------------------------------------------------------------- [ TITLES ] */

#weblog-title {
	text-align: center;
	margin: auto;
}

#weblog-title a {
	font-size: 3rem;
	text-decoration: none;
	border: none;
	background-image: var(--gradient1);
	background-size: 0;
	background-blend-mode: lighten;
	color: var(--foreground);
	padding-top: 1.5rem;
	padding-bottom: 0;
	transition: all 0.6s ease-in-out;
}

#weblog-title a:hover {
	background-size: 100%;
	color: transparent;
	-webkit-background-clip: text;
    	background-clip: text;
	text-shadow: 
	2px 2px 1px var(--transparent);
	transition: all 0.6s ease-in-out;
}

.description {
	text-align: center;
	color: var(--foreground);
	opacity: 0.9;
	margin-top: -0.1rem;
}

/* hr/dividers ------------------------------------------------------------------------------------------- [HR STYLES] */

hr {
	margin-top: 1em;
	background-image: var(--gradient1);
	height: 0.05rem;
	border: 0;
	max-width: 100%;
}

.divider {
	margin-top: 1em;
	background-image: var(--gradient1);
	height: 0.09rem;
	border: 0;
	max-width: 100%;
}


/* -------------------------------------------------------------------------------------------- [ EFFECTS ] */

.shadow {
	text-shadow: 6px 6px 0px #000000;
}

.b-shadow {
	box-shadow: 
		rgba(0, 0, 0, 0.1) 0px 1px 1px, 
		rgba(0, 0, 0, 0.01) 0px -12px 30px, 
		rgba(0, 0, 0, 0.1) 0px 4px 6px, 
		rgba(0, 0, 0, 0.1) 0px 12px 13px, 
		rgba(0, 0, 0, 0.03) 0px -3px 5px;
}

.gradient-yb {
background-image: linear-gradient(8deg, var(--yellow), var(--cyan)) !important;
	background-size: cover;
    color: transparent !important;
    -webkit-background-clip: text;
    background-clip: text;
	z-index: 10;
}

/* ----------------------------------------------------------------------------------------- [ HEADER/NAV ] */

header {	
	background: #44475a;
	border-radius: var(--border-radius);
	max-width: 600px;
	margin: 2em auto 2em;
	padding: 1em 2em 2em;
	box-shadow: 
		rgba(0, 0, 0, 0.1) 0px 1px 1px, 
		rgba(0, 0, 0, 0.01) 0px -12px 30px, 
		rgba(0, 0, 0, 0.1) 0px 4px 6px, 
		rgba(0, 0, 0, 0.1) 0px 12px 13px, 
		rgba(0, 0, 0, 0.03) 0px -3px 5px;
}

.header-img {
  border-radius: var(--border-radius);
  opacity: 0.7;
  margin: auto !important;
  filter: saturate(4) !important;
  background-blend-mode: multiply;
  display: block;
  padding: 1rem;
}

header nav {
	text-align: center;
}

header nav ul {
	list-style-type: none;
	padding: 2rem;
}

header nav li {
	display: inline-flex;
	padding: 0 0.5rem 0;
}

header nav li a {
	display: inline-flex;
	text-align: center;
	text-decoration: none;
	max-height: fit-content;
}

/* ----------------------------------------------------------------------------------------------- [ TYPE ] */

h1, h2, h3, h4, h5, h6 {
	font-family: 'VC Honey Deck', serif;
	margin: 1rem 0;
	text-shadow: 6px 6px 0px #0000000c;
}


p, li {
	line-height: 1.5em;
}
/*
a:link { color: var(--purple); }
a:visited { color: var(--purple); }
a:hover { color: var(--foreground); }
a:active { color: var(--foreground); }

a {
	background-image: var(--pink);
	background-size: 100%;
	height: 4em;
	transition: all .3s ease-in-out;
}

a:hover {
	background-size: 40%;
	-webkit-background-clip: text;
	background-clip: text;
	opacity: 1;
}
*/
/* -------------------------------------------------------------------------------------- [ LAYOUT ] */

main {
	max-width: 800px;
	margin: auto;
	margin-top: 0.5em;
	padding: 1em 1em 1em 1em;
	font-size: 1em;
	word-break: normal;
	hyphens: auto;
}

main p {
	margin: 1rem 0 1rem;
}

.card {
	margin: 1rem;
	padding: 1rem;
	border-radius: var(--border-radius);
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
  border-radius: var(--border-radius);
  opacity: 0.7;
  filter: saturate(2);
  background-blend-mode: multiply;
}

.image-grid {
  display: flex;
  flex-wrap: wrap;
  justify-content:center;
  margin: 0.5rem;
}

.image-grid img {
  width: 260px; /* Adjust the width as needed */
  height: auto;
  margin: 1rem;
  border-radius: 8px; /* Optional: Add rounded corners */
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* Optional: Add a subtle shadow */
}

.img-card {
	border-radius: var(--border-radius);
	max-height: 250px;
	max-width: 250px;
}

.recent {
	max-width: 550px;
	margin: auto;
  	padding: 0 1em 1em;
	border: 0.5em solid var(--main-color);
	border-radius: var(--border-radius) var(--border-radius) 0 0;
	border-bottom: 0;
}

.recent-posts {
	margin: 1rem 1rem 3rem;
}

/* ------------------------------------------------------------------------------------------- [POST] */

article {
	margin-top: 2rem;
	margin-bottom: 1rem;
}

article h1 a, article h2 a, article h3 a {
	color: var(--foreground) !important;
}

/* date ----------------------------------- [DATE] */

.post-info-container {
	padding-bottom: 2rem;
}

.post-info {
    text-decoration: none !important;
	padding: 0.5rem;
	max-width: fit-content;
	float: right;
	text-shadow: 6px 6px 0px #0000000c;
	font-size: 0.9em;
	border-radius: 0.7rem  0rem 0rem 0.7rem;
	color: var(--foreground);
	text-align: right;
}

.post-info a {
	border-bottom: 1px solid var(--foreground);
}


/* date svg ----------------------------------- [DATE SVG] */
.post-info i {
	padding-right: 0.1rem;
}

/* tags ----------------------------------- [TAGS] */

.post-tags {
	margin-top: 1.5rem;
	text-align: left;
}

.post-info i:nth-child(2) {
	padding-left: 1em;
}

.tag {
	font-size: 0.8rem;
    background-color: var(--purple);
	color: var(--background) !important;
	padding: 0.3rem;
	margin: .8em 0 0 .4em;
	border-radius: 0.7rem;
	display: inline-block;
}

.tag a {
	border-bottom: none !important;
	text-decoration: none !important;
}

.tag:hover {
	background-image: var(--gradient2);
}


.stream {
	max-width: 50%;
}

/* markdown ----------------------------------- [MARKDOWN] */

blockquote {
	line-height: 1em;
	margin: 1rem;
	margin-left: 0.3rem;
	padding: 1rem;
}

blockquote p {
	display: inline;
	font-family: 'VC Honey Deck', serif;
	color: var(--purple);
}


blockquote p:before {
	content: '\201c';
	position: absolute;
	color: var(--purple);
	font-size: 10em;
	margin-left: -0.7rem;
	margin-top: 3rem;
	opacity: 0.1;
}

blockquote .footer {
	text-align: right;
	padding: 1rem 0 0;
}

blockquote .footer:before {
	content: '—';
	padding: 0.5rem;
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

.footer-main {
	position: relative;
	left: 0 !important;
	bottom: 0 !important;
	width: 100%;
	margin: 0;
	background-color: var(--main-color) !important;
	color: var(--foreground) !important;
	padding: 1em 0 1.5em 0;
	box-shadow: 
		rgba(0, 0, 0, 0.1) 0px 1px 1px, 
		rgba(0, 0, 0, 0.01) 0px -12px 30px, 
		rgba(0, 0, 0, 0.1) 0px 4px 6px, 
		rgba(0, 0, 0, 0.1) 0px 12px 13px, 
		rgba(0, 0, 0, 0.03) 0px -3px 5px;
}

.footer-main p {
	font-size: 0.9rem;
	font-family: 'VC Honey Deck', serif;
	color: var(--foreground);
	text-align: center;
}