<script>
	import { goto } from '$app/navigation';
	import '$lib/style.css';
	// @ts-ignore
	import _$ from 'jquery';
	import Typed from 'typed.js';
	if (typeof document !== 'undefined') {
		_$(document).ready(function () {
			var typed = new Typed('.typing', {
				strings: ['CWC', 'CURAJ WEB CLUB'],
				typeSpeed: 100,
				backSpeed: 60,
				loop: true
			});
		});
	}
</script>

<svelte:head>
	<title>CURAJ WEB CLUB</title>
</svelte:head>
<section class="onboard" id="onboard">
	<div class="max-width">
		<div class="onboard-content">
			<div class="text-1">Welcome to</div>
			<div class="text-2"><span class="typing"></span></div>
			<a href="/join-cwc">Join CWC →</a>
		</div>
	</div>
</section>
<section class="services" id="services">
	<div class="max-width">
		<h2 class="title">Services</h2>
		<div class="serv-content">
			<div class="card">
				<div class="card-header">
					<div class="button-circle-wrap">
						<div class="button-circle"></div>
						<div class="button-circle"></div>
					</div>
					<div class="header-title">
						<div>-services.html</div>
					</div>
					<div></div>
					<div></div>
				</div>
				<div class="box">
					<i class="fas fa-code"></i>
					<div class="text">Apps Design</div>
					<p>
						Our talented team crafts intuitive and visually appealing mobile and web applications.
						Whether it's a club app, an event-specific app, or an app for cultural events held on
						campus, we ensure seamless experiences for your users.
					</p>
				</div>
				<div class="bottom-button">
					<span>Coming Soon</span>
				</div>
			</div>
			<div class="card">
				<div class="card-header">
					<div class="button-circle-wrap">
						<div class="button-circle"></div>
						<div class="button-circle"></div>
					</div>
					<div class="header-title">
						<div>-services.html</div>
					</div>
					<div></div>
					<div></div>
				</div>
				<div class="box">
					<i class="fas fa-paint-brush"></i>
					<div class="text">Web Design</div>
					<p>
						We specialize in creating stunning websites that captivate visitors. From personal blogs
						to e-commerce platforms, our designs are both functional and aesthetically pleasing. For
						clubs and campus events, we tailor websites to showcase your unique identity and engage
						your audience effectively.
					</p>
				</div>
				<div class="bottom-button">
					<a href="#onboard">Coming Soon</a>
				</div>
			</div>
			<div class="card">
				<div class="card-header">
					<div class="button-circle-wrap">
						<div class="button-circle"></div>
						<div class="button-circle"></div>
					</div>
					<div class="header-title">
						<div>-services.html</div>
					</div>
					<div></div>
					<div></div>
				</div>
				<div class="box">
					<i class="fas fa-chart-line"></i>
					<div class="text">Advertising</div>
					<p>
						Need to boost your club's visibility? Our advertising services cover social media
						campaigns, SEO optimization, and eye-catching banners. Let us help you reach your
						audience effectively, whether it's promoting a cultural event, a club gathering, or any
						campus activity!
					</p>
				</div>
				<div class="bottom-button">
					<a href="#onboard">Coming Soon</a>
				</div>
			</div>
		</div>
	</div>
</section>

<style>
</style>
