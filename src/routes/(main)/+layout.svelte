<script>
	import '../../app.scss';
	import 'aos/dist/aos.css';

	import Header from '$lib/components/pageLayout/HeaderComponent.svelte';
	import Footer from '$lib/components/pageLayout/FooterComponent.svelte';
	import AOS from 'aos';
	import { onMount } from 'svelte';
	import { page } from '$app/stores';
	import SimpleHeader from '$lib/components/pageLayout/SimpleHeaderComponent.svelte';
	let simpleHeader = false;

	$: if ($page.url.pathname) setHeader();

	onMount(() => {
		AOS.init({
			once: true
		});

		setHeader();
	});

	function setHeader(){
		if($page.url.pathname.includes("imprint") || $page.url.pathname.includes("privacy")){
			simpleHeader = true;
		} else {
			simpleHeader = false;
		}
	}
</script>

{#if simpleHeader}
	<SimpleHeader />
{:else }
	<Header />
{/if}
<main class="content center-main">
	<slot />
</main>
<Footer />