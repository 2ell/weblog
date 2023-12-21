Type: Template
Title: Page Template

<!DOCTYPE html>
<html lang="en">
<head>
<title>{weblog-title}{separator}{post-title}</title>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
{feeds}
<style>
@import url('https://static.omg.lol/type/font-honey.css');
@import url('https://static.omg.lol/type/font-lato-regular.css');
@import url('https://static.omg.lol/type/font-lato-bold.css');
@import url('https://static.omg.lol/type/font-lato-italic.css');
@import url('https://static.omg.lol/type/font-md-io.css');
@import url('https://static.omg.lol/type/fontawesome-free/css/all.css');
</style>
<link rel="stylesheet" href="https://laurel.weblog.lol/style.css">


	<div class="top">
		<div class="top-left">
			<h2 class="top-title">
				<a href="https://laurel.weblog.lol">wblg</a>
			</h2>
		</div>
		<div class="top-right">
			<ul>
				<li><a href="/about">about</a></li>
				<li><a href="/theindex">index</a></li>
				<li><a href="/colophon">colophon</a></li>
				<li><a href="/linkroll">linkroll</a></li>
				<li><a href="https://laurel.weblog.lol/xml.rss">rss</a></li>
			</ul>
		</div>
	</div>


	<header>
	<div class="header-container">
			<div class="header-img">
				<img src="https://cdn.some.pics/laurel/65766b3770711.jpg">
			</div>

			<div class="header-text">
				<h1 id="weblog-title"><a href="{base-path}">{weblog-title}</a></h1>
					<h3 class="description">A thoughtful description</h3>
						<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam tristique et mi non aliquet. Vestibulum faucibus luctus justo. Pellentesque eu risus at nibh commodo ultricies. </p>
			</div>
	</div>
	</header>

</head>	

<body>
<main>

{body}


<div class="spacing">
</div>
</main>

<footer class="footer-main">
			<span>made with <i class="fa-solid fa-heart" style="color: var(--pink)"></i> by <a href="https://laurel.omg.lol">laurel</a></span>
			<br>
			<span>powered by the endlessly delightful <a href="https://home.omg.lol/referred-by/laurel">omg.lol</a></span>
	</footer>
</body>
</html>