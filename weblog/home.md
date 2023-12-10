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

<header>
    <div class="image-container">
        <img src="https://cdn.some.pics/laurel/64e91056c93bb.jpg">
    </div>
	<h1 class="weblog-title"><a href="{base-path}">{weblog-title}</a></h1>
	{navigation}
</header>

<main>

{body}

<nav>
{previous-page}
{next-page}
</nav>

</main>

<footer>
	<p>Made with <a href="https://weblog.lol">weblog.lol</a>.</p>
</footer>

</body>
</html>