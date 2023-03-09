<script lang="ts">
import TheCategorieItem from './TheCategorieItem.vue';

export default {
	data() {
		return {
			texts: [
				'All',
				'Trucks',
				'Tools',
				'Machines',
				'Engines',
				'Snow',
				'Ships',
				'Roads',
				'Tanks',
				'Building',
				'Mars',
				'Woodworking',
				'Tractors',
				'Songs',
				'TV',
				'Shows',
				'Football',
				'Planes',
				'Live',
				'Streets',
				'Math',
				'Programming',
			],
		};
	},
	components: {
		TheCategorieItem,
	},
};
</script>

<template>
	<section class="pt-14 md:pl-24 xl:pl-64 w-full fixed bg-white bg-opacity-95 z-10">
		<div class="border-t border-b px-4 max-w-screen-2xl m-auto">
			<div class="py-3 flex space-x-3 overflow-auto text-sm whitespace-nowrap scrollbar">
				<TheCategorieItem v-for="text of texts" :key="text" :text="text" :isActive="text == 'All'" />
			</div>
		</div>
	</section>
</template>
