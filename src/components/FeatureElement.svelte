<script lang="ts">
	const { src, alt, text } = $props();
</script>

<div>
	<img {src} {alt} class="mx-auto mb-6 h-24 sm:h-32" />
	<h3 class="text-center text-lg font-semibold text-white sm:text-2xl">{text}</h3>
</div>
