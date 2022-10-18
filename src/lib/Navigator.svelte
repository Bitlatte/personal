<script lang="ts">
	import MenuLinks from './MenuLinks.svelte';
</script>

<div class="navbar bg-base-100">
	<div class="navbar-start">
		<div class="dropdown">
			<!-- svelte-ignore a11y-no-noninteractive-tabindex -->
			<div tabindex="0" class="btn btn-ghost md:hidden">
				<i class="fa-solid fa-bars fa-2xl" />
			</div>
			<!-- svelte-ignore a11y-no-noninteractive-tabindex -->
			<ul
				tabindex="0"
				class="menu menu-compact dropdown-content mt-3 p-2 shadow bg-base-100 rounded-box w-52"
			>
				<MenuLinks />
			</ul>
		</div>
		<a href="/" class="btn btn-ghost lowercase">Coby McKinney</a>
	</div>
	<div class="navbar-end hidden md:flex">
		<ul class="menu menu-horizontal p-0">
			<MenuLinks />
		</ul>
	</div>
</div>
