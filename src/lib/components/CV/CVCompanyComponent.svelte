<script>
	export let companyName;
	export let companyLink;
	export let timespan;
	export let noBottomPadding = false;
</script>

<li class:no-bottom-padding={noBottomPadding}>
	<h4 class="mb-2"><a href="{companyLink}" class="company-link" target="_blank">{companyName}</a>
	</h4>
	<span class="time">{timespan}</span>
	<ul class="list-inline resume-list my-3">
		<slot />
	</ul>
</li>

<style>
    .no-bottom-padding {
        padding-bottom: 0;
    }
</style>