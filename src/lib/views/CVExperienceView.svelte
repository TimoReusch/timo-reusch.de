<script>
import CVJob from '$lib/components/CV/CVJobComponent.svelte';
import CVCompany from '$lib/components/CV/CVCompanyComponent.svelte';
import CVContainer from '$lib/containers/CVContainer.svelte';
</script>

<CVContainer>
			<CVCompany companyName="Julius-Maximilians-Universiät Würzburg - Chair of computer science X (Data Science)"
								 companyLink="https://www.informatik.uni-wuerzburg.de/datascience/" timespan="Sept. 2022 - now">
				<CVJob jobTitle="Student Research Assistant, Anomaly Detection" timespan="Sept. 2023 - now">
				</CVJob>
				<CVJob jobTitle="Software Developer" timespan="Sept. 2022 - Sept. 2023" noBottomPadding="true">
					Creating a web-application (FastAPI, SvelteKit) experts can use to annotate selected data points of a dataset
					without having any knowledge in machine learning at all. This involves a user- and role-management, as well as
					a highly customizable interface for the annotation process.
				</CVJob>
			</CVCompany>

			<CVCompany companyName="bb-net media GmbH" companyLink="https://bb-net.de" timespan="Jan. 2020 - Sept. 2022">
				<CVJob jobTitle="Project Manager / Software Developer" timespan="June 2021 - Sept. 2022">
					bb-net uses their own software called "SAM" to automate big
					parts of the refurbishment process. SAM carries out all partial processing
					steps automatically and gives the employee special guidance through the
					whole process. The software started as a small script that grew a lot over
					time, which now results in issues in terms of scaling and complexity, why
					EOL is expected in the next few years.<br> My job was to
					plan and carry out the re-development of the whole architecture. This
					involved migrating the whole codebase from VBS to Java, redesigning the
					relational database and planning a highly scalable server infrastructure
					based on Spring Boot.<br>
					I was responsible for the project management and also coded along, working
					with various web technologies, Swift and of course Java.
				</CVJob>

				<CVJob jobTitle="Software Developer" timespan="Jan. 2020 - June 2021" noBottomPadding="true">
					Working with web technologies (HTML, CSS, JavaScript, PHP) on
					the company's own ERP system and online shop, where I developed a few new
					features (like the creation of 360° images and their display in the online
					shop).
					<br> Furthermore, I gave various outdated web-frontends a fresh coat of
					paint, which included a mobile-first approach, complete redesign and SEO.
				</CVJob>
			</CVCompany>

			<CVCompany companyName="SAP SE" companyLink="https://www.sap.com/germany/index.html" timespan="Sept. 2018 - Sept. 2019" noBottomPadding="true">
				<CVJob jobTitle="Software Developer @ Next Level IT Labs & Experiences"
							 timespan="Jan. 2019 - Sep. 2019">
					I worked at the SAP IT division, which takes care of the internal IT of the
					company. There I joined a project called "SAP IT Showroom" within the "Next
					Level IT Lab and Experiences" subdivision.<br> Next
					Level IT Lab is building IT Showrooms at SAP Locations worldwide, to
					showcase how SAP is transforming into an intelligent enterprise with a
					future workplace. Within the Showrooms, visitors can discover products
					and tools from SAP, understand technologies and their impact on daily work
					and leverage tools and technologies to increase productivity.

					<div slot="additionalContent">
						<!-- Also available on Sebastians YouTube channel: https://youtu.be/GGLmQNO2uPE -->
						<a href="https://timo-reusch.de/files/SAP_IT_Showroom.mp4" target="_blank"
							 class="btn btn-outline-primary btn-small mt-4">
							Have a closer look at the showroom
						</a>
						<p>
							<br> During my time there, we planned and opened the first ever IT Showroom
							at the headquarters in Walldorf. <br> Before the opening, I was involved in
							creating the frontend for the Stations, using Angular.
							After the opening, I supported the daily showroom business, which included
							answering technical questions of our colleagues, fixing bugs, documenting
							best practices, coordination with the partially external
							showroom staff and giving tours for the main showroom, as well as the
							VR/AR-Showroom. <br> My main project however became the creation of an
							e-learning solution to train tour guides for the Showroom, which
							is globally used by today.<br>
						</p>
					</div>
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

				<CVJob jobTitle="Corporate Student" timespan="Sept. 2018 - Sept. 2019" noBottomPadding="true">
					While being employed at SAPs headquarters in Walldorf, Germany
					as a corporate student, I attended classes at the Corporate State University
					Baden-Württemberg in Mannheim (Business Informatics focused on Sales
					& Consulting, B.Sc.), worked at a division (SAP IT) and took part in the
					following projects for the VT-Department:<br> - Realizing an Android app (Java)
					concept & prototype for accessing SAP facilities with your
					smartphone during a hackathon<br> - Content creation for SAPs social media
					channels
					<br> - Attending various trainings for project management, agile software
					development, User Experience & UI-Design, ABAP-Development, Web-Development, Fiori
				</CVJob>
			</CVCompany>
			<li></li>
</CVContainer>