<script setup lang="ts">
const dayText = 'Today';
</script>

<template>
	<article :class="$style.day">
		<h2 :class="$style.title">{{ dayText }}</h2>

		<div :class="$style.log">
			<Fed />
			<Gap />
		</div>
	</article>
</template>

<style module>
.day {
	padding: 0.5em calc(50dvw - 180px);
}

.day:nth-child(even) {
	background-color: #fff1;
}

.title {
	position: sticky;
	top: 0;
	float: right;
	margin-block: 0.5em;
	padding-inline: 0.25em;
	writing-mode: vertical-lr;
}

.log {
	margin-right: 5ch;
}
</style>
