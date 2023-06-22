<script lang="ts">
	import '../theme.postcss';
	// The ordering of these imports is critical to your app working properly
	// import '@skeletonlabs/skeleton/themes/theme-skeleton.css';
	// If you have source.organizeImports set to true in VSCode, then it will auto change this ordering
	import '@skeletonlabs/skeleton/styles/skeleton.css';
	// Most of your app wide CSS should be put in this file
	import '../app.postcss';
	import { AppShell, Avatar } from '@skeletonlabs/skeleton';
	import SideNav from '../components/nav/side-nav.svelte';
</script>

<AppShell>
	<svelte:fragment slot="header">
		<div class="my-16" />
	</svelte:fragment>
	<svelte:fragment slot="sidebarLeft">
		<SideNav />
	</svelte:fragment>
	<!-- (sidebarRight) -->
	<!-- (pageHeader) -->
	<!-- Router Slot -->
	<slot />
	<!-- ---- / ---- -->
	<!-- (pageFooter) -->
	<!-- (footer) -->
</AppShell>

<style>
	.sidenav-link {
		transition: all 0.2s;
	}

	.sidenav-link:hover {
		background-color: #474e53;
	}

	.sidenav-link.active {
		background-color: #f7fafc;
		font-weight: bold;
	}
</style>
