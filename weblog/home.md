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
</head>
<body>
<div class="gradient-bg">
	<header>
    <img class="header-img" src="https://i.postimg.cc/9FZvWMzb/circle.png">
	<h1 id="weblog-title" class="gradient"><a href="{base-path}">{weblog-title}</a></h1>
	<h5 class="description">{weblog-description}</h5>
	<nav>
	{navigation}
</nav>
</header>
</div>

<main>

{body}

<nav>
{previous-page}
{next-page}
</nav>

</main>

<footer class="footer-main">
	<p>handmade with <i class="fa-solid fa-heart" style="color: var(--pink)"></i> by <a href="https://laurel.omg.lol">laurel</a></p>
	<p>powered by <a href="https://home.omg.lol/referred-by/laurel">omg.lol</a>'s super nifty <a href="https://weblog.lol">weblog</a> service </p>
	</footer>

</body>
</html>