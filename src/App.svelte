<script>
	import Header from './components/header.svelte';
	import Section1 from './components/section-1.svelte';
	import Section2 from './components/section-2.svelte';
	import Section3 from './components/section-3.svelte';
	import Section4 from './components/section-4.svelte';
</script>

<main class="w-full h-full m-0 px-5 flex flex-col mx-auto xl:max-w-screen-xl lg:max-w-xl xl:px-0 lg:px-0 xl:py-16 lg:py-16">
	<Header />
	<Section1 />
	<Section2 />
	<Section3 />
	<Section4 />
</main>

<style global>
  @tailwind base;
  @tailwind components;
  @tailwind utilities;
</style>
