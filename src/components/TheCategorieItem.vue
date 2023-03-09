<script setup lang="ts">
defineProps<{ text: string }>();
/* export default {
	props: ['text'],
}; */
</script>

<template>
	<a href="#" class="px-3 py-1 transition bg-gray-600 border border-gray-700 rounded-full hover:bg-gray-500 text-white">{{ text }}</a>
</template>
