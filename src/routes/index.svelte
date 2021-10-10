<script context="module" lang="ts">
	export const prerender = true;
</script>

<script lang="ts">
	let name: string = 'Juslin';
</script>

<svelte:head>
	<title>Home</title>
</svelte:head>

<section>
	<h1>
		Je suis {name} !
	</h1>
</section>