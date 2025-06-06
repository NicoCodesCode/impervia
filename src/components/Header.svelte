<script lang="ts">
	import type { NavbarTop } from '../types';

	let top: NavbarTop = $state('-top-full');

	// Toggle top position of navbar on small screens
	function showNavbar() {
		top = top === '-top-full' ? 'top-[4rem]' : '-top-full';
	}
</script>

<!-- Phone navbar -->
<nav
	class="text-md bg-impervia-blue fixed {top} flex w-full flex-col items-center gap-4 pb-8 font-semibold text-white transition-all duration-300 sm:hidden"
>
	<a href="#impervia-description">
		<ul>¿Qué es Impervia?</ul>
	</a>
	<a href="#instructions">
		<ul>Instrucciones de uso</ul>
	</a>
</nav>

<header
	class="bg-impervia-blue fixed flex min-h-16 w-screen flex-wrap items-center justify-between px-10 py-4 text-white sm:px-16 lg:px-32"
>
	<h2 class="text-2xl font-extrabold sm:text-3xl">IMPERVIA</h2>

	<!-- Desktop navbar -->
	<nav class="text-md hidden flex-wrap justify-center gap-4 text-center font-semibold sm:flex">
		<a href="#impervia-description">
			<ul>¿Qué es Impervia?</ul>
		</a>
		<a href="#instructions">
			<ul>Instrucciones de uso</ul>
		</a>
	</nav>

	<!-- Hamburger button -->
	<button onclick={showNavbar} class="hover:cursor-pointer sm:hidden">
		<img class="h-7 invert" src="/icons/hamburger.png" alt="Navbar menu icon" />
	</button>
</header>
