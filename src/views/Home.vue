<script>
// import AppBanner from '@/components/shared/AppBanner';
import ProjectsGrid from '../components/projects/ProjectsGrid.vue';
import AboutMe from '@/components/about/AboutMe';
import AboutCounter from '@/components/about/AboutCounter';
import feather from 'feather-icons';

export default {
	name: 'Home',
	components: {
		// AppBanner,
		ProjectsGrid,
		AboutMe,
		AboutCounter
	},
	data: () => {
		return {};
	},
	mounted() {
		feather.replace();
	},
	updated() {
		feather.replace();
	},
};
</script>

<template>
		<div>
			<!-- About me -->
			<div class="container mx-auto">
				<AboutMe />
			</div>

			<!-- About counter -->
			<AboutCounter />
		</div>
	<div class="container mx-auto">
		<!-- Banner -->
		

		<!-- <AppBanner class="mb-5 sm:mb-8" /> -->

		<!-- Projects -->
		<ProjectsGrid />

		<!-- Load more projects button -->
	</div>
</template>

<style scoped></style>
