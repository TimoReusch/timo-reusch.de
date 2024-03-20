<script>
	import SectionContainer from '$lib/containers/SectionContainer.svelte';
	import { onMount } from 'svelte';

	let yearsOfExperience = 0;
	let age = 0;

	async function fetchAge() {
		const options = {
			method: 'GET',
			headers: {
				"content-type": "application/json; charset=UTF-8",
			}
		};

		fetch('https://api.timo-reusch.de/age.php', options)
			.then(response => response.json())
			.then(data => {
				age = data.age
			})
			.catch(err => console.error(err));
	}

	function calculateYearsOfExperience(){
		// Get today's date
		const today = new Date();

		// Convert today's date to a Date object representing September 1st, 2018
		const september1st2018 = new Date(2018, 8, 31);

		// Calculate the number of years that have passed
		const yearsPassed = today.getFullYear() - september1st2018.getFullYear();

		// Return the number of years
		return yearsPassed;
	}

	onMount(async () => {
		yearsOfExperience = calculateYearsOfExperience();
		age = await fetchAge();
	});
</script>

<section class="about background_gpattern" id="about">
	<SectionContainer title="Who I Am" backgroundText="About Me">
		<div class="row justify-content-center align-items-center">
			<div class="col-md-6">
				<div class="avatar-area m-auto">
					<img src="https://api.timo-reusch.de/images/002.jpg" width="400" height="550" alt=""
							 class="img-fluid mx-auto">
				</div>
			</div>
			<div class="col-md-6 mt-5 mt-md-0">
				<h3 class="m-0">Hey! I'm Timo,</h3>
				<p class="my-4">a {age}-year old Software Developer, with a passion for web development,
					UI/UX, and mobile solutions.
				</p>
				<p class="my-4">
					Over the past few years, I've gained extensive experience in web development, working with
					a variety of technologies and frameworks, especially Svelte.
					Lately, mobile solutions have sparked my interest, so I'm actively working on native, as
					well as cross-platform applications with Swift, Flutter and Compose Multiplatform.<br>
					Besides that, I'm passionate about good UI/UX, having an eye for user-friendly and
					visually appealing designs.
				</p>
				<div class="row">
					<div class="col-lg-12">
						<div class="about-info mb-2">
							<span class="desc">Based in:</span>
							<span>Würzburg, Bavaria, Germany</span>
						</div>
					</div>
					<div class="col-lg-12">
						<div class="about-info mb-2">
							<span class="desc">Experience:</span>
							<span>{yearsOfExperience} years</span>
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
									<a href="https://api.timo-reusch.de/mail"
										 target="_blank">
										<i class="fa fa-envelope"></i>
									</a>
								</li>
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