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
	<div class="top-left">
		<h2 class="top-title">
			<a href="https://laurel.weblog.lol">wblg </a>{separator} <span class="page-title">{weblog-title}</span>
		</h2>
		</div>
	<div class="top-right">
		<i class="fa-solid fa-bars"></i>
	</div>
</div>


<div class="top-nav">
	<div class="top-nav-left">
		<ul class="no-line">
<li><a href="https://laurel.omg.lol/">@laurel</a></li>
<li><a href="https://laurel.omg.lol/now">/now</a></li>
<li><a href="https://laurel.status.lol">/status</a></li>
	</ul>
	</div>
		<div class="top-nav-right">	

		</div>
</div>	
		<nav>
			<ul>
				<li><a href="/about">about</a></li>
				<li><a href="/theindex">index</a></li>
				<li><a href="/colophon">colophon</a></li>
				<li><a href="/linkroll">linkroll</a></li>

				<li><a href="https://laurel.weblog.lol/xml.rss">rss</a></li>
	</div>
			</ul>
		</nav>

	<header>
<div class="header-container">
		<div class="header-img">
			<img src="https://i.postimg.cc/9FZvWMzb/circle.png">
			</div>
	<div class="header-text">
	<h1 id="weblog-title"><a href="{base-path}">{weblog-title}</a></h1>
	<h3 class="description">A thoughtful description</h3>
	<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam tristique et mi non aliquet. Vestibulum faucibus luctus justo. Pellentesque eu risus at nibh commodo ultricies. Fusce maximus convallis sapien, at consectetur turpis tempus id. Duis elit nibh, lacinia eget erat et, sollicitudin vehicula sem. Donec id aliquet dui, ac porttitor massa. Integer congue vestibulum commodo. Nunc in felis ut enim mattis viverra ac eget arcu. Sed posuere orci eget consectetur accumsan. </p>
</div>
</div>
</div>
</header>
</head>	

<body>
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