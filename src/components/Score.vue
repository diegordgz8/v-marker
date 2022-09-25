<script setup lang="ts">
defineProps<{
	score: string;
}>();
</script>

<template>
	<div class="flex justify-center items-center p-8 bg-white text-black aspect-square">{{score}}</div>
</template>