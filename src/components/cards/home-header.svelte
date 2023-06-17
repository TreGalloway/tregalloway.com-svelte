<script>
	export const ProfileImage = '';
	import { Avatar } from '@skeletonlabs/skeleton';
</script>

<main>
	<div class=" max-w-full">
		<div class="card flex flex-wrap p-4">
			<div class="p-2">
				<Avatar
					src="https://source.unsplash.com/YOErFW8AfkI/128x128"
					width=" w-48"
					rounded="rounded-full"
				/>
			</div>
			<div class="flex grow">
				<section class="card w-full">
					<div class="p-4 space-y-4">
						<h1 class="h1">
							<span
								class="bg-gradient-to-br from-blue-500 to-cyan-300 bg-clip-text text-transparent box-decoration-clone"
								>Tre Galloway.</span
							>
						</h1>
						<div class="grid grid-cols-3 gap-10">
							<span class="chip bg-gradient-to-br variant-gradient-secondary-primary"
								>Fullstack Developer</span
							>
							<span class="chip bg-gradient-to-br from-red-500 to-yellow-500">Writer</span>
							<span class="chip bg-gradient-to-br from-pink-500 to-violet-500">Overly Curious</span>
						</div>
						<div class="grid grid-cols-4 gap-4">
							<div class="placeholder animate-pulse" />
							<div class="placeholder animate-pulse" />
							<div class="placeholder animate-pulse" />
							<div class="placeholder animate-pulse" />
						</div>
					</div>
				</section>
			</div>
		</div>
	</div>
</main>
