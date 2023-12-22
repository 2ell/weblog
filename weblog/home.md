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

<div class="gradient-frame">
    <div class="top">
        <div class="top-container">
        <div class="top-left">
            <h3 class="top-title">wblg</h3>
        </div>
        <a rel="me" href="https://social.lol/@laurel"></a>
        <div class="top-right">
    <i class="fa-solid fa-solid fa-hourglass"></i>
    <a rel="me" href="https://laurel.omg.lol/now">now</a>
    <i class="fa-solid fa-solid fa-message"></i>
    <a rel="me" href="https://laurel.status.lol/">status</a>
    <i class="fa-solid fa-solid fa-rss"></i>
    <a rel="me" href="https://laurel.weblog.lol">weblog</a>   
    </div>
</div>
</div>
</div>    

  </head>
  <body>

    <main>
		<div class="main">
			<div class="wrapper">
			<div class="header-text">
				<h1 id="weblog-title"><a href="{base-path}">{weblog-title}</a></h1>
					<h3 class="description"><i>a weblog in the process of arriving</i></h3>
						<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam tristique et mi non aliquet. Vestibulum faucibus luctus justo. Pellentesque eu risus at nibh commodo ultricies. </p>
			</div>
	</div>
</div>


{body}
<hr class="post-spacing"></hr>

{previous-page}
{next-page}
<hr class="post-spacing"></hr>

</main>

	<footer class="footer-main">

			<span>made with <i class="fa-solid fa-heart" style="color: var(--pink)"></i> by <a href="https://laurel.omg.lol">laurel</a></span>
			<br>
			<span>powered by the endlessly delightful <a href="https://home.omg.lol/referred-by/laurel">omg.lol</a></span>
	</footer>
</body>
</html>