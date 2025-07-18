<script lang="ts">
	// Components
	import FeatureElement from '../components/FeatureElement.svelte';
	import InstructionCard from '../components/InstructionCard.svelte';
</script>

<svelte:head>
	<title>Impervia | Protege tu casa de la humedad</title>
</svelte:head>

<!-- Hero section -->
<section
	class="bg-impervia-darker-blue flex min-h-[calc(100vh-4rem)] flex-wrap justify-evenly px-10 py-24 sm:items-center sm:px-16 lg:px-32"
>
	<div class="font-poppins h-min max-w-sm text-white sm:max-w-xl">
		<h1 class="mb-4 text-3xl/snug font-extrabold sm:text-4xl/tight lg:text-5xl/tight">
			Protege Tu <span class="text-impervia-yellow">Casa</span> De La
			<span class="text-impervia-blue">Humedad</span>
		</h1>
		<p>Impervia mantiene la humedad fuera, para que tu hogar permanezca seco, limpio y fuerte.</p>
	</div>
	<img class="h-72 sm:h-80" src="impervia-logo.png" alt="Impervia logo" />
</section>

<!-- Humidity threats section -->
<section
	class="bg-impervia-dark-blue flex min-h-[calc(100vh-4rem)] flex-wrap-reverse items-center justify-evenly px-10 py-16 sm:px-16 lg:px-32"
	id="humidity-threats"
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
	class="bg-impervia-third-blue flex min-h-[calc(100vh-4rem)] flex-wrap justify-evenly px-10 py-16 sm:items-center sm:px-16 lg:px-32"
	id="impervia-description"
>
	<div class="font-poppins h-min max-w-sm text-white sm:max-w-xl">
		<h2 class="mb-4 text-3xl/snug font-extrabold sm:text-4xl/tight md:text-5xl/tight">
			IMPERVIA Como <span class="text-impervia-yellow">Solución</span>
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
	class="bg-impervia-dark-blue flex h-min flex-wrap items-center justify-evenly gap-8 px-10 py-16 sm:px-16 lg:px-32"
>
	<FeatureElement src="/icons/shield.png" alt="Shield" text="Protección Duradera" />
	<FeatureElement src="/icons/favorites.png" alt="Badge" text="Calidad Garantizada" />
	<FeatureElement src="/icons/dollar.png" alt="Money" text="Costo Accesible" />
	<FeatureElement src="/icons/earth.png" alt="Earth" text="Mejora Ecológica" />
</section>

<!-- Instructions section -->
<section
	class="bg-impervia-darker-blue flex h-min flex-wrap justify-evenly gap-12 px-10 py-16 text-white sm:items-center sm:px-16 lg:px-32"
	id="instructions"
>
	<h2 class="mb-4 text-3xl/snug font-extrabold sm:text-4xl/tight md:text-5xl/tight">
		Instrucciones De <span class="text-impervia-yellow">Uso</span>
	</h2>
	<div>
		<InstructionCard
			title="1. Mézclalo"
			text="Dentro de la cubeta, encontrarás botellas que contienen los componentes de la fórmula del impermeabilizante. Vierte todo el contenido en el cubo y mézclala bien con ayuda de cualquier herramienta. Déjalo reposar unos minutos."
		/>
		<InstructionCard
			title="2. Aplícalo"
			text="Una vez listo, aplica Impervia uniformemente usando una brocha o un rodillo sobre las superficies que desees proteger: paredes, techos o cualquier lugar donde la humedad amenace tu hogar."
		/>
		<InstructionCard
			title="3. Despreocúpate"
			text="Al secarse, Impervia forma una barrera resistente e invisible que bloquea la humedad y evita la formación de moho, las goteras y regula la temperatura del hogar."
		/>
	</div>
</section>

<!-- Testimonials section  -->
<section
	class="bg-impervia-dark-blue flex min-h-[calc(100vh-4rem)] flex-col items-center justify-evenly px-10 py-16 sm:px-16 lg:px-32"
	id="testimonial"
>
	<h2 class="mb-16 text-3xl/snug font-extrabold text-white sm:text-4xl/tight md:text-5xl/tight">
		Testimonio
	</h2>
	<div class="mb-8 flex flex-wrap items-center justify-center gap-8">
		<img
			class="h-48 rounded-xl shadow-lg/40 sm:h-60"
			src="/images/testimonial-1.jpeg"
			alt="Testimonial 1"
		/>
		<div
			class="font-poppins bg-impervia-darker-blue h-min max-w-sm rounded-xl px-10 py-6 text-white shadow-lg/40 sm:max-w-lg"
		>
			<p class="sm:text-lg">
				<span class="m-4">
					<img class="inline h-6 invert sm:h-8" src="/images/open-quote.png" alt="Open quote" />
				</span>
				Desde que aplicamos Impervia en el techo de nuestra casa, hemos notado una gran diferencia. Ya
				no hay goteras cuando llueve, y la temperatura de adentro se siente mucho más agradable. Es fácil
				de aplicar y da muchísima tranquilidad.
				<span class="m-4">
					<img class="inline h-6 invert sm:h-8" src="/images/close-quote.png" alt="Close quote" />
				</span>
			</p>
		</div>
	</div>
</section>

<!-- ONU SDG section -->
<section
	class="bg-impervia-third-blue flex min-h-[calc(100vh-4rem)] flex-wrap justify-evenly px-10 py-16 sm:items-center sm:px-16 lg:px-32"
	id="onu-ods"
>
	<div class="font-poppins h-min max-w-sm text-white sm:max-w-xl">
		<h2 class="mb-4 text-3xl/snug font-extrabold sm:text-4xl/tight md:text-5xl/tight">
			<span class="text-impervia-yellow">Alineado</span>
			Con Los ODS De La
			<span class="text-impervia-blue">ONU</span>
		</h2>
		<p>
			Impervia contribuye a un futuro más sostenible al mejorar la eficiencia energética y prevenir
			problemas de salud causados por la humedad, apoyando así varios Objetivos de Desarrollo
			Sostenible de la ONU.
		</p>
	</div>
	<div class="mt-14 flex max-w-80 flex-wrap items-center justify-center gap-4 sm:max-w-96">
		<img class="h-32 sm:h-44" src="/icons/S_SDG_Icons-01-09.jpg" alt="ONU SDG 9 Icon" />
		<img class="h-32 sm:h-44" src="/icons/S_SDG_Icons-01-12.jpg" alt="ONU SDG 12 Icon" />
		<img class="h-32 sm:h-44" src="/icons/S_SDG_Icons-01-11.jpg" alt="ONU SDG 11 Icon" />
		<img class="h-32 sm:h-44" src="/icons/S_SDG_Icons-01-13.jpg" alt="ONU SDG 13 Icon" />
	</div>
</section>
