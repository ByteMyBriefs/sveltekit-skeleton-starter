<script>
	// See https://www.skeleton.dev/docs/get-started#stylesheets
	// Your selected Skeleton theme:
	// NOTE: make sure this matches the theme specified in the 'data-body' tag in app.html
	import '@skeletonlabs/skeleton/themes/theme-rocket.css';
	// This contains the bulk of Skeletons required styles:
	import '@skeletonlabs/skeleton/styles/all.css';
	// Finally, your application's global stylesheet (sometimes labeled 'app.css')
	import '../app.postcss';

	import Header from '$lib/components/app/Header.svelte';
	import { AppShell } from '@skeletonlabs/skeleton';
</script>

<!-- See https://www.skeleton.dev/components/app-shell -->
<AppShell>
	<svelte:fragment slot="header">
		<Header />
	</svelte:fragment>
	<slot />
</AppShell>
