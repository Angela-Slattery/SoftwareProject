<script lang="ts">
	import '../app.css';
</script>

<nav class="bg-gray-800 p-4 text-white">
	<div class="mx-auto flex max-w-7xl items-center justify-between">
		<div class="flex items-center space-x-2">
			<img 
				src="https://i5.walmartimages.com/asr/12314833-2e54-4739-94a2-7db45b63109d.16ff07e3c111df9be4158853c2e505ef.jpeg?odnHeight=2000&odnWidth=2000&odnBg=FFFFFF" 
				alt="Lime" 
				class="h-8 w-8 rounded-full"
			/>
			<a href="/" class="text-lg font-bold">Actively Accountable</a>
		</div>

		<!-- Navigation Links -->
		<div>
			<a href="/login" class="mr-4 hover:underline">Login</a>
			<a href="/profile" class="hover:underline">Profile</a>
		</div>
	</div>
</nav>

<main class="p-4">
	<slot />
	<!-- This is where child content will render -->
</main>
