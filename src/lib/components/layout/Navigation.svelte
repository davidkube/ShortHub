<script lang="ts">
	import Menu from './Menu.svelte';
	import Logo from '../display/Logo.svelte';
	import FunctionsMenu from './FunctionsMenu.svelte';
</script>

<div class="navbar bg-base-100 ">
	<div class="flex-none">
		<Menu />
	</div>
	<div class="flex-1">
		<Logo />
	</div>
	<div class="flex-none">
		<FunctionsMenu />
	</div>
</div>
