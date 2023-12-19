<script>
	import "../app.scss";
	import Header from "./Header.svelte";
	import Footer from "./Footer.svelte";
</script>

<Header />
<main class="content center-main">
	<slot />
</main>
<Footer />