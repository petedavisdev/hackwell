<script setup lang="ts">
const gapText = '2h 15m';
const gapHours = '2';
</script>

<template>
	<time :class="$style.gap" :style="{ color: `var(--hours${gapHours})` }">{{
		gapText
	}}</time>
</template>

<style module>
.gap {
	--hours0: tomato;
	--hours1: orange;
	--hours2: gold;
	--hours3: greenYellow;
	--hours4: greenYellow;
	--hours5: greenYellow;
	--hours6: greenYellow;
	--hours7: greenYellow;
	--hours8: greenYellow;
	--hours9: greenYellow;
	--hours10: greenYellow;
	--hours11: greenYellow;
	--hours12: paleGreen;

	font-size: large;
	color: var(--hours12);
}

.gap::before,
.gap::after {
	display: block;
}

.gap::before {
	content: '▲';
}

.gap::after {
	content: '▼';
}
</style>
