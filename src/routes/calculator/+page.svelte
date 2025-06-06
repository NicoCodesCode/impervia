<script lang="ts">
	const SQUARED_METERS_PER_BUCKET = 22;
	let squaredMeters = $state(0);
	let buckets = $derived(Math.ceil(squaredMeters / SQUARED_METERS_PER_BUCKET));
</script>

<section
	class="bg-impervia-dark-blue flex min-h-[calc(100vh-4rem)] flex-wrap justify-evenly px-10 py-24 sm:items-center sm:px-16 lg:px-32"
>
	<div class="font-poppins mb-8 h-min max-w-sm text-white sm:max-w-lg">
		<h2 class="mb-4 text-3xl/snug font-extrabold sm:text-4xl/tight lg:text-5xl/tight">
			Calcula Cuántas <span class="text-impervia-yellow">Cubetas</span> Necesitas
		</h2>
		<p>
			Ingresa la cantidad de metros cuadrados que deseas impermeabilizar para conocer cuántas
			cubetas Impervia necesitarás en total
		</p>
	</div>
	<div
		class="font-poppins bg-impervia-darker-blue h-min max-w-sm rounded-lg p-12 text-white shadow-lg/40 sm:max-w-lg"
	>
		<div class="mb-4 flex">
			<label class="block text-lg font-semibold sm:text-xl" for="squared-meters">
				Metros cuadrados:
			</label>
			<input
				class="ml-4 max-w-20 rounded-lg bg-white pl-2 text-black"
				bind:value={squaredMeters}
				id="squared-meters"
				placeholder="Ingrese los metros cuadrados"
				type="number"
			/>
		</div>
		<p class="mb-2 text-lg font-semibold sm:text-xl">Cubetas: {buckets}</p>
	</div>
</section>
