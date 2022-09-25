<script setup lang="ts">
defineProps<{
	name: string;
}>();
</script>

<template>
	<div class="uppercase font-bold">{{name}}</div>
</template>