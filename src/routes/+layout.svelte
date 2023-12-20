<script>
	import '../app.scss';
	import 'aos/dist/aos.css';

	import Header from './Header.svelte';
	import Footer from './Footer.svelte';
	import AOS from 'aos';
	import { onMount } from 'svelte';

	onMount(() => {
		AOS.init({
			once: true
		});
	});
</script>

<Header />
<main class="content center-main">
	<slot />
</main>
<Footer />