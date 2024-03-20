<script>
	import SectionContainer from '$lib/containers/SectionContainer.svelte';
	import CVExperienceView from '$lib/views/CVExperienceView.svelte';
	import CVEducationView from '$lib/views/CVEducationView.svelte';
</script>

<section class="resume background_gpattern" id="resume">
	<SectionContainer title="Experience" backgroundText="Resumé">
		<CVExperienceView />
	</SectionContainer>

	<SectionContainer title="Education" backgroundText="Resumé">
		<CVEducationView />
	</SectionContainer>
</section>