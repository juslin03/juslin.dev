<script lang="ts">
	import Header from '$lib/header/Header.svelte';
	import Footer from '$lib/footer/Footer.svelte';
	import '../app.css';
</script>

<div  class="mx-auto container px-6 lg:px-14 xl:px-0">
	<Header/>

	<slot>
	</slot>

	<Footer/>
</div>
