<script lang="ts">
	import { IconHome } from '@tabler/icons-svelte';
	import { AppBar, LightSwitch } from '@skeletonlabs/skeleton';
</script>

<AppBar gridColumns="grid-cols-3" slotDefault="place-self-center" slotTrail="place-content-end">
	<svelte:fragment slot="lead">
		<IconHome />
	</svelte:fragment>

	Svelte/Tailwind/Skeleton Starter

	<svelte:fragment slot="trail">
		<LightSwitch />
	</svelte:fragment>
</AppBar>
