<script lang="ts">
	export let name: string;
	import InactionCard from "./comps/InactionCard.svelte"
</script>

<main>
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
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>