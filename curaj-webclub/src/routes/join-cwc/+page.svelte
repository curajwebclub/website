<script>
	import '$lib/style.css';

	import _$ from 'jquery';
	import Typed from 'typed.js';
	_$(document).ready(function () {
		var typed = new Typed('.typing', {
			strings: ['CWC', 'CURAJ WEB CLUB'],
			typeSpeed: 100,
			backSpeed: 60,
			loop: true
		});
	});
</script>

<svelte:head>
	<title>Join CWC</title>
</svelte:head>
<section class="onboard" id="onboard">
	<div class="max-width">
		<div class="onboard-content">
			<div class="text-2">Coming Soon</div>

			<a href="/">← Go Back</a>
		</div>
	</div>
</section>
