<script>
	import {
		IconBrandTwitter,
		IconBrandYoutube,
		IconBrandMedium,
		IconBrandLinkedin
	} from '@tabler/icons-svelte';
</script>

<div class="mx-3">
	<div class="container h-full mx-auto justify-center items-center">
		<div class="">
			<header class="card-header">
				<h1 class="h1">
					<span
						class="bg-gradient-to-br from-blue-500 to-cyan-300 bg-clip-text text-transparent box-decoration-clone"
						>Tre Galloway.</span
					>
				</h1>
			</header>
			<section class="p-4"><p>Short little bit about me</p></section>
			<footer class="card-footer flex">
				<IconBrandTwitter size={34} stroke={0.6} />
				<IconBrandMedium size={34} stroke={0.6} />
				<IconBrandYoutube size={34} stroke={0.6} />
				<IconBrandLinkedin size={34} stroke={0.6} />
			</footer>
		</div>
	</div>
</div>
