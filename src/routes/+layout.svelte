<script lang="ts">
	import '../app.css';
	import Navigator from '$lib/Navigator.svelte';
</script>

<svelte:head>
	<script src="https://kit.fontawesome.com/bbec805730.js" crossorigin="anonymous"></script>
</svelte:head>

<div class="select-none lowercase">
	<Navigator />
	<div class="w-[90%] md:w-3/4 lg:w-2/3 mx-auto my-10">
		<slot />
	</div>
</div>
