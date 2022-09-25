<script setup lang="ts">
defineProps<{
	set: string;
}>();
</script>

<template>
	<div class="flex justify-center items-center p-2 bg-white text-black aspect-square">{{set}}</div>
</template>