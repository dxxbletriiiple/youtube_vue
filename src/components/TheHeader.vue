<script setup lang="ts">
import TheDropDownSettings from './TheDropDownSettings.vue';
import TheDropDownApps from './TheDropDownApps.vue';
import TheLogo from './TheLogo.vue';
import TheSearch from './TheSearch.vue';
</script>

<template>
	<header class="flex justify-between fixed z-30 w-full">
		<div class="lg:w-1/4 flex">
			<div class="flex items-center xl:w-64 xl:bg-white pl-4">
				<button class="mr-3 sm:ml-2 sm:mr-6 focus:outline-none">
					<svg class="w-6 h-6" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
						<path
							fill-rule="evenodd"
							d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z"
							clip-rule="eve	nodd"
						></path>
					</svg>
				</button>
				<TheLogo />
			</div>
		</div>
		<div class="hidden sm:flex items-center justify-end p-2.5 pl-8 md:pl-12 md:px-8 flex-1 lg:px-0 lg:w-1/2 max-w-screen-md">
			<TheSearch />
			<button class="ml-4 focus:outline-none">
				<svg class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
					<path
						fill-rule="evenodd"
						d="M7 4a3 3 0 016 0v4a3 3 0 11-6 0V4zm4 10.93A7.001 7.001 0 0017 8a1 1 0 10-2 0A5 5 0 015 8a1 1 0 00-2 0 7.001 7.001 0 006 6.93V17H6a1 1 0 100 2h8a1 1 0 100-2h-3v-2.07z"
						clip-rule="evenodd"
					></path>
				</svg>
			</button>
		</div>
		<div class="flex items-center justify-end lg:w-1/4 sm:space-x-3 p-2 sm:px-4">
			<button class="sm:hidden p-2 focus:outline-none">
				<svg class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
					<path
						fill-rule="evenodd"
						d="M7 4a3 3 0 016 0v4a3 3 0 11-6 0V4zm4 10.93A7.001 7.001 0 0017 8a1 1 0 10-2 0A5 5 0 015 8a1 1 0 00-2 0 7.001 7.001 0 006 6.93V17H6a1 1 0 100 2h8a1 1 0 100-2h-3v-2.07z"
						clip-rule="evenodd"
					></path>
				</svg>
			</button>
			<button class="sm:hidden p-2 focus:outline-none">
				<svg class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
					<path
						fill-rule="evenodd"
						d="M8 4a4 4 0 100 8 4 4 0 000-8zM2 8a6 6 0 1110.89 3.476l4.817 4.817a1 1 0 01-1.414 1.414l-4.816-4.816A6 6 0 012 8z"
						clip-rule="evenodd"
					></path>
				</svg>
			</button>
			<button class="relative group p-2 focus:outline-none">
				<svg class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
					<path
						d="M5 3a2 2 0 00-2 2v2a2 2 0 002 2h2a2 2 0 002-2V5a2 2 0 00-2-2H5zM5 11a2 2 0 00-2 2v2a2 2 0 002 2h2a2 2 0 002-2v-2a2 2 0 00-2-2H5zM11 5a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2h-2a2 2 0 01-2-2V5zM11 13a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2h-2a2 2 0 01-2-2v-2z"
					></path>
				</svg>
				<TheDropDownApps />
			</button>
			<button class="relative group p-2 focus:outline-none">
				<svg class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
					<path d="M10 6a2 2 0 110-4 2 2 0 010 4zM10 12a2 2 0 110-4 2 2 0 010 4zM10 18a2 2 0 110-4 2 2 0 010 4z"></path>
				</svg>
				<TheDropDownSettings />
			</button>
			<button
				class="focus:outline-none flex items-center whitespace-nowrap px-2 py-1 text-sm text-blue-700 uppercase border border-blue-700 rounded-sm"
			>
				<svg class="mr-2 w-7 h-7" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
					<path
						fill-rule="evenodd"
						d="M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-6-3a2 2 0 11-4 0 2 2 0 014 0zm-2 4a5 5 0 00-4.546 2.916A5.986 5.986 0 0010 16a5.986 5.986 0 004.546-2.084A5 5 0 0010 11z"
						clip-rule="evenodd"
					></path>
				</svg>
				Sign In
			</button>
		</div>
	</header>
</template>
