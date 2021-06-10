<script lang="ts">
	export let name: string;
	import InactionCard from "./comps/InactionCard.svelte"
	import Logo from "./comps/Logo.svelte"
</script>

<main>
	<Logo />
	<h1>Hello {name}!</h1>
	<p class="intro">To do:</p>
	<InactionCard
		title="Learn Svelte and TypeScript"
		notes="Share my website as open-source to github"
	/>
	<InactionCard
		title="Learn Svelte and TypeScript"
		notes="Share my website as open-source to github"
	/>
	<InactionCard
		title="Learn Svelte and TypeScript"
		notes="Share my website as open-source to github"
	/>
		
</main>

<style>
	
	main {
		background-color: #303131;
		color:white;
		height: 100%;
	}

	
</style>