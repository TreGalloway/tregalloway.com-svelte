<script>
	import { Avatar } from '@skeletonlabs/skeleton';
</script>

<!-- SideNav.svelte -->
<div class="fixed top-20 left-20 w-24 h-full">
	<div class="px-6 py-4">
		<!-- <h1 class="text-xl font-bold">Tre Galloway.</h1> -->

		<Avatar
			border="border-4 border-surface-300-600-token hover:!border-primary-500"
			cursor="cursor-pointer"
			initials="TG"
		/>

		<p class="text-gray-200">Web Developer</p>
	</div>
	<nav class="mt-6">
		<ul>
			<li class="mb-4">
				<a
					href="/"
					class="block sidenav-link rounded-lg px-4 py-2 hover:bg-gray-100 transition-all duration-200 ease-in-out"
					>Home</a
				>
			</li>
			<li class="mb-4">
				<a
					href="/blog"
					class="block sidenav-link rounded-lg px-4 py-2 hover:bg-gray-100 transition-all duration-200 ease-in-out"
					>Blog</a
				>
			</li>
			<li class="mb-4">
				<a
					href="/portfolio"
					class="block sidenav-link rounded-lg px-4 py-2 hover:bg-gray-100 transition-all duration-200 ease-in-out"
					>Portfolio</a
				>
			</li>
			<li class="mb-4">
				<a
					href="/store"
					class="block sidenav-link rounded-lg px-4 py-2 hover:bg-gray-100 transition-all duration-200 ease-in-out"
					>Store</a
				>
			</li>
			<li class="mb-4">
				<a
					href="/socials"
					class="block sidenav-link rounded-lg px-4 py-2 hover:bg-gray-100 transition-all duration-200 ease-in-out"
					>Contact</a
				>
			</li>
		</ul>
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
