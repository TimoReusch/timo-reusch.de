<script>
import CVContainer from '$lib/containers/CVContainer.svelte';
import CVUniversityComponent from '$lib/components/CV/CVEducationComponent.svelte';
</script>

<CVContainer>
	<CVUniversityComponent universityName="Julius-Maximilians-University of Würzburg"
												 programName="M.Sc. Computer Science"
												 programLink="https://www.informatik.uni-wuerzburg.de/studium/studiengaenge/master-informatik/"
												 timespan="April 2024 - Oct. 26"
	/>
	<CVUniversityComponent universityName="Julius-Maximilians-University of Würzburg"
												 programName="B.Sc. Computer Science"
												 programLink="https://www.informatik.uni-wuerzburg.de/studium/studiengaenge/bachelor-informatik/"
												 timespan="Oct. 2020 - Oct. 2024"
	/>
</CVContainer>