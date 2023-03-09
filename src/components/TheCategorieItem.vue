<script setup lang="ts">
defineProps<{ text: string; isActive: boolean }>();
</script>

<template>
	<a
		href="#"
		class="px-3 py-1 transition rounded-full"
		:class="{
			'bg-gray-600 border border-gray-700 hover:bg-gray-500 text-white': isActive,
		}"
		>{{ text }}</a
	>
</template>
