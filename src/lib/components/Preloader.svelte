<script>
	import { onMount } from 'svelte';

	onMount(() => {
		function fade(element) {
			let o = 1;
			let t = setInterval(function() {
				if (o <= 0.1) {
					clearInterval(t);
					element.style.display = 'none';
				}
				element.style.opacity = o;
				o -= o * 0.1;
			}, 50);
		}

		window.addEventListener('load', function(event) {
			fade(document.getElementById('preloader'));
		});
	});
</script>

<div id="preloader">
	<div class="text-center w-100">
		<div class="loader"></div>
	</div>
</div>

<style>
    #preloader {
        background-color: #FFFFFF;
        width: 100%;
        height: 100%;
        z-index: 9999999;
        position: fixed;
        top: 0;
        left: 0;
        display: -webkit-box;
        display: -ms-flexbox;
        display: flex;
        -webkit-box-orient: horizontal;
        -webkit-box-direction: normal;
        -ms-flex-direction: row;
        flex-direction: row;
        -webkit-box-align: center;
        -ms-flex-align: center;
        align-items: center;
        overflow: hidden;
    }

    /*# sourceMappingURL=preload.css.map */
</style>