<script>
	export let technologyName;
</script>

<div class="col-6">
	<div class="iconContainer">
		<slot />
		<span>{technologyName}</span>
	</div>
</div>