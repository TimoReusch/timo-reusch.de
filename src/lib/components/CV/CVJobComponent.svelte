<script>
	export let jobTitle;
	export let timespan;
	export let noBottomPadding = false;
	export let stack = "";
</script>

<li class:no-bottom-padding={noBottomPadding}>
	<h4 class="mb-2">{jobTitle}
	</h4>
	<span class="time">{timespan}</span>
	<p class="my-2">
		<slot />
	</p>

	<slot name="additionalContent" />

	{#if stack}
		<p>Main technologies used: {stack}</p>
	{/if}

</li>

<style>
    .no-bottom-padding {
        padding-bottom: 0;
    }
</style>