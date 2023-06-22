<script>
	import { Avatar } from '@skeletonlabs/skeleton';
	import { LightSwitch } from '@skeletonlabs/skeleton';
</script>

<!-- SideNav.svelte -->
<div class="ml-24 mr-10 w-24">
	<div class="px-2 py-4">
		<!-- <h1 class="text-xl font-bold">Tre Galloway.</h1> -->

		<Avatar
			border="border-4 border-surface-300-600-token hover:!border-primary-500"
			cursor="cursor-pointer"
			initials="TG"
		/>
	</div>
	<nav class="mt-2">
		<ul>
			<li class="">
				<a
					href="/"
					class="block sidenav-link rounded-lg px-4 py-2 hover:bg-gray-100 transition-all duration-200 ease-in-out text-lg font-bold"
					>Home</a
				>
			</li>
			<li class="">
				<a
					href="/blog"
					class="block sidenav-link rounded-lg px-4 py-2 hover:bg-gray-100 transition-all duration-200 ease-in-out text-lg font-bold"
					>Blog</a
				>
			</li>
			<li class="">
				<a
					href="/portfolio"
					class="block sidenav-link rounded-lg px-4 py-2 hover:bg-gray-100 transition-all duration-200 ease-in-out text-lg font-bold"
					>Portfolio</a
				>
			</li>
			<li class="">
				<a
					href="/store"
					class="block sidenav-link rounded-lg px-4 py-2 hover:bg-gray-100 transition-all duration-200 ease-in-out text-lg font-bold"
					>Store</a
				>
			</li>
		</ul>
		<div class="px-4"><LightSwitch /></div>
	</nav>
</div>

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
