<script>
	export let programName;
	export let programLink;
	export let timespan;
	export let universityName;
	export let noBottomPadding = false;
</script>

<li class:no-bottom-padding={noBottomPadding}>
	<h4 class="mb-2"><a href="{programLink}" class="company-link" target="_blank">{programName}</a>
	</h4>
	<span class="time">{universityName}</span><br>
	<span class="time">{timespan}</span>
</li>

<style>
    .no-bottom-padding {
        padding-bottom: 0;
    }
</style>