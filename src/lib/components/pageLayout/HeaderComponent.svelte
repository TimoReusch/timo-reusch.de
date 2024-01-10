<script>
	import { onMount } from 'svelte'

	onMount(() => {

	})
</script>

<header class="navigation horizontal_header transparentOnScroll navbar navbar-expand-lg fixed-top">
	<div class="header-ins">
		<div class="container">
			<!--LOGO AREA-->
			<div class="site-logo">
				<a href="#" class="hoveroff" title="">
					<!--<img src="" alt="">-->
					TIMO<span>REUSCH</span>
				</a>
			</div>
			<button class="button-toggler navbar-toggler collapsed" type="button" data-target="#navigation"
							data-toggle="collapse" aria-controls="navigation" aria-expanded="false">
				<span></span>
				<span></span>
				<span></span>
			</button>
			<!--Main Navigation START-->
			<ul class="justify-content-end scrollspy collapse navbar-collapse" id="navigation">
				<li>
					<a href="#home" class="nav-link">Home</a>
				</li>
				<li>
					<a href="#about" class="nav-link">About</a>
				</li>
				<li>
					<a href="#stack" class="nav-link">Stack</a>
				</li>
				<li>
					<a href="#resume" class="nav-link">Resumé</a>
				</li>
			</ul>
			<!--Main Navigation END-->
		</div>
	</div>
</header>