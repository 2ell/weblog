Type: Template
Title: Landing Page Template

<!DOCTYPE html>
<html lang="en">
<head>
<title>{weblog-title}</title>
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
	<div class="left">
		<h2 class="top-title"><a href="https://laurel.weblog.lol">wblg </a>{separator} <span class="page-title"><a href="{location}">{weblog-title}</a></span></h2>
		</div>
	<div class="right">
		<i class="fa-solid fa-bars"></i>
	</div>
</div>


<div class="top-nav">
	<div class="left">
		<ul class="no-line">
<li><a href="https://laurel.omg.lol/">@laurel</a></li>
<li><a href="https://laurel.omg.lol/now">/now</a></li>
<li><a href="https://laurel.status.lol">/status</a></li>
	</ul>
	</div>
		<div class="right">	
		</div>
</div>	
		<nav>
			<ul>
				<li><a href="/about">about</a></li>
				<li><a href="/index">index</a></li>
				<li><a href="/colophon">colophon</a></li>
				<li><a href="/linkroll">linkroll</a></li>

				<li><a href="https://laurel.weblog.lol/xml.rss">rss</a></li>
	</div>
			</ul>
		</nav>

	<header>

<div class="header-container">
		<div class="gradient-bg-circle">
			<img class="header-img" src="https://i.postimg.cc/9FZvWMzb/circle.png">
			</div>
	<h1 id="weblog-title" class="gradient"><a href="{base-path}">{weblog-title}</a></h1>
	<h5 class="description">{weblog-description}</h5>
	<hr class="divider"></hr>
</header>
</div>
</head>	

<main>

{body}
<hr class="post-spacing"></hr>

{previous-page}
{next-page}
<hr class="post-spacing"></hr>

</main>

<footer class="footer-main">
	<p>handmade with <i class="fa-solid fa-heart" style="color: var(--pink)"></i> by <a href="https://laurel.omg.lol">laurel</a></p>
	<p>powered by <a href="https://home.omg.lol/referred-by/laurel">omg.lol</a>'s super nifty <a href="https://weblog.lol">weblog</a> service </p>
	</footer>

</body>
</html>