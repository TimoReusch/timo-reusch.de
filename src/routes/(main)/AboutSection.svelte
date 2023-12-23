<script>
	import SectionContainer from '$lib/components/pageLayout/SectionContainer.svelte';
	import { onMount } from 'svelte';

	let yearsOfExperience = 0;

	onMount(() => {
		// Get today's date
		const today = new Date();

		// Convert today's date to a Date object representing September 1st, 2018
		const september1st2018 = new Date(2018, 8, 31);

		// Calculate the number of years that have passed
		const yearsPassed = today.getFullYear() - september1st2018.getFullYear();

		// Return the number of years
		yearsOfExperience = yearsPassed;

	});
</script>

<section class="about background_gpattern" id="about">
	<SectionContainer title="Who I Am" backgroundText="About Me">
		<div class="row justify-content-center align-items-center">
			<div class="col-md-6">
				<div class="avatar-area m-auto">
					<img src="https://timo-reusch.de/assets/images/002.jpg" width="400" height="550" alt=""
							 class="img-fluid mx-auto">
				</div>
			</div>
			<div class="col-md-6 mt-5 mt-md-0">
				<h3 class="m-0">Hey! I'm Timo,</h3>
				<p class="my-4">a 23-year old Software Developer, home in the wonderful city of Würzburg in
					Bavaria, Germany, where I'm studying computer science at the Julius-Maximilians-University.
					<br>My focus is on modern web applications and iOS apps.
				</p>
				<div class="row">
					<div class="col-lg-12">
						<div class="about-info mb-2">
							<span class="desc">Experience:</span>
							<span>{yearsOfExperience} years</span>
						</div>
					</div>
					<div class="col-lg-12">
						<div class="about-info mb-2">
							<span class="desc">Contact:</span>
							<span><a href="mailto:mail@timo-reusch.de"
											 style="color: #b5b5b5">mail@timo-reusch.de</a></span>
						</div>
					</div>
				</div>
				<div class="button_and_social my-4">
					<div class="row justify-content-center align-items-center">
						<div class="col-xl-6">

						</div>
						<div class="col-xl-6">
							<ul class="social-icons list-inline mt-4 mt-xl-0">
								<li class="list-inline-item">
									<a href="https://github.com/TimoReusch" target="_blank">
										<i class="fab fa-github"></i>
									</a>
								</li>
								<li class="list-inline-item">
									<a href="https://dev.to/timo_reusch" target="_blank">
										<i class="fab fa-dev"></i>
									</a>
								</li>
								<li class="list-inline-item">
									<a href="https://www.linkedin.com/in/timo-reusch/" target="_blank">
										<i class="fab fa-linkedin-in"></i>
									</a>
								</li>
								<li class="list-inline-item">
									<a href="https://www.youtube.com/channel/UC2IkJAxyNK35shPaAhAkjjw"
										 target="_blank">
										<i class="fab fa-youtube"></i>
									</a>
								</li>
							</ul>
						</div>
					</div>
				</div>
			</div>
		</div>
	</SectionContainer>
</section>