<script>
export default {
	data: () => {
		return {
			experienceTitle: 'Years of experience',
			githubTitle: 'Stars on GitHub',
			feedbackTitle: 'Positive feedback',
			projectsTitle: 'Projects completed',
		};
	},
};
</script>

<template>
	<div class="mt-10 sm:mt-20 bg-primary-light dark:bg-ternary-dark shadow-sm">
		<!-- About me counters -->
		<div
			class="font-general-regular container mx-auto py-20 block sm:flex sm:justify-between sm:items-center"
		>
			<p	class="font-general-regular text-ternary-dark dark:text-ternary-light text-3xl">
				Neste curso vamos aprender os fundamentos do Vue.JS e construir uma aplicação (app) para colocar estes conceitos em prática.
			</p>
		</div>
	</div>
</template>
