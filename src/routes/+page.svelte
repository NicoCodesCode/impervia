<script lang="ts">
	import Header from '../components/Header.svelte';
</script>

<svelte:head>
	<title>Impervia | Protege tu casa de la humedad</title>
</svelte:head>

<Header />
<section
	class="bg-impervia-darker-blue flex min-h-[calc(100vh-4rem)] items-center justify-evenly px-32"
>
	<div class="font-poppins max-w-xl text-white">
		<h1 class="mb-4 text-5xl/tight font-extrabold">
			Protege Tu <span class="text-impervia-yellow">Casa</span> De La
			<span class="text-impervia-blue">Humedad</span>
		</h1>
		<p>Impervia mantiene la humedad fuera, para que tu hogar permanezca seco, limpio y fuerte.</p>
	</div>
	<img class="h-96" src="impervia-logo.png" alt="Impervia logo" />
</section>
