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
				<h2 class="h2">
					<span
						class="bg-gradient-to-br from-blue-500 to-cyan-300 bg-clip-text text-transparent box-decoration-clone"
						>Tre Galloway.</span
					>
				</h2>
			</header>
			<section class="p-4">
				<p>
					Hey I&apos;m Tre&apos;. I&apos;m a <a class=" font-semibold">
						Fullstack Developer, Writer and Overly Curious Person</a
					>
					with access to the internet.
				</p>
			</section>
			<footer class="card-footer grid grid-cols-4">
				<div class="flex hover:text-blue-400"><IconBrandTwitter stroke={1} /> Twitter</div>
				<div class="flex"><IconBrandMedium stroke={1} /> Medium</div>
				<div class="flex"><IconBrandYoutube stroke={1} /> YouTube</div>
				<div class="flex"><IconBrandLinkedin stroke={1} /> Linkedin</div>
			</footer>
		</div>
	</div>
</div>
