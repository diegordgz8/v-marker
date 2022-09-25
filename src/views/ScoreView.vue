<script setup lang="ts">
import { ref } from "vue";
import Score from "../components/Score.vue";
import TeamName from "../components/TeamName.vue";
import Set from "../components/Set.vue";

const set = ref(0);
// 	const teamA: {
// 	name: null,
// 		score: null,
// 			set: null,
// 			},
// const teamB: {
// 	name: null,
// 		score: null,
// 			set: null,
// 			},
// 		};
</script>

<template>
	<main>
		<div class="space-y-4">
			<div class="flex justify-between">
				<TeamName name="Atléticos" />
				<Set set="4" />
				<TeamName name="Guerreros" />
			</div>
			<div class="flex justify-around">
				<Set set="1" />
				<Set set="2" />
			</div>
			<div class="flex justify-evenly">
				<Score score="4" />
				<Score score="6" />
			</div>
		</div>
	</main>
</template>