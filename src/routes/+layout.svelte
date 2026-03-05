<script lang="ts">
	import Footer from '$lib/components/Footer.svelte';
	import NavBar from '$lib/components/NavBar.svelte';
	import './layout.css';
	let { children } = $props();
</script>

<div class="flex min-h-screen flex-col justify-between">
	<header>
		<NavBar />
	</header>

	<main class="flex flex-1 flex-col bg-base-200 font-mono">
		<!-- terminal workspace -->
		<div class="relative mx-auto w-full max-w-6xl px-6">
			<!-- terminal session indicator -->
			<div class="pointer-events-none fixed top-24 right-6 hidden text-xs opacity-40 lg:block">
				<p>$ session: rain@portfolio</p>
				<p>$ status: browsing</p>
			</div>

			{@render children()}
		</div>
	</main>

	<footer>
		<Footer />
	</footer>
</div>
