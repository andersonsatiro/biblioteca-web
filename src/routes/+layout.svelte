<script lang="ts">
	import '../app.css';
	import Footer from '$lib/componentes/Footer.svelte';
	import Header  from '$lib/componentes/Header.svelte';
	let { children } = $props();
</script>
<Header parametro={101} />
{@render children()}
<Footer />