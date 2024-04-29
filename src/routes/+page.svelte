<style>
	:root {
		--background-color-light: rgb(255, 228, 182);
		--background-color-dark: rgb(164, 55, 15);
	}

	.custom-underline {
		position: relative;
		display: inline-block;
		padding-bottom: -20px;
	}

	.custom-underline::after {
		content: "";
		position: absolute;
		left: 0;
		bottom: 0;
		width: 100%;
		height: 18px;
		background-color: var(--background-color-light);
		z-index: -1;
	}

	@media (prefers-color-scheme: dark) {
		:root {
			--background-color-light: rgb(164, 55, 15);
		}
	}
</style>

<main class="flex w-full min-h-screen">
	<div class="hero bg-base-200">
		<div class="hero-content text-left">
			<div class="w-full">
				<p>Hi there, I am</p>
				<h1 class="text-5xl font-bold custom-underline">Matyáš Strelec</h1>
				<p class="py-4">
					and I am a Information technology student<br />
					at Brno University of Technology.
				</p>
				<p class="text-lg font-bold">Get in touch</p>
				<p>
					Find my projects on
					<a class="link" href="https://github.com/mstrlc">GitHub</a>,
					<br />
					Connect with me on
					<a class="link" href="https://linkedin.com/in/mstrlc">LinkedIn</a>,
					<br />
					Send me an email
					<a class="link" href="mailto:hello@mstrlc.eu">hello@mstrlc.eu</a>.
				</p>
			</div>
		</div>
	</div>
</main>
