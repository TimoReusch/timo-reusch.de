<script>
	import '../../app.scss';
	import CVComponent from '$lib/views/CVExperienceView.svelte';
	import { onMount } from 'svelte';

	const apiUrl = "https://timo-reusch.de/api/private/cv.json";

	let data;
	let password;

	function getCredentials(){
		password = prompt("Please enter the API-Password");
	}

	// Function to perform the GET request
	async function fetchData() {
		const options = {
			method: 'GET',
			headers: {
				"content-type": "application/json; charset=UTF-8",
				Authorization: 'Basic <Password>'
			}
		};

		fetch('https://timo-reusch.de/api/private/cv.json', options)
			.then(response => response.json())
			.then(response => console.log(response))
			.catch(err => console.error(err));
	}

	// Call the function on component mount
	onMount(async () => {
		data = await fetchData();
	});
</script>

{data}

<div class="container mt-3">
	<div class="row">
		<div class="col-3">
			<img src="https://timo-reusch.de/assets/images/002.jpg" class="rounded-circle img-fluid mt-4" alt="Portrait">
		</div>
		<div class="col-9">
			<hr>
			<h3>Timo Reusch</h3>
			<ul>
				<li>Straße 6</li>
				<li class="mb-3">970xx Würzburg</li>
				<li class="mb-3">Geboren am xx.xx.xxxx in xxxxxxxxxx</li>
				<li>Telefonnummer</li>
				<li>Mail</li>
				<li>https://timo-reusch.de</li>
			</ul>
			<hr>
		</div>
	</div>
	<div class="row">
		<div class="col-3">
			<h3>Experience</h3>
		</div>
		<div class="col-9 cv">
			<CVComponent />
		</div>
	</div>
	<div class="row">
		<div class="col-3">
			<h3>Education</h3>
		</div>
		<div class="col-9">

		</div>
	</div>
	<div class="row">
		<div class="col-3">
			<h3>Links</h3>
		</div>
		<div class="col-9">
			Overview over Tech Stack
			GitHub Profile
			LinkedIn Profile
		</div>
	</div>
	<div class="row align-top">
		<div class="col-3">
			<h3>Languages</h3>
		</div>
		<div class="col-9">
			<ul>
				<li>German (mother tongue)</li>
				<li>English (C1)</li>
			</ul>
		</div>
	</div>
</div>

<style lang="scss">
  :global(body) {
    background-color: white;
  }

	.cv{
    :global(.time) {
      color: rgb(102,102,102);
    }

		:global(company-link){
			color: black;
		}

		:global(h4){
			color: black;
		}

		:global(p){
			color: black;
		}


		:global(btn-small){
			color: black;
		}
	}

  h3, ul {
    color: black !important;
  }

  h3 {
    margin-top: 20px;
  }

  .rounded-circle {
    max-width: 200px;
  }

  ul {
    color: #F0F0F0;
    list-style-type: none;
    padding-left: 0;
  }

	h3 {
		color: #E54144 !important;
		margin-top: 0;
	}

	hr {
		border: 2px solid black;
	}
</style>