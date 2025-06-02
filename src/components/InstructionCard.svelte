<script lang="ts">
	const { title, text } = $props();
</script>

<div class="bg-impervia-dark-blue mb-8 max-w-3xl rounded-xl px-10 py-6 shadow-lg/40">
	<h3 class="mb-2 text-lg font-semibold sm:text-2xl">{title}</h3>
	<p class="text-gray-300">{text}</p>
</div>
