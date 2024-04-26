<script>
	import '$lib/style.css';

	import _$ from 'jquery';
	import Typed from 'typed.js';
	_$(document).ready(function () {
		var typed = new Typed('.typing2', {
			strings: ['Stay Tuned!', 'Onboarding Soon!'],
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
			<div class="text-2"><span class="typing2"></span></div>
			<p>
				Stay tuned for more updates! We’re just as excited to get started<br> and can’t wait to share what’s coming up with the CURAJ Web Club.
			</p>
			<a href="/">← Go Back</a>
		</div>
	</div>
</section>
