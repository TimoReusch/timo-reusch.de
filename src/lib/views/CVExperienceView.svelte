<script>
	import CVJob from '$lib/components/CV/CVJobComponent.svelte';
	import CVCompany from '$lib/components/CV/CVCompanyComponent.svelte';
	import CVContainer from '$lib/containers/CVContainer.svelte';
</script>

<CVContainer>
	<CVCompany companyName="Julius-Maximilians-Universiät Würzburg - Chair of computer science X (Data Science)"
						 companyLink="https://www.informatik.uni-wuerzburg.de/datascience/"
						 timespan="Sept. 2022 - now">
		<CVJob jobTitle="Student Research Assistant, Anomaly Detection"
					 timespan="Sept. 2023 - now"
					 stack="Python for ML, Docker">
		</CVJob>
		<CVJob jobTitle="Software Developer"
					 timespan="Sept. 2022 - Sept. 2023"
					 noBottomPadding="true"
					 stack="FastAPI, Svelte, Docker">
			Design and development of a web-application for the annotation of datasets in a user-friendly way.
		</CVJob>
	</CVCompany>

	<CVCompany companyName="bb-net media GmbH"
						 companyLink="https://bb-net.de"
						 timespan="Jan. 2020 - Sept. 2022">
		<CVJob jobTitle="Project Manager / Software Developer"
					 timespan="June 2021 - Sept. 2022"
						stack="Azure DevOps, Java, Swift, Figma">
			Planning and carrying out the re-development of an internal software tool used to automate big parts of the
			refurbishment process.
			<ul class="unorderedList">
				<li>System Architecture Design</li>
				<li>Migration of the codebase from VBS to Java</li>
				<li>Redesign and migration of the database</li>
			</ul>
		</CVJob>

		<CVJob jobTitle="Software Developer"
					 timespan="Jan. 2020 - June 2021"
					 noBottomPadding="true"
		stack="PHP, WordPress, Bootstrap">
			<ul class="unorderedList">
				<li>Implementation of new features for the company's self-written PHP-based ERP-system</li>
				<li>Rebuilding the frontend of the online shop</li>
				<li>Search Engine Optimization for the company website</li>
				<li>Redesign of bb-net.de and tecxl.de</li>
			</ul>
		</CVJob>
	</CVCompany>

	<CVCompany companyName="SAP SE" companyLink="https://www.sap.com/germany/index.html"
						 timespan="Sept. 2018 - Sept. 2019" noBottomPadding="true">
		<CVJob jobTitle="Corporate Student @ Intelligent Enterprise Solutions"
					 timespan="Jan. 2019 - Sep. 2019">
			Next Level IT Lab is building IT Showrooms at SAP Locations worldwide, to showcase how SAP is transforming into an
			intelligent enterprise with a future workplace. Tasks included:
			<ul class="unorderedList">
				<li>Development of an Angular Front-End for one of the showroom stations</li>
				<li>Supported the daily showroom business</li>
				<li>Development of a video-based E-Learning solution used to train guides for showroom tours</li>
			</ul>
		</CVJob>

		<CVJob jobTitle="Project lead: Imagefilm @ VT" timespan="Jan. 2019 - Sept. 2019">
			As a team of students, we created a concept for a new VT
			commercial and produced it. The end result can be watched on YouTube and
			sap.de/ausbildung

			<div slot="additionalContent">
				<a href="https://youtu.be/9Ee8QmSTj58" target="_blank"
					 class="btn btn-outline-primary btn-small mt-3">
					Watch the commercial
				</a>
			</div>
		</CVJob>

		<CVJob jobTitle="Corporate Student (Business Computer Science focused on Sales & Consulting)"
					 timespan="Sept. 2018 - Sept. 2019" noBottomPadding="true">
			<ul class="unorderedList">
				<li>Realizing an Android app concept & prototype for accessing SAP facilities with your smartphone during a
					hackathon
				</li>
				<li>Content creation for SAPs social media channels</li>
				<li>Attending various trainings for project management, agile software development, User Experience & UI-Design,
					ABAP-Development
				</li>
			</ul>
		</CVJob>
	</CVCompany>
	<li></li>
</CVContainer>

<style lang="scss">
  .unorderedList {
    list-style-type: disc;
    padding-left: 20px;
    margin-top: 10px;

    li {
      position: static; /* Reset to default */
      padding: initial; /* Reset to default */

      &:before, &:after {
        content: none;
      }
    }
  }
</style>