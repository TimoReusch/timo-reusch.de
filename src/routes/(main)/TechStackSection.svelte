<script>
	import SectionContainer from '$lib/containers/SectionContainer.svelte';
	import pythonLogo from '$lib/assets/images/logos/python.svg';
	import mariaDBLogo from '$lib/assets/images/logos/mariaDB.svg';
	import abapLogo from '$lib/assets/images/logos/sap.svg';
	import sapUI5Logo from '$lib/assets/images/logos/sapui5.svg';
	import arduinoLogo from '$lib/assets/images/logos/arduino.svg';
	import azureDevOpsLogo from '$lib/assets/images/logos/azure_devops.png';
	import TechIcon from '$lib/components/TechIconComponent.svelte';
</script>

<section class="stack background_gpattern" id="stack">
	<SectionContainer title="What I Work With" backgroundText="Tech Stack">
		<div class="row">
			<div class="col">
				<div class="row">
					<div class="col-md-6">
						<div class="row">
							<div class="col">
								<p>Languages</p>
							</div>
						</div>
						<div class="row">
							<TechIcon technologyName="Python">
								<img src={pythonLogo} width="35" style="margin-right: 20px;">
							</TechIcon>
							<TechIcon technologyName="JavaScript">
								<span class="devicon-javascript-plain colored icon"></span>
							</TechIcon>
							<TechIcon technologyName="Swift">
								<span class="devicon-swift-plain colored icon"></span>
							</TechIcon>
							<TechIcon technologyName="Dart">
								<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/dart/dart-original.svg" width="35" style="margin-right: 20px;"/>
							</TechIcon>
							<TechIcon technologyName="Kotlin">
								<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kotlin/kotlin-original.svg"
										 width="35"
										 style="margin-right: 20px;" />
							</TechIcon>
						</div>
					</div>
					<div class="col-md-6">
						<div class="row">
							<div class="col">
								<p>Frameworks & Tools</p>
							</div>
						</div>
						<div class="row">
							<TechIcon technologyName="FastAPI">
								<span class="devicon-fastapi-plain colored icon"></span>
							</TechIcon>
							<TechIcon technologyName="MariaDB">
								<img src={mariaDBLogo} width="35" style="margin-right: 20px;">
							</TechIcon>
							<TechIcon technologyName="SvelteKit">
								<span class="devicon-svelte-plain colored icon"></span>
							</TechIcon>
							<TechIcon technologyName="Flutter">
								<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/flutter/flutter-original.svg" width="35" style="margin-right: 20px;"/>
							</TechIcon>
							<TechIcon technologyName="Bootstrap">
								<span class="devicon-bootstrap-plain icon"></span>
							</TechIcon>
							<TechIcon technologyName="SASS">
								<span class="devicon-sass-original colored icon"></span>
							</TechIcon>
							<TechIcon technologyName="Docker">
								<span class="devicon-docker-plain colored icon"></span>
							</TechIcon>
							<TechIcon technologyName="GitHub">
								<span class="devicon-github-original icon"></span>
							</TechIcon>
						</div>
					</div>
				</div>
			</div>
		</div>
		<div class="row">
			<div class="col">
				<h3 class="mt-5 mb-4">Worked with before</h3>
				<div class="row">
					<div class="col-md-6">
						<div class="row">
							<div class="col">
								<p>I don't use these on a daily basis, but from time to time:
								</p>
							</div>
						</div>
						<div class="row">
							<TechIcon technologyName="WordPress">
								<span class="devicon-wordpress-plain icon"></span>
							</TechIcon>
							<TechIcon technologyName="PHP">
								<span class="devicon-php-plain colored icon"></span>
							</TechIcon>
							<TechIcon technologyName="Java">
								<span class="devicon-java-plain colored icon"></span>
							</TechIcon>
							<TechIcon technologyName="GitLab">
								<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/gitlab/gitlab-original.svg"
										 width="35" style="margin-right: 20px;" />
							</TechIcon>
							<TechIcon technologyName="Google Cloud">
								<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/googlecloud/googlecloud-original.svg"
										 width="35" style="margin-right: 20px;" />
							</TechIcon>
							<TechIcon technologyName="Microsoft Azure">
								<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/azure/azure-original.svg"
										 width="32" style="margin-right: 23px;" />
							</TechIcon>
						</div>
					</div>
					<div class="col-md-6">
						<div class="row">
							<div class="col">
								<p>I haven't used those in a while now, but worked with them in the past:
								</p>
							</div>
						</div>
						<div class="row">
							<TechIcon technologyName="ABAP">
								<img src={abapLogo} style="margin-right: 20px;">
							</TechIcon>
							<TechIcon technologyName="SAPUI5">
								<img src={sapUI5Logo} style="margin-right: 25px;">
							</TechIcon>
							<TechIcon technologyName="Firebase">
								<span class="devicon-firebase-plain colored icon"></span>
							</TechIcon>
							<TechIcon technologyName="Spring">
								<span class="devicon-spring-plain colored icon"></span>
							</TechIcon>
							<TechIcon technologyName="Arduino">
								<img src={arduinoLogo} style="margin-right: 25px;">
							</TechIcon>
							<TechIcon technologyName="Azure DevOps">
								<span style="margin-right: 20px;">
									<img src={azureDevOpsLogo} width="35">
								</span>
							</TechIcon>
						</div>
					</div>
				</div>
			</div>
		</div>
	</SectionContainer>
</section>