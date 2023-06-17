<script lang="ts">
	import '../theme.postcss';
	// The ordering of these imports is critical to your app working properly
	// import '@skeletonlabs/skeleton/themes/theme-skeleton.css';
	// If you have source.organizeImports set to true in VSCode, then it will auto change this ordering
	import '@skeletonlabs/skeleton/styles/skeleton.css';
	// Most of your app wide CSS should be put in this file
	import '../app.postcss';
	import SideNav from '../components/nav/side-nav.svelte';
</script>

<div class="flex h-screen p-10">
	<SideNav />
	<div class="">
		<slot />
	</div>
</div>
