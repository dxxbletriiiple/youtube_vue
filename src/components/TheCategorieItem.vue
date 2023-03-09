<script setup lang="ts">
defineProps<{ text: string; isActive: boolean }>();
</script>

<template>
	<a
		href="#"
		class="px-3 py-1 transition rounded-full border"
		:class="{
			'bg-gray-600 border-gray-700 hover:bg-gray-500 text-white': isActive,
			'bg-gray-100  border-gray-300 hover:bg-gray-200': !isActive,
		}"
		>{{ text }}</a
	>
</template>
