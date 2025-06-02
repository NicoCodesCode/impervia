<script lang="ts">
	import Header from '../components/Header.svelte';
</script>

<svelte:head>
	<title>Impervia | Protege tu casa de la humedad</title>
</svelte:head>

<Header />

<!-- Hero Section -->
<section
	class="bg-impervia-darker-blue flex min-h-[calc(100vh-4rem)] flex-wrap justify-evenly px-10 pt-16 text-center sm:items-center sm:px-16 md:text-left lg:px-32 lg:pt-0"
>
	<div class="font-poppins h-min max-w-sm text-white sm:max-w-xl">
		<h1 class="mb-4 text-3xl/snug font-extrabold sm:text-4xl/tight md:text-5xl/tight">
			Protege Tu <span class="text-impervia-yellow">Casa</span> De La
			<span class="text-impervia-blue">Humedad</span>
		</h1>
		<p>Impervia mantiene la humedad fuera, para que tu hogar permanezca seco, limpio y fuerte.</p>
	</div>
	<img class="h-72 sm:h-96" src="impervia-logo.png" alt="Impervia logo" />
</section>

<!-- Humidity threats -->
<section
	class="bg-impervia-dark-blue flex min-h-[calc(100vh-4rem)] flex-wrap-reverse items-center justify-evenly px-10 pt-16 text-center sm:px-16 md:text-left lg:px-32 lg:pt-0"
>
	<img
		class="h-40 rounded-xl shadow-lg/40 sm:h-64 lg:h-72"
		src="/images/rain-432770_640.jpg"
		alt="Rain on roof"
	/>
	<div class="font-poppins h-min max-w-sm text-white sm:max-w-xl">
		<h2 class="mb-4 text-3xl/snug font-extrabold sm:text-4xl/tight md:text-5xl/tight">
			¿Por Qué La
			<span class="text-impervia-blue">Humedad</span>
			Es
			<span class="text-impervia-yellow">Dañina</span>
			?
		</h2>
		<p>
			La humedad se filtra lentamente en paredes, techos y cimientos, provocando con el tiempo la
			aparición de moho, aumento de la temperatura, malos olores e incluso daños estructurales.
			También crea el ambiente perfecto para alérgenos y bacterias dañinas.
		</p>
	</div>
</section>
