<script>
	export let companyName;
	export let companyLink;
	export let timespan;
	export let jobTitle;
	export let stack;
	export let noBottomPadding = false;
</script>

<li class:no-bottom-padding={noBottomPadding}>
	<h4 class="mb-2"><a href="{companyLink}" class="company-link" target="_blank">{companyName}</a></h4>
	{#if jobTitle}
		<h4 class="mb-2">- {jobTitle} -</h4>
	{/if}
	<span class="time">{timespan}</span>
	<div class="content">
		<slot />
	</div>

	{#if stack}
		<p>Main technologies used: {stack}</p>
	{/if}

</li>

<style>
    .no-bottom-padding {
        padding-bottom: 0;
    }

		.content {
        color: #b5b5b5;
				font-size: 1rem;
		}
</style>