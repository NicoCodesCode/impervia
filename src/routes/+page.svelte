<script lang="ts">
	import FeatureElement from '../components/FeatureElement.svelte';
</script>

<svelte:head>
	<title>Impervia | Protege tu casa de la humedad</title>
</svelte:head>

<!-- Header -->
<header class="bg-impervia-blue flex h-16 items-center px-10 text-white sm:px-16 lg:px-32">
	<h2 class="text-2xl font-extrabold sm:text-3xl">IMPERVIA</h2>
</header>

<!-- Hero section -->
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

<!-- Humidity threats section -->
<section
	class="bg-impervia-dark-blue flex min-h-[calc(100vh-4rem)] flex-wrap-reverse items-center justify-evenly px-10 py-16 text-center sm:px-16 md:text-left lg:px-32"
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

<!-- Impervia description section -->
<section
	class="bg-impervia-darker-blue flex min-h-[calc(100vh-4rem)] flex-wrap justify-evenly px-10 py-16 text-center sm:items-center sm:px-16 md:text-left lg:px-32"
>
	<div class="font-poppins h-min max-w-sm text-white sm:max-w-xl">
		<h2 class="mb-4 text-3xl/snug font-extrabold sm:text-4xl/tight md:text-5xl/tight">
			IMPERVIA como <span class="text-impervia-yellow">solución</span>
		</h2>
		<p>
			Impervia es un impermeabilizante aislante diseñado para proteger techos y paredes frente a la
			humedad, filtraciones y radiación solar. Forma una barrera eficiente que reduce el impacto
			térmico y ayuda a mantener una temperatura interior estable, mejorando el confort del hogar y
			alargando la vida útil de las superficies tratadas.
		</p>
	</div>
	<img class="h-72 sm:h-96" src="/images/impervia-bucket.png" alt="Impervia logo" />
</section>

<!-- Features section -->
<section
	class="bg-impervia-dark-blue flex h-min flex-wrap items-center justify-evenly gap-8 px-10 py-16 text-center sm:px-16 md:text-left lg:px-32"
>
	<FeatureElement src="/icons/shield.png" alt="Shield" text="Protección Duradera" />
	<FeatureElement src="/icons/favorites.png" alt="Badge" text="Calidad Garantizada" />
	<FeatureElement src="/icons/dollar.png" alt="Money" text="Costo Asequible" />
	<FeatureElement src="/icons/earth.png" alt="Earth" text="Mejora Ecológica" />
</section>
