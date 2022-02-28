<script>
	import Profilecard from './aboutme/Profilecard.svelte';
	import Form from './contact/form.svelte';
	import Cta from './cta/Cta.svelte';
	import MyProjects from './myprojects/MyProjects.svelte';
	import Skills from './skills/Skills.svelte';
	import Footer from './footer/Footer.svelte';
	import Navigation from './navigation/Navigation.svelte';

</script>

<header>
	<nav>
		<Navigation />
	</nav>
</header>


<main>
	<div class="gradientbackground profilecardoutter">
		<div class="cardspacing">
			<Profilecard />
		</div>
	</div>

	<Skills />

	<div class="gradientbackgroundProjects">
		<div class="projectspacing">
			<MyProjects />
		</div>
	</div>
	<Cta />

	<div id="parallax" class="contactformbackground">
		<Form />
	</div>	
</main>

<footer>
	<Footer />
</footer>

<style>

</style>