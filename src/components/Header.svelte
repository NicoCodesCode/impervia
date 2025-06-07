<script lang="ts">
	import type { NavbarTop } from '../types';

	let top: NavbarTop = $state('-top-full');

	// Toggle top position of navbar on small screens
	function toggleNavbar() {
		top = top === '-top-full' ? 'top-[4rem]' : '-top-full';
	}
</script>

<!-- Phone navbar -->
<nav
	class="bg-impervia-blue text-md fixed {top} flex w-full flex-col items-center gap-4 pt-3 pb-9 font-semibold text-white transition-all duration-300 lg:hidden"
>
	<a
		class="hover:underline active:text-gray-200"
		onclick={toggleNavbar}
		href="/#impervia-description"
	>
		<ul>¿Qué es Impervia?</ul>
	</a>
	<a class="hover:underline active:text-gray-200" onclick={toggleNavbar} href="/#instructions">
		<ul>Instrucciones de uso</ul>
	</a>
	<a class="hover:underline active:text-gray-200" onclick={toggleNavbar} href="/calculator">
		<ul>Calculadora de cubetas</ul>
	</a>
	<a class="hover:underline active:text-gray-200" onclick={toggleNavbar} href="/about">
		<ul>Sobre la empresa</ul>
	</a>
</nav>

<!-- Header -->
<header
	class="bg-impervia-blue fixed flex min-h-16 w-screen flex-wrap items-center justify-between px-10 py-4 text-white sm:px-16 xl:px-28"
>
	<a href="/">
		<h2 class="text-2xl font-extrabold sm:text-3xl">IMPERVIA</h2>
	</a>

	<!-- Desktop navbar -->
	<nav class="hidden flex-wrap justify-center gap-4 text-center text-sm font-semibold lg:flex">
		<a class="hover:underline active:text-gray-200" href="/#impervia-description">
			<ul>¿Qué es Impervia?</ul>
		</a>
		<a class="hover:underline active:text-gray-200" href="/#instructions">
			<ul>Instrucciones de uso</ul>
		</a>
		<a class="hover:underline active:text-gray-200" href="/calculator">
			<ul>Calculadora de cubetas</ul>
		</a>
		<a class="hover:underline active:text-gray-200" href="/about">
			<ul>Sobre la empresa</ul>
		</a>
	</nav>

	<!-- Hamburger button -->
	<button onclick={toggleNavbar} class="hover:cursor-pointer active:scale-90 lg:hidden">
		<img class="h-7 invert" src="/icons/hamburger.png" alt="Navbar menu icon" />
	</button>
</header>
