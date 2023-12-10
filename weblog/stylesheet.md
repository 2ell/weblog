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
  	--red: #ff5555;
  	--yellow: #f1fa8c;
}

@media (prefers-color-scheme: dark) {
	:root {
	--foreground: #F8F8F2;
	--background: #282A36;
	--link: #9580ff;
	--accent: #BD93F9;
	}
}

* {
	margin: auto;
	size: 1em;
}

body {
	font-family: 'Lato', sans-serif;
	font-size: 1em;
	color: var(--foreground);
	background: var(--background);
}


/* -------------------------------------------------------------------------------------- [ TITLE ] */

	
.weblog-title a {
	font-size: 1.5rem;
	color: var(--foreground) !important;
	margin: 0;
}

#author {
	color: var(--background-color);
	display: none;
	font-size:1.5em;
	margin-top: -1rem;
	margin-left: 1rem;
}

/* -------------------------------------------------------------------------------------- [ NAV ] */

header nav ul {
	list-style-type: none;
	margin: 0;
	padding: 0;
}

header nav li {
	display: inline-block;
}

header nav li a {
	display: block;
	text-decoration: none;
	margin-right: 1em;
}

/* -------------------------------------------------------------------------------------- [ TYPE ] */

h1, h2, h3, h4, h5, h6 {
	font-family: 'VC Honey Deck', serif;
	margin: 1rem 0;
}


p, li {
	line-height: 1.5em;
}


a:link { color: #9580ff; }
a:visited { color: #9580ff; }
a:hover { color: #BD93F9; }
a:active { color: #6272A4; }


/* -------------------------------------------------------------------------------------- [ SECTIONS ] */


header {	
	background: #44475a;
	border-radius: 0.7em;
	max-width: 50%;
}


header {
	margin-top: 2em;
	padding: 2em 2em;
}

main {
	max-width: 60%;
	margin-top: 2em;
	padding: 2em 2em;
}

.post {
	padding-bottom: 2em;
}

.image-container {
	background-image: -webkit-linear-gradient(60deg, #bd93f9, #8be9fd) !important;
	padding: 0.4rem;
	border-radius: 0.7em;
 }

.image-container img {
  margin: 0 !important;
  padding: 0 !important;
  border-radius: 0.7em;
  opacity: 0.7;
  filter: saturate(4);
  background-blend-mode: multiply;
}

.img-card {
	border-radius: 50%;
	max-height: 250px;
	max-width: 250px;
}

.prami-logo {
	height: 1em;
	transition: all 0.3s ease;
	margin: 0 .3em -.1em 0;
}

/* -------------------------------------------------------------- [POST] */

.post-info, .post-tags {
	font-size: 0.9em;
	color: var(--accent);
	text-align: right;
}

.post-info i:nth-child(2) {
	margin-left: 1em;
}

.tag {
	background: var(--accent);
	font-size: 0.8rem;
	color: var(--background) !important;
	padding: .1em .2em;
	margin: .8em 0 0 .4em;
	border-radius: .5em;
	text-decoration: none;
	display: inline-block;
}

.post-info i {
	padding-right: 0.5rem;
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

#footer {
	min-width: 100% !important;
	color: var(--forground) !important;
	padding-top: 0! important;
	padding-bottom: 2em;
	border-radius: 0.7rem;
}

footer p {
	margin-top: 2em;
	font-size: 0.9em;
	font-family: 'VC Honey Deck', serif;
	color: #F8F8F2;
	text-align: center;
	padding: 2em 2em;
}

#footer a {
	text-transform: lowercase;
	color: var(--forground) !important;
	font-family: 'VC Honey Deck', serif;
}

#footer a:hover {
	text-decoration: underline;
}